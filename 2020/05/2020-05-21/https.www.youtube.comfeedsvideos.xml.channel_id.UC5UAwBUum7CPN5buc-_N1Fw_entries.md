# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## How To Install Linux (with or w/o separated /home partition)
 - [https://www.youtube.com/watch?v=dWFJ2fGtmKs](https://www.youtube.com/watch?v=dWFJ2fGtmKs)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-05-21 00:00:00+00:00

Visit http://linode.com/linuxexperiment for a 20$ credit on your new Linode account !
Installing a Linux distro is a complex step if you’ve never done it. You’re messing with your hard drive, and it can cause some issues and potentially wipe all your data. It’s scary, and not very intuitive if you’ve never installed another OS on your computer. 

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

Linux is a diverse system, and this is also reflected in its installer software. you basically will find 4 major options. - The Ubuntu installer, called Ubiquity - The elementary installer, that only PopOs uses for now, but elementary OS will move to it for elementary 6 - The Manjaro / calamares installer - The Fedora / Anaconda installer

Keyboard and language selection
There is nothing much to it, just choose the language you want for your distro install, and the kayboard layout. Don’t hesitate to try out the various weird keys to make sure that everything is correct and works well with your keyboard. Automatic detection is not too bad either to help you get to the right keyboard layout if you’re confused by the many, many layout available.

Partitions
The first thing you’ll have to take care of is select what kind of install you want to do. Generally, you’ll get 3 choices: - Erase the whole disk and install the distro - Install alongside your existing OS - Select what to do manually

Probably a lot of you have heard about having a separate /home partition, and what that would mean. Honestly, if you’re a beginner, do not bother with that. Having a separate /home partition can be useful if you plan to change linux distributions often and don’t want to bother with copying your data back to your new system.

If you really want to have a separate /home partition, you must choose the manual partitioning option. Be aware that any errors here could result in your existing OS being wiped, or data being lost, so be very careful. Let’s see how to manually partition and install your distro:

Manual install
Linux stores everything in a main directory called “/”. You can put the various subfolders of “/” in their dedicated partitions, such as /home, which is the folder that contains all of the users and their files. To do so, you can use the manual partitioning tool of the installer to map the /home folder to a specific partition. We will need to create multiple partitions, which are virtual slices of your disk. We’ll need one for the system, one for your /home directory, one for swap, and a final one for EFI, if your computer requires it.

You’ll need to create first a “/” partition that will be the one where the system is installed. This one should be sufficiently large to host all the programs you might want to install, so don’t skimp on disk space there ! Most distributions use the ext4 filesystem, which is probably your best choice if you don’t need any specific features, so select that, and create the partition, mapping it to the “/” mount point.

Next, you’ll need to create a second partition out of the free disk space on your drive. Make it as big as possible, it’s going to be your place to store your user files. Use ext4 as well, and select /home as a mount point.

If your computer is relatively recent, you’ll also be asked to create an EFI partition, to store the files that will allow your various systems to boot. This partition should be no less than 512 Mb.

If your computer doesn’t have much RAM, like 4Gb or less, you also need to create a swap partition. This will be a place where program data can go when your RAM is full, and will avoid your system grinding to a halt when that happens. The general recommendation is to use twice the size of your computer’s RAM, si if you have 4GB of RAM, create an 8Gb swap partition, and use the swap mount point.

Finally, you have to tell the system where to install the bootloader. This is a small program that allows you to start the various operating systems you have on your machine, and select which one to start if you have more than one. I’d recommend you put it on your main system partition, the one you attributed to “/”.

User creation
You don’t have much to fill in here: just your full name, a user picture, the username that will be used as the name of your user’s folder in the /home directory, and a password. Select something you can remember here, it’s going to be asked of you every time you want to install software, or change some settings, so don’t pick something too random.

Once your user is done, you’ll just have to wait for the installer to finish, and will be asked to reboot the system, and remove the install media.

