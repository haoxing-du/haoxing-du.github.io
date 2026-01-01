---
title:  Alignment is neither necessary nor sufficient for the future to go well
date: 2025-11-04
tags: ["AI safety"]
mathjax: true
draft: true
---

Here are some loosely connected thoughts—more like vibes than arguments—on why we might actually survive the rise of AI.

## 1. The old man who lost his horse

Here is the translation on Wikipedia of the famous Chinese parable, 塞翁失马.

> Old Man of the Frontier Loses Horse

> Good luck and bad luck create each other
and it is difficult to foresee their change.
A righteous man lived near the border.
For no reason, his horse ran off into barbarian territory.
Everyone [people] felt sorry for him.
[But] His father spoke [to him]:
"Who knows if that won't bring you good luck?"
Several months later,
his horse came back with a group of [good, noble] barbarian horses.
Everyone [people] congratulated him.
[But] His father spoke [to him]:
"Who knows if that won't bring you bad luck?"
Now his house is rich in horses
and the son mounted with joy/loved riding.
He fell and broke his leg.
Everyone [people] felt sorry for him.
[But] His father spoke [to him]:
"Who knows if that won't bring you good luck?"
One year later
the barbarians invaded across the border.
Adult men strung up their bows and went into battle.
Nine out of ten border residents were killed,
except for the son because of his broken leg.
Father and son were protected/both survived.
Hence: Bad luck brings good luck
and good luck brings bad luck.
This happens without end
and nobody can estimate it.

I have been thinking about this story a lot lately for non-AI-safety-related reasons[^horse].
And even if you don't work on weather forecasting as I do, you should know the world is fundamentally chaotic. 
You can’t predict what’s going to happen, certainly not through pure reasoning. 
There isn’t a level of intelligence that lets you perfectly foresee every consequence or execute a flawless plan, which I think features in a number of AI takeover stories as how humans end up defeated.

In fact, this is often cited as a reason why it is hard to ensure superintelligent AI goes well.
Anyone who thinks they can “outsmart the world” enough to design and execute a perfect plot is delusional; the world is too unpredictable. 
Even if you are extremely smart, you should *know* that you’ll inevitably screw something up.
Even we, at mere human-level intelligence, know this.

