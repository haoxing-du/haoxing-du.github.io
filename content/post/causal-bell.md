---
title:  Understanding nonlocality via causality
date: 2035-07-30
tags: ["Bell", "nonlocality", "causality"]
mathjax: true
draft: true
---

When I started drafting this blog post a few months ago, I planned for a different intro, one about a causality and quantum physics workshop that I attended in Berkeley. But as I continued to procrastinate on this draft, I was handed a more relevant intro strategy straight from the Nobel committee: The 2022 Nobel Prize in Physics was awarded to John Clauser, Alain Aspect, and Anton Zeillinger, "for experiments with entangled photons, establishing the violation of Bell inequalities and pioneering quantum information science". Since then, a friend has complained to me directly that she couldn't find any good popular science introduction to Bell's inequality. While I doubt that's true, I couldn't see a better motivation for me to finally buckle down and get this post done.

In this post, I will start by explaining Bell's theorem from a more traditional angle, with the CHSH game (the C here is for Clauser). Then I will take on a more novel angle, and focus on a line of research that takes tools from causal modeling and applies them towards the understanding of Bell’s theorem and nonlocality. In my view, this is the most modern and clearest analysis of the meaning of Bell’s theorem, and yet seems hitherto(?) unknown in popular media.

<!-- A few months ago, I attended an unusual workshop at the Simons Institute at UC Berkeley, titled “Quantum physics and statistical causal models”. Half the people in attendance were statisticians working in causal inference, and the other half were physicists thinking about quantum foundations. The two communities were not just there in the same room by coincidence, or as an excuse to enjoy the beautiful California spring weather. They were brought together by a line of recent research that takes tools from causal modeling and applies them towards the understanding of Bell’s theorem and nonlocality. In my view, this is the most modern and clearest analysis of the meaning of Bell’s theorem, and yet seems hitherto(?) unknown in popular media. In this blog post, I will try to explain how to understand Bell’s theorem from a causal perspective, ...

But before going into the causal modeling world, let us start with a more old-school presentation of Bell’s theorem. Unlike the causality connection, Bell's theorem _has_ been extensively written about in the popular science media, and here are [some] [presentations] that are also very good. -->

## The CHSH game

It is incredible to me how many students in physics finish their undergraduate degrees without having learned about, or even heard of Bell’s theorem. Or perhaps I shouldn’t be that surprised, given that the interpretational stance towards quantum theory of most physics curricula is “don’t worry about it”, and Bell’s theorem certainly has the potential of pushing young curious minds down the rabbit hole of quantum foundations... But there are really no excuses, because it is so simple to explain Bell's theorem and nonlocality in its basic form.

The simplest presentation that I know of Bell's theorem is in the form of a game, the CHSH game [^CHSH]. It is a game not in the sense that it is fun to play. (Although, if you want to play it for fun with a friend, be my guest!) It is a _game_ in the game theory sense: there is a set of rules that the players stick to, and an objective that they are trying to optimize towards, and the goal is to reason about the strategies and their xxx under these rules and objectives. 

In a CHSH game, there are two players, say Alice and Bob. They each take a binary input, and give a binary output. Just for fun, let's say that the binary input they receive is in the form of a coin flip, so the two possibilities are Head (H) or Tails (T). Let's also say arbitrarily that they each outputs a color, Red (R) or Green (G).

[^CHSH]: CHSH are the initials of four people. Apart from Clauser, the other three are Michael Horne, Abner Shimony, and Richard Holt. 


## Conclusion

I get the question a lot: What is exactly the field of quantum foundations? I don’t blame folks for asking questions such as this, and I think I can see the image that they picture in their head what quantum foundations is—a bunch of old dude physicists philosophizing and bickering about their pet interpretations. But precisely because of tools such as causal modeling, it is what the field of modern quantum foundations is not. I haven’t gotten very good at expressing this with a few sentences yet—as you see, I have quite a few thoughts on this subject… But from now on, I will be able to point folks to this post
