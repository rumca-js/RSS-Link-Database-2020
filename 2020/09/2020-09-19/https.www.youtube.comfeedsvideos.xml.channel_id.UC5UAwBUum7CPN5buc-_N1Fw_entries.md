# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Backup and Restore your whole system with Time Shift
 - [https://www.youtube.com/watch?v=-Mxq8m_Hlxo](https://www.youtube.com/watch?v=-Mxq8m_Hlxo)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-09-20 00:00:00+00:00

Download Safing's Portmaster for free here: https://safing.io/portmaster/

Participate in their Reddit AMA here: https://www.reddit.com/r/privacytoolsIO/comments/iv6mca/we_are_safing_a_forprivacy_counterculture_company/

Windows and Mac OS X have long had backup features baked in, that allow users to restore their system to a usable state after something went wrong. By default, a lot of distros don't include such a tool, but there is an option called Time Shift, which is our Project of the Month.

TimeShift website: https://github.com/teejee2008/timeshift

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

## What is Time Shift

Time Shift is a backup and restore application designed to restore your system to a usable state after you've encountered an issue or you've broken it by installing something you shouldn't have.

Time Shift is not, however, intended to backup and restore user files. The goal here is to grab a snapshot of your system at a given time, and allow you to return to that state while leaving all your user files unchanged. It's basically like setting up a separate partition for your user files, but without the hassle of completely reinstalling a system.

The snapshots are incremental, which means that the first backup will be the biggest, and the next ones will only include the files that actually changed compared.

## The Features

Time Shift has 2 modes: one based on rsync, and one based on BTRFS.

The Rsync mode uses rsync as a tool to copy the files, and hard links to avoid duplicating all files on each snapshot. Snapshots created using Rsync can be browsed using a file manager, since they are just copies of your files. This is pretty handy, as it allows you to just grab one file that you want to restore, without restoring everything else to a previous snapshot entirely.

The second mode, based on BTRFS, uses this file system's native backup and restore features. You obviously need to have a BTRFS filesystem to make use of that mode, but there are some advantages to it: these snapshots are perfect copies of your system, byte for byte, and can be restored in seconds, where the Rsync backups might take a lot more time, since they have to copy back all files. These BTRFS snapshots also use a lot less space.

Once you've chosen your backup and restore mode, you can decide what backup strategy you want: hourly, daily, weekly, monthly, or at boot. The more snapshots you store, the more disk space you're going to use, obviously, so choose something reasonable depending on your needs and how often you tinker with your system.

By default, time shift will store them on the system partition in a /timeshift folder, so they'll use up disk space on your main partition, it's highly recommended you save them to another partition, or to another drive entirely, just in case.

Finally, you can also choose how many snapshots you want to keep for each level: so you could choose to keep 4 hourly snapshot, 2 weekly snapshots, and 1 monthly one. The older snapshots will get deleted automatically.

Where Time Shift gets really interesting though, is with how it can restore your data. All snapshots can be used on any distro you like, as long as the distro runs Time Shift. So you could, for example, decide you want to distro hop for a while. You backup your system using Time Shift, try out something new, and when you want to go back to your older system, you just restore it using Time Shift, it will erase your distro hopping mistakes, and restore you to your previous distro of choice.

It also means that you can restore your system even if it can't boot anymore: you boot from a live USB, install timeshift there, locate your snapshots, and restore from the Live USB.

Since Time Shift doesn't affect your user files, you'll keep everything you were working on, your app settings, everything. Only the system files will be replaced by the ones from the snapshot. If you really want to backup some things from your user directory, though, you can select to include the hidden files and folders of your home directory. Be aware though, that this might restore older config files and app preferences, or even application databases, so you could lose some amount of work.

The team has also taken into account encrypted home partitions, and will backup and resotre your .ecryptfs folder, to avoid your files being available to anyone after you restore a snapshot.

Timshift supports a bunch of configurations, including GRUB2, EFI, and encrypted filesystems, but it won't work in containers or using Docker, so you won't be able to use it for servers if you use these technologies.

