# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Multitouch Gestures in elementary OS 6 (and any other distribution) with Touchegg
 - [https://www.youtube.com/watch?v=o74_ddzi1kw](https://www.youtube.com/watch?v=o74_ddzi1kw)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-12-10 00:00:00+00:00

Try KernelCare+ for free for 30 days by signing up here: https://lp.kernelcare.com/kernelcare-plus-experiment

Using Linux on laptops has always lacked something special: good trackpad gestures. I looked for solutions to this issue, and I could only find one, that didn't really work like I wanted. But now, there's a project that is swiping my doubts away, and that will definitely satisfy your gestures needs in a pinch.

Join this channel to get access to a monthly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

# Multitouch gestures on elementary OS 6 (and any other Linux distro) - Touchegg


## The gestures problem on Linux
Ok, let's start by talking about gestures on Linux, really quick. Linux and its various desktop environments don't tend to support touchpad gestures, at least not on X.org, which is what most distributions use. Wayland seems to improve the situation, at least on GNOME, but we're not there yet.

For a long time, I've been using libinput gestures. It's sort of a middle ground between gestures, and keyboard shortcuts: what it does is map your multi touch gesture to a keyboard shortcut. This works, as in, you do the gesture, and then the action happens, but it's not ideal.

Well, that's where Touchegg comes to save the day!

## Touchegg

Touchegg is not a very recent project, it actually began in 2015. It's developed by Jose Esposito, and 11 other contributors.
How is it better than libinput-gestures? That's simple. It translates your gestures into visible movement on the screen.

For example, if you use gestures to tile your windows, you'll see the outline of where the window will be positioned, as you drag your fingers on the touchpad, just like when you drag that window to the screen's edge with your mouse.

Touch egg supports a lot of actions: Maximising, or restoring a window to its original size, minimizing a window, snapping a window to a screen's edge, closing a window, but also switching to another virtual desktop, or minimizing all windows to show the desktop itself.

These actions can be performed using a wide variety of gestures, from 3 to 4 fingers swiping, pinching or tapping.

It comes with a default configuration, that you can tweak if you want, to use your own gestures. You can obviously also map these to any keyboard shortcut you want.

Touchegg is in the AUR, and also provides a deb package for anything Debian based, like Ubuntu, or a RPM package for Fedora, Red Hat, CentOS and other derivatives.

## The problem

Not everything is sunshine and roses, though, because Touchegg has 2 problems.

The first one, is that it lacks a graphical tool to configure gestures. Unlinke libinput gestures, which can rely on the "Gestures" app, Touchegg can only be configured out of the box using a text file. it's not very complicated once you've looked at the default configuration, but it's not easy to tweak in a pinch, pun intended.

You still have to mind the syntax, and restart touchegg so that your configuration changes are taken into account. It does allow you to create application specific gestures, though, for example using a specific gesture inside of your web browser to reload a page, or go back or forward.

The second issue, is that Touchegg doesn't really move the elements on your screen, it only gives you a visual cue of what is going to happen.

Well, I'm glad to report that both these issues are perfectly fixable, and that elementary OS 6 will fix them when they release!

elementary OS 6 has had a item in its backlog about implementing multitouch gestures, for as long as the project has been on track. Problem was, there didn't seem to be a feasible solution for good, 1:1 gestures using X.org.

For now, only the multitasking view and desktop switching are implemented, and all other actions still use touchegg's visuel cues, but that could be changed.

As per the graphical user interface, the elementary team is working on something pretty basic that will let you define what gestures do what action. It's only a start, and I hope people will develop full plugins for the settings of GNOME, Plasma, or elementary OS, that will allow people to really completely tweak everything they want.

Now touchegg is only a part of what elementary OS 6 will offer in terms of multitouch gestures. They also implementend libhandy, a new library developed by Purism for their GNOME efforts on smartphones. This allows multiple applications in elementary OS 6 to respond to two finger swipes to go back and forward.

This video is sponsored by KernelCare+.

