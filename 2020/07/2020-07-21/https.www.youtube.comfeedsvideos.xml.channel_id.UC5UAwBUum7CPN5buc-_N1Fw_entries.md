# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Fedora Silverblue: is this the FUTURE of Linux? - Project of the Month
 - [https://www.youtube.com/watch?v=5TjIzUJtF-I](https://www.youtube.com/watch?v=5TjIzUJtF-I)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-07-21 00:00:00+00:00

Protect your servers and limit downtime with Cloud Linux and KernelCare: https://lp.kernelcare.com/bundle

This time, we're going to take a look at Fedora, but not the mainline release, its flatpak  and ostree based spinoff called Silverblue. It's an interesting distro, not in terms of desktop experience, but in terms of its internal workings, which are different from about all other distros. let's take a look !

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

Silverblue is what was previously called Fedora Atomic workstation. It's waht they call an immutable OS, as in: you can't touch the system files. It is delivered using images built with rpm-ostree. This tool allows people to make bootable, read-only OS images and manage them just like they would their code repository, by committing their changes and pushing out updates, instead of relying on regular packages. This bootable image can be combined with packaging systems to add stuff to it, but the base image is immutable and can't be changed by the user, which limits greatly the risk of breaking stuff.

Silverblue allows you to focus on your work and not on the OS: if there's an update, you just reboot to the new image, and you're good to go. If the new image doesn't work for you? You just revert to the older one and keep on working. No dependencies to solve, or packages to downgrade, you just restore the previous version.

If you want to move to a development release to test some new stuff, you also can, and you can switch back to your production system anytime you want. It's really secure, stable, and make the whole OS basically indestructible.

From the outside, there is no real difference from the regular current release of Fedora: it's a gnome based distro, which looks like vanilla gnome. The main difference is that you won't get the DNF package manager by default. Silverblue uses Flatpak to install graphical applications. For now, the base system includes all the default apps in the system image, but these will be transfered to flatpaks to make the system image as small as possible and ensure speedy updates.

You can, however, install your good old packages using rpm-ostree, but it's not really recommended: these packages will be added to the system image, and this image will need to be rebuilt at every update, which will take time, and can basically negate the advantages of ostree by introducing conflicts and issues.

Your system always keeps the current system image you're using, and the previous one, but if you want to pin other images, you can, so you can restart to any version of your system that you'd like!

There's an interesting side effect to this "immutable" model: if the most popular distro agreed on a similar base, and just shipped the rest of their software and differenciating elements as flatpaks or layered packages, Linux could have a stable, identical target for developers. his could bring more third party developers on board, as it would make the OS a lot easier to support. Of course, this is pure conjecture, since Silverblue is based on rpm-ostree, so debian based distros wouldn't be able to jump on the bandwagon anyway without some serious restructuring.

The most obvious one is the package installation: if you need something other than an application, and isn't provided in the base system image, you'll need to add a package. Fonts, for example, are installed using RPMS. This means that you'll have to use the rpm-ostree command to add the package to the base system, rebuilt the image, and reboot to that new image to benefit from the fonts, since the system image isn't writable: you can't add stuff to it while it's running.

You'll also have an issue if you want to run Chrome: as it's not available as a flatpak, and you can't install it as a layered package on top of the iamge, since it writes stuff in non standard directories. You'll have to use Firefox, or Chromium on Silverblue for now. That's not an issue for me, as I dislike Chrome, and use Firefox, but other users might not have the same experience.

Developers might also be faced with an issue: if they want to mess around with their system files, they'll hit a roadblock, since the filesystem is read only ond immutable. THat's why the silverblue team added toolboxes. A toolbox is basically a container where you can run a regular OS and tweak it as you like. For example, you could create t toolbox running the latest fedora workstation, and iteract with that system to change it and modify what you need to change, all while running Silverblue on your machine for maximum stability and security.

