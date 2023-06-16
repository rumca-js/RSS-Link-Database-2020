# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Flatpak vs Snaps vs Appimage vs Packages - Linux packaging formats compared
 - [https://www.youtube.com/watch?v=9HuExVD56Bo](https://www.youtube.com/watch?v=9HuExVD56Bo)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-06-23 00:00:00+00:00

Visit http://linode.com/linuxexperiment for a 20$ credit on your new Linode account !

Linux often gets a bad rap when it comes to installing software, and this is mainly due to the fact that we have so many different application distribution formats. Most of them also are misunderstood, or have preconceived notions attached to them, so I think it’s time to take a look at the differences between the various packaging formats !

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

There are 2 main package formats here: the DEB and RPM. Debs are used by Debian and debian based distros like Ubuntu, and RPMs are used by Fedora, Red Hat, or OpenSUSE. Both of these formats are usually pulled straight from the distribution’s repositories, or can be installed manually. They contain a binary version of the application or library you’re trying to install, so it’s already compiled for your system’s architecture.
These packages come with a descriptive file that also includes all the various libraries and other applications your program needs to be able to run. 
These DEB and RPM packages have advantages: they’re fast to install, they’re already compiled for your architecture, and they pull all your dependencies immediately if they’re available. They do have problems though: first, since these packages are distro-specific, app developers need to package their app for multiple distros, multiple versions, and architectures of these distributions.

To fix these problems, the Flatpak format was created. This one differs from the packages in a very important way: while flatpaks are also shipped as binaries, so no compilation needed, they also embark all the libraries they need directly in the package. They can also used shared libraries provided in other flatpaks.

Flatpaks are also relatively quick to install, and can be pulled from repositories called remotes. The biggest one out there is Flathub, which sources most available flatpak applications.

Flatpaks also introduce some issues, mainly in terms of security: while flatpaks are sandboxed, they still can provide outdated versions of libraries that light or might not be kept up to date by the developer.
They also use up more space. Flatpaks can run on any distro that have the flatpak package installed, and can be downloaded from most distro’s software centers if they have added the flathub remote.

Snaps are based on the same model generally as flatpaks: they are binary applications shipped in a single package with their own dependencies. They can also make use of runtimes, and are sandboxed as well to avoid the snaps being able to see or read everything you have on your system.

Snaps have an interesting difference though: they can also ship server stuff. While flatpaks are mainly geared towards graphical applications, snaps can contain pure command line packages. Another difference is that snaps can be updated while they are in use, and can receive delta updates. Snaps can also revert to the previous version easily.

Snaps do have some problems though: first, they don’t make use of the system theme. Second, they can’t use external repositories: all snaps are shipped through snapcraft, which is the “official” distribution center for these.

Snaps also tend to be bigger, and slower to launch than flatpaks or regular packages. Snaps can run on any distro that have access to snapd, the backend part of snaps.

Appimages are yet another way to distribute applications in a single contained package. They use the “one app one file” method: an appimage ships all the files needed, and all the libraries as well, in a single file. They are not downloaded from a repo, but there is AppImage hub, a website that lists most if not all of the available Appimages.

These can just be downloaded manually and started immediately, wherever they are located on the system. No need to install runtimes, or shared components like Snaps or Flatpaks, you can just put your appimage anywhere and run it.

This means that appimages are super portable: to keep all your apps, you can just copy / past the appimages and you’re good to go.

This a a big advantage, but there are some issues there as well: first, you can’t update an appimage without downloading the new version yourself, so it’s a bit like apps on windows.
Appimages also don’t respect the system’s theme at all, and can get pretty big, since they don’t make use of share runtimes at all. Appimages can run on any distro, they don’t need any specific plumbing to work.

