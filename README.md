# Kawaii-AI
DIY AI for free!

OK so look, I don't think we need a whole river of water and a mountain of copper to get an AI to do basic stuff that it would be good at, like librarian type of functions; summaries and search.

SO background, I used to do some translation back in 2016 that must have been and back then machine learning, OCR, translation libraries were doing a lot of the work, I kinda saw it coming that AI was going to be doing a lot of the work, but basically that's just clerical work and what it essentially would do is work ahead of you and you would check what it had done - so it was a massive help in productivity. Prices got squeezed and anybody without a barrier to entry eg. lawyer or doctor was gonna struggle to get paid. Nowadays of course you just use DeepL unless you need a rubber stamp.

There's all this noise that AI is going to take over the world and so on - well, there's a big difference between LLMs and general AI.
I reckon what is going to happen is, many companies will believe the hype, buy the services, fire their people, then the prices will go up - and it's not going to be cheap, and it may be too late to self host depending on how regulations work out. It'll be the same story as cloud computing.
I mean you could just deploy your own AI to do information management and everyone's helpful assistant.

Anyway just for fun and for a proof of concept, I'm going to deploy an AI agent on some hardware I got for free.
It's a Fujitsu Mini PC - an Esprimo Q900 from 2011.
Here are it's stats;
  Intel i5-2520M CPU @ 2.50GHz
  8GB DDR3 12800

2 cores, 2 threads, all obsolete. This is the cutest AI deployment I am currently aware of. Let's begin.

The first issue is the power button has fallen off and it's a cap touch sensor so I have to reach into the case with a pencil and touch the other end of the graphite - power on!

POST - boot, great. Let's ditch this mobile HDD and put in this 60GB Kingston SSD that I actually found in some computer that had been out in the rain for weeks to months - still works! (I mean it's solid state right? The power was off)

Debian NetInstall, SSH from my actual computer (It's also an Esprimo I got for free), ollama, qwen3:4b...

OK so there was quite a lot of bad noise at this point and as you might suspect, the core temperatures hit 100°C in very quick time.

OK so Thermal paste, no problem. Is that... the cooler has blued?

I notice at this point, that this machine is built down to a price. 

OK so what I want to do is first make an idiom generator, it's going to message me with some absurd idiom once a day. For morale.

Then I want to have it work as a queriable librarian so I'll give it some large PDF and be able to ask questions about it. Like the PMBoK. You know, that huge PDF file you're supposed to have read and somewhat internalised? Yeah I'm going to get it to do that job for me - AI will be super good at that.

Obviously I want it to sleep most of the time, and I'll track its power consumption - to prove the point - AI agents do not need to cost the world and do not need to be hosted by some wizard in their tower.

OK so it works generating a pointless phrase - I mean it's not actually good or fast, it took like 30 minutes to come up with "Wenn ein Schmetterling ein Schwein trägt, dann ist es ein Schwein."
Probably gonna do some work on that.
