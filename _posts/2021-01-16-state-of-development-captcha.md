---
title: 'State of Development: Captcha'
layout: post
tags:
- Red
- Cogs
- English
date: '2021-01-16 00:37:11'
author: Predeactor
category: blog
description: More informations of the actual state of development of the Captcha cog.
---

I am lazy. I do not feel any new feelings for coding, instead of being annoyed. And it's kinda, hard to start typing code without feeling good, to be honest.
## From Captcher to Captcha
Actually, I have a cog called Captcher on my repository, which is made for when someone join the server, it got challenged through a captcha test.
If this seem easy enough... It's not really. There is a ton of things to take in count when you make the kind of cog that must wait for shits and stuff, like:

- I must generate the image, create the code, and check if both are correct
- I must send it, check if everything goes fine, if there was nothing bad in permissions while the bot was taking a rest.
- Whenever I wait for user's response, did he leave meantime?
- Is the code correct to what it gave?
- Can I give roles?
- Was role given?

And ton of others things...

Actually, Captcher cog is maybe one of the worst cog to install... really, I am serious. The cog is a pure pain for me and your bot.
Everything is handled in the `on_member_join` function, which is a REALLY BAD idea, there's no class for the on going challenge, and that's really bad and nasty from me...

So my first goal was, make something more sane, more clear, more performant, more trustable. And boom, from the idiot Captcher to the awesome Captcha cog!
First, I called the first cog Captcher because of a problem that happens with cog and pip, which is used to install some things that can be useful for developers. Captcher and Captcha are depend of a library called "captcha", if I also call the folder that store all files for the cog, Python will refuse the code, because of some non importable thingy, so what did I do? I heavily copied the dependency's code into the cog's files and... yay, it work, a little victory!

You didn't understand what I wrote? It's fine;..

## Making the cog
When I started writing the cog, everything was pretty fine, everything goes well, everything was... quite better, but here was my first mistake: I didn't made any road maps, any list to follow.

Believe me, **if you want, or plan to make an important cog, plan everything before**, or everything gonna be a mess, you won't know what you're doing.

So, I finally ended up with a somewhat proper list of to-do:

![Cool page, right](https://predeactor.please-end.me/U0Qdqb.png)

![All the to-do, to do...](https://predeactor.please-end.me/8yigwc.png)

For being honest, writing those weren't so easy, because of what I already wrote in my code, I was trying not to delete too many things, but, eh, guess what, ton of things already got deleted...

Sure, before making this "Follow the rules" page, all I was doing was in my mind, I was thinking everything directly in my head... 
Also, let's... don't talk about the fact I'm not using a lot of comments in my code (what a good dev I am)
## Over the time...
So... It's been 6 months since Captcher is available... *sigh*
i really want to get ride of him, even if it was one of my most major cog (Maybe not the most used one tho), it doesn't mean it's my proudest work, nope, not at all, at this point, it could be CustomCooldown cog.

Over the time, I've lost myself in making this cog, things didn't turn well, I wanted to do other things in the meantime.
When I was completely rewriting the cog, I also closed my support server and closed my IDE (Where I work on my code, basically, with all the cool dev stuff) for a good time.

![Announcing some pause](https://predeactor.please-end.me/YakBaO.png)

Meh, it was also because my laptop broke. lul.

But I've discovered other things too, while this was happening, all I wanted was to get back my laptop and open a new project, and make it, Red was... a little bit overtaking from me, to be all honest.

# Now?
Now? Now... Captcha will be delayed.
.
I don't want to code because I must code while advancing, being blind. Not anymore.
Even if it's gonna take way, way, way more time than I expect, I'll still continue on making this cog, but it will be only when I want.

I mean, yeah, I must advance anyway, but this does not limit to my fingers, my keyboard and my Python's knowledges, I still must think of me.

Red is a project I am happy to work one, really, but it take a lot of my time, and I may not have a ton of time, most especially with the global pandemic and my work.
