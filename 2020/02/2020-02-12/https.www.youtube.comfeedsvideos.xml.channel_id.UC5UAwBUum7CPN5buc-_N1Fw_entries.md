# Source:The Linux Experiment, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw, language:en-US

## KDE Plasma 5.18 LTS: refinements and improvements, but nothing game changing
 - [https://www.youtube.com/watch?v=hHcdTut5Y1A](https://www.youtube.com/watch?v=hHcdTut5Y1A)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UC5UAwBUum7CPN5buc-_N1Fw
 - date published: 2020-02-13 00:00:00+00:00

KDE Plasma has a new release out: Plasma 5.18 LTS. As its name indicates, its a long term support version, which will be supported for 2 years. It should be included in all major distros that ship a KDE variant, and it comes with a bunch of new stuff, so let’s take a look !


Support the channel on Patreon: https://www.patreon.com/thelinuxexperiment
Follow me on Twitter : http://twitter.com/thelinuxEXP

The Plasma desktop has seen a bunch of improvements to its general usability in 5.18. The first thing is the disappearance of the top right “edit” menu. It was honestly pretty confusing and annoying to have it present at all times, so it’s been replaced by a simple right click on the desktop, and selecting “Customize layout”. This action brings up Global edit bar, on top of the screen, and it lets you access your widgets, your activities and the whole desktop layout options.

The system tray widgets have received a lot of love. A new one allows you to toggle night colour, which shifts the tones of your screen from blue to red to avoid too much blue light emission at night. It supports keyboard shortcuts as well if you want to set some.

The audio volume widget has been redesigned to be more simple and make it easier to change the audio source, and applications playing audio now sport a volume indicator in the task manager. Clicking on it allows you to quickly mute the app.

Smaller adjustments have been added all around, like in the weather widget, which now shows the wind speed as well, or the Kickoff menu, which has been made more touch friendly and uses circular icons for profile pics.

More notifications are now available as well, for example when a bluetooth device get to the end of its battery life, or file download notifications which allow you to quickly drag the file from the notification to where you want to store it.
The big one here is the new user feedback. Don’t worry, it’s all disabled by default, it’s an opt-in way for plasma users to give some feedback to the developers. It’s very granular, and lets you choose how much data you’re willing to share. In all cases, no personal information is ever sent to the plasma team, so you can crank that up all the way without risking any of your privacy, and the collected feedback will be used to improve plasma and identify the areas the developers need to focus on.

In the settings, the application styles window has been revamped with the grid view that permeated most of all the appearance settings. It makes it easir to look at the various themes and select the one you want to use. The grid view has also been applied to the global themes browser, so when you’re looking to download global themes to change your whole desktop’s look, you’ll be able to see a lot more accurately what the result will be.

Window animations are also now easier to tweak, with a slider allowing you to control the animation speed.

The search feature in the settings has also been improved, since it now filters as you type. This is a very nice improvement: KDE has often been roasted for offering too many options and making the settings unreadable, but this basically negates that concern: typing what you’re looking for is more intuitive than browsing through a list of categories trying to guess where the setting you want to tweak is located.

The major improvement is how KDE integrates with GTK applications. It now correctly supports client side decorations, which is about every GTK app using a headerbar these days. These didn’t display shadows before and the resize handles were inconsistent. It’s all in the past now, and these apps should look a lot more at home on a plasma desktop, apart from the fact that KDE apps don’t tend to use headerbars and sport menus and toolbars.

GTK applications should also inherit the plasma desktop’s settings for their theme, the icons they use, the mouse cursors, so they will be a lot better integrated with the system. It’s nice to see a bit more interoperability, since consistency in a desktop is important, and it’s not the user’s job to know which toolkit an application uses and if that toolkit is well supported on their desktop environment or not.

In Discover, Plasma’s package manager, the search field is now focused by default, so once you open it, you can immediately start typing and looking for what you need. It’s a small improvement, sure, but all in all, discover has outgrown its infancy issues and is shaping up to be a lot more reliable and user friendly than it once was.

Plasma should also perform better while using your GPU, and fractional scaling will now cause a lot less visual glitches. Nvidia GPUS are also included in the system monitor, so you can check a few stats on your graphics card.

A new emoji picker has also been added. You can bring it to front pressing Super + period.

