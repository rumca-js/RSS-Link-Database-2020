# Source:Luke Smith, URL:https://lukesmith.xyz/rss.xml, language:en-US

## Advice on Some Other Languages
 - [https://lukesmith.xyz/articles/other-langs/](https://lukesmith.xyz/articles/other-langs/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<p>This page is just for minor pointers on lesser studied languages that I
don't have enough to have on their own pages.</p>
<h2 id="gothic">Gothic</h2>

<figure class="resright"><img src="https://lukesmith.xyz/pix/lambdin-small.jpg" /></figure>

<p>Gothic is a dead language and the only thing existing in it is a
partially translated New Testament by Wulfila. It still is a very
important language for the study of Germanic and Indo-Europeanism
because it is the only language of &quot;Eastern Germanic&quot; so well
attested. Eastern Germanic languages are distinct from other Germanic
languages in their lack of umlaut and some other characteristically
Germanic features, while Gothic still retains some earlier Indo-European
inflectional categories.</p>
<p>I mention Gothic only because one of the best ever language learning
books I've ever seen is written for it, and that is Thomas Lambdin's
<em>Introduction to the Gothic Language</em>. I actually took a Gothic class
flippantly in graduate school, but the book stuck out to me as being
perfectly designed for the typical target audience of Gothic in
historical linguistics.</p>
<p>The book has very well designed lessons and activities, but I think
greatest is that in the back of the book, for each chapter there is a
corresponding lesson on the historical grammar of the content learned.
It goes through what conjugates of each word exist in English, Latin,
Greek or Sanskrit or other Indo-European languages and provided
comparative paradigms of noun and verb inflections. No word or concept
is left without a <em>real</em> mneumonic device, not a fake one fake from some
joke about the word, but one tied into the actual historical facts of
the word.</p>
<p>I've said before that one of the reasons I never use things like <em>Anki</em>
and &quot;spaced repetition software&quot; is that the real way to retain
information is to understand how it fits within a wider web of
information. In historical linguistics, you have an ideal of this
because the more you learn, the easier it is to &quot;remember:&quot;
remembering that the Gothic word for &quot;field&quot; is <em>akrs</em> is incredibly
simple when you realize it's the same as Latin <em>ager</em>, Greek <em>agrós</em>,
Sanskrit <em>ájra</em> and English <em>acre</em>.</p>
<h2 id="sanskrit">Sanskrit</h2>

<figure class="resright"><img src="https://lukesmith.xyz/pix/devavanipravesika-small.jpg" /></figure>

<p>Sanskrit is the crown jewel of Indo-European languages and there are
very few resources for it. Luckily, there is <em>Devavanipravesika</em> by
Goldman and Sutherland, which again is a star in terms of language
books.</p>
<p>I do recommend you have some of these abilities before attempting
Sanskrit:</p>
<ol>
<li>Some grammatical knowledge of a classical inflected Indo-European
language like Latin or Greek.</li>
<li>Knowledge of the Devanagari script which is used for Sanskrit
nowadays (also the script of Hindi and many other modern Indian
languages).</li>
</ol>
<h3 id="sandhi">Sandhi</h3>
<p>In English, if you say the sentence &quot;What are you up to?&quot; it usually
comes out closer to &quot;Whatchu up to?&quot; This kind of phonological
compression is a natural and systematic process in all languages. What
is interesting is that when written language was younger, it was very
common to express these phonological changes in the writing system
itself. It looks slangish in modern English to write &quot;whatchu,&quot; but it
is more accurate after all.</p>
<p>Sanskrit overtly writes every alternation like this, including when
words seem to combine together into a single prosodic word. The term for
this is [Sandhi]{.dfn}.</p>
<p>The tricky thing that newbies to Sanskrit must understand is that
knowing the principles of Sandhi are the first priority in knowing
Sanskrit because it's impossible to even parse a basic sentence before
you understand it. Phonemically, many Sanskrit words end in an -s, but
one of the first rules of Sandhi is that words <em>are not allowed to end
in -s in most cases</em>. So -s might show up as -h or -o or something else
depending on the phonetic context.</p>
<p>I say this because before you get excited about diving into Sanskrit,
you have to make sure you know the basics of Sandhi or it will all be a
mess.</p>
<h2 id="classicalkoiné-greek">Classical/Koiné Greek</h2>

<figure class="resright"><img src="https://lukesmith.xyz/pix/biglot.jpg" title="One of the books I've gotten the most use out of." /></figure>

<p>Greek, much like Spanish, I never really sat down to learn. Greek is
close enough in form to Latin that I learned it from reading a biglottic
Bible in both languages. Its grammar presents very few concepts alien to
Latin, the only big hurdles probably being the novel uses of the article
and if you want to learn classical Greek like a pro, the pitch accent
system.</p>
<p>What I mean is that I only read very little of Greek grammar before I
could pick up my Latin-Greek Bible and start reading the Greek with the
aid of the parallel Latin. This was also a nice experience because you
can see the similaries between the two languages, but also how the
expressiveness of Greek is sometimes lost in translation.</p>
<p>Greek, for example, has such a complete and elegant paradigm of
participles that many of them are unstranlatable in Latin. Latin has
only passive perfect participles and active present participles, while
Greek has participles for the whole spectrum of voice, tense and aspect.
What that means is that Latin has to talk around some common Greek
expressions, often utilizing Latin deponents (which can have perfect
active participle) to get the meaning across.</p>

## Command Line Bibles
 - [https://lukesmith.xyz/articles/command-line-bibles/](https://lukesmith.xyz/articles/command-line-bibles/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/deadsea-small.jpg" title="Where the Dead Sea Scrolls were found." /></figure>

<p>I've made a couple very useful command-line accessible Bibles for a
quick and scriptable lookup of Bible verses and passages. They exist not
only in English, but for Latin and Greek as well.</p>
<ol>
<li>English King James Version (including Apocrypha) &mdash;
<a href="https://github.com/lukesmithxyz/kjv">Github</a>,
<a href="https://gitlab.com/lukesmithxyz/kjv">Gitlab</a></li>
<li>Latin Vulgate &mdash; <a href="https://github.com/lukesmithxyz/vul">Github</a>, <a href="https://gitlab.com/lukesmithxyz/vul">Gitlab</a></li>
<li>Greek Septuagint &amp; New Testament &mdash;
<a href="https://github.com/lukesmithxyz/grb">Github</a>,
<a href="https://gitlab.com/lukesmithxyz/grb">Gitlab</a></li>
</ol>
<h2 id="installation">Installation</h2>
<pre><code>git clone https://github.com/lukesmithxyz/kjv.git
cd kjv
sudo make install
</code></pre>
<p>Or just replace <code>kjv</code> with <code>vul</code> for the Latin version or <code>grb</code> for the
Greek.</p>
<h2 id="usage">Usage</h2>
<h3 id="single-run">Single run</h3>
<p>Run the program name followed by a passage. The text will appear to you
in your pager. Arrows or vim-keys to scroll, <code>q</code> to quit.</p>
<pre><code>kjv rev 3:9
Revelation
3:9     Behold, I will make them of the synagogue of Satan, which say they are
        Jews, and are not, but do lie; behold, I will make them to come and
        worship before thy feet, and to know that I have loved thee.
</code></pre>
<p>Note that you may also give whole books or chapters. <code>kjv genesis</code> will
give you all of Genesis. <code>kjv mat 1:1-10</code> will show only Matthew 1:1-10.
Note also that you can usually abbreviate books.</p>
<h3 id="searching">Searching</h3>
<p><code>/</code> searches for patterns. For example, <code>kjv /offering</code> will search the
whole Bible for the word &quot;offering.&quot; You may specify a book/location
before it to search only that book.</p>
<h3 id="interactive-mode">Interactive mode</h3>
<p>Just type <code>kjv</code> (or <code>vul</code> or <code>grb</code>) alone to enter interactive mode. You
can then just type verses/books without prefixing them with the command
name each time if you prefer.</p>
<h2 id="origin">Origin</h2>
<p>I forked the original software from <a href="https://github.com/bontibon/kjv">this
repository</a> which is an incomplete
English King James Version (without the Apocrypha). With the use of
coreutils and vim, I found online texts of the Apochrypha, Vulgate,
Septuagint and the <a href="http://sblgnt.com/download/">SBL New Testament</a> and
formatting them to function with this program.</p>

## Hating Brave is Cool!
 - [https://lukesmith.xyz/articles/hating-brave-is-cool/](https://lukesmith.xyz/articles/hating-brave-is-cool/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/leshilllion.png" title="le shill lion" /></figure>

<p>I like and use the Brave Browser. It's a <strong>free and open source
browser</strong> with features like:</p>
<ol>
<li>Ad-blocking by default.</li>
<li>Tracker-blocking by default.</li>
<li>Anti-fingerprinting mechanisms to prevent you from being monitored.</li>
<li>Built-in Tor windows.</li>
<li>Run by a based Christian and not furry leftists.</li>
</ol>
<p>As far as I'm concerned, Brave is indisputably the best out-of-the-box general-purpose
browser out there. There are other okay browsers, and I'll mention
things about Brave I don't like, but Brave is especially good because
it comes with all of these sensible features out of the box (you don't
have to go install an ad-blocker), so this makes it very good for
installing it on your grandma's computer. The anti-fingerprinting
abilities are even unique among power-user browsers.</p>
<p>Despite that, there is a loud clique of anti-Brave agitators and Brave
skeptics. Whenever I do a video on Brave, I can expect at least 20%
dislikes and a torrent of comments from people with anime avatars
calling me a &quot;shill&quot; for &ldquo;recommending&rdquo; this browser.</p>
<p>This, I suspect, is because Brave has an optional extra feature: Brave
Rewards, which is &quot;too good to be true.&quot;</p>
<h2 id="brave-rewards">Brave Rewards</h2>
<p>By default, Brave blocks all ads, but users can turn on &quot;Brave
Rewards&quot; to voluntarily view occasional ads and will receive a small
amount of Basic Attention Token (BAT), Brave's cryptocurrency. The ads
don't mess up webpages by appearing in them, but appear in their
computer's notification system.</p>
<p>Brave's entire motivation is to replace traditional ads that fill up
webpages with these kind of ads that share revenue directly with the web
page owners and the people browsing the sites themselves. Ad companies
disappear, the internet debloats and users and actual sites get a direct
cut.</p>
<p>This ad feature is not just <em>optional</em>, but is <em>disabled by default</em>.</p>
<h3 id="the-archetypical-brainlet-brave-skeptic">The Archetypical Brainlet Brave Skeptic</h3>
<blockquote>
<p>&ldquo;The fact that brave has exploded on the scene so quickly make me
suspicious. There's money involved somewhere.&rdquo; &mdash;Comment on a
YouTube video of mine</p>
</blockquote>
<p>Yes. Because <strong>Brave users literally get money to browse with it.</strong> Duh.</p>
<p>So there is no conspiracy theory about this. <strong>Brave just does
everything right as a browser and they give you free money.</strong> In the
Basic Attention Token system, companies buy ads and the revenue is
shared directly by the owners of sites and the people who view the ads.
This cuts out the middleman ad-companies from the internet. It removes
and disincentivizes bloat in webpages. This is a drastically more
effective and bloatfree way to monetize the internet than old-school
ads. <strong>Or,</strong> you can just keep <em>the default functionality</em> where there
are no ads.</p>
<p>I literally have people post on my videos constantly about how Brave is
a big scheme and &quot;you'll never see a cent of that money.&quot; Meanwhile,
literally every Brave user, including me, gets a monthly payout. You can
even receive your payout directly in US dollars if you want! Even if the
Basic Attention Token framework totally flops, it's not like you're
putting any money into it. The worst that can happen is you saying, &quot;Oh
no, all I have left is the browser with the best out-of-the-box
functionality!&quot;</p>
<p>It reminds me of the joke of two economists walking down the street. One
says, &quot;Hey look, there's a $100 bill on the sidewalk!&quot; The other one
replies, &quot;That's not possible, if there were, someone would've picked
it up already.&quot;</p>
<p><strong>The anti-Brave crowd's argument is always some form of &quot;it's too
good to be true.&quot;</strong> In reality, you don't realize how inefficient and
wasteful the previous way of internet ads was. Why pay an ad agency with
employees to pay website developers to put ads into the actual code of
websites, contorting it all into a mess? The BAT system and Brave just
cuts out the middle man and keeps webpages clean by allowing ads to only
be shown when wanted in the user's already existing notification
system. The goal of the BAT project is to universalize Brave and perhaps
similar browsers which block ads and trackers by default, thus cutting
off the very lifeblood of that inefficient and anti-social system.</p>
<p>If you still don't trust the BAT project or think it's gimmicky,
great. <strong>By default, the &quot;Brave Rewards&quot; system is off.</strong> Complaining
about Brave because it has an optional feature to make money is like
complaining about another browser because it has an add-on you don't
plan on using.</p>
<h3 id="tactical-ignorance">Tactical Ignorance</h3>
<blockquote>
<p>&ldquo;I use to love brave. NOT anymore.. I'm sure that they are
fingerprinting and using my browsing habits and even search queries
and shows relevant ads. It is not like they are showing some random
pop up for ads. I get ads for NordVPN if I search for best vpn 2020. I
instantly get pop up for lenovo laptops as soon as I search for
laptop. Obviously, with all the utm source and other tracking stuff. I
am making around 15 BAT/month. I don't need those pennies. Back to
Firefox with Ublock Origin and Privacy Badger.&rdquo; &mdash;Comment on a
YouTube video of mine</p>
</blockquote>
<p>This guy is literally talking as if how Brave works is some kind of
mystery, as if its <em>entire code base</em> isn't openly auditable. No, Brave
doesn't take or &quot;fingerprint&quot; your browsing habits, instead, if you
are enrolled in Brave Rewards, you browser pulls the entire list of adds
from the system, then <em>locally</em> decides on your own computer what ads to
serve.</p>
<p>On <a href="https://brave.com/faq/">Brave's FAQ</a>:</p>
<blockquote>
<p>&ldquo;Only the browser, after HTTPS terminates and secure pages are
decrypted, has all of your private data needed to analyze user intent.
Our auditable open source browser code protects this intent data on
the client device. Our server side has no access to this data in the
clear, nor does it have decryption keys. We do not run a MitM proxy or
VPN service. We provide signals to the browser to help it make good
decisions about what preferences and intent signals to expose to
maximize user, publisher and advertiser value. Each ad request is
anonymous, and exposes only a small subset of the user&rsquo;s preferences
and intent signals to prevent &ldquo;fingerprinting&rdquo; the user by a possibly
unique set of tags.&rdquo;</p>
</blockquote>
<h2 id="is-brave-bad-for-privacy">Is Brave bad for privacy?</h2>
<p>A popularly linked Neocities site <a href="https://spyware.neocities.org/articles/brave.html">Spyware
Watchdog</a> ranks Brave
as having a rank of &quot;High&quot; spyware. The information on the site is
generally good, but a little context-less: if you compare their Brave
article to <a href="https://spyware.neocities.org/articles/index.html">their articles on other
browsers</a>, this bad
ranking for Brave is utterly out of place.</p>
<p>Many people who read things and lack basic critical thinking skills
wanted me to either admit or refute this page. Again, the website's
information is good, but there is that same implicitly more skeptical
standard held to Brave than other browsers.</p>
<p>As a point of comparison, take the browser Pale Moon. On their site, the
Spyware Watchdog <a href="https://spyware.neocities.org/articles/browsers.html">classifies Pale Moon as being &quot;Top Tier&quot; in privacy,
while Brave is &quot;Low
Tier.&quot;</a> But if
you look at <a href="https://spyware.neocities.org/articles/palemoon.html">their own
analysis</a>, on
<em>nearly every point</em>, <strong>Brave is superior to Pale Moon</strong>.</p>
<table>
<thead>
<tr>
<th>Issue</th>
<th>Brave&rsquo;s Flaws</th>
<th>Pale Moon&rsquo;s Flaws</th>
</tr>
</thead>
<tbody>
<tr>
<td>Trackers</td>
<td>Brave blocks ads and trackers, but whitelists Facebook and Twitter to not break cross-site logins for normies. Users can still choose to block these sites in the settings menu.</td>
<td>Pale Moon does not block any ads or trackers at all, so tough luck. Go find an extension that works well with it.</td>
</tr>
<tr>
<td>Forced incompatibility</td>
<td>None.</td>
<td>Pale Moon ships with a blocklist of add-ons that the developers don't want you installing. This includes NoScript and Ad Nauseam.</td>
</tr>
<tr>
<td>Auto-updates</td>
<td>Brave checks for updates on startup. (I'm not sure if this is the case on Linux too). There is no menu option to disable this but you can block connections to the update site in your hosts file.</td>
<td>Pale Moon automatically checks for updates, add-on updates and changes to the add-on blocklist on start-up. In the <code>about:config</code> some of these can be disabled.</td>
</tr>
<tr>
<td>Analytics on the Start Page</td>
<td>Brave connects to a free/open source Piwik service to get the number of ads/trackers blocked for the startpage. This can be disabled on the start page.</td>
<td>Pale Moon <strong>connects to Google analytics</strong> on the start page. This can be disabled by changing the start page.</td>
</tr>
<tr>
<td>Other bad connections</td>
<td>If ads are enabled, Brave makes connection to a site to get ads. It also checks a HTTPS ruleset on an <strong>Amazon server</strong>.</td>
<td>Pale Moon makes a OCSP request for <strong>every website you connect to</strong> to verify their SSL with a third party. This can be turned off in the options.</td>
</tr>
</tbody>
</table>
<p>On pretty much all of these points, when Brave is lacking, Pale Moon is
much worse (that isn't to say that Pale Moon is a bad browser either).
So it doesn't really make sense to me why Brave, which also comes with
additional privacy features like fingerprint-blocking, should be
classified as <em>lower</em> than Pale Meme. That site also claims that Brave
uses the Google search engine as default. If that was ever true, it
isn't now, or at least not on any version of Brave I've used. Brave
asks the user on the first start up which search engine he would like to
use as default. Google is among the choices though.</p>
<p>Note that in their articles they admit that Pale Moon has
&quot;auto-updates,&quot; but complain that Brave has &quot;shitty auto-updates.&quot;
Okay. I wonder what the difference is aside from personal emotion. In
the last paragraph or so, they do mention, if not skirt around all the
<em>actual features</em> of Brave:</p>
<blockquote>
<p>&ldquo;and the fingerprinting protection I don't think is found in any
other browser (but I didn't confirm if it actually works).&rdquo;</p>
</blockquote>
<p>It does (of course it's an arms-race). But this is an acknowledgment
that Brave is fighting on a level that no other browser is. While other
honorable browsers like Ice Cat are committed to free software, Brave is
also committed to an internet free from ads enmeshed in web pages and
the people who simp for them.</p>
<h2 id="brave-for-normies">Brave for normies</h2>
<p>Aside from nit-picking different browsers, if you want to install a
browser on a computer for a normie relative or friend, <strong>there is no
debate that Brave is the best</strong>. Again, Brave is <em>built</em> with ad and
tracker blocking. Browsers like Pale Moon or Firefox are bad browsers
that <em>can become</em> okay browsers after you manually disable their junk
features and download a bunch of add-ons, but Brave comes as it should
be. Even Brave's token feature of viewing ads to get paid is not on by
default. As it ships, Brave is just a good browser.</p>
<p>This is why I have Brave ship with <a href="https://larbs.xyz">LARBS</a>: it's a
pain to hosts a repository and edit browser settings via dotfiles, while
I can just have Brave installed and that gives a passable, ad-free
experience for users.</p>
<p>So if you want to make a normie's life easier, install Brave. They will
be able to do everything they could do on Chrome, but now they have
decreased their Google liability and no longer have to put up with ads.</p>
<h2 id="grasping-at-straws">Grasping at Straws...</h2>
<h3 id="chromium-based">Chromium based</h3>
<p>When you corner an anti-Brave aggitant, they usually mumble something
about how Brave is bad because it's &quot;Chromium-based.&quot; I've never
seen people use this argument about, say, qutebrowser or other minor
Chromium-based browsers, but I think it's just become &quot;that reason&quot;
for Brave. I honestly, really can't get worked up against a free and
open source software project just because it's been spearheaded by
Google. The ability to fork it always remains if the code goes south or
if it does degenerate stuff.</p>
<p>I think it's especially absurd to place your trust in Mozilla FurryFox
and their team of stereotypical SJWs and soydevs as a functioning
alternative. Remember Mozilla spends its money <a href="https://foundation.mozilla.org/en/campaigns/regrets-reporter/">developing fun add-ons
like
this</a> to
&quot;protect&quot; people emotionally from scary &quot;conspiracy theories&quot; and
&quot;alt-right content&quot; on YouTube. I consider Google just as insane and
dangerous, but not necessarily so much <em>more</em> insane so that I for some
reason trust the judgment of Mozilla developers over Google ones.</p>
<p><strong>EDIT:</strong> Here's another one from Mozilla FurryFox: <a href="https://archive.is/hzS8G">&quot;We need more
than deplatforming&quot;</a> Moreso than Google,
Mozilla's openly stated goal is an internet totally controlled by
stereotypical dyed-hair SJWs with bad physiognomy.</p>
<p>What I mean by this is, sure, I'd <em>like</em> some browser with an
independent engine. Pale Moon does sort of has that. That's cool. But
that is not enough to make a difference for actual usage. Again, look at
the list of benefits of Brave at the top of this article, all of those
are hard to replicate or find in other browsers. I could go into it
elsewhere, but there are a million little reasons why I don't use Pale
Moon (but you might like it).</p>
<h3 id="affiliate-links">Affiliate links</h3>
<p>Twitter users/Redditors went apoplectic several months ago when they
realized Brave had included affiliate links to some sites whose names
are filled in in the url bar. <a href="https://lukesmith.xyz/blog/le-shill-lion">I have already written on
this.</a> It's literally
nothing. As I say there, this is what affiliate links are for. I've
never heard the same crowd through a fit that DuckDuckGo <a href="https://help.duckduckgo.com/duckduckgo-help-pages/company/advertising-and-affiliates/">does exactly
the same
thing</a>.
You could even actually see the Brave affiliate links fill in, which is
<em>not</em> the case when clicking on a DuckDuckGo affiliate site link. Still
took these guys months to even notice... This is only something
&quot;controversial&quot; to people who are trying their damnedest to find
something to not like about Brave.</p>
<h2 id="actual-good-complaints-about-brave-and-bat">Actual good complaints about Brave and BAT</h2>
<p>Since most visceral anti-Brave agitators just have a kind of general ax
to grind, I want to take this time to voice my actually annoyances with
Brave and the BAT project. I consider all of these ultimata: I only use
Brave with the expectation that these issues will be fixed in the
future.</p>
<h3 id="get-rid-of-uphold">Get rid of Uphold!</h3>
<p>Actually, let me say that in &lt;h1&gt;...</p>
<h1 id="get-rid-of-uphold-1">Get rid of Uphold!</h1>
<p>So you can get BAT from viewing ads, and people with websites and
YouTube channels can receive donations, great. The annoying thing
however is that you can't just get payouts to a random Ethereum wallet,
instead, you have to use the company <em>Uphold</em>. This is probably
because of legal issues and because I'm sure they have some financial
arrangement, but the BAT project cannot be considered to be a universal
and private solution if users are funneled into some site that requires
a real-world identity.</p>
<p>Legally or technologically difficult to do otherwise? Maybe. But that is
one of the goals of cryptocurrencies anyway and it should be met. Build
the technology so that it's impossible to legally constrain. Most
blockchain technology <em>is already</em> like that.</p>
<p>Users should just be able to give a public Ethereum/Token address and
receive BAT there. That should be it. If you want to offer a
normie-friendly partner service like Uphold, fine, but that should not
be either the default or required. Uphold, I should say, is definitely
not normie-friendly anyway. Since they did a redesign late
September/early Ocotober, I admit I literally cannot figure the site out
and how to transfer my BAT out efficiently.</p>
<p>I should say, in development Brave has had some suboptimal or
non-private features in the past before better solutions were devised. I
mentioned the fact that Brave pulls a non-personalized ad list, but that
wasn't always the case to my understanding: when Brave was starting
out, the browser did request specific ads, giving the central service
some information about user browsing habits. So that at least indicates
that Brave is open to reevaluating methods that are exploitable.</p>
<h3 id="bat-as-a-coin">BAT as a 💩coin</h3>
<p>Let me state it again though, <strong>if the BAT system requires Uphold for
basic functionality, it is not a serious long-term service</strong>. That's
it. I only use and recommend the BAT system under the expectation that
this is a temporary situation that they are actively seeking to remedy.
If anti-Brave shills want to shill about something <em>that actually
matters</em>, <strong>this should be it!</strong></p>
<p>Like most 💩coins, BAT is not decentralized in any meaningful sense. It&rsquo;s KYCed into oblivion and relies on a significant number of platforms in bottleneck positions, including in particular the BAT Project itself. I wouldn&rsquo;t say I even support the BAT Project itself for this reason, I just don&rsquo;t mind using Brave since you can dip your fingers into it without getting KYCed.</p>
<h3 id="auto-updates-and-integrations">Auto-updates and integrations</h3>
<p>I agree strongly with the argument from the Spyware Watchdog site above
that Brave should not make any unsolicited requests to sites, especially
auto-updates, and if it has a reason to, it should have some menu option
to disable it. Any connections a browser makes in the background for
these purposes or for analytics <strong>should be disabled by default</strong> too.</p>
<h3 id="the-browser-should-be-neutral-and-decentralized">The Browser should be neutral and decentralized.</h3>
<p>Somewhat related to the above, if Brave is actually serious about
becoming the commonly used system not just for browsing, but for
internet monetization, it has to be as neutral and decentralized as
possible. Brave has added a lot of optional features for different
services and other little annoyances. Obviously, you can immediately
disable them, but if you want to have a personalizable and universal
browsing experience, Brave should be absolutely blank when you pull it
up on a fresh install.</p>
<h3 id="general-little-features">General little features</h3>
<ul>
<li>The ability to not keep track of history but to still keep cookies.
All Chromium browsers lack this menu feature which exists in
Firefox. I'm not sure why this isn't an option because it has
always seemed to me the most sensible way to browse. I don't want
sites I've already seen filling in my url bar!</li>
</ul>

## Learn Chinese
 - [https://lukesmith.xyz/articles/learn-chinese/](https://lukesmith.xyz/articles/learn-chinese/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/qing.gif" title="The Chinese flag back when it was more based before being subverted by communists and democrats." /></figure>

<p>Chinese is the hardest language to learn according to normies who have
never tried to learn it.</p>
<p>In reality, Chinese is really easy. It has literally no complex
morphology: no tense, plurals, gender. It doesn't have irregular verbs
or nouns because it has no verb and noun endings whatsoever. It's
almost difficult to explain how easy Chinese is.</p>
<p>The only different thing is the writing system which is I hesitate to
say anachronistic. The Chinese character system is more structurally
similar to Sumerian cuneiform than to English morphophonemic writing.
That presents a unique hurdle, but one if properly tackled is not too
difficult and also edifying. It's important to realize in any case that
<em>learning a language and learning its writing system are two separate
things</em>.</p>
<p>Knowing this is important for mastering or even beginning Chinese.</p>
<h2 id="these-are-the-best-chinese-books">These are the best Chinese Books</h2>
<p>The Yale series by John DeFrancis is not just the absolute best for
learning Chinese, but they are an eternal exemplar of basically the best
you can do for any language. The books all have generic names and
they're linked below with audio. The books are <strong>massive</strong>. Even if you
just get &quot;Beginning Chinese&quot; and &quot;Beginning Chinese Reader, Part 1,&quot;
you'll know around 4 semesters worth of Chinese compared to your
average university course. They have free audio too. Remember that if
you get nervous about their price tags, which might be as high as $50.
These books are severely worth it though.</p>
<p>There are actually two parallel book series in the DeFrancis/Yale
series: the <a href="https://lukesmith.xyz/rss.xml#green">green books</a>, which cover the spoken language (in
Romanization) and the <a href="https://lukesmith.xyz/rss.xml#red">red books</a> (the readers) that cover
characters. It might sound strange to cover the language itself and the
characters separately, but it is <em>massively</em> superior.</p>
<h3 id="green">The Green Books (for the language)</h3>

<figure class="resright"><a href="https://yalebooks.yale.edu/book/9780300020588/beginning-chinese"><img src="https://yalebooks.yale.edu/sites/default/files/styles/book_jacket/public/imagecache/external/478b0744626b90030043cff06649da88.jpg?itok=GNVvraEn" /></a></figure>

<p>The great thing about the main series is that <em>they come with many, many
exercises and drills</em> which are actually good for individual use. Books
that expect you to read something once and internalize it are
irreparable.</p>
<p>Links are to the official Yale site. Probably better to buy on eBay or
something though. Worth the money even when they are expensive.</p>
<ul>
<li><a href="https://yalebooks.yale.edu/book/9780300020588/beginning-chinese">Beginning
Chinese</a>
(<a href="https://archive.org/details/podcast_beginning-chinese_705335764">audio</a>)</li>
<li><a href="https://yalebooks.yale.edu/book/9780300000641/intermediate-chinese">Intermediate
Chinese</a>
(<a href="https://itunes.apple.com/us/itunes-u/intermediate-chinese/id714087247?mt=10">audio</a>)</li>
<li><a href="https://yalebooks.yale.edu/book/9780300000566/advanced-chinese">Advanced
Chinese</a>
(<a href="https://itunes.apple.com/us/itunes-u/advanced-chinese/id716758957">audio</a>)</li>
</ul>
<p>You can get .pdfs of all these books on Library Genesis. I have physical
copies, except some an ex-girlfriend borrowed and never gave back. If
you read this, you better send them back!</p>
<p>Note that I've also linked audio that was recorded for these books,
which is great. They used to cost a lot too, but now they're free!</p>
<h3 id="red">The Red Books (for characters)</h3>

<figure class="resright"><img src="https://yalebooks.yale.edu/sites/default/files/styles/book_jacket/public/imagecache/external/2e28a044fcf820cc8a8624c30530e31c.jpg?itok=rEV2_fKY" /></figure>

<p>The reason the language in transliteration and the characters are in two
books is because learning them is really two different processes. The
green books are more typical language learning books. The red
books/readers are different.</p>
<p>Every chapter, they teach you 10 characters, but with those 10
characters, you might learn to combine them into 50 new words based on
them. The pacing here is for only learning the essential and most used
characters as simply as possible as you advance. The readers do not
explain grammar and expect you to be advancing in the green books to
understand grammatical things.</p>
<ul>
<li><a href="https://yalebooks.yale.edu/book/9780300020601/beginning-chinese-reader-part-1">Beginning Chinese Reader, Part
1</a>
(<a href="https://archive.org/details/podcast_beginning-chinese-reader_712302997">audio for parts 1 and
2</a>)</li>
<li><a href="https://yalebooks.yale.edu/book/9780300020618/beginning-chinese-reader-part-2">Beginning Chinese Reader, Part
2</a></li>
<li><a href="https://yalebooks.yale.edu/book/9780300000658/intermediate-chinese-reader-part-i">Intermediate Chinese Reader, Part
1</a>
(<a href="https://itunes.apple.com/us/itunes-u/intermediate-chinese-reader/id716628737?mt=10">audio for parts 1 and
2</a>)</li>
<li><a href="https://yalebooks.yale.edu/book/9780300000665/intermediate-chinese-reader">Intermediate Chinese Reader, Part
2</a></li>
<li><a href="https://yalebooks.yale.edu/book/9780300010831/advanced-chinese-reader">Advanced Chinese
Reader</a>
(<a href="https://itunes.apple.com/us/itunes-u/advanced-chinese-reader/id716763840">audio</a>)</li>
</ul>
<h3 id="the-blue-books">The Blue Books?</h3>
<p>I won't link them because they sort of the defeat the point, and I
don't have them, but there is also a blue series which is just the
green series but with the language in characters. I think it's intended
more for classes that can't do the DeFrancis method due to bureaucratic
constraints. If it has the exercises of the green books, that's good
and all, but really the value of the system is the fact that when you do
the spoken language in the green books, you don't have to worry about
unknown characters and when you do the characters in the red book,
that's all you need to pay attention to.</p>
<p>I'm not dismissing the blue books, because the quality of the
Yale/DeFrancis series is still light-years ahead of all other series,
but I'd stick with the classics here.</p>
<h2 id="notes-about-chinese">Notes about Chinese</h2>
<h3 id="the-tone-cope">The tone cope</h3>
<p>I remember having normalfriends in my Chinese class (which was a waste
of time, just get the DeFrancis books) who would say that Chinese
wasn't too hard &quot;except for the tones.&quot; Mandarin Chinese has four
tones that distinguish words. If you've sat through your first day in
Chinese class or even seen a YouTube video on Chinese, you know this.</p>
<p>Normies see this alien concept of having tones and they turn their
brains off. There were kids in my class who said they'd &quot;just not
learn&quot; the tones. Which is sort of like saying you're going to learn
English, but not the vowels &quot;because they're too hard.&quot;</p>
<p>Actually around half of the world's languages have tones. They are not
bizarre or highly &quot;marked&quot; in an objective sense. They are much more
common that the &quot;th&quot; sound in English. You can bear it.</p>

## Learn Latin
 - [https://lukesmith.xyz/articles/learn-latin/](https://lukesmith.xyz/articles/learn-latin/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/romanpep.gif" /></figure>

<p>Latin was the first language I learned and has probably been the most
useful. Here I'll talk about some of the things it's gotten me and
some recommendations for how to learn it well.</p>
<h2 id="what-ive-gotten-out-of-learning-latin">What I've gotten out of learning Latin</h2>
<h3 id="you-get-multiple-languages-for-one">You get multiple languages for one.</h3>
<p>Latin, as you probably know is the ancestor of Italian, French, Spanish,
Portuguese, Romanian, etc. Once you know Latin, it is quite literally
downhill learning any of these. In college, I decided to take Spanish
for a degree specialization (I was doing an international business thing
and required a foreign language). Merely based on my knowledge of Latin,
I just tested into fifth-level Spanish and figured it out from there. I
don't even remember learning Spanish, but I can speak it and still do
every once in a while.</p>
<p>In grad school I took classes taught in Spanish and French. I can
basically read all Romance languages. I even read Rhaeto-Romance poetry
for fun (the languages of Switzerland). All of this is nearly free stuff
when you learn Latin.</p>
<h3 id="latin-will-unironically-red-pill-you-on-many-subjects">Latin will unironically red-pill you on many subjects.</h3>
<p>Looking to other cultures in the world might change your view of things
in some superficial way, but looking into the past will revolutionize
how you see it. A recurring point I make in many contexts is that <strong>the
past is literally an alien civilization</strong>. Most of what people pretend
they know about it is repeatedly cited modern rumors about it. Seeing it
in its own words is very different.</p>
<p>It's insane the amount of writing done in Latin in the medieval period
and antiquity, so much of which isn't even on the mind of translators.
A lot of historians just cite modern historians. Theologians cite modern
theologians. Scientists cite modern scientists. Once you crack open a
traditional book on any of these subjects you realize the provinciality
and oblviousness of modern &quot;frameworks.&quot;</p>
<p>In generative linguistics, people who have never read anything written
before 1950 pat themselves on the back for all the &quot;problems&quot; they've
solved not knowing they are only retreading paths long established by
Stoics, Modistae and early Indo-Europeanists. There are a lot of
theologians and philosophers who are trapped in modern citation circles
because they don't have the power of Latin that can bring them in touch
directly with Aquinas or Augustine or other philosophers of the early
periods.</p>
<p>Knowing Latin is like an academic superpower and supposed intellectuals
will fear you. Latin used to be the bare minimum of a respectable
intellectual... actually... you know what, it still is. Now is your
chance to have an actual one up over more pompous people whose only
function is writing lit reviews with a disability to read original
sources. Being privy to an original and long-neglected source will be a
continuous content mill which will unironically be the envy of others in
academia.</p>
<h3 id="knowing-latin-is-better-academically-than-an-undergraduate-degree-in-linguistics">Knowing Latin is better academically than an undergraduate degree in linguistics.</h3>
<p>The process of learning Latin and the lore around you will equip you
with all the terminology and principles to make you superior to someone
who just studies &quot;linguistics&quot; without any actual application. I
really mean this. When I was a grad student in linguistics, all the
brightest undergrads had one thing in common: Latin. I actually came to
judge people based on how they first got interested in linguistics. The
smartest ones always started with Latin, the biggest plebs always
started because they liked some Steven Pinker book (sorry Pinkucks!
Those are the honest facts!)</p>
<h2 id="how-to-learn-latin">How to Learn Latin</h2>

<figure class="resright"><img src="https://lukesmith.xyz/pix/magister.jpg" /></figure>

<h3 id="what-i-used">What I used</h3>
<p>When I learned Latin, all I had was a copy of <a href="https://www.textkit.com/learn/ID/113/author_id/41/">this
book</a>: Collar &amp;
Daniell's <em>Beginner's Latin Book</em>. The truth is that most <em>old</em> Latin
books are good (old being at least 70 to 100 years old). After language
learning became commercialized, it all became dismissable. You can see a
list of downloadable Latin textbooks and other materials here
<a href="https://www.textkit.com/latin_grammar.php">here</a>.</p>
<p>The only other source I used in the past to learn and read Latin in a
biglottic Latin/Greek New Testament (i.e. Greek on the left and Latin on
the right). This is probably actually the single most significant book I
own, now that I think about it. I learned Greek from it too and I've
had it for around 15 years now.</p>
<h3 id="lingua-latina-per-se-illustrata">Lingua Latina per se Illustrata</h3>
<p>Although I didn't know about until later, there is another very unique
and excellently made Latin series called <em>Lingua Latina per se
Illustrata</em> &quot;The Latin Language Illustrated by Itself&quot; by <a href="https://lingualatina.dk/wp/">Hans
Orberg</a>. You can see an English publisher
<a href="https://www.hackettpublishing.com/lingua-latina-per-se-illustrata-series">here</a>,
but you can also find them on eBay or pdfs on Library Genesis or Pirate
Bay (along with audio for the books).</p>
<p><em>LLPSI</em> is unique and really stands out. <strong>The entire book, including
explanations is in Latin.</strong> Latin words and grammatical concepts are
explained by illustration and example. This sounds absurd frankly: how
are you supposed to learn a language from a book written in that
language? But the design is so perfect that it works.</p>
<p>I recommend to get <em>LLPSI</em> <em>and</em> some classical grammar primer like
<a href="https://www.textkit.com/learn/ID/113/author_id/41/">Collar &amp;
Daniell's</a> because
I think especially for newbs, it might be necessary to have explicit
instruction about grammar points in English.</p>
<h2 id="read-this">Read this</h2>
<p><a href="https://wcdrutgers.net/Latin.htm">Read this article: &quot;Latin by the Dowling
Method.&quot;</a> It's back from the early
internet and its recommendations have stood the test of time and I agree
with them.</p>
<h2 id="latin-links">Latin links</h2>
<p>You may've known about these already, but they're worth noting.</p>
<ul>
<li><a href="https://www.thelatinlibrary.com/">The Latin Library</a> &ndash; Massive
collection of classical and
<a href="https://www.thelatinlibrary.com/medieval.html">medieval</a> Latin
works</li>
<li><a href="https://www.textkit.com/">Textkit</a> &ndash; Greek and Latin resources and
forum</li>
</ul>

## Learning European Languages (Michel Thomas)
 - [https://lukesmith.xyz/articles/learning-european-languages-michel-thomas/](https://lukesmith.xyz/articles/learning-european-languages-michel-thomas/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<figure class="titleimg"><a href="https://lukesmith.xyz/pix/hensel1741.jpg"><img alt="From Gottfried Hensel's 1791 *Synopsis Universae Philologiae*" src="https://lukesmith.xyz/pix/hensel1741-small.jpg" title="A language map from Hensel's 1741 Synopsis Universae Philologiae." /></a></figure>

<p>I've said on a couple livestreams that the ideal way for an English
speaker to begin learning or excel in learning other major European
languages (Spanish, French, Italian and German) is to use <strong>Michel
Thomas's audiotapes</strong>. They can be found for free on Pirate Bay and
other sites, but you can also buy them <a href="https://www.michelthomas.com/">on his official
site</a>.</p>
<p>This style of audiotapes is so far above any other, it's hard to even
put it in words. They make really exceptional promises: &quot;learn a
language in 8 hours&quot; and in some sense I'm inclined to agree.</p>
<p>They certainly give a reflexive foundation that makes learning anything
else about a language very easy. There are multiple courses and they're
worth listening to multiple times until it's a totally internalized.</p>
<h2 id="explanation-of-the-method">Explanation of the Method</h2>
<p>The tapes all have Thomas locked in a room with two people who don't
know the language, one male, one female. Thomas simply teaches and
illicit basic responses from the two students, teaching them as they go.
As the listener, your part is to say the proper responses to yourself
before the example students. At all points in time, the students are
creating novel sentences, combining basic concepts.</p>
<h3 id="lack-of-vocabulary">Lack of vocabulary</h3>
<p>Probably the most important part of the tapes is the <em>lack</em> of
vocabulary taught. You don't get 20 irrelevant nouns with each lesson
to memorize that you don't even now how to use. What new words you
&quot;learn&quot; are mostly shared in common with English. The goal is to make
you fluent before you have to memorize words.</p>
<p>Thomas, instead, <em>actually teaches the language</em> and how to be
constructive in it: the verbs, the verb inflections, how to combine
them, basic pronouns and the like. Only once the students understand
them does he move on to the words for real-world objects. Thomas will
sometimes explain why he does this in the course, but it amounts to what
I've said <a href="https://lukesmith.xyz/learning-languages.html">in other places</a>: you can guess or
figure out nouns or talk around them, but if you don't know how to put
verbs together, you just don't know the language and you can't even
fake it. <strong>It is much easier to learn nouns after you actually learn the
structure of the language and can actually use them.</strong></p>
<h3 id="lack-of-comprehension">Lack of &quot;comprehension&quot;</h3>
<p>You're never told to &quot;listen to this passage and think about what it
means&quot; in the Thomas method. The Thomas method is entirely productive:
<em>you</em> make the sentences and <em>you</em> have to put yourself in the mindset
of how the language works.</p>
<p>A lot of other audiotapes, say Pimsleur, have you sit and listen to text
and implicitly ask you to &quot;translate&quot; it. This in essense, keeps you
thinking in English, or thinking in translating mode. The also keep you
chained to canned responses in a single dialog. When people do this,
they ignore the actual structure/grammar of the language, listen for big
noticable nouns, and then piece together what the sentence means. This
is always a bad idea.</p>
<h3 id="michel-thomas-actually-just-knows-what-hes-doing">Michel Thomas actually just knows what he's doing.</h3>
<p>It's honestly rare that you even ever see a &quot;good teacher.&quot; By that I
mean someone who can easily keep track of what his students know and can
devise questions perfect to pry their knowledge. Thomas is just honestly
good at this and it goes a long way. In the tapes, if he notices that a
student repeatedly messing something up, he knows how to elicit better
responses and remind them of what they need. This is 99% of teaching,
despite the fact that it's a really rare skill.</p>
<h2 id="dont-bother-getting-the-tapes-without-michel-thomas">Don't bother getting the tapes without Michel Thomas</h2>
<p>After Michel Thomas's death (or perhaps a little before) the company
running his website above put out tapes for many other languages:
Chinese, Arabic, Hindi, Japanese, etc. under his name. They are done
&quot;in his method&quot; theoretically, but they are no good. They do weird
things like have two different teachers: one who instructs the students
and one who is a native speaker of the language to say the sentences in
it. I think the idea behind it was to make sure you hear a &quot;perfect&quot;
accent, but it's a total waste and the sponteneity required for actual
teaching is lost because you have these two different people trying
organize among themselves. I think the teachers lack the introspective
skill to keep tabs on the students' learning that I mentioned above, so
all-in-all, I think they're awkward and fake.</p>
<p>Donovan Nagel (you may know him from <a href="https://www.youtube.com/channel/UCk9NvmsPBC3lTn_L9kFaylA">his YouTube channel on
BSD</a>) gave
Michel Thomas <a href="https://www.mezzoguild.com/michel-thomas-review/">a negative
review</a> after using
the &quot;Michel Thomas&quot; Arabic tapes. I listened to part of the Chinese
tapes and they were not worth it (if you want to learn Chinese <a href="https://lukesmith.xyz/chinese.html">I've
written about what I recommend</a>).</p>
<p>But the <em>real</em> Michel Thomas tapes: Spanish, French, Italian, German,
done by the man himself, are the best for all their respective
languages.</p>

## Making Free Money off Credit Cards
 - [https://lukesmith.xyz/articles/making-free-money-off-credit-cards/](https://lukesmith.xyz/articles/making-free-money-off-credit-cards/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<p>While I've done a video on this topic before
(<a href="https://videos.lukesmith.xyz/videos/watch/72cc673c-e2d8-46fc-8c26-d56b9011b874">PeerTube</a>,
<a href="https://www.youtube.com/watch?v=_8F9JbUQlWQ">YouTube</a>), some people
asked me for more information, so here it is.</p>
<h2 id="arent-you-glad-to-be-an-american">Aren't you glad to be an AMERICAN?</h2>
<p>In America, people are so <strong>notoriously dumb</strong> with credit and money
that credit card companies can <em>literally give out free money by the
hundreds</em> to attract new customers. For brainlets who don't bother to
understand the basics of credit and debt and the fact that you
apparently have to pay back the money you spend, this is like a fly
trap. For non-retarded people it is what it is: <em>free money</em>.</p>
<h2 id="intro">Exploiting introductory offers: &quot;Churning&quot;</h2>
<p>Many credit cards have introductory offers like this: &quot;If you spend
$500 on this card in the first 3 months, you'll get a free credit of
$200.&quot; That would be a cool offer in the first place, but since there
are <em>so many</em> cards that have offers like this, a pattern emerges:</p>
<ol>
<li>Open a card with an introductory offer, for example: &quot;Get a $200
credit when you spend $500 in 3 months.&quot;</li>
<li>Use it for your normal daily life until you spend that $500 which you would be spending anyway.</li>
<li>Get/redeem/spend the credit/cashback/points on that card. Literally
free money.</li>
<li>Lock away the card and don't use it anymore unless it has some
other extremely good offer or cashback perk.<sup id="fnref:1"><a class="footnote-ref" href="https://lukesmith.xyz/rss.xml#fn:1">1</a></sup></li>
<li>Rinse and repeat, this time with a new card and new offer.</li>
</ol>
<p>This cycle is often called &quot;credit card churning&quot; and some people like
me don't mind living off of it.</p>
<p>Every year I go through a couple cards like this, making a couple
hundred or a thousand dollars back. <strong>If you do the math, it can be like
living with a permanent 20-25% off coupon that you use on literally
everything.</strong> Individual cards will have even more perks to
pump-and-dump for extra cash back.</p>
<p>I recommend especially young guys to try this out: it's a way of saving
money, while improving your credit by paying off many lines of credit,
and once you're done churning, you have a wide selection of credit
cards to use for their various normal features.</p>
<h3 id="cards">Cards to churn</h3>
<p>Here's a brief list of some cards whose introductory offers I've taken
advantage of. This is just an example list, there are many more.</p>
<ul>
<li><a href="https://www.referyourchasecard.com/18a/HM1OKNKXSA">Chase Freedom</a></li>
<li><a href="https://refer.discover.com/s/LUKE645">Discover It</a></li>
<li><a href="http://refer.amex.us/LUKESM18v?XLINK=MYCP">American Express Cash Magnet</a></li>
<li><a href="http://refer.amex.us/LUKESwRRP?XLINK=MYCP">American Express Blue Business</a></li>
</ul>
<h4 id="links-to-more-cards-per-company">Links to more cards per company:</h4>
<ul>
<li><a href="https://www.bankofamerica.com/credit-cards/">Bank of America</a></li>
<li><a href="https://creditcards.wellsfargo.com/">Wells Fargo</a></li>
<li><a href="https://www.citi.com/credit-cards/home">Citi Bank</a></li>
</ul>
<p>That's it! That's all you need to know, to take advantage of this, but
the rest of this page is just details that people ask about. Read on for
more!</p>
<h3 id="how-credit-card-companies-try-to-mitigate-this">How credit card companies try to mitigate this</h3>
<p>As I said, introductory offers exist primarily to get dim-witted people
who don't know how credit works into using cards unwisely or at least
normal people into switching to a different company. They know that
high-agency people can exploit this system, so there are some rules they
put in place to mitigate the extent to witch you can take advantage of
their offers.</p>
<p>Chase, for example, will not approve anyone for a credit card who has
gotten five other cards in the past two years. Wells Fargo will not
allow you too open cards with introductory offers without a 18 month gap
in between. Those are the main ones; other banks like Bank of America
don't bother preventing it at all, but it's possible that they will
start something like this soon.</p>
<h3 id="cautionary-note-for-credit-brainlets">Cautionary note for credit brainlets</h3>
<p>I suppose it goes without saying that credit cards are not magical money
devices and everyone who has a credit card should only spend what they
have the account that autopays their card or even better, do what I do
and <strong>never let my head hit the pillow before paying off all debts</strong>.
This might sound like a condescending thing to say, but obviously some
people out there don't understand how credit cards work and are going
into debt for no good reason. I know everyone who follows me is smart of
course, but I say this rhetorically.</p>
<p>When I did a video on this I was surprised to learn that there are
<em>also</em> people that resist and detest credit cards but <em>still</em> don't
understand them. Some people have this strange idea that merely
possessing a credit cards causes debt to occur in some cultic fashion
outside of your control. And for people who can't know better, maybe
it's better for them to think of credit cards as essentially magical
objects if it means they aren't misusing them. For everyone else,
credit cards are easy to use and exploit and benefit from.</p>
<h3 id="other-advantages-of-having-multiple-cards">Other advantages of having multiple cards</h3>
<p>It's actually nice to have a number of rewards cards from different
companies. I will occasionally check the bank or card's web interface
and there will often be additional perks especially for points-based
cards. It can often mean 10% in addition to everything else from buying
from a hardware store or grocery store. There are many niche businesses
and I don't recommend into getting roped into buying something you
wouldn't be buying anyway, but I keep tabs on if there is anything
familiar.</p>
<p>Similarly, it's nice to have &quot;rotating category&quot; cards that offer
say, 5% on a certain <em>type</em> of buy for a period of several months. The
<a href="https://www.referyourchasecard.com/18a/HM1OKNKXSA">Chase card</a> I
mentioned above, for example is giving 5% cash back on every purchase
made on PayPal as I write this in Q4 of 2020 (it looks like they do
PayPal every year or so). I've actually been deliberately making all
purchases I would be making anyway over PayPal, just so I can maximize
earnings. I'm even going to be paying bills in advance with PayPal so
when they are actually due next year, they'll be paid, and I'll have
the extra cash back.</p>
<h2 id="faq">Common questions about exploiting introductory offers</h2>
<p>A lot of people hear this and think, &quot;sounds too good to be true.&quot;
Makes sense, but <strong>we live in a complex world which again is primarily
targeted to the unwise</strong>. I've been doing this for years and have made
back a lot of lot of money and even increased by credit score.</p>
<p>Let's talk about some of the concerns people new to credit card
churning might have:</p>
<h3 id="but-what-about-muh-credit-score">&quot;But what about muh credit score?&quot;</h3>
<p>I'm not entirely sure why people think this, but there's this idea
that somehow you're scamming or defrauding credit card companies by
doing this. You aren't. You're just obeying their terms of service.
You're certainly not neglecting payment or proving yourself a bad
investment for a loan, which is what a credit score is actually about.</p>
<p>Opening new credit, including credit cards, will mean an inquiry on your
account and for a time being, you'll be marked as &quot;looking for
credit.&quot; This will decrease your credit score by a small amount; it's
normal. But over time, <strong>having lots of credit which you have paid off
is good for your credit score</strong>. That's, like, what a credit score is.
Having more credit cards and properly paid off is a great plus on your
account.</p>
<h3 id="bbut-thats-unethical">&quot;B...but that's unethical!&quot;</h3>
<p>You gotta be an extreme simp to see these companies massively ripping
off retards and nickel-and-diming people and say something stupid like,
&quot;I mean is this really ethical?&quot; You're an idiot. You don't deserve
free money. Why use your principles to defend people who obviously
don't share them?</p>
<p>A lot of these companies even charge people <em>to have checking accounts</em>.
Just in case you don't know how banks work, they make money loaning out
their reserves. They are already making money off of every account.
Charging you extra so they can make money off you is just more icing on
the cake for them. There are many banks who are less shills who simply
don't do this because it's totally unnecessary.</p>
<p>People who think this, do you go to the grocery store and chide people
who get free samples as unethical? It quite literally is the same thing
except for the store never makes money off people who just take samples.
A bank whose offer you exploit still might make a lot of money loaning
out money you put in a checking account there or even on the credit card
transaction fees they charge merchants. And if they didn't, who cares?</p>
<h3 id="do-i-need-a-checking-account">&quot;Do I need a checking account?&quot;</h3>
<p>If you get a bonus from, let's say, a Chase credit card, do you need a
Chase checking account to redeem your bonus or points? <strong>Usually not.</strong></p>
<p><strong>Every credit card company I've used allows you to set up automatic
payments from another bank.</strong> So you shouldn't have to worry about
remembering to paying your bills, although I usually pay everything
manually anyway just to be careful.</p>
<p>If you get an account credit, that will appear as a negative number on
your card and you will be able to spend it without paying it off. If you
get points, it might be that you need a checking account to redeem it as
cash, but you can also usually redeem previous purchases or sometimes
receive your bonus in the form of a bunch of gift cards.</p>
<p>This is an important question because some companies like Chase or Bank
of America will <em>charge you</em> several dollars a month to have a checking
account open, which I find utterly ridiculous. In both cases, you can
waive the fee if you have either direct deposit into the account or if
you just have a certain amount of money in the account (I think it's
$1,500 in the case of Chase). Either way, you can avoid this problem as
having a checking account is not usually necessary.</p>
<h2 id="advice">Three important notes on Credit Cards</h2>
<h3 id="the-psychology-of-spending">The psychology of spending</h3>
<p>One aspect of human psychology is that people are more likely to be okay
with spending or wasting money if they're using credit or debit cards
rather than paper money. It makes sense. If you have to part with a
physical object to spend something, it can hurt. It doesn't hurt as
much to use a card.</p>
<p>I find that the antidote to this is actually in introductory offers. If
I get a card that gives me a bonus for spending $500 in 3 months, I
treat that $500 as my absolute budget no matter what. Bills included if
possible.</p>
<p>Additionally, I started pasting sticky slips on the back of my cards
where I keep track of the exact amount of money I use on each card so I
know when I hit the required amount for the bonus. Each time I spend, I
deduct that amount from the original number. This actually serves the
double purpose of making the money-spending more real to me. I'm not
just swiping my card, but subtracting the amount and can feel what I'm
spending.</p>
<h3 id="dont-use-cards-with-annual-fees">Don't use cards with annual fees.</h3>
<p>Or at least if you do, be smart about it.</p>
<p><strong>None of the cards <a href="https://lukesmith.xyz/rss.xml#cards">I recommended above</a> have any annual
fees.</strong> So you can get them and not worry about canceling them. You can
logically exploit the offers of cards with annual fees and cancel them
afterwards to avoid paying the fee, but I don't do this myself.</p>
<p>Firstly, annual-fee cards are usually targeted to big spenders: their
offers will be something more like &quot;spend $4000 in the first 3 months
and get $750.&quot; If you're making a big purchase, that might be worth
it, but I personally am the kind of guy who feels guilty for spending
too close to $300 a month. I would definitely contemplate one of these
if you know you're going to spend some massive amount of money though.
Don't forget to cancel it later!</p>
<p>The bigger issue with annual-fee cards because they are used primarily
for <strong>social engineering and corporate sponsorships</strong>. That might sound
strange, for example, but some cards which cost several hundred dollars
a year might give you a big free annual credit on their favorite
airlines or on Uber or Lyft or Amazon or some other godless corporation.
That makes them work for people who are loyal consooomers of their
chosen affiliates, but for most people, getting the benefits of those
cards requires you to <em>use the products they want</em>.</p>
<p>I've seen some cards that give you bonuses for using them 30 times a
month or something else. Sure you can juke the system, but I feel like
the incentives they put forth are too strong and will probably
manipulate you into spending more than you usually do. The reason I
recommend <a href="https://lukesmith.xyz/rss.xml#cards">the other cards I do</a> is because you can easily spend
that much if you're an independent person without feeling like you have
to spend more.</p>
<h3 id="minimizing-privacy-exposure">Minimizing Privacy Exposure</h3>
<p>Now if you're someone principally concerned with privacy, there are
ways for you to take advantage of these kinds of offers without exposing
your daily purchases. Obviously opening a credit card does require some
basic information, like who you are and where you live (other things
your bank already knows). But you can minimize your exposure by using
the money on the card for a single recurring payment credit.</p>
<p>For example, let's say you pay an electric bill every month. Many power
companies/co-ops allow you to prepay or accumulate a credit, so if you
open a spend-$1,000-get-$250 card, you can immediately prepay $1,000,
wait for your free $250, then prepay that amount as well.</p>
<p>In that, you've got your free $250 (and you can forget about paying
bills for a year or so) and the only new thing the credit card company
knows is your power supplier (which they could probably guess anyway
from where you live). You could do the same with other recurring
payments.</p>
<p>A lot of people I've talked to plan on using these offers to by
over-the-table cryptocurrencies. That works too.</p>
<p>Additionally if you make a large purchase like a car that is going to
have to be registered with &quot;the system&quot; anyway, it might be a good
time to get one (or maybe more) of these cards.</p>
<p><strong>The most important thing, however, is that <em>you</em> are the one ripping
them off and never the reverse. Do not spend more or waste more because
you feel richer because you have something that feels like a free money
card.</strong></p>
<h2 id="daily-drivers">&quot;Daily drivers&quot;</h2>
<p>When not pumping-and-dumping a credit card for an introductory offer,
there are also generally good cards that you can keep to maximize idle
cash back. <strong>Obviously the true red-pill is using cash</strong>, but if you'd
rather get bonuses from cards, here are some options I use with links:</p>
<ul>
<li><a href="https://www.usaa.com/inet/wc/bank-credit-card-cashback-rewards-plus-american-express">5% on gas and purchases on military
bases</a>
(unfortunately USAA is very exclusive (you must have family in the
military), but great for members)</li>
<li><a href="https://www.referyourchasecard.com/18f/AR8H2DIPP8">5% on groceries</a>
(only for first year, but there are multiple cards that do this can
can be cycled (or get your wife to get it next year))</li>
<li><a href="https://www.usbank.com/credit-cards/cash-plus-visa-signature-credit-card.html">5% on
bills</a>,
specifically, you get 5% on rotating categories and home utilities
is one of them.</li>
<li><a href="https://www.wellsfargo.com/credit-cards/propel">3% at restaurants and on travel
expenses</a></li>
<li><a href="https://www.paypal.com/us/webapps/mpp/credit-card/2-percent-cash-back-mastercard">2% on everything
else</a></li>
</ul>
<p>It should also go without saying that you should have fixed costs/bills
set to charge credit cards just for the free cash back. I mean if you
have $250 dollars in bills a month and hook them up to a 2% cashback
card, that's $60 back a year. It adds up over the years.</p>
<p>Again:</p>
<blockquote>
<p>&quot;The NEET will work harder than the wagie to stay out of a job.&quot;
&mdash;Nullennial (YouTube comment)</p>
</blockquote>
<blockquote>
<p>&quot;I'm Jewish and I find this video Jewisher&quot; &mdash;shiran (response to
<a href="https://www.youtube.com/watch?v=_8F9JbUQlWQ">my original video</a> on
this)</p>
</blockquote>
<div class="footnotes">
<hr />
<ol>
<li id="fn:1">
<p>Note: Never <em>close</em> a credit card. It looks bad on your record, while having many credit cards over a period of time which you pay off looks good. Just store your old cards away and you can often disable them on their websites.*&#160;<a class="footnote-backref" href="https://lukesmith.xyz/rss.xml#fnref:1">&#x21a9;&#xfe0e;</a></p>
</li>
</ol>
</div>

## Notes on Learning Languages
 - [https://lukesmith.xyz/articles/notes-on-learning-languages/](https://lukesmith.xyz/articles/notes-on-learning-languages/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<p>I get asked a lot about learning languages, so I have a few comments
about it here. Hopefully I can awaken you from some dogmatic slumbers
about language.</p>
<h2 id="vocabulary-is-the-least-important-part-of-learning-a-language">Vocabulary is the least important part of learning a language.</h2>
<p>This is hard for people to understand because I think most monolingual
people think that languages are just different word lists that people
use. As a result, 101 students will manually look up every word in the
dictionary to translate. This actually increases the mental load of
learning a language because people have the idea that to speak it, they
have to think of something in English, then translate the sentence word
by word, then say that. What a pain.</p>
<p>So what is a language if not words? It really is a set of constraints as
to how words can go together: what order they go in when modifying each
other, but also languages are morphology. Verb endings and tenses and
such are literally the most important part of a sentence. If you don't
have a productive and reflexive use of verbs, you are literally just
going to be reciting nouns you know like a monkey.</p>
<p>This is actually why I recommend people learning Romance languages or
German to <a href="https://lukesmith.xyz/learning-european-languages-michel-thomas.html">use Michel Thomas's
audio</a>. Thomas doesn't
lecture at all about what he's doing, but he focused only on using
verbs and building up basic expressions from the bottom up until it's
understood reflexively by students. To actually learn any language, this
is more or less what you are going to have to mentally do anyway in the
process.</p>
<p><strong>I would say it's actually possible to fluently speak a language
knowing only about 50 words.</strong> If you understand the &quot;grammar&quot; of a
language, you can basically get by anywhere anytime with a couple dozen
words only. What words you don't know can easily be figured out, but
you <em>can't</em> wing it with grammar and you <em>can't</em> wing it with
morphology.</p>
<h3 id="computer-metaphor">Computer metaphor</h3>
<p>Granted, the same is true of programming &quot;languages&quot; as well, weirdly
enough. No one would think &quot;knowing a [computing] language&quot; means
just knowing all the function and variable names. The important thing is
knowing the syntax of how you put functions (loosely verbs) and
variables (loosely nouns) together. After all, variable names are always
different and functions can be easily invented too or called from some
obscure library. Someone who knows a language is someone who can use its
syntax to produce novel expressions. If you take a Python script,
replace its functions with C functions, it's still Python, just calling
a bunch of undefined functions. People can only get away with even sort
of believing this in the domain of human languages if you just don't
know enough and end up assuming that all languages just work the same.</p>
<h2 id="then-what-is-a-language">Then what is a language?</h2>
<p>So really when you learn a language, you can't look at it as new words,
but new patterns of speech that interconnect in a logical way.</p>
<p>Speaking fluently in that language means being able to use and combine
its basic constructions into complex thoughts put in words. This is why
I'm really against &quot;translating in your head.&quot; If you're doing that,
you're not actually using the language. You're teaching yourself a
silly English-word-replacement game. I know it's very hard for
word-thinkers not to think in words, but if you can't stop doing that
for a second, you're not going to be able to learn a new language.</p>
<h2 id="you-will-not-learn-a-language-by-consoooming-media">You will not learn a language by consoooming media.</h2>
<p>There's this lazy idea that somehow if you passively sit around and
watch people using a language this will somehow endow you with the
ability to flexibly produce a language in the same way you see others
using it. People want to believe it because they want to be able to
watch TV or play a cell phone game like Duolinguo or valueless Rosetta
Stone-like software and somehow gain competence in a language.</p>
<p>It's not going to happen ever. <strong>Learning to play a boring computer
game using words from a different languages is not the same as learning
to speak the language.</strong></p>
<p>You might say of &quot;just listening to speech&quot; that &quot;that's what
children do,&quot; but that's not true at all. Children try pretty hard to
participate and understand conversation. They sometimes have a desperate
personal need to understand each passing sentence and hear the language
they are trying to learn for hours a day for years. You watching some
forgettable movie in the background as you play with your phone don't.</p>
<h2 id="are-you-actually-thinking">Are you actually thinking?</h2>
<p>If you want to know if you are actually learning a language, ask
yourself that. People are weirdly afraid against actually thinking
through things and making new expressions in other languages when
that's exactly how you learn them.</p>
<p>A lot of language nerds love to email me about their Anki cards or their
harebrained schemes for mass-memorizing words as if they're an Asian
studying for a chemistry test. Given what I've said about &quot;learning
words,&quot; you can guess my opinion on that. Once people abandon the lazy
route, sometimes they take up the <em>via dolorosa</em>: the route of suffering
and assume that training themselves like a Pavlovian dog will help them
become fluent in a language.</p>
<p>In reality, the only question that matter is: &quot;Are you actually
thinking?&quot; Are you actually going through the mental process of
creating new sentences in a new language?</p>
<p>When I was learning Latin obviously I had no Latin-speaking friends and
could barely get my hands on anything Latin-related. But after I learned
the basics of the language I started thinking in it constantly. First
that starts in my always implicitly translating English song lyrics or
ads in my head into Latin. That's actually difficult if you're dealing
with something modern and idiomatic. Not as bad with church songs. As
time goes on, I would overtly remember things in Latin sentences instead
of English. If I mumbled something under my breath I would make sure it
was Latin. At all points in time, I was thinking about how the language
was structured and what it meant to produce sentences in it.</p>
<p>The sad fact is that most people who &quot;learn&quot; languages in school treat
them as advanced cross-word puzzle like games where they don't
<em>actually think</em> in the language, but have hilarious mnemonic devices in
their head for relating what they want to say in English with something
in the language they're learning.</p>
<h2 id="translating-is-a-bad-habit">Translating is a bad habit.</h2>
<p>If anything, you should become <em>worse</em> at translating the further you go
on and the more independently you can stand on your own in another
language.</p>
<p>Latin is a good example. I can read and comprehend Latin very well, but
if asked to translate what I'm reading, I find that more and more
difficult the better I read Latin. Now it's easy for me to report the
meaning of a passage, but phrase-by-phrase translation is something you
have to think through because Latin and English are structurally very
different. This isn't just word order, but even how a Latin speaker
approaches expressions and the kinds of phrases they use can translate
only very delicately into English.</p>
<p>The problem nearly doesn't exist between English and Spanish, which are
basically the same language. I'm sure someone who only knows Spanish
will feel like English and Spanish have many differences, but in the
context of other languages, like Latin or Chinese or Japanese, it's
hard not to view English and Spanish as having basically the same kind
of syntax 95% of the time. That actually goes for most modern European
languages.</p>
<h2 id="you-sound-stupid-if-you-dont-sound-stupid">You sound stupid if you don't sound stupid.</h2>
<p>Every language has its own set of phonological rules that determine what
particular sounds are said how and where. Phonological rules give us
&quot;our accents.&quot; When someone speaks English in an accent, they are
really just speaking English using the phonological constraints of
whatever language they're more familiar with. If they speak English
competently, there's at least some extent to which they are abandoning
their native phonological rules.</p>
<p>When you first start learning a language, you might read something aloud
and say &quot;I sound stupid.&quot; This is because your natural way of speaking
is obviously to say everything with an accent consistent with English.
You can probably remember the apathetic jock in Spanish class or
whatever who religiously pronounced every Spanish word he mindlessly
read with an almost intentionally non-Spanish accent.</p>
<p>To actually speak another language is to adopt the phonological
tendencies and even the prosodic and tonal traits of that language. When
you initially do that, you will probably sound very stupid to yourself
since violating phonological rules you're familiar with always sounds
wrong. If you do overcome that illusion of felt stupidity, you <em>won't</em>
sound stupid when it counts. If you refuse to improve your accent
<em>immediately and from the beginning</em> you will sound like an utter moron
forever.</p>
<p>There's actually a trick too: when you imitate a foreign accent, you
are actually implicitly adopting the phonological rules of their
language that you have noticed in real life. My suggestion is when you
are starting out, <em>read the other language in what you'd guess would be
a stereotypical accent of the person speaking the language</em>. If your
imitation is good, you're speaking their language without an accent.</p>
<h2 id="the-critical-period-is-fake">&quot;The Critical Period&quot; is fake.</h2>
<p>That reminds me.</p>
<p>There's an idea in academic and clinical linguistics as well as popular
culture that children have a magical plasticy of the brain that makes
them uniquely good at learning languages. This is supposed to be the
reason why children learn languages &quot;fast&quot; and adults don't. <strong>I
think this is a myth.</strong> You don't have to send me all the &quot;proof&quot;
about this (don't worry, the Universities of Georgia and Arizona
would've failed me totally if I hadn't seen it for my linguistics
degrees there). I sort of assumed that this was true for years, but on
further thought, I think it's just a conspiracy of irrelevant data and
copes... or at least, it's not nearly as true as people pretend it is:
adults are just about as capable of learning languages in most senses.</p>
<p>After all, think about it, children actually take several years to
function in a language, which is often much longer than an adult that
knows what he's doing. The Michel Thomas style tapes which I alluded to
above are good at giving an adult a passable diving-board for a language
in about 8 hours. It can be done. You can also give an adult a
crash-course in phonology and articulatory phonetics that will make it
easy to understand and with practice produce the sounds children take
years to master.</p>
<p>The motivation of a child and adult are utterly different. A
language-less child has lots of reasons to invest most of his mental
life in attention to language. Apathetic adults don't.</p>
<p>What I really get sick of is doomer adults who cope with their laziness
by talking about how hard it is to learn a language as an adult. Many
adults still learn languages all the time. There is some circumstantial
evidence that infants cue into some acoustic cues and other things
quicker than adults, but I think in most cases we're just looking at
infants semi-consciously honing in on what details they've acknowledged
to be linguistically relevant. In reality, developed humans have huge
institutional and intellectual advantages to learn.</p>

## Only Use Old Computers!
 - [https://lukesmith.xyz/articles/only-use-old-computers/](https://lukesmith.xyz/articles/only-use-old-computers/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/dream_thinkpad_small.gif" title="If only ThiccPads were this THICC!" /><figcaption>The ideal ThiccPad</figcaption></figure>

<p>If there is a single point of advice I can offer novice computer users,
it is <em>stop using modern computers</em>.</p>
<p>If you look at &quot;technology YouTube,&quot;  by which I mean the massive multi-million subscriber channels, nearly all of
it is devoted to constantly reviewing and comparing every new computer,
processor, graphics card and product. There's big money in it because
obviously all of these companies put money in it, but also if you're a
normal person, you automatically assume you need the &quot;best&quot;
technology.</p>
<h2 id="do-you-need-a-modern-computer">Do you need a modern computer?</h2>
<p>Absolutely not. More than 95% of people could be using a computer from
2008 or before without any problems. Needing a recent machine is limited
to people who:</p>
<ol>
<li>Do extreme, professional, processor-intensive video-rendering.</li>
<li>Compile massive programs and operating systems with severe time constraints.</li>
<li>Play recent triple AAA video-games on high settings.</li>
<li>Use many massive Electron apps and other inexcusably bad software
written by soydevs and other people who shouldn't be writing
software.</li>
</ol>
<p>The last two reasons aren't really real reasons at all because they are
totally unnecessary and avoidable things.</p>
<p>But to the point, watching YouTube videos and using a word processor
does not require last month's new release.</p>
<p>Every video I upload, I transcode for settings optimal for YouTube,
meaning I render each video I record. On my computer from a decade ago,
that still takes only a couple minutes. A fancy $5000 computer might be
able to do it in less than one, but it is honestly not worth the pain
associated with modern computers.</p>
<h3 id="how-much-should-a-computer-cost-a-normal-person">How much should a computer cost a normal person?</h3>
<p>Either nothing or just around $200, I say. I use a ThinkPad X220 I got
for $90 on eBay. Before that, I used another ThinkPad X220 I also got
for $90. Like anything else, <strong>if you are buying things on Amazon,
you're doing it wrong</strong>.</p>
<h2 id="the-pain-of-modern-computers">The Pain of Modern Computers</h2>
<h3 id="modern-computers-are-more-breakable">Modern computers are more breakable</h3>
<p>As computing has become more and more popular, companies have started to
realize that a consumer's first reaction on having their $5 wifi card die is
immediately buy a whole new computer. This means two things: (1) they don't
bother to make computers easy to repair, in fact, they make it more difficult
and (2) there is absolutely no need to make computers durable at all. In fact,
it's probably better to let computers break so you'll get yet another sale.</p>
<p>Apple is by far the most anti-social computing company because of this.
I'll let the larger tech channels show you the specifics, but every
Apple product is brilliantly designed to make it difficult to fix very
basic and otherwise fixable problems. They have quite a racket licensing
out the ability and tools to companies that want to fix their terrible
hardware. Apple even used pentalobe screws just so normal people
couldn't open their computers up with a typical screwdriver. Of course
nowadays every other computer manufacturer imitates the Apple style
where apparent &quot;sleekness&quot; is supposed to be a signal of high quality.</p>
<h3 id="modern-computers-are-increasingly-monitoring-devices-and-come-with-proprietary-junk">Modern computers are increasingly monitoring devices and come with proprietary junk.</h3>
<h4 id="the-management-engine">The Management Engine</h4>
<p>You might've heard that all Intel i3/i5/i7 processors (that is, after
the Intel Core 2 Duo) have an onboard alternate processor that is meant
to function as spyware. This is called the Intel Management Engine. It
can view your memory and connect to the internet: basically all modern
computers have this permanent back door. In older computers, say the
ThinkPad X200, you can, with a little hardware action, remove the other
processor and replace the proprietary BIOS with
<a href="https://libreboot.org">Libreboot</a> or <a href="https://coreboot.org">Coreboot</a>,
but that is <em>not possible</em> on more modern computers (you can install
Coreboot on a more modern machine, but not all of the components of the
Management Engine are removed).</p>
<p>More recent computers, however are non-removable spyware by design and,
yes, the NSA can monitor any machine with a Management Engine. There are
actually even rumors that one of the taps that the FBI under the Obama
administration put on Trump during his campaign was a Management Engine
bug.</p>
<p>Note that AMD (Ryzen) processors have what they call a &quot;Platform
Security Processor&quot; that is equivalent to the Intel Management Engine,
so you're not escaping the issue by using one of them.</p>
<h4 id="nvidia">NVIDIA</h4>
<p>Again, unless you play modern videos alone all day, you literally have
no reason to have a modern computer, especially one with an expensive
graphics card. NVIDIA is a great example because they make graphics
cards and develop proprietary drivers for them to make it harder and
harder to use them on machines that aren't running whatever the most
recent spyware variant of Windows 10 is. Linux works perfectly on all
computers ancient and modern, but if you plug some NVIDIA thing up to
it, you might lose your screen or not be able to boot. A lot of gaymers
whine about their NVIDIA products &quot;not working&quot; on Linux without
realizing <strong>that is by design</strong>. NVIDIA and other companies and all CPU
designers go out of their way to keep their source code and standards
private which makes their products tangibly worse because it is harder
for other parties to write drivers for them. Why? Because most of them
have partnerships with Microsoft.</p>
<h3 id="the-problem-of-windows">The Problem of Windows</h3>
<p>How many times have you heard a normie explain to you that their
computer is slow because it's &quot;really old&quot; and they bought it &quot;way
back in 2015?&quot; It's an absurd statement of course. Computers don't
just get magically slow... <strong>...unless they've been running
Windows.</strong></p>
<p>In the future, once even Microsoft has switched over to a purely
Unix-based backend for their operating system, we're all going to have
a good laugh about how Microsoft Windows, <em>literally the worst and least
functioning operating system ever devised</em>, was the largest consumer
market share for decades.</p>
<p>I might go into how Windows is poorly designed in another page or video,
but I want to be clear that there is no such loss of speed on any Linux
distribution, which is what you should be using. I am one of the first
to complain about the feature bloat of the Linux kernel and Linux
software, but compared to Windows, it's no contest: <strong>Linux runs fast
on old hardware</strong>. You'll know from some of my videos, however, that
I'm not <em>big</em> into &quot;Linux Evangelism,&quot; mostly because it's sort of
strident and doesn't really work with a high success rate. Using Linux
is just something that normies have been immunized against (mostly
because &quot;It's what smart people do&quot;), but I always find myself in a
position where someone's Window installation has permanently crashed
and they're at the awkward decision of having to <em>buy a license</em> to
reinstall the dysfunctional and slow operating system they've grown to
hate.</p>
<p>There is quite literally no problem that normal people have with
computers that is not immediately alleviated by installing Linux.</p>
<h2 id="why-do-people-use-thinkpads">Why do people use ThinkPads?</h2>
<p>As I said above, I use a X220 ThinkPad. Older ThinkPads are fairly popular among people who think and care about doing things effectively and economically on a computer. Why is this?</p>
<p>ThinkPads were always designed for enterprise environments, meaning the financial incentives for the manufacturer are not always planned obsolesce, but a long-standing reputation among large companies of having durable, fixable and expandable machines.</p>
<p>To replace a hard drive on the X200 requires unscrewing just a single screw. Same to replace the memory. To replace a spoiled keyboard is no more than three screws.
Modern laptops, including the degraded modern ThinkPad have abandoned this simplicity and opt for the Apple-Mac/cell phone design technique of making batteries, memory and the rest functionally soldered and irremovable.</p>
<h3 id="how-far-can-500-go">How far can $500 go?</h3>
<p>Over the years, I&rsquo;ve had many things break on my laptops, but since I&rsquo;ve been using ThinkPads, it is incredibly easy to keep a working computer even after rough use. I estimate that I have never spent more than a combined total of $500 on computers, which is usually a bare minimum for what someone can buy a &ldquo;modern&rdquo; laptop for nowadays.</p>
<p>When the keyboard on my ThinkPad breaks, I can just buy a replacement keyboard for $30 or $40 and replace the old one much easier than any other model. That&rsquo;s the modularity of these computers.</p>
<p>Even in the worst case scenario when something on the motherboard makes the computer unbootable, I still get to keep my &ldquo;broken&rdquo; ThinkPad and repurpose the memory, wifi card, keyboard and everything else. I still have some parts of every laptop I&rsquo;ve had just because they do come in a lot of use. The other month, a friend&rsquo;s wifi on his desktop went out and I could replace it with one of my old ThinkPad modules.</p>
<p>This is the kind of thing you lose with modern computers. This is purposeful on the part of manufacturers, and it&rsquo;s important not to pay them huge amounts of money to incentivize this behavior. It&rsquo;s very easy to live off of 10 year old computers nowadays. The eBay-and-etc resale market is massive even thought many of us have gotten wise to the value of these old computers.</p>

## Reviews of All Linux Distros (That Matter)
 - [https://lukesmith.xyz/articles/reviews-of-all-linux-distros-that-matter/](https://lukesmith.xyz/articles/reviews-of-all-linux-distros-that-matter/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<p>Firstly, once you reach basic competency in Linux, different
distributions don't matter. A lot of newbies analyze distros based on
what they look like when you install them, often not realizing that
it's a pretty simple affair not just to change superficial things like
your theme and setup, but entire desktop environments. <strong>Basically all
distro reviews online are wastes of time for people who know what
they're doing.</strong> When I came to YouTube, all Linux YouTube was was
people constantly installing distro after distro in a virtual machine
and critiquing minutiae. It was a bleak and boring world. One of my
first and greatest achievements on YouTube was making this video: <a href="https://www.youtube.com/watch?v=3zpgQpdy_fI">How
to choose a Linux distro: Stop
Thinking!</a>, which went
semi-viral and sort of put a damper on distro reviews. Either way, I'll
say what I think about different distro minutiae here.</p>
<h2 id="things-that-matter">Things that matter</h2>
<ul>
<li><strong>Free software.</strong> If you are switching to Linux, there is no point
of you just using junk proprietary spyware &quot;apps&quot; that you used on
Windows. Any distribution that advertises proprietary software as a
feature should be viewed as suspect. You can always <em>install</em>
proprietary software if there is some particular need (usually the
only &quot;need&quot; is a lack of knowledge of free software that is more
extensible and performs the same tasks and more).</li>
<li><strong>Up-to-date software.</strong> This matters because if you want to install
a program, you're often going to need recent
libraries/depencencies. This is especially important if you want to
use software in active development: say software for video-game
compatibility on Linux.</li>
<li><strong>No gimmicky additions.</strong> Probably the worst thing you can do is
install a distribution that puts a giant wall between you and the
system itself. One of the biggest advantages of using Linux is the
ability to understand what's going on on your computer and optimize
it. If you use a distribution that hand-holds basic things, it might
seem convenient at first, but as time goes on, you won't have a
clue when that fragile system fails.</li>
<li><strong>Consistent and reliable maintainence.</strong> Lastly, you'll want to
make sure that your distribution has humans on the development side
that are at least fixing basic problems. As programs change and are
updated, it often requires some changes in your distro's
repositories and more. Unmaintained distributions are usable, but it
becomes annoying to deal with as time goes on if you want to install
software with the distribution's package manager.</li>
</ul>
<h2 id="ubuntu">Ubuntu</h2>
<p>Ubuntu is a common distribution because it is the distribution shilled
by the company Canonical. Canonical has probably had a positive effect
on making GNU/Linux more widely used and accessible, but Ubuntu has a
lot of long-term headaches that will plague users.</p>
<p>That said, <strong>Ubuntu is nearly the worst distribution for new users</strong>. It
is maintatined at least, but fails on all the metrics above:</p>
<ol>
<li>It advertises proprietary software in its software center and
encourages users to use programs because they are &quot;familiar&quot; from
Windows.</li>
<li>It releases slowly and you'll run into problems if you try to
install something out of the box.</li>
<li>It is full of gimicks, the elephant in the room being the Snap
system, but Canonical has thrown in a lot of junk features in the
past and a lot can break.</li>
</ol>
<h2 id="debian">Debian</h2>
<p>Debian is just a more reasonable version of Ubuntu: it separates free
and non-free software clearly&mdash;it has a optional version that allows
unstable and testing packages for some recent software and it has so few
gimmicks it's probably the most boring distro!</p>
<p>I haven't used Debian much as a desktop system (I do use it on my
servers), but the package manager and even the release speed of the
testing versions isn't quite fast enough for me personally.</p>
<h2 id="artix-and-arch">Artix and Arch</h2>
<p><a href="https://artixlinux.org">Artix</a> is the distribution that I use and have
been using for a while. It is really the same thing as
<a href="https://archlinux.org">Arch</a>, except for Artix allows the usage of
different init systems (I use runit).</p>
<p>Arch and Arch-based distributions are &quot;bleeding-edge&quot; in their release
time and have access to the Arch User Repository (AUR) allowing the
single widest software library of all major Linux distributions.</p>
<p>Artix offers many installable desktop-environment ISOs for newbie users,
but thankfully they don't over-bloat them with gimmicky features. Arch
itself only has an official minimal installation, and that's kind of
its thing.</p>
<p><strong>If I had to choose, Artix is the distribution that I recommend for
both novice and most veteran users.</strong></p>
<h2 id="manjaro">Manjaro</h2>
<p>Manjaro is another Arch-based distro. I've even recommened it before
for new users in the past and installed it on many people's computers
in real life, but I will admit that my view on it is souring. They have
definitely started to go the way of Ubuntu by adding lots of extra
features, directly people to rely more on flatpak and &quot;harmful&quot;
systems and generally adding more layers of abstraction between the user
and the system.</p>
<p>All the good things that can be said about Manjaro can also be said of
<a href="https://artixlinux.org">Artix</a>, which also has easy to install ISOs, so
I consider Artix the superior system.</p>
<h2 id="parabola">Parabola</h2>
<p><a href="https://parabola.nu">Parabola</a> is the FSF-approved, all-free software
version of Arch Linux (it also has an OpenRC version for
soystemd-haters). In the abstract, Parabola is my optimal distribution,
but I don't actually use it anymore for two reasons:</p>
<ol>
<li>It uses the Linux-libre kernel, which is all free software, but
networking will not function with laptops with proprietary wifi
cards.</li>
<li>It is not quite as well maintained as Arch and Artix, and you'll be
a little more likely to run into package breakage.</li>
</ol>
<p>The second problem isn't the end of the world, but it can be annoying.</p>
<h2 id="gentoo">Gentoo</h2>
<p><a href="https://gentoo.org">Gentoo</a> is one of the best distributions and excels
in all of the 4 requirements I give. Not only is non-free software
obviously separated, but it isn't too difficult to have your Gentoo
install with a Linux-libre kernel if you want.</p>
<p>Gentoo is also unique because it is a source-based distribution: you can
set basic compilation settings for your programs and have a lot of
control over them. While Gentoo is very well maintained, <em>you</em> actually
end up with a good bit more control over your system. That is a
responsibility that has some prerequisite knowledge of course, so Gentoo
has a reputation of being difficult to install.</p>
<p>If you want to look into Gentoo, you should first be familiar with Linux
and what specific kind of system you want. When you first install
Gentoo, because you can customize it so specifically, it obviously helps
to know what exact network backend you're comfortable with, whether you
want to use GTK or QT, or many other little things that a Linux noob
might not know too much about.</p>
<h2 id="void">Void</h2>
<p><a href="https://voidlinux.org">Void</a> is another great distribution. It's
notable also for using runit instead of soystemd, having a musl version,
and having a package system reminiscent of Arch, but in many ways more
minimalist and extensible. It again separates free and non-free
packages, and has a wide repository of them, included even more
installable via the <code>xbps-src</code> system which is somewhat analogous to the
AUR, although unlike the AUR, I don't believe it's quite as easy to
update packages.</p>
<p>Void has had a somewhat tumultuous development culture. It was
originally the brainchild of one man, one man who went missing for a
year... After he returned, drama eventually caused other member of the
team to encourage his retirement. Either way, while I used the distro
for a while and was one of the first people advertising it online, I
never remember this translating into any downstream problems on my
computer.</p>
<h2 id="distro-not-here">Distro not here?</h2>
<p>This is only a list of distributions that I've used for a bit. I don't
do &quot;distro reviews&quot; or just install random distributions just to test
them, so if it isn't here, I'm not going to have an experience-based
opinion.</p>

## Science vs. Soyence
 - [https://lukesmith.xyz/articles/science-vs-soyence/](https://lukesmith.xyz/articles/science-vs-soyence/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/soyence.jpg" /></figure>

<p>There's nothing necessarily <em>wrong</em> with science, reason, knowledge
etc. To some degree, they're fundamental for survival in this world in
one way or another. But one of the more worrisome problems which have
arisen since the Enlightenment, and especially in the past several
years, is the fact that whenever scientific knowledge has increased,
human arrogance has accelerated even faster. This isn't a metaphysical,
moral arrogance; it's one that is more and more jeopardizing the human
cosmos.</p>
<p>We live in a pop-scientific and pop-technological world. Because common
people are constantly weighing themselves down with new gadgets and
state-of-the-art genetically engineered food, there's a tendency to
want to pay homage to the amorphous blob of &quot;knowledge.&quot; Of course,
much like the Greek Gods, we cannot seem to speak to &quot;knowledge&quot;
directly, or to mentally murky academics, but only to official
mediators: journalists and &quot;science communicators&quot; and the like.</p>
<p>The religious metaphor is intentional. Of course the actual view of
Popperian science is that scientific &quot;advancement&quot; is less of an
increase in knowledge than a decrease in falsity. We can never be sure
of what is true, but we can gradually establish what is false and
contradictory; science does exclusively the latter. Real scientific work
refutes and calls into question established fact and is in a constant
self-regeneration. Facts mean nothing in themselves.</p>
<p>And scientific models, from our models of the atom, to models of the
Earth's weather and climate, to models of our body are highly
circumstantial, and as a rule, will nearly all inevitably be proven
false. Theories are the narratives we cast over facts which have not yet
been ruled false. We know nearly nothing of how the brain works. Sure,
we know there are synapses, and we know what brains end up doing in some
circumstances, but we haven't begun to scratch the surface of how a
brain is actually engineered (computational models be damned). The same
is true of the human body and is especially true of human society.</p>
<p>Now Neil deGrasse Tyson has the annoying mantra that he repeats at every
possible opportunity, which goes something like: &quot;the good thing about
science is that it's true whether or not you believe in it.&quot; First
off, I don't know what's good about that; it'd be pretty damn
convenient to live in a world where we could imagine away gravity or CO2
or cancer, but aside from this, science, actual science as a critical
methodology is manifestly <em>not</em> true and is <em>not</em> the truth. Science is
a way of marginally approaching truth by discovering falsity, and in
most endeavors, this approachment is so marginal as to be inert in all
our daily lives. There is nothing to &quot;believe in&quot; in science anyway,
because it's an exposer of <em>non</em>-truth.</p>
<p>But in pop-science, Science<sup>®</sup> is &quot;knowledge&quot; and deviation from the
scientific catechism is &quot;irrational.&quot; It's not just irrational to
dispute consensus, but irrational to <em>fail to implement it in your
personal life</em>.</p>
<h2 id="in-practice">In Practice</h2>
<p>The greatest danger of pop-science is the unquestioned assumption that
life should be led &quot;scientifically.&quot; That we should &quot;look for
evidence,&quot; &quot;question everything,&quot; and universally &quot;challenge
authority&quot; (unless that authority is a professor). The problem should
be blatantly obvious in hindsight.</p>
<p>An obvious example: in the 20th century, Western societies had to deal
with the very real problem of a bizarre increase in lung cancer rates.
We &quot;know&quot; now that smoking tobacco and other substances apparently
cause drastically higher lung cancer rates, but this was lost on the
people at the time.</p>
<p>The relationship between smoking and cancer was highly circumstantial;
there were some statistical correlations established, but as any
pop-science guru will tell us &quot;correlation is not causation!&quot; For
decades, scientifically minded people looked for evidence while millions
more died. Smoking companies took refuge in the fact that there was no
<em>mechanism</em> understood behind how smoking could cause lung cancer. With
all scientific rigor, they insisted for decades that the increase in
lung cancer was due to something else, or merely an increase in
diagnosis capacity. And <em>they were on the side of scientific
skepticism!</em></p>
<p>Only now that there is some understanding of how carcinogens in smoke
can damage the lungs can we say that the &quot;scientific consensus&quot; is
that smoking causes lung cancer. Cute, but if people had been
<em>&quot;irrationally&quot; cautious</em>, the human tragedy would've been
substantially mitigated.</p>
<p>The problem is that &quot;looking for evidence&quot; before acting or non-acting
is personally and socially dangerous. In nearly all circumstances, our
intuition (crafted by millions of years of evolution) or social norms
(which keep us to established safe routes) are much better guides to
life than the scientific consensus, despite them being &quot;irrational&quot;
(and sorry, religion is part of this too). When someone guzzles down
some newly fabricated energy drink or gallons of soda, they're nearly
certainly damaging their bodies in ways science does not yet understand.
Don't wait 40 years for some longitudinal peer-reviewed study to prove
that eating plastic is bad for you. Trust your instincts before you give
credence to some YouTuber who says inane things like &quot;There's no
evidence that...&quot;</p>
<p>My favorite little &quot;irrationality&quot; that we all commit is of course,
sleep. After millennia of trying to understand it, there is no
established scientific reason or justification for why humans &quot;need&quot;
sleep. Sure there are hypotheses (memory processing, repair, maybe even
something Freudian), but none close to common currency. In the words of
one of the world's most prominent sleep researchers, William Denent,
&quot;As far as I know, the only reason we need to sleep that is really,
really solid is because we get sleepy.&quot; Of course the absence of
logical evidence to the necessity of sleep keeps no NdGT fan from
wasting their time on the &quot;Bronze-Age Myth&quot; of the importance of
sleep.</p>
<h2 id="not-mis-understanding-complex-systems">(Not) (Mis-)Understanding Complex Systems</h2>
<p>The human body is a complex system in which every &quot;system&quot; is
overlapping, somewhat redundant, all-affecting and fundamentally beyond
linear analysis. Our scientific studies can find binary variables that
correlate with a low <em>p</em> value, but that tells us nothings about what's
actually going on and nothing about the underlying mechanisms. Again,
the same is true of the human brain and the same is true of human
<em>society</em>. Nothing is a simple input-output system.</p>
<p>What this means is that basically nothing from the world of pop-science
can <em>ever</em> affect the basics of our lives because the interaction of our
component parts are just non-amenable to any kind of generalizations
that make intuitive sense to us. Everything we do affects our bodies in
ways we can't predict so the proper strategy is always an
&quot;irrational&quot; precaution and avoidance of novelty.</p>
<p>Things, of course, get especially touchy when talking about the
&quot;rational&quot; management of society. Every good denizen of the
post-Enlightenment world, even most of those on the &quot;Right&quot; have the
idea that the economy and social relationships are simple one-to-one
hydraulic systems that can be managed like a little steam engine. Now
we've been rationally managed to hell and not back (and the solution is
always more rational management).</p>
<p>The terrible truth is that traditional social norms are <em>irrational</em> and
<em>still do</em> exist for a reason in the perennial gale of social evolution.
Social change and social progress (note the lack of scare quotes) have
always been happening, but only now do we have the naive idea that the
units of society (people) have the competence to design and contribute
to an otherwise unconscious evolution of social memes.</p>
<p>Anyway, I'll give the last word on this issue to Noam Chomsky, who
somehow manages to say something clear and admirable on the subject:</p>
<blockquote>
<p>&ldquo;Science is a very strange activity. It only works for simple
problems. Even in the hard sciences, when you move beyond the simplest
structures, it becomes very descriptive. By the time you get to big
molecules, for example, you are mostly describing things. The idea
that deep scientific analysis tells you something about problems of
human beings and our lives and our inter-relations with one another
and so on is mostly pretense in my opinion&mdash;self-serving pretense
which is itself a technique of domination and exploitation and should
be avoided. Professionals certainly have the responsibility of not
making people believe that they have some special knowledge that
others can't attain without special means or special college
education or whatever. If things are simple, they should be said
simply; if there is something serious to say that is not simple, then,
fine, that's good and interesting. We can perhaps find deep answers
to certain questions that do bear directly on issues of human interest
and concern, but that is rarely true.&rdquo;</p>
</blockquote>
<h2 id="science-communicators">&quot;'Science' 'Communicators'&quot;</h2>
<p>One of the worst aspects of all of this is that this understanding of
pop-science encourages people to distrust what they know or can judge of
the world in favor of the caricature of the consensus of
institutionalized academics. People have this idea that there are these
intellectual, peer-reviewed demigods in universities who discover the
secrets to the universe and communicate them through their messengers
stationed at BuzzFeed and the Huffington Post. Betraying their infinite
wisdom would make you &quot;irrational&quot; or a &quot;fundie.&quot; The reality is
that these demigods really just went to graduate school because they
were lazy and initiativeless, and even in the abstract, most of their
real work has nothing to do with your life whatsoever. It's only the
messengers that convince you of that because it stimulates their power
trip.</p>
<p>Science journalists, much like journalists generally, are people too
incompetent and emotional to work in the private sector, too dumb to be
academics (and the standards are abysmally low these days), too full of
themselves to work in charity and too bumbling, weak and arrogant to
work in a blue collar or manual occupation. Journalism is an attractive
career to many because it demands the least rigor and honor and promises
the greatest power and influence.</p>
<p>Their self-ordained duty is to overwhelm the public with a confusion of
&quot;studies&quot; that increasingly seem to micromanage a neurotic person's
life. &quot;Studies show that&quot; classical music may help infant brain
growth, or that gluten ravages the intestines, or that simply owning
more books causes higher scholastic achievement, or that Vitamin C or
antioxidants or kale or whatever health-food <em>de jour</em> solve all the
world's problems.</p>
<p>At the end of the day, the worst part is that we talk about &quot;science&quot;
as if it's some kind of anthropomophic creature with desires and
feelings and a plan for us all. It's a uniquely modern flaw to say
things like, &quot;Science tells us that...&quot; &quot;Science is about..&quot;
&quot;Science is against...&quot; Does this not strike anyone else as creepy?
The interpretation of science forced on the public is a scriptural one,
where law to live life by are codified in &quot;peer-reviewed&quot; journals and
communicated by intermediaries. 'Science's' purview is infinite and
any failure to conform is some congenital failure or reason.</p>

## The Fragility of Physics
 - [https://lukesmith.xyz/articles/the-fragility-of-physics/](https://lukesmith.xyz/articles/the-fragility-of-physics/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<p>Physics has a reputation of being a uniquely &quot;scientific&quot; field. In
other fields, you might hear of the concept of &quot;Physics Envy&quot; which is
supposed to be a deep-seated desire of academics of other disciplines
for the rigorousness and elegance of physics. Only physics, so the
popular understanding goes, is truly able to abstract away from the
messiness of detail and create truly beautiful and solvent models of
their subject matters. Physics is thus the queen of the &quot;hard
sciences.&quot;</p>
<p>I object to the very idea of &quot;hard vs. soft sciences&quot; for reasons that
will soon be clear, but I think it is most important to remember that
for all its pretensions, <strong>physics is the most fragile science</strong>. That
isn't necessarily <em>bad</em>, but it's true.</p>
<h2 id="why-fragile">Why &quot;fragile?&quot;</h2>

<figure class="resright"><img src="https://lukesmith.xyz/pix/purity_theology.jpg" title="The purity of theology" /></figure>

<p>Put simply, physics, partially due to its somewhat abstract nature, is
exactly that domain where our interpretation of the universe is <em>most
likely</em> to change <em>radically</em> in the event of any kind of theoretical
sea change. That is, while in other more terrestrial sciences, the data
is well-known and the theory is in debate, in physics, the opposite is
arguably true. In astrophysics, quantum mechanics, the study of gravity
or relativity, this should all be obvious.</p>
<p>Even without departing the cuddling embrace of mainstream physics, we
can actually see this clearly. What is the ultimate fate of the universe
to be? A continuous expansion of the universe until heat death? Perhaps
gravity or some other force will pull everything back in a Big Crunch?
The correct alternative is a statement of very specific and tendentious
data which changes quite a great deal with any kind of new
interpretations of what we see.</p>
<p>It's worth it to remember that for most of man's history, including
the initial development of what we nowadays call physics, the &quot;normal
state&quot; of the universe was assumed to be the state of affairs we're
familiar with on the surface of the Earth: everything falls down to the
ground and things propelled in space will slow down until they stop.</p>
<p>But modern physics now looks at the nature of our life on Earth as an
exception to the general rule of frictionless and continuous movement in
the vacuum of space. A valid question to ask is <em>how much more that we
take to be normal is a special case of reality?</em> As we encounter more
and more abberrant data, such as quantum mechanics, we might soon find
ourself unifying seemingly disparate forces in the same was that Newton
in a novel and seemingly absurd way the fact that objects fall to the
ground with the apparent fact that the Earth orbits the Sun into one new
concept: <em>Gravity</em>. Such a unification religates all our universals to a
special case.</p>
<h3 id="does-light-really-go-the-speed-of-light">Does light really go the speed of light?</h3>
<p>Physics is fragile because it is like a game of Jenga. Pull out or
change one piece and the whole thing is either reordered or simply
collapses.</p>
<p>As an example, say that within several years, we realize that the speed
of light, for some known or unknown reason, doesn't function with the
universality we assumed. Suppose that there is some kind of interaction
of light and gravity such that light is faster in some parts of the
universe. The reason isn't important. Or suppose we merely find out
that in the past, there has been a systematic principle (similar to the
Heisenberg Principle) that has miscalibrated all of our measurements of
light.</p>
<p>Even if we have minutely mismeasured, the Jenga piece of light will
radically alter everthing: our ideas of how old the universe is, our
relationships with other planets, the solvency of general relativity,
etc. You might say that there is a &quot;concordance of evidence&quot; that
attests to our single known speed of light, but another way of putting
that is that we have many other things tied into our interpretation of
light that will have to change if we realize our models of it are
flawed.</p>
<h3 id="poverty-of-data">Poverty of data</h3>
<p>Especially in the astronomical domain, it's worth remembering exactly
how circumstantial our ideas of space are. We sometime speak of the
traits of other solar systems' planets as if we've been there. But in
reality, astrophysicists guess the chemical compositions of foreign
planets based on their light frequencies and other fragile data. Any
systematic error in observation over those thousands or millions of
lightyears and we have been counting angels on pinheads the whole time.</p>
<p>People have the idea that because astrophysicists make extraordinary
claims about planets, galaxies and time periods far beyond our mortal
ken that they must have extraordinary evidence for them. That is frankly
not the case. We have a piece-meal and jury-rigged set of circumstantial
reasoning leading us to these claims. Seeing them computerized in full
color in a science documentary doesn't make them more real. It just
makes them look more official.</p>
<h2 id="physics-vs-soft-sciences">Physics vs. &quot;soft sciences&quot;</h2>
<p>I remember talking to someone over the internet who accused me of having
a low view of institutionalized science and being a dreaded
epistemological anarchist because one of my degrees is in the &quot;soft
science&quot; of linguistics. While I have a lot of bad things to say about
the current state of linguistics, as a field, it is substantially more
advanced and its findings are substantially more solid than physics. At
that, formalizing ideas in math doesn't just make something a better or
a more rigorous science anyway, which is the assumption of many people
have.</p>
<p>While linguistics undergoes theoretical changes every several
generations, the <em>data</em>, or really more importantly <em>the phenomenology</em>
of linguistics is as secure as ever across all theoretical frameworks.
That is, we know how language works. We can see abstract relationships
between morphemes and syntactic structure. Even if we totally rewrite
our narratives and theories about linguistic basics, there is no debate
about the structure of language and how basic data relates to other
data. This is absolutely the opposite of physics.</p>
<p>Physics is pretty solid on earth, and solid when you are running objects
at each other in a vacuum, but once we broach the territory of
astrophysics, relativity, gravity and more or less <em>anything else that
we as humans lack direct intuition of</em> most of the &quot;facts&quot; of physics
are theory-internal facts, and will fade away or be rendered obsolete
when the next theoretical fad comes around.</p>
<h2 id="my-standard-for-theoretical-frameworks">My standard for theoretical frameworks</h2>
<p>I think any serious scholar needs the ability to operate cognitively
with multiple different theoretical frameworks in mind.</p>
<p>For example, (on linguistics) I don't really take Generative Grammar
very seriously, in fact, despite it being on of the most well-funded
dialects of linguistics nowadays, it's pretty inert. Despite that, I
view it as very important for me to be able to process linguistic
problems within Generative Grammar and word explanations within its
ideas. It's nice to be able to say to someone &quot;this alternation is
accounted for if this DP occupies the spec of CP.&quot; I don't <em>believe</em>
in CPs or specifiers as being psychologically real, but I can recognize
the language as communicative.</p>
<p><strong>A good theoretical framework is one that can produce facts and
observations that can be recognized and explained outside of its
framework as well.</strong></p>
<p>That is, a framework should cue us in to finding utterly novel
observations and thus a new <em>phenomenology</em>. This goes against the
egocentric motivations of a lot of scientific frameworks whose
practitioners are trying to edge out &quot;the competition.&quot; Fields that
spend most of their time trying to formalize previous observations
within their own theoretical language are mostly a waste of time (this
is Generative Grammar, frankly, although due to historical ignorance,
many people in GG do not know they are re-treading steps).</p>
<p>One of the biggest issues of modern post-war institutionalized science
is that the funding and peer-review mechanism is self-reinforcing: all
fields converge to be &quot;unipolar&quot;: only one methodology or framework is
deemed &quot;scientific.&quot; This creates a community of &quot;scientists&quot; who
are more an more incestuous and generally oblivious not just to other
possibilities of inquiry, but don't even have to be aware of their own
priors or assumptions.</p>
<h2 id="the-blinders-of-positivism">The blinders of positivism</h2>
<p>As I've interacted with physicists more, I'm often <em>surprised</em> by how
irrelevant they think even the most basic theoretical awareness is.
That's &quot;philosophy&quot; for them. It's not uncommon to hear zingers like
these:</p>
<ol>
<li>&quot;Science isn't about truth, it's about creating models.&quot;</li>
<li>&quot;Physics is about fitting equations.&quot;</li>
<li>&quot;We don't do philosophy.&quot;</li>
</ol>
<p>Things like these are said as if they are some kind of statement of
universal and well-consented-to truth, when in reality they are absurd
Zen koans of the positivist religion. This was a loony opinion a hundred
years ago and people saying these things now <em>know</em> that they are
ludicrous. They have just become identifying marks of the social club.</p>
<p>Yep, science is about creating models... models that replicate reality,
i.e. <em>Truth</em>.</p>
<p>A scientists who doesn't do philosophy isn't a scientist: he's a
meter-reader. A philosopher who doesn't do science isn't a
philosopher: he's just a stoner. The attempt to sever these two words
from each other is part of the problem.</p>
<p>Physicists seem to be particularly touchy on this point. On one hand,
they insist that philosophy is &quot;not their thing&quot; and &quot;not related.&quot;
On the other hand, they get incredibly angry when <em>anyone else</em> dares to
either put the methodology of modern physics to any kind of
philosophical tests <em>or even</em> to look into philosophical ramifications
of their work.</p>
<p>In reality, modern scientists and positivists have their own
metaphysics, it is just an <em>implicit</em> one that they advertently or
inadvertently sneak into their theories. They can only do it because its
clumsy sterile &quot;materialism&quot; is the background-radiation of the modern
world.</p>

## The Parable of Alien Chess
 - [https://lukesmith.xyz/articles/the-parable-of-alien-chess/](https://lukesmith.xyz/articles/the-parable-of-alien-chess/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<p><em>A parable on the Logical Postivist &quot;interpretation&quot; of scientific
models.</em></p>

<figure class="titleimg"><img src="https://lukesmith.xyz/pix/alien_pepe_small.gif" title="Save before they delete it again..." /></figure>

<h2 id="the-parable">The Parable</h2>
<p>Suppose an alien race comes to Earth and wants to observe our games.
They are very interested in chess, despite the fact that they have eyes
with properties that make it impossible to make out what actually
happens on a chess board. (The whites and blacks and squares all blur
together.)</p>
<p>They can still learn about chess experimentally, they know they can sit
two players (a so-called &quot;white&quot; and &quot;black&quot; player) down to play
it, and they can tell behaviorally who at the end wins.</p>
<p>After extensive experimentation, they realize this: 50% of the time, the
white player wins and 50% of the time, the black player wins (we'll
ignore draws and any first-move advantage for the example).</p>
<h3 id="the-best-model">The &quot;best&quot; model</h3>
<p>A logical positivist alien thus creates the ultimate, long-term model of
chess as an iterated game: Chess amounts to just a drawn-out coin flip.
Half of the time white wins, half of the time black wins, just as if
they were tossing a quarter.</p>
<p>The aliens then decide to model chess as a coin flip, as a 50-50 game
with no underlying principles. While this statistical technique might
not be useful for predicting a single game, over the long run and over
iterated games, <em>it is the most efficient and parsimonious possible
model</em>.</p>
<h3 id="inferior-models">&quot;Inferior&quot; models</h3>
<p>Suppose, however that a &quot;crank&quot; scientist of the alien race posits
that &quot;God doesn't play dice&quot; and that chess is a more complicated
game, despite the fact that the aliens cannot observe it. Suppose even
he asks around and determines from humans that there are actually pieces
on the board with functions, and he even devises a machine that allows
his alien eyes to see the first move of the game of chess.</p>
<p>Seeing this move allows him to create a new theory and model of the
game, one that takes into account the first move made and he tries to
generate a new set of probabilities of victory based on that move. The
model he makes, is of course highly arbitrary, stipulated and <em>ad hoc</em>.
In fact, this model is inferior on many inevitable accounts. For
example:</p>
<ol>
<li>It is less predictive over iterated games than the coin flip model.</li>
<li>It is not as parsimonious/minimal as the coin flip model.</li>
<li>It adds new variables to the theory (pieces) that are suspect.</li>
</ol>
<h2 id="which-model-is-right">Which model is &quot;right?&quot;</h2>
<h3 id="which-model-is-closer-to-truth">Which model is closer to truth?</h3>
<p>Since we, unlike the aliens, are not prevented by defect from observing
chess, we know that the second, &quot;inferior&quot; theory of chess is truer.
Its theoretical categories, if apparently arbitrary in the eyes of the
aliens, are getting at the actual underlying mechanics of chess. Even if
the model is less effective, it is certainly <em>righter</em>.</p>
<h3 id="which-will-cause-fruitful-scientific-inquiry">Which will cause fruitful scientific inquiry?</h3>
<p>The coin flip model is a scientific dead-end. Firstly, the coin flip
model is constructed statistically, which presents the underlying
mechanism to be randomness, and thus unworth of inquiry. This isn't
statistics hoisted above random variation we know to exist, instead,
it's utterly blind statistics that covers over whatever principles
underlie it.</p>
<p>Secondly and more importantly, in order to actually improve that model,
it has to <em>lose</em> empirical solvency: embracing the abstractions of
pieces means introducing mess and deviating in some way from the
empircal generalization that half of all chess games are won by white
and half by black.</p>
<h3 id="this-is-not-an-abnormal-circumstance">This is not an abnormal circumstance.</h3>
<p>The parable here, really an <em>example</em> is not abnormal. In most affairs
in science, whether that be physics or neuroscience or economics or
chemistry, we are exactly like the partially-blind aliens.</p>
<h3 id="but-science-isnt-about-truth">&quot;But science isn't about truth!&quot;</h3>
<p>Yeah, it is dude.</p>
<p>Even if you are pretending that science is about &quot;models&quot; or fitting
equations and the like, again, the well-fit model is impossible to
perfect, while the flawed, yet more true to reality model does have a
potential over the long-term to be a superior one. After exhaustive
inquiry, an alien race might not only discover the pieces and the full
set of rules behind chess, they might be able to predict what moves are
good or bad and predict individual chess games. Even on the standards of
mere instrumentalism, the mindless positivistic theory is still actually
inferior.</p>
<h2 id="local-maxima">Local maxima</h2>

<figure class="resright"><img src="https://lukesmith.xyz/pix/maximum.gif" /></figure>

<h3 id="the-plot">The plot</h3>
<p>One of the ways I visualize science and models is that each model is
really like an n-dimensional optimization plot. &quot;Truth,&quot; or if you
deny truth as metaphysics, &quot;accuracy in data&quot; or &quot;well-fit
equations&quot; are upwards and the goal of science is to get further that
way.</p>
<p>At the point you're at, you can tell which direction you can go to move
upward, or, which little changes you can make to improve your model.
That is what incremental science is, after all: don't change
assumptions and just fine-tune your equations. The endless fine-tuning
is sometimes thought of as &quot;progress.&quot; Of course I don't think that
this is <em>bad</em>, but it is a very minor and scientifically less important
part of science as a whole.</p>
<p>The reality of incremental science is that once you're at a local
maximum, once you've fine-tuned your equations about as perfectly as
possible, it's over. Everything next to you <em>looks</em> like a
disimprovement. It <em>looks</em> just like those inferior theories of alien
chess that posit the existence of pieces. From that, you might
erroneously conclude that you have found the <em>global</em> maximum, which due
to the nature of the complexity of the universe and the multiplicity of
possible answers and theories, you flatly haven't.</p>
<p>Logical positivism is kind of theoretical lobotomy that implicitly tells
scientists that they should never, ever, ever change foundational
assumptions: tweaking equations like an oblivious autist is Science<sup>®</sup>
and everything else is &quot;philosophy&quot; or &quot;metaphysics&quot; or
&quot;pseudoscience.&quot; This amounts to keeping each scientific field on
whatever local maximum is closest, utterly unable to extricate
themselves from it even when they see on the horizon abberant data. <strong>If
you want to understand the stagnation of science or any other specific
field, this is where it comes from.</strong></p>
<h3 id="purposefully-bad-science">Purposefully &quot;bad&quot; science</h3>
<p>In <em><a href="https://traffic.libsyn.com/secure/notrelated/S02E01_-_Against_Method_and_For_Pseudoscience.ogg">Against
Method</a></em>,
Paul Feyerabend, in what an unreflective mind might misinterpret as a
&quot;troll,&quot; says that it is important for science that people have
biases, financial interests, interfering religious and political
doctrines and the like in science. Looking at the plot, you might now
see why. When we are stuck on a local maximum, every new data keeps our
already-optimized model where it is no matter how low that maximum
actually is. What you need to shake it up is an external shock that
totally moves our theoretical position somewhere new on the plot where
we can try to optimize at another point, and then compare.</p>
<h3 id="basic-assumptions">Basic assumptions</h3>
<p>A prudent person should be able to question, &quot;Am I even on the right
track or am I playing with some model that has a fundamental flaw?&quot; I
can guarantee you, optimizing for data and fitting math and equations is
easy. <strong>All theoretical programs are wrong because they make incorrect
core assumptions.</strong> This is very hard for the ego of scientists because
it means:</p>
<ol>
<li>Possibly illiterate dilettantes on the internet might see and bring
to attention legitimate theoretical flaws.</li>
<li>All the years you spend in graduate school counting angels on
pinheads in your respective theoretical framework is mostly a waste
of time.</li>
<li>The borders of science are borders more of a sociological club than
being the border of raw rigor.</li>
<li>Most of the scientific work is not meaningful outside of the
theoretical framework that gave rise to it.</li>
</ol>

## Why I Use the GPL and Not Cuck Licenses
 - [https://lukesmith.xyz/articles/why-i-use-the-gpl-and-not-cuck-licenses/](https://lukesmith.xyz/articles/why-i-use-the-gpl-and-not-cuck-licenses/)
 - RSS feed: https://lukesmith.xyz/rss.xml
 - date published: 2020-12-11 00:00:00+00:00

<p>Every piece of software I write I license under the <a href="https://www.gnu.org/licenses/quick-guide-gplv3.html">GNU Public License
Version 3</a> (GPLv3)
unless I have forked it from something else.</p>
<p>The GPLv3 is the premiere <em>copyleft</em> license, meaning that it not
only allows users to run, modify and distribute their own versions of
what I write, but it also requires that no one in that chain of
development restrict and close-source that software: it and software
deriving from it must forever remain open, usable and sharable. Richard
Stallman, one of the minds behind the GPL has described it as a &quot;hack&quot;
of the copyright system because it uses the legal infrastructure of
copyright to ensure software is free rather than restricted.</p>
<p>But occasionally I get asked why I don't use so-called <em>permissive licenses</em> like BSD or MIT. These are free software licenses, but
they <em>do not</em> require that forked versions of the code be free and open
source software. In other words, you can take something written with a
BSD or MIT license, put it in the next version of Windows and no one
will ever know. If you did that with GPL code, you'd be in for big
legal trouble if found out.</p>
<p>I and others have recently taken to calling these permissive licenses
<em>Cuck Licenses</em>.</p>
<h2 id="why-cuck-licenses">Why &quot;Cuck Licenses?&quot;</h2>
<p>Why be mean and bully BSD and MIT licenses calling them &quot;Cuck
Licenses?&quot;</p>
<p>Quite simply, using them is precisely analogous to being cuckolded. When
you really look at it, the similarity is uncanny.</p>
<p>I understand GPL free software and its ethical vision for software. I
also understand that desire for people and businesses to <em>not</em> release
their source code for commercial and monetary benefits. What I don't
understand is simultaneously releasing free code with no requirement
that it remain free. It can now be used against you and others&mdash;if you
had moral qualms about that, you could've <em>at least</em> made money off of
it yourself.</p>
<p>Using a Cuck License <em>especially</em> for &quot;ethical reasons&quot; or &quot;because I
like open source software&quot; is beyond absurd. You're simply writing
code and effectively abandoning the privileges of intellectual property
while allowing any large corporation to come and close-source and
monetize your software and sell it back to you without any other
obligations. You have also abandoned your ability to ever complain about
IBM, Microsoft, Apple or any other tech giant because <strong>you are
literally writing their proprietary software</strong>. These companies even
sometimes take very simple code from minor projects and use it to save a
buck and a little effort.</p>

<figure class="resright"><a href="https://lukesmith.xyz/pix/timnolet.png"><img src="https://lukesmith.xyz/pix/timnolet.png" title="'Noooo! You can't use my heckin' code that I legally gave you the right to use!'" /></a><figcaption>When you license with a permissive license, you don't have a say anymore.</figcaption></figure>

<p>At the end of the day, using a Cuck License is little different from
either releasing software in the public domain or just not licensing it
(in some jurisdictions, at least). It has the pretense of a license, but
for no real function. I suppose depending on which you use, you at least
get your name on the license, but I hardly think that that's how
internet fame and glory is actually distributed anyway. As far as I'm
concerned <strong>using a Cuck License is worse for user freedom than just
releasing it in the public domain</strong>. This is because at least public
domain software can be taken and later additions can be protected by the
GPL. The legal case for doing that with a Cuck License is not so clear.</p>
<h3 id="no-whiners">No whiners!</h3>
<p>The funniest thing is when Cuck Licensers <em>complain</em> that people are
abiding by their licenses. They will <em>complain</em> that people took their
code and made money off of it. They will <em>complain</em> when they don't get
some social credit they feel like they deserve when their code is used
in a project. They will <em>complain</em> if people fork their project and it
becomes more popular than the original. They will <em>complain</em> when some
tech giant takes their code and makes spyware out of it.</p>
<p>If they were serious about stopping any of this, <em>they easily could've
by licensing their project as anything other than a code giveaway</em>. If
you want praise for some contribution, put it in the license. If you
don't want your software used for proprietary software, use the GPLv3.</p>
<h2 id="a-cuck-licenser-gets-what-he-deserves-and-we-all-pay-the-price">A Cuck Licenser gets what he deserves (and we all pay the price).</h2>
<p>One of the funniest and saddest horror stories of Cuck Licenses I can
think of is Andrew Tanenbaum, who released MINIX, an operating system,
under a BSD license. Intel silently took this software (thanks to its
license) and unbeknownst to him, used it for their Intel Management
Engine, <strong>making it the OS of the spyware microprocessor/backdoor now
running in all Intel CPUs</strong>. We all have a permanent NSA backdoor
because of the Intel Management Engine&mdash;all made possibly by Cuck
License cuckery.</p>
<p><a href="https://www.cs.vu.nl/~ast/intel/">Only many, many years later was this even revealed to
Tanenbaum.</a> Read that blog post of his
as he slowly externalizes his mixed feelings, tinged with guilt. After
all, on the &quot;bright&quot; side, he says:</p>
<blockquote>
<p>&quot;I guess that makes MINIX the most widely used computer operating
system in the world, even more than Windows, Linux, or MacOS.&quot;</p>
</blockquote>
<p>Wow, what a proud achievement. But regardless, Tanenbaum already feels
some regret about the fact that his permissive license allowed Intel to
withhold this:</p>
<blockquote>
<p>&quot;This was a complete surprise. I don't mind, of course, and was not
expecting any kind of payment since that is not required. There isn't
even any suggestion in the license that it would be appreciated.</p>
</blockquote>
<blockquote>
<p>&quot;The
only thing that would have been nice is that after the project had
been finished and the chip deployed, that someone from Intel would
have told me, just as a courtesy, that MINIX was now probably the most
widely used operating system in the world on x86 computers. That
certainly wasn't required in any way, but I think it would have been
polite to give me a heads up, that's all.&quot;</p>
</blockquote>

<figure class="resright"><img src="https://lukesmith.xyz/pix/cia.png" title="A glow-in-the-dark CIA gamer" /></figure>

<p>You can feel the regret. <strong>With Cuck Licenses, you get the worst of two
worlds:</strong> You get no credit for your work, nor money for licensing fees
like other proprietary software and your software will be used to
violate your and other users' privacy when it is used in closed-source
environments. Oh, no... copes incoming:</p>
<blockquote>
<p>&quot;Many people (including me) <strong>don't like the idea of an all-powerful
management engine in there at all</strong> (since it is a possible security
hole and a dangerous idea in the first place), but that is Intel's
business decision and a separate issue from the code it runs. A
company as big as Intel could obviously write its own OS if it had
to.&quot; <em>emphasis added</em></p>
</blockquote>
<p>If Tanenbaum had released MINIX under the GPL, we <em>wouldn't be</em> at the
mercy of Intel's business decision. They would've had to release the
source code for the microprocessor, keeping user privacy ensured and
irradicating the permanent spyware liability all computers have
nowadays.</p>
<p>If they wouldn't want to do that, they'd have to just write an
operating system themselves. Tanenbaum is right, they obviously
<em>could've</em> taken the time and money to write an OS themselves if they
had to, but they <em>didn't have to</em>, <strong>because a BSD license cuck wrote
it for them</strong>. Thanks a lot, sucker! Now our computers are being
monitored at a lower start-up cost and we have you to thank. It
would've been a lot <em>more</em> respectable to <em>not</em> use a permissive
license and instead license it proprietarily if he has no moral issues
with proprietary software: he could've <em>at least</em> gotten Intel to pay
him to use his operating system. Heck, if he had used the GPL and if
they took it anyway, he could become an insta-millionaire by suing them
right now.</p>
<p>The moral of the story is perhaps lost on Tanenbaum, who finishes up his
blog post with:</p>
<blockquote>
<p>&quot;If nothing else, this bit of news reaffirms my view that the
Berkeley license provides the maximum amount of freedom to potential
users.&quot;</p>
</blockquote>
<p>&quot;Maximum amount of freedom to potential users&quot; is somehow
mass-surveilance of every computer user thanks to the BSD license.
Thanks for your contribution to &quot;freedom.&quot;</p>
<h2 id="the-freedom-that-cuck-licenses-preserve">The Freedom that Cuck Licenses &quot;preserve&quot;</h2>
<p>&quot;Freedom&quot; is an incoherent buzzword if you don't define it. There are
some people who might argue that the fact that they can't kill and
steal freely is a violation of their &quot;freedom.&quot; That's very true in
some sense.</p>
<p>In the same way, the GPL (unlike Cuck Licenses) &quot;violates&quot; the freedom
of all people to close-source code and hide it from the public and (in
effect) do annoying or privacy-violating things with it.</p>
<p>The goal of the Free Software Movement, defended by copyleft licenses
like the GPL is for all software writers and users to live in an
environment of publicly auditable, editable and exchangable code. The
goals of the Open Source movement have a similar goal, albeit often
guided by practical considerations.</p>

<figure class="resright"><img alt="Cuck-licensers write proprietary software for free." src="https://lukesmith.xyz/pix/janny.jpg" /><figcaption>He does it for free.</figcaption></figure>

<p>Cuck Licenses, however, undermine those goals. They will <em>say</em> that they
maximize freedom by placing no requirement on those who distribute When
you release any code under a Cuck License, you are simply writing free
commercial code for corporations that will inevitably use it against
you. You might as well just <em>actually get a job with them</em> so you can
get paid for what you do instead of just getting cucked. When you
release code under the GPL, you write free software that benefits other
people who write free software.</p>
<p>The Free Software Foundation and the GPL people have correctly realized
that just being &quot;permissive&quot; with licenses is unworkable in the
current environment. The legal infrastructure incentivizes and defends
proprietary software and gives it a systematic financial advantage. The
GPL is a viral antidote to that. Obviously if all software were free and
no laws protected &quot;intellectual property&quot; in publicly obtainable
software, <em>everything</em> would be &quot;permissively licensed.&quot; We don't
live in that world. The GPL and other &quot;copyleft&quot; licenses are ways of
undermining and disincentivizing and making impossible the
close-sourcing of software. Not using the GPL and using a cuck license
is just the same as writing proprietary because <em>you literally are</em>
because all of your software can be snatched up and proprietarily
licensed.</p>
<h2 id="bbuut-the-gpl-isnt-enforceable">&ldquo;B...buut the GPL isn't enforceable!&rdquo;</h2>
<p>I've heard some people pass around the idea that somehow the GPL is
unenforceable. After all, if you have close source software, how can
anyone really tell what's going on? In some cases, that might be true
if you have perfect op-sec. That wouldn't be the case for the Intel
Management Engine above, and that wouldn't be the case for Windows XP,
whose source code recently leaked.</p>
<p>I have known people in industry writing proprietary software and
worrying about the GPL is real. The &quot;virus&quot; of GPL taking over
everything and making it free is something people have to take heed of.
I'm sure there is some level of GPL-violation going on in some places
at least, just because lifting simple routines or copy-and-pasting some
things from GPL with significant enough changes could go unseen even if
leaked, but integrating larger GPL programs would be nearly an
impossibility.</p>
<p>At the end of the day, though, what does it matter? What is a totally
unenforced GPL? It's just a Cuck License&mdash;Isn't that what license
cucks want? So why should they care? At their very best, BSD and MIT
licenses are only what GPL might be at its very worst.</p>
<p>The GPL is a permanent liability for any company that crosses it. Some
companies might be so bold to lift GPL code and hide it, but there is
always a risk and a worry that prevents its general violation.</p>
<h2 id="addendum">Addendum</h2>
<h3 id="are-copyleft-licenses-always-best-even-for-freedom">Are copyleft licenses always best even for freedom?</h3>
<p>No!</p>
<p>Here's a question I got about this article that I'll reproduce here
because it touches on something good.</p>
<blockquote>
<pre><code>[personal details omitted for anonymity]

However, I read your article, and I can see your point. I have an idea for an
Operating System and due to your arguments, I would definitely license that
under the GPL, as well as any new programs I write. I might even change most or
all of my current programs to GPL, with the exception of that bc, which needs
to remain BSD since it is default in FreeBSD now.

That said, I have a library I am working on, and my experience is that
libraries under the GPL do not get used, unless a commercial license is offered
as well, and often, not even then. You can see this with glibc, which has a
special linking exception and the fact that the LGPL is fairly popular for
libraries.

First question: what is your opinion on the linking exception and the LGPL? Are
they Cuck Licenses? I mean, they do require that the library and any
modifications be put under the LGPL, which means that the library remains libre
software. However, they can also be put into proprietary code, which is the
entire reason you call MIT and BSD licenses Cuck Licenses.

Basically, it seems as though you are correct when it comes to licensing
programs themselves. But it gets murkier when talking about libraries.

[other personal details omitted]
</code></pre>
</blockquote>
<p>This was my response to this email explaining this finer point.</p>
<blockquote>
<pre><code>Yeah. There are sometimes times when it is tactically better to license
things under a permissive license if for institutional reasons:
mass-adoption is required and companies and such might be unnerved by
the GPL. Libraries might often be like that. So it's not necessarily a
purity-spiralling point.

RMS actually advised that ogg/vorbis should use a cuck license to
maximize adoption (it originally used the LGPL, but switched to BSD):

https://lwn.net/2001/0301/a/rms-ov-license.php3

It's thanks to this that it has now become a usable and wide-spread
format, used now on nearly every proprietary web service because of its
small-size, good fidelity and general superiority.

So yeah, if you're writing a standalone program, I'd use the GPL, but I
would choose licenses ultimately in terms of which would maximize the
possibilities for users of using free-software. In some circumstances,
that means using a cuck license. Same is true of the LGPL. I think
GNU/FSF recommend LGPL only to be used when it is competing with a
proprietary library, and if that's usually what you are writing, you
might end up writing a lot in the LGPL.
</code></pre>
</blockquote>

