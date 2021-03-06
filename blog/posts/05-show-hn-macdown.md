---
title: "Show HN: MacDown"
author: Tzu-ping Chung
published_at: 2014-08-25 18:00:00
---

MacDown showed up on HackerNews yesterday [again](https://news.ycombinator.com/item?id=7946786). This time as a [Show HN](https://news.ycombinator.com/item?id=8217360)—Wait, I though Show HN is for sharing [something that you’ve made](https://news.ycombinator.com/showhn.html)? I don’t recall myself posting anything on HackerNews. Ah well, I get the [clicks](https://twitter.com/MacDownApp/status/503389840008687616/photo/1), and that certainly isn’t something to complain about.

Anyway. There seems to be some confusion about the origin of MacDown, and its relationship (if there is one) to Mou. I’ll try to go through some things that happened in chronological order so that you might get a better idea why things are how they are now.

I was a long-time Mou user (since late 2011, I think) before starting MacDown. It was fine for the most part, being standard-compliant, steady, good-looking, and simple. But that was also the time when I started using GitHub. The more I write on GitHub, the more unsatisfied I became.

Last year (2013) I built my personal website/blog. I included a Markdown-based publishing system inspired by [Logdown](http://logdown.com) and [Ghost](https://ghost.org), and started writing even more Markdown documents. I [illustrated](https://uranusjr.com/blog/post/58/introducing-macdown/) some problems I had in a blog post (in Chinese) when I launched MacDown:

![Code block rendering in Mou](http://d.pr/i/oh5B+)

![Code block highlighting in Mou](http://d.pr/i/UkDg+)

Which made Mou far from ideal for technical articles.

You know what happened next (take a look at <http://macdown.uranusjr.com> if you don’t). Mou didn’t (still haven’t) receive an update since September 2013, and there were efforts made trying to sell it.

Some supplemental comments might be necessary here. There aren’t further campaigns trying to sell Mou after the initial failures, and according to [various](https://twitter.com/chenluois/status/485060820863160320) [tweets](https://twitter.com/chenluois/status/488989332380712960) [on](https://twitter.com/chenluois/status/496165170092056576) [this](https://twitter.com/Mou/status/490445700186914816) [issue](https://twitter.com/chenluois/status/482107255584612352) development is now alive again. Which is good news. :)

Back to the storyline. I looked for alternatives to Mou, but there are none (no free ones, at least), so I decided to roll my own solution. It’s just a text view, an embedded web browser, a Markdown-to-HTML engine (there are tons of those available on the Internet). Can’t be that hard, right?

(Well turns out it’s not easy either, and MacDown still isn’t as good as I wish. But that’s another story.)

I spent two weekends putting together MacDown. Most things went smoothly enough, but I still lack some good-looking editor highlighting colour schemes and CSS for the HTML output. So I contacted Chen Luo and asked whether I could re-distribute his themes and styles. The conversion went like this:

> Me: I’m building a Markdown editor, and I like the PEG highlighting styles in Mou a lot. Can I use them?
>
> Luo: Yes, you just need to put a notice that the CSS came from Mou, and attach a link to Mou’s homepage.

You might notice that

1. I mentioned that I was building a Markdown editor, but not exactly *what* I intended to do.
2. I was asking about *editor styles*, but Luo’s said *CSS* which is used in HTML.

Looking back, maybe I should’ve been more explicit. But I didn’t think that much at the time, and just went on publishing the initial version of MacDown.

Things went well until Luo found out (if that’s the right expression) about MacDown. Obviously he felt offended, accusing me being a [copycat](https://twitter.com/chenluois/status/484813471842705408). Now, nobody would be happy being called a copycat, but I did copy his idea. He is right. So I took this advice (which is *not* tweeted by Chen Luo, the author of Mou, I should note):

<blockquote class="twitter-tweet"><p>那些 “Inspired by XXX”，克隆，并开放源代码的人都应该吃屎。他们应该将 Description 换成 “Stole the idea from XXX, and let everyone make crappy clones.”</p>&mdash; Sean Cheng (@remaerd) <a href="https://twitter.com/remaerd/statuses/484914820408279040">July 4, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

> Literal translation: Those who clone and open-source softwares “inspired by XXX” should all go eat shit. They should change their descriptions to “Stole the idea from XXX, and let everyone make crappy clones.”

and changed the [project description](https://github.com/MacDownApp/macdown/blob/master/README.md) accordingly.

And that’s the end. I guess. MacDown is still fundamentally the same with Mou—they are both OS X-specific Markdown editors with an instant preview pane that can be styled with CSS, and offers syntax highlighting in the editor. But so are a bunch of other softwares—Just search for “Markdown” in the App Store. At least my own crappy clone has unique features Mou doesn’t offer, and they are useful to some people, including myself. I’m fine with just that.

So now you know what happened. I don’t have (more) “philosophical axe to grind with the author of Mou”, and the author of Mou did not tweet the specific tweet mentioned. And developement of Mou will continue. But none of them matter anymore. MacDown holds its own ground now, and should continue to survive as an free (as in freedom) option toward Markdown editing. Let’s focus on making better software for everyone.

Note: Please kindly drop a word if you feel there are inaccuracies in this article, or if I missed some thing worth mentioning. I wrote this from my own perspective, and is likely to not be objective enough. Thank you.
