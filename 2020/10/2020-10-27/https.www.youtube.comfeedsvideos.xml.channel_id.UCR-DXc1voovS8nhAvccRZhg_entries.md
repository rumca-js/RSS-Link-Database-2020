# Source:Jeff Gerling, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg, language:en-US

## GPUs on a Raspberry Pi Compute Module 4!
 - [https://www.youtube.com/watch?v=ikpgZu6kLKE](https://www.youtube.com/watch?v=ikpgZu6kLKE)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2020-10-27 00:00:00+00:00

tl;dw - I couldn't get the video cards to work. But I got very close!

And I learned a lot in the process. I'm putting everything here: https://pipci.jeffgeerling.com

After I learned the Raspberry Pi Compute Module 4 IO Board comes with a PCIe slot, I know the first thing I thought about testing was a graphics card. The Mali GPU inside the Pi 4 is decent on its own, but what if you could use external video cards, for mining, for rendering, or for CUDA or other GPU-accelerated computing purposes?

So that's what I sought to try out in this video, going boldly where... a couple others have gone before, but unsuccessfully!

Check out all the PCIe devices I'm testing: https://pipci.jeffgeerling.com

Support me on Patreon: https://www.patreon.com/geerlingguy
Sponsor me on GitHub: https://github.com/sponsors/geerlingguy

#RaspberryPi #ComputeModule

Products I used in this video (some links are affiliate links):

  - Zotac Nvidia GeForce GT 710: https://amzn.to/3mttxRq
  - VisionTek AMD Radeon 5450: https://amzn.to/3mttwgk
  - I/O Crest 4-port SATA card: https://amzn.to/3kzP4Y7
  - Intel I340-T4 NIC: https://amzn.to/34ylhtm
  - Raspberry Pi Compute Module 4: https://www.raspberrypi.org/products/compute-module-4/

Contents:

00:00 - Intro
01:10 - Zotac Nvidia GPU
02:20 - Trying Nvidia's ARM drivers
03:39 - Go to the BAR
05:39 - Trying CUDA
06:28 - Switch to AMD Radeon
07:44 - Trying the Nouveau driver
09:09 - Recompiling the Kernel
10:15 - That pesky IO BAR
11:25 - Rationale and next steps
12:29 - Pi PCI website
12:54 - Bloopers

