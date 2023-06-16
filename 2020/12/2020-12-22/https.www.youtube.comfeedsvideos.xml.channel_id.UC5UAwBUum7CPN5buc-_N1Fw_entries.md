# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## WAYLAND: what is it, and is it ready for daily use?
 - [https://www.youtube.com/watch?v=g1BoZnekkyM](https://www.youtube.com/watch?v=g1BoZnekkyM)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-12-22 00:00:00+00:00

Try Kernelcare Enterprise for free: https://lp.kernelcare.com/kernelcare-enterprise-experiment

Probably everyone that is interested in the Linux desktop has heard about Wayland. It's the next big thing, the replacement for X.org, a solution to a lot of woes in terms of performance and graphics on Linux. And still, it has failed to materialize, over and over, and is still not the default on many big distributions, like Ubuntu, or Linux Mint. Let's see what Wayland is, and how ready it is, right after this!

Join this channel to get access to a monthly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment


Wayland is, in itself, just a protocol. It's not a program, or a replacement for the old X.org display server. This protocol has to be implemented by a compositor, which will display the application's content on the user's screen.

Currently, a lot of distributions use X.org, the very old display server that has served us pretty well for ages. The goal of wayland is to put this old beast to pasture, but for what benefits ?

First, let's take a look at how X.org works. This old thing, dating back to 1987, the blessed year of my birth, by the way,  is a multi-layered process:
First, you have your display server, or the X server. It's the central platform to communicate with the clients, like the applications you're using, and the compositor, which displays the windows for these apps themselves. This server is interacting with clients, which are basically your applications, but also with a compositor, which is your window manager, like Kwin on KDE, or Mutter on GNOME.

It's a sturdy process, but it introduces a lot of delay, with some back and forth betwen the server, the compositor, and the application itself.

Wayland has a simpler model, because in Wayland, the compositor IS the server as well.
This means that, in our example, the application opens, tells the compositor that it wants a window, and the compositor gets all the details from the app in one go, decides what to do with the window, and tells the app to draw itself. Yep, on Wayland, the applications also have to do their own rendering on the screen: they manage their own titlebars, their own drop shadows, everything.

This is why you can't just switch GNOME or KDE from X.org to Wayland: the pieces that compose the desktop environment don't play the exact same role on both solutions. On Wayland, the compositor doesn't draw the windows, the app themselves do, so you have to update the window managers to become compositors that don't do any drawing, and you have to update the toolkits, GTK and Qt, to let them draw stuff themselves.

Then there's the issue of the graphics drivers: the Nvidia drivers, the open source AMD or Intel drivers, these were written to send information back and forth with X.org, not with a wayland compositor.

So they also have to be updated to work with that new model. This is already the case, as the open source Mesa drivers, which cover AMD and Intel, already support wayland using a solution called GBM. Nvidia, on the other hand, decided that they had a more efficient solution called EGL, which has to be supported separately by the wayland compositors.

Since Nvidia doesn't seem to be willing to update their driver to use GBM, for nvidia drivers to work with wayland, desktop environments have to also support EGL, which is an extra burden, and also explains why Nvidia drivers are hit or miss when using Wayland.

So, where is Wayland? Well, it's already very well supported:
- GNOME supports Wayland, with Mutter, its window manager and compositor
- KDE supports Wayland as well, with Kwin
- Both GTK 3.20 and QT 5 support wayland out of the box

In terms of distros, Fedora already uses Wayland as the default, if the drivers permit it, and has been since 2016. Red Hat Enterprise Linux 8 also uses Wayland as the default, and Debian does so as well, for their GNOME sessions. Manjaro also defaults to wayland for the GNOME sessions, if the drivers allow it.

Some programs that were made specifically to work with X.org don't work on wayland-based systems, especially games.

For that use case, Wayland developers have a solution: as wine or proton expects to run in an X Server, Wayland provides the ability to run such a server inside of Wayland, as a client, this is called Xwayland. 

The performance of Xwayland, however, seems on par with just running a game on X.org, as demonstrated by Phoronix early this year:

https://www.phoronix.com/scan.php?page=article&item=ubuntu-2004-waylandgame&num=3

