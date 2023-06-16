# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## Linux Browser wars - Performance isn't everything...
 - [https://www.youtube.com/watch?v=DPVrjH1mkkk](https://www.youtube.com/watch?v=DPVrjH1mkkk)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-11-13 00:00:00+00:00

The first 1000 people to use the link will get a free trial of Skillshare Premium Membership: https://skl.sh/thelinuxexperiment11201

Personal computing is increasingly dependent on web applications, for better or worse. A lot of stuff is now available in web form, instead of native apps, or as electron applications. While I'm not a big fan of this transition, it does mean that more apps are available on Linux everyday, and for that, you need a web browser. But not all browsers are created equal, and some offer more than others.

Video sponsored by skill share

Join this channel to get access to a monthly patroncast and vote on the next topics I'll cover:
https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw/join

Support the channel on Patreon: 
https://www.patreon.com/thelinuxexperiment

Follow me on Twitter : http://twitter.com/thelinuxEXP

My Gaming on Linux Channel: https://www.youtube.com/channel/UCaw_Lz7oifDb-PZCAcZ07kw

Follow me on LBRY: https://lbry.tv/@TheLinuxExperiment:e

The Linux Experiment merch: get your goodies there! https://teespring.com/en-GB/stores/the-linux-experiment

## Performance
In terms of speed, with the speedometer test, we see these results: 
Firefox: 87.9 runs / minute
Epiphany: 92.0
Chromium: 99.6

In terms of Javascript and webassembly, with the jetstream 2 benchmark: 
Firefox: 85.224
Epiphany: can't complete, crashes
Chromium: 115.504

For graphics performance, using the MotionMark test
Firefox: 51.16
Epiphany: 160.42
Chromium: 418.17

Let me know if your results are any different, because this baffles me, especially since in use, Firefox only felt marginally slower than Chromium, and definitely faster than Epiphany, which still got better benchmark results. In one last  fanboy effort, I ran Mozilla's own Javascript benchmark, Kraken. Lower is better.

Firefox:  972.2ms
Chromium: 947.6ms
Epiphany: 872.7ms

Now, to round this up, and look at standards compatibility, I ran the HTML5 test on each browser, here are the results:
Firefox: 466
Epiphany: 427
CHromium: 474

## Features

Let's start with Epiphany. As a native GTK web browser, Epiphany isn't the most loaded browser ever. You get the obvious: tabs, bookmarks, search engine selection, an integrated ad and popup blocker, intelligent tracking prevention, and syncing with a Firefox account if you want to carry all of your browser data, and passwords to another computer that can't run epiphany, or on your phone. You also get the obligatory incognito mode.

Firefox is more of a middle ground. On top of the basics, it adds a Protections dashboard, letting you know what the various blockers have actually, well, blocked, but it can also show you if some of your passwords have been hacked, it has a big library of extensions that you can use, including way more powerful ad blockers than what Epiphany offers, and full theming capabilities.

Chromium, in the other hand, is just a de-branded version of Chrome, so basically, it's the exact same browser, complete with Google account login, and all the bells and whistles. The only differences are that it lacks some codec support, and doesn't restrict users to the CHrome Web Store extensions. Speaking of extensions, CHromium has the biggest library out there, thanks to the aforementioned chrome web store. It's also not very well integrated with Linux desktops, although it can also be themed.

Brave is the most interesting: it's touted as a privacy focused browser, and it ships with its own custom ad and tracker blockers. Its private browsing mode actually uses TOR instead of just not saving your browsing history and cookies locally. It also includes something called Brave rewards, which basically gives you crypto tokens if you accept to watch ads, and these tokens can be used to reward various creators. In theory, it's a good idea, but the fact that Brave blocks the ads on these creator websites by default, and leaves the user to decide if their content is worth it might make some of you uncomfortable. I personally am, especially since not everyone can receive Brave Tokens. Brave touts faster speeds, but in my experience, it's only due to the default ad blocker. Add one to CHromium, and you get the same speeds.

Now, we also have Vivaldi, which also has tracking and ad blocking out of the box, user account syncing, but also goes crazier with the features. You can stack tabs, or open tabs side by side, although I don't see how that's more convenient than jus thaving 2 browser windows side by side, and it also uses a sidebar that lets you access some features, like the download manager, bookmarks, history, a note taking application, and some website shortcuts. As all chromium based browsers, it supports the extensions from the chrome web store, and it even lets you tweak the keyboard shortcuts. Vivaldi is basically the browser you want if you spend your whole day inside of it, and if you really want to tailor the experience as much as possible.

