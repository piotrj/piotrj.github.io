---
layout: post
title:  "There is always a process"
date:   2016-12-06 06:52:18 +0100
permalink: /blog/there-is-always-a-process
---

_This post has been originally posted on [Medium][medium]_

After reading the article about [how they used data analysis to find a rogue train in Singapore][rogue-train] (you should really read it, it is amazing) I started thinking. Not exactly about the topic of the article. Not about data analysis either. Or code for that matter. I guess it was the whole story, how it was written and how it showed the investigation unfolding and all the “Aha!” moments that made me ponder.

* * *

So often I look at some finished project, at its sophisticated structure and brilliant ideas and deep down have this feeling that I could have never figure such thing out. How on earth a person could form a thing like that in their brain. Out of thin air.

There is a small part that I’m not seeing though. I’m not seeing that what is in front of me is a product of many other solutions, problems and adjustments, good and bad decisions.

> We found a rogue train by looking at incidents occurrence data.

Such statement would be impressive. Man, how did they figured it out. There is no way I could have done that. I wouldn’t even know where to start. How do you start looking for a train in raw numbers? How am I even supposed to know that I am looking for a train? All I know is that stuff breaks from time to time. Are those incidents connected? I don’t know …And you know what, they didn’t know too.

The whole investigation started with them cleaning data and displaying it in some very rudimentary way.

> Well I could have figured that out…

you might say. And you are probably right.

* * *

I’m a software engineer. For last few years of my career I have been focusing mainly on Ruby. You may have heard about it. You probably heard about Ruby on Rails by now too. Sometimes I would go there, play with the code, help fix some bugs. Every time I’m astounded with how complex it is. How many layers and how many ideas are there.

How anybody could have just sit down and come up with something like that. In the moment of weakness I would have such thoughts: “Man, those people are machines. I must not be very smart. There is no way I could have invent that refined architecture. My cuffs are not big enough to get something like that off them”. And then it would make me sad.

I would try to fix some bug. But there is so much code I have no idea where to start. So much information that you would need to study for a week to know basic dependencies. “I would never start debugging”. And I’m even more sad.

* * *

Fortunately, since most of modern code-related stuff is in version control I can go to the very beginning and see how Rails progressed to be the massive framework it is today. And boy, it was a long road. It took 10 years to get to the current state. There were a lot of discussions on the way. Good and bad ideas were thrown all around. There was even a schism and then big reconciliation among Ruby web framework enthusiasts. So, current Rails is actually 2 major projects merged together. And probably dozens of small ones. Over 3000 people contributed to that one project.

When you look at the majestic structure of Rails you may forget that, way back in the past, it all started with someone sitting in front of an empty screen.

You always have to start somewhere. When I am on that bug hunt I mentioned before, I just choose a place that I think may be vaguely connected to the thing I am looking for. Am I right? Great, I continue digging deeper and deeper. Am I wrong? Then I look for some other place to start.

Repeat.

On the way I may learn a thing or two, so next time it would be easier for me to identify those hot spots.

* * *

[Casey Neistat][casey-youtube] in one of his wildly popular vlogs, said that there are two points in life - where you are and where you want to be. And between those two points is just some amount of work that you need to put in to get from point A to point B.
[And when you follow the path you may take some twists and turns in the process][casey-path]
And those twists and turns are essential formative ingredients that make the result of your work what it actually is. And makes you, you. And makes your path, your path. This could have been easily observed recently when he and his business partner Matt sold their social media company to CNN and will
[build modern media platform that would fit current day and age][casey-cnn].
But I bet that when they were starting [Beme][beme], an app that is based on an idea that can be put next to Snapchat and Instagram Stories, not once did they think that it will lead them to a deal with CNN. To push news outlets into new era. For (reportedly) whopping 25 million dollars.

* * *

I’m not saying that Daniel Sim and company should not be recognized for the amazing work they have done investigating the problem in Singapore’s subway system. The way they came up with conclusion is still amazing even though they started with very basic stuff. And it took them only a day to figure this out.

I’m not saying that Rails is just another piece of software that we should not marvel at. In a large part it helped to shape the internet that we know today.

I guess I’m just trying to say that whenever you see some amazing work, you have to remember that there is most likely a long process behind it. When you see someone come up with a brilliant idea, it most probably did not happen overnight, but was preceded by long preparation and hard work. And even though you don’t see yourself coming up with this idea or building that splendid thing any time soon it does not mean you won’t. Just take the first step.


[rogue-train]: https://blog.data.gov.sg/how-we-caught-the-circle-line-rogue-train-with-data-79405c86ab6a
[casey-youtube]: https://www.youtube.com/user/caseyneistat/
[casey-path]: https://youtu.be/7HF4peQxeXA?t=393
[casey-cnn]: https://medium.com/@mhkt/beme-is-shutting-down-but-our-work-is-just-starting-3d4636b37c32#.ng2ld5b9s
[beme]: https://beme.com/
[medium]: https://medium.com/@piotrjakubowski/there-is-always-a-process-9817a72ace03
