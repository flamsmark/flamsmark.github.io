---
published: true
layout: illustrasplosion
title: You Probably Shouldn't Just Run Your Own Infrastructure
subtitle: 'Specialization, expertise, and deduplication of effort in grassroots infrastructure'
lede: Email, online storage, instant-messaging and the like are core infrastructure for both hackers and humans in the 21st century. It's often said that <a href="https://noisysquare.com/run-your-own-fcking-infrastructure/">running your own</a> instances of these services is the only route to a trustworthy provider. However, running infrastructure takes a fair amount of time, money, and effort to get right.
category: an essay
reading-time: five or six minutes
revision-date: 2013-09-13 00:00:00
image: powerlines-shoes.jpg
image-alt: A powerline at sunset. Dozens of pairs of shoes adorn the line.
image-caption: <a href="https://secure.flickr.com/photos/nathangibbs/70425448/">Shoes On the Line</a> by <a href="https://secure.flickr.com/photos/nathangibbs/">Nathan Gibbs</a> on <a href="https://secure.flickr.com">Flickr</a> / <a href="https://creativecommons.org/licenses/by-nc-sa/2.0/">CC BY NC SA 2.0</a>
---

You know the deal. The NSA does a bang up job of intercepting the internet, and they're cataloguing all your emails, your sexts, your snapchats, and your tweets. Sometimes the spooks even check out who you were calling [without even realizing they're doing it][1]. All your favorite tech companies are collaborators, and so's Yahoo. You can't even rely on the might of Google and Facebook to keep the NSA out of your email and... basically everything else that there is to know about you. What now?

I suspect that you're not ready to give up on email yet, as much as you might like to. Some folks like [Mc.Fly][3] have been dropping by [hacker][2] [camps][5] & suggesting that you just [run your own f'ing infrastructure][4] already. I don't want to freak you out, but that's really quite hard. Each of the sorts of services you use has its own ocean of software, with diverse foibles and config files, and a whole bunch of different ways to set up the encryption wrong. Then you need to make sure that it stays working, even when your roommate trips the power by running the kettle, toaster and microwave at the same time, or your ISP has an outage. You need to make sure to install security updates, and make sure that you don't run out of any of the scarce resources that your servers need to keep running smoothly.

This is a lot of work; it takes time and effort. You need to become an expert in several specialized tech fields to get things right. Plus: servers aren't cheap, and nor are fast, reliable network connections, or even power. Running your own infrastructure is a serious commitment. There's a reason that companies have sysadmins, IT departments, and server rooms. Specialists keep everyone from having to spend time learning arcane skills. Centralization means that you only need to get one of something, and set it up once, rather than everyone needing to get their own.

On the other hand, it's hard to build a central system which meets the needs of a thousand people, let alone a million. Gmail has somewhere between four and five *hundred* million users[¹][6]. Centralization also makes those central systems into juicy targets for control, exploitation, and surveillance: last year, Google got more than forty thousand requests for user data[²][7]. So: you're not willing to give up email, you don't want to use a big central system, and you probably shouldn't just run your own. What's left?

Set up and share infrastructure with your friends. You can share responsibility: one person works on email while another runs the storage. You can share costs by running lots of services on the same physical machine. You get to centralize and pool your knowledge and resources among a group of people you know and trust. Your communal services and community sysadmins are probably not very interesting targets for three-letter-agencies. Different groups of folks can pick different software and setups depending on their needs.

Don't have a bunch of reasonably-technical friends who're interested in trying new things? Go to your [local hackerspace][8] and make some new ones. Don't have a local hackerspace? Now you have two projects!



[1]: https://twitter.com/normative/status/377938813236285440
[2]: http://toorcamp.org/content12/36
[3]: http://www.elmarlecher.de/main.shtml
[4]: https://noisysquare.com/run-your-own-fcking-infrastructure/
[5]: https://archive.org/details/OHM2013-RunYourOwnFuckingInfrastructure
[6]: http://www.theverge.com/2012/6/28/3123643/gmail-425-million-total-users
[7]: http://www.google.com/transparencyreport/userdatarequests
[8]: http://hackerspaces.org/wiki/List_of_Hacker_Spaces
