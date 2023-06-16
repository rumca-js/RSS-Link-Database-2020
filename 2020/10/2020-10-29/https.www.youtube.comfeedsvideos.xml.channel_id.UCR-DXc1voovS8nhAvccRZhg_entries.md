# Source:Jeff Gerling, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg, language:en-US

## 5 Gbps Ethernet on the Raspberry Pi Compute Module 4?!
 - [https://www.youtube.com/watch?v=KL0d68j3aJM](https://www.youtube.com/watch?v=KL0d68j3aJM)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2020-10-30 00:00:00+00:00

tl;dw - I can get five 1 Gbps network interfaces using an Intel I340-T4 PCIe NIC, but I can only get a maximum of 3.06 Gbps throughput using all five interfaces at the same time.

You could use this setup to build a custom router or switch using OpenWRT or pfSense, or to run other specialized network setups for multiple-interface webservers, bandwidth metering, network bonding, or more!

Check out all the PCIe devices I'm testing: https://pipci.jeffgeerling.com

And check out the GitHub issue containing all the testing and research notes for this video: https://github.com/geerlingguy/raspberry-pi-pcie-devices/issues/3

Support me on Patreon: https://www.patreon.com/geerlingguy
Sponsor me on GitHub: https://github.com/sponsors/geerlingguy

Products I used in this video (some are affiliate links):

  - Intel I340-T4 NIC: https://amzn.to/34HKBgz
  - 16x to 1x PCIe Adapter: https://amzn.to/34JcdS8
  - Raspberry Pi Compute Module 4: https://www.raspberrypi.org/products/compute-module-4/

#RaspberryPi #ComputeModule4

Contents:

00:00 - Intro
00:34 - The Intel I340-T4
01:22 - Plugging in the Card
02:53 - Finding a driver
04:16 - Patching Intel's driver
05:10 - Four new eth interfaces!
05:25 - Benchmarking
08:20 - Benchmark results
09:07 - Next steps
10:04 - Secret projects!
10:38 - Bloopers

