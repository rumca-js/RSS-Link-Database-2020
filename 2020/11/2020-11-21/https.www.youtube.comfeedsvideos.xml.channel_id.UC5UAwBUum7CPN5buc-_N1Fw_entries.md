# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Is this the Linux equivalent to iMovie? Not quite... - Pitivi - Project of the month
 - [https://www.youtube.com/watch?v=CDvGHENGvDY](https://www.youtube.com/watch?v=CDvGHENGvDY)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-11-21 00:00:00+00:00

Linux doesn't lack in the video editor department. You have Kdenlive, Lightworks, Shotcut, Openshot, Davinci Resolve, Olive, and you also have one, just one, using GTK. It's called Pitivi, and it's pretty great. Let's take a look at how it works.


Join this channel to get access to a monthly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

## What can it do ?

Pitivi will be familiar to anyone who's ever dabbled with a non linear video editor: you have your media library, your tracks, and your preview pane. You just drag the video files you want to use inside the media library, and then drag them to one of your track, which are called layers here.

You can then cut the video clips to remove unwanted footage, add effects, transitions, audio, and then render the whole project as a complete video file.

Pitivi's interface is super simple: it uses the whole bottom part for your layers where you'll drop your video, audio or image files, and the top is hosting your media library, the various effects you can apply, as well as the clip properties and the transitions you can use to smooth out moving from one clip to another.

You also get, obviously, your monitor where you can see a live preview of your work.

On the surface, Pitivi seems too simple, but it hides some advanced features. First, you can work using proxy clips. THis feature allows you turn your full resolution video files into smaller, easier to handle proxies, generally at the cost of a reduced resolution. Once the transcoding process is done, the preview monitor will use these proxies instead of the full size files, which means you can edit 4K video even on a potato computer that couldn't handle it at full size, but could handle 720p files easily. The only issue is that you basically NEED these proxies, we'll talk about why a bit later.

Next, Pitivi has a very good backup system. If your application crashes during editing, it will pick back up right where you left off, without losing your work, which is a very important feature. 

Pitivi also makes use of keyboard shortcuts, and you can customize each and every one of them, so if you're already used to something else, you can tweak how Pitivi works to suite your habits, which is always nice.

Now for more advanced editing, Pitivi supports a lot of effects. You have audio filters, color manipulation, various compositing modes if you want to create a specific look, a bunch of transformations and deformations, blurs, rotations, you name it. These effects can easily be applied by dragging and dropping them onto a clip, and can be configured with the "Clip" pane, where all effects are located. Most of these effects also support Keyframes, which means you'll be able to time them easily if you need to.

Creating transitions between clips in your project is also easy: you just need to overlap the two clips you want to animate, select the overlap, and choose the transition you want to use. There is a lot of choice, although these are all wipes, so they'll just make one clip appear on top of another through a specific shape or motion.

Now, when Rendering time comes, the render dialog looks super basic. it only shows you the preset, and where you want to store your rendered file, and how to name it. If you unfold the "advanced" panel, though, you'll get to pick the container, the framerate, the codec, the audio sample rate and codec, and more.

You can also select to render from the proxy clips, although if you used scaled proxies that use a lower resolution, I'd advise against that, as your video will not be as high quality as it should be, or you can pick to render from your original source files.

## The Issues

First, Pitivi doesn't use hardware acceleration, at least not on Nvidia GPUs. This means that the more effects you add, the more stuff you layer on top of each other, the less your timeline preview will be smooth. Just editing 4K video grinded it to a few frames per second unless I used scaled proxies.

Apart from that, I can't say I experienced that many issues with it. It was stable, rendering worked fine, although it did take a lot of time, as Pitivi doesn't use the GPU to render: a 20 minutes long video, exported from 4K clips to 1080p 30fps took about an hour and a half to render, where Davinci Resolve exports this kind of stuff in about 10 minutes. Once again, if you're working with smaller resolution files, you probably won't see this as an issue.

