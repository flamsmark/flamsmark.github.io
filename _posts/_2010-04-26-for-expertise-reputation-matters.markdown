---
layout: essay
category: an essay
title: For Expertise, Reputation Matters
subtitle: Reputation as an SnR amplifier
reading-time: nineteen minutes
revision-date: 2010-04-26 00:00:00
---

Techniques for optimising useful expertise output from crowdsourcing.

When we talk about crowdsourcing complex tasks -- like writing policy, or designing a product -- we are always faced with a similar set of conundra. We want to crowdsource because we think that there is someone -- perhaps a great many people -- out there on the internet (just past the clouds), who have the time, inclination, and expertise necessary to solve this problem. However, there are also a great many people who make the undead hordes look positively Nobel-worthy by comparison. Unfortunately, all the members of the latter class *think* that they are members of the former class, and are happy to *[orate from their respective recta until the bovines are redomesticated].

Typically, the aim of crowdsourcing is to reduce the workload of the crowdsourcer. Unfortunately, traipsing through heaps of mindless drivel in search of occasional, fleeting examples of peerless insight is not fun, and a lot of work. To make matters worse, crowdsourced problems are typically not true needle-in-a-haystack problems: the answers may not be obvious, even after having them pointed out. However, often, they will display some needle-haystack-like properties. Although there is rarely one obviously "right" answer, there may be many "good" ones, which are not too difficult to identify.

Fortunately this is a problem which geeks have faced before, and for which they have produced some interesting solutions. Technologies like [UserVoice](http://uservoice.com/), [Get Satisfaction](http://getsatisfaction.com/), and [Google Moderator](http://www.google.com/moderator/#0) are all designed to adress different versions of this problem. Each one is designed for a specific use case, and imports certain assumptions and optimisations for that particular application. However none of them take advantage of one of the most powerful metrics of all: reputation.

Currently, those platforms -- and their brethren -- treat all users equally. There are, however, other systems -- mostly dealing with user comments -- that allow users to "rise through the ranks", as it were, by accruing reputation. Slashdot's [commenting system](http://slashdot.org/faq/com-mod.shtml), and Gawker's ["featured comments"](http://gawker.com/5311027/gawker-comments-are-made-of-stars) are both designed to estimate the value of a commenter's current contribution to the conversation based on the community's collective consideration of their prior participation.

If many of the active members of a forum think that my ideas are good, it's likely that I have good ideas. Further, if my opinion of an idea is a good predictor of the community's collective opinion of the idea, it might be worth giving my opinions additional credence. This is some of the way that Facebook and Google Reader respond to "like"s. If a user likes several things which are alike, it is likely that they'll like other things like those. A similar principle can be applied to expertise-sharing systems like those noted above. Combining crowdsourced evaluation with persistent reputation might be a reliable method for filtering the dross from such systems.

Understandably, community-based reputation creates the risk of sock-puppetry. However, it is the pervasive and organic nature of such reputation and evaluation systems which make them most resistant to this class of attacks. Because up- and down- voting, establishing and applying reputation is part of users' day-to-day interaction and participation with the system, sock-puppets are unlikely to have similar activity signatures to legitimate users. Moreover, because "contributions" are made in the form of computer-readable activity first, and text second, the potential reliability of automated sock-puppet-identification is improved.

At the end of the day, it's not how you say it, but who says it that really matters. So, If we're designing systems to determine what's worth hearing, we'd better note who's talking.

	{% include links.markdown %}
        {% include img-links.markdown %}

   *[orate from their respective recta until the bovines are redomesticated]: talk out of their asses until the cows come home
