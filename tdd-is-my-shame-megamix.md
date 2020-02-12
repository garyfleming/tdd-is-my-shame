theme: Ostrich, 1
footer: @garyfleming

# TDD is My Shame
### A Draft


---

![](images/CODE-CRAFT-V2-01-09.svg)

^ I run a meetup called CodeCraft, that focusses on the craft of writing good software. It was kind of a spin-off from this meetup... Don't worry, this isn't a pitch for that meetup: it's just where the story starts.

---

![](images/CODE-CRAFT-V2-01-09.svg)

^ A few years ago, we were running a session on either mob or pair programming, I don't remember which, but there was an unusual argument that broke out in one of the groups but dissipated before we could intervene and figure out what was wrong.

---

# Pub / Plato

^ Afterwards, a few of us went to a nearby pub, given the grey miserable weather, to continue our conversation. One of the attendees, who I'll call Plato, seemed unusually perturbed. When I asked him, what was wrong, he mentioned that he was feeling some pretty severe imposter syndrome after the session. Plato looked deeply uncomfortable, in a way that only a 2500 year old man whose world view has been crushed can. The argument had made him realise something:

---

> "I'm a little ashamed, but I don't TDD as much as I think I should."

^ There's a *lot* packed into that one little sentence. Layers, and nuance, and meaning. We decided to spend a while dealing with it.

---

^ Since that conversation on that night, all those years ago, I've spoken and attended a number of conferences and meetups around the world. As a consultant, I also get to work with a lot of developers of different ages, backgrounds, etc. When I can, I keep asking people the same question:

---

"Do you TDD?"

^ Put your hand up if you've do TDD for most of your production code?

^ The phrasing changes, the context shifts, but I've asked a tonne of developers how and when they TDD. While no-one does it 100% of the time (well, one person claimed to, but we'll introduce him later), one thing that's become very clear to me: the number of developers who routinely do TDD is *miniscule*. Tiny. A fraction of a percent. And it appears to be getting smaller.

---

# Shame

^ Worse, it appears to regularly be accompanied by shame. People feel they ought to do TDD, but they don't, and they often can't articulate why.


<!--
---

What is TDD?

Let's start by taking a big question off the table.

TODO bunch of stuff explaing the big picture, then the Liz keogh stuff about how it's an anchor term. and Rob jeffries on how things get smushed on top of each other

-->

---

# Why feel shame?

^ I asked Plato why he felt SHAME specifically. He said that he found the whole idea overwhelming: it was too big, and any time he'd tried he failed, and he'd never know enough. This was imposter syndrome manifest.. I offered three pieces of advice


---

# 1. Satir(ish)

^ TODO Virgina Satir was a therapist. Did a lot of work on change. Can't get into the details here, but well worth reading her work

---

![inline original fit](images/curve.jpg)

^ explain the changes

---

# 2. No One True TDD.

^ I also explained that there really isn't one thing called TDD. We like to pretend that TDD is a thing and you can just do it... but that's not quite true. The practices involved and the processes and the people doing it all... mush together. RJ says That's how ideas are. Mushy. It's like a bunch of different play-doh making up something.

---

# Anchor Terms

^ Liz Keogh describes TDD as an anchor term. It's a useful term for searching and tying these mushy ideas together. If you want to know more about ideas in the space, searching for TDD will probably tell you something useful; which is better than trying to find all the individual practices.

---

# 3. Shu-Ha-Ri

^ Everyone is a beginner. That's okay. That's how we all start. There's an idea, that is somewhat misunderstood but probably applies here: shuhari.

---

# Obey - Detach - Separate

---

* Do the moves
* Understand the moves
* Move beyond the moves

---

# Sudoku

^ TODO

---

# Easy

![original fit inline](images/easy.jpg)

^ TODO

---

# Expert

![original fit inline](images/expert.jpg)

^ TODO

---

# Find some guides. Try them.

^ Red/green/refactor etc. Try these things. Keep trying them study. You'll learn more about when they work and when they don't

---

# You can do it

^ You might not think this story applies to you because you're not a developer. You're mistaken. This applies to most skills and practices.

---

1. Change Takes Time -- Satir
2. Practices are messy -- No One True....
3. Learn from experts, move on -- Shu-ha-Ri

---

# Thank You

![inline fit](images/shoulder-cat.jpg)

@garyfleming

---


TODO

Satir
Felt like

---

Someone else came over... Socrates.

Structuring.
Sudoku.


---

Why do so few developers do it?

Tips for doing it better

- rules of simple design
- immutability

---

TODO everything below here are from false starts.

---

When I knew I was going to be speaking about TDD, I decided that it would be a good idea to ask as many people as possible, both online and offline, about their experiences of TDD. Did they like it? Did it help? etc

Most of the experienced people I spoke to gave the same answers we've seen many times before, essentially the selling points. That is:

* It gives them more confidence that they can change their code later.
* Fewer bugs
* Living documentation.
* It helps them think through a design.
etc

A small, but not insignificant number said something different. It was articulated by one of the last people I spoke to: "I'm a little ashamed, but I don't TDD as much as I think I should."

There's a lot packed into that little sentence, so I want to spend some time exploring it.

TODO

---

^ When I was first said I'd do a talk on TDD, I thought it would be easy enough. I've been practicing TDD to some degree for around a decade now. As a software and agile consultant, I also spend a lot of my time helping other people to do TDD.

I had, however, forgotten that context is king.

When someone asked me to spend an hour or so with them to show them how to do TDD, it was a surprising challenge. I'd gotten used to spending weeks or months with teams, helping them learn the nuance of TDD as their problems emerged. Trying to distill it all down into an hour or so didn't work well.

There's a LOT to learn. It takes time and practice.


---

"I don't TDD as much as I think I should"
"to some degree"
" you're going to test on way or another" - driven, first, after, or in prod.

why do people who know that it works not always do it? Why can it be hard? How can we make it easier?

Talk a bit about handing over LA Portal (not directly) -- People questioning the tests. Mostly they weren't used to a technique I use (no mocks), which was fine; but the process did show me that some of the tests we had were going to be brittle. --that is, even with years of experience, there will always be things you don't like. You're getting better.

Shu-ha-ri?


---

# Thank You

![inline](images/shoulder-cat.jpg).

@garyfleming