[^horse]: The startup I work for, WindBorne, recently got a bunch of relatively positive news coverage due to the most serious safety [incident](https://windbornesystems.com/blog/ua-1093) that had happened in the history of the company.


## 2. “Smart” is a messy word

We call a lot of different behaviors "smart," but they’re not the same thing.
Here are at least three buckets of things that we call "smart" but are distinct:
- Passing exams, solving math problems, playing chess
- Reasoning about causes and effects, distilling theories from observing patterns
- Making plans and decisions that lead to good outcomes

In humans these are highly correlated, though already imperfectly.
This is why the world is not run entirely (or even predominatly) by IMO metalists.
The recent progress in LLMs has further exposed this disconnection. 
Some people are calling this "spikiness"; in any case they’re showing us that many forms of "intelligence" that tend to go together in humans are quite separable. 

I think a lot of (not all) discussion on AI risk from current models is ignoring this distinction.
Elon Musk isn’t where he is because he’s the smartest guy around.
VCs are not picking which founders to fund by SAT score.

We’re seeing models get better at specific tasks, but there’s little evidence so far that they’re improving at *making decisions that make them more effective agents*. 
Maybe one can argue that getting better at programming tasks (METR) and solving math problems is one such evidence, but I think they are much closer to playing chess and acing exams than creating a few of the most valuable companies in the world. 

[intelligence like and unlike magic discussion?]

[By the way this is a contingent view. I do think that if the frontier AIs today are trained like AlphaZero without the LLM base on long-horizon tasks that require them be effective in the world, I would be more worried.]


## 3. Intelligence isn’t the bottleneck

Most real-world problems aren’t bottlenecked by the intelligence level of the people working on them, or by the number of people working on them. 
A lot of the intuition of superintelligent AI being scary comes from them being smarter and faster than humans, plus their ability to run 24/7 and have many copies run in parallel.
Sure this increases the amount of intelligence available a lot, but in practice, progress is often limited by other factors: coordination, logistics, incentives, physical constraints.

I thought this before I worked at a hardware startup, and working here has reinforced this view.
I work for a company with a very straightforward goal: Get to Atlas, a network of 10,000 of our global sensing balloons aloft at any given time.
We are hiring talent to help with the scaling, but it's obviously not the case that all we need is more talented people.
Adding more smart people doesn’t make us scale 10x faster. 

Dan Wang's process knowledge


## 3.5 What makes people effective?

I don't know but the vibe I get is something like motivation and drive.
I think this is the same reason that humans are power-seeking agents but mostly don't take over the world.



## 4. From LLMs to "the AI"

I think almost everyone agrees that pure next-token predictors, like the base model of GPT-5, no matter how low of a training loss they achieve on the pretraining corpus, is not able to take over the world in one forward pass.
Then, how do we get from today’s next-token-predicting LLMs to some more agent-like entities in AI takeover stories?
It feels like the details should matter here.
The current paradigm—pretrained, RLHF’d, maybe scaffolded models—still boils down to a giant function generating one token at a time. Each forward pass is a new instance.

How are these supposed “agents” coordinating with each other? Are they even the same entity in any meaningful sense? Given that they often can’t follow a simple three-line instruction, it’s hard to imagine them organizing world domination.

The missing ingredients—persistent memory, online learning, individuality, lived experience—are precisely the things current systems *don’t* have. Without them, it’s unclear how a persistent, goal-driven, world-changing agent could emerge.

Specifically I don't think the AIs gets being really good at coordinating with each other for free.


## 5. Alignment seems neither necessary nor sufficient

This might just be me misunderstanding what "AI alignment" is supposed to be mean, which I think usually is stand-in for "making sure the AIs do what we want them to".
I'm just not sure why this is a reasonable goal at multiple levels.

Level 1: It seems like we haven't really succeeded at aligning anything ever?
Parents usually don't succeed at getting their children to do everything they want them to do.
Corporations often act in ways misaligned with public good. 
Countries certainly aren’t aligned with their citizens’ best interests.
Heck, even ourselves—when I open Twitter for the 50th time of the day, I *know* that it's not in my best interest and it's not what I wanted to do when I sat down to write this blog post.
I don't know why it would even be conceivable to align a superintelligent AI.
And about the things that we do currently face that are misaligned, it doesn't seem like the problem is that they are misaligned.

Level 2: "What we want" is not computable.
This is aside from the concern for who is supposed to be "we", or who gets to set the values and goals for AIs, or how we are ever going to agree if we can't agree on much more basic things.
I frequently find myself in situations where I don’t always know what I want. 
I encounter a new situation, I deliberate, sometimes for a long time. 
Maybe I notice a value conflict I hadn’t seen before, maybe I change my mind on something.
Is the idea of "aligned AI" that it will reproduce the outcome of that internal process for me, or every future situation?
If I later turn out to regret my decision, does that mean I was misaligned with my future self?

Level 3: Are we simply talking about unintended consequences?
Even if we succeeded at aligning AIs—made sure that AIs do what we want—I'm not sure things are going to just go well by default, because there still will unintended consequences, just as there is with everything.
Like pollution and inequality from econonic development.
Comment from my friend that caused me years of mental health struggles.
We are back to the old man that lost his horse.
I don't think it's helpful to use the alignment/misalignment frame instead of simply talking about unintended consequences.
I certainly don't see how it would help if we came up with a theoretical solution to "alignment" by reasoning about decision theories or what not.

The uncharitable view on this is that we have in fact solved (with RLHF) the hard part of what people worried about "misalignment" were worried about (specifying what it is that you want).
Sure there is still reward hacking—but fundamentally you can't reward-hack into taking over the world.
What is left is good old unintended consequences of any normal technology.
Maybe let's call it that.


## 6. Who’s worried about AI takeover?

This is a meta observation: the people most concerned about AI existential risk via takeover tend to have a particular set of shared characteristics. 
They’re often thinkers rather than builders.
People who prefer reasoning to experimentation—guilty as charged here by the way, I studied theoretical physics for many years.
People who value intelligence highly but may not have much experience interacting with messy, real-world systems.

You might think that these people are likely to make mistakes in a particular direction.

At an EA/AI-safety gathering recently, I caught up with a friend who worked in AI safety and recently started working on a new project scaling personal protective equipment (PPE) manufacturing. 
She didn’t know *anyone* else whose work touched manufacturing and found it interesting to talk to me, who works at a balloon company. 

Of course this does not mean that their arguments are wrong.
But if they were wrong, they would be directionally wrong, in the direction of over-valuing intelligence, and under-valuing other factors.


## 7. We can talk to them!

Maybe I'm just being too much of a nerd who's still giddy that we can *talk* to *machine minds* now for days on end.
Asking ChatGPT about a Chinese mythology story I only vaguely remember in a combination of Mandarin and English in voice-to-voice mode, and have it respond back in a similar combination of Mandarin and English with exactly what I asked for, was a moment that I cried a few incredulous tears to.
Compared to when we first started arguing about risks from superintelligence, it feels like we should absolutely update on the fact that we can now literally talk to the AIs. 
Whatever they become, we’re not facing a black box god—we’re facing something that can be reasoned with, questioned, maybe even persuaded.
That doesn’t guarantee safety, but it’s a weirdly hopeful place to start.


## To end

In 2021 I interacted with GPT-3 for the first time and decided to quit physics to work on AI safety. 
This is a contingent decision, very specifically contingent to the LLM revolution that we were/are witnessing. 
It is partly for the same reasons that Yudkowsky & Bostrom were worried about existential risks from superintelligence, and partly not.
The arguments/views/vibes in this post are mostly not meant to argue against the broad possibility of superintelligent AIs built in any fashion causing x-risks in general, but for risks seeming not particularly high, or at least lower than I had previously thought, if we just muddle our way into building superintelligent AIs within the current LLM-based paradigm, in the next few years.
My decision to work on AI safety is very contingent on the current LLM-based paradigm being relevamt.
I will once again invoke the old man and his lost horse here.
It doesn't seem like there is anything useful one can do to prevent any harm from any future paradigm that might produce powerful AIs.