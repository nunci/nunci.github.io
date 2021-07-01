---
layout: post
title:  "Improve your Language Learning with Spaced Repetition"
description: "Highlighting a bit of science behind your own memory and helping you understand how nunci can help you never forget a language"
date:   2021-06-23 10:06:07 +0700
---

## Spaced Repetition and Language Learning

We all forget. That is what makes us human. But how do we remember when we are about to forget something? That is where spaced repetition comes into play.

[Spaced repetition learning](https://en.wikipedia.org/wiki/Spaced_repetition) is really quite simple. The newer or more difficult a flashcard is for you to remember, the more frequently it is shown to you. So, let's say you are learning Japanese. If you are having a more difficult time remembering how to pronounce `よろしくお願いします` rather than `こんにちは`, you will see flashcards asking you to speak `よろしくお願いします` sooner and more often than `こんにちは`. It is that simple!

Of course, the science behind determining exactly when to show you your flashcards, such as [forgetting curves](https://en.wikipedia.org/wiki/Forgetting_curve) and the [Leitner system](https://en.wikipedia.org/wiki/Leitner_system), is a bit more complicated. But you don't need to worry about that because we at [nunci](https://nunci.app) take care of it for you!

## The Basics

When you use [nunci](https://nunci.app), you only need to worry about telling us how difficult it was for you to recall any given flashcard. When you are finished answering a flashcard in nunci, you will be asked to rate how difficult it was for you to recall the answer. Take the following examples below:

<br>
<div style="text-align:center">
<em>Figure 1:<br></em>
<img id="blog-img" src="/images/spaced-repetition-ratings-short.jpg" width="50%"/>
<br>
<em>Difficultly ratings in nunci when answering a new flashcard<br></em>
</div>
<br>
<div style="text-align:center">
<em>Figure 2:<br></em>
<img id="blog-img" src="/images/spaced-repetition-ratings-full.jpg" width="50%"/>
<br>
<em>Difficultly ratings in nunci when answering an older flashcard</em>
</div>
<br>

Each rating has an emotion associated with it (usually 😞, 😕, 🙂, 😄, 👍, or 👎). When choosing a rating, you should pick the choice that most closely matches the difficulty you experienced when answering the flashcard. For example, if you recalled the answer with no problem, you could perhaps choose the 😄 option. At the other extreme, if you could not recall any piece of the answer, you might want to choose the 😞 option. Imagine you are at a doctor's office, pointing to a [pain chart](https://en.wikipedia.org/wiki/Pain_scale) with the attempt of telling the doctor how much something hurts. This is similar, only it's much more fun!

Each option also specifies the time interval of when you will next see the flashcard. In *Figure 2*, if you choose the 😄 option, you won't see the flashcard again until one month from the current date. If you choose the 😞 option, you will see it again in 10 minutes.

These options and time intervals are not fixed. Depending on how many times you have answered a flashcard correctly or incorrectly, the options and their time intervals will change. nunci uses a modified version of the [SuperMemo](https://en.wikipedia.org/wiki/SuperMemo) algorithm. If you are interested in learning more, check it out :)

## Advanced Topics

If you just want to be able to use nunci to help you generally remember your language better, you don't need to continue reading. However, if you're interested in learning exactly how nunci works and how to customize nunci to better fit your personal schedule, keep on reading!

### Learning, Review, and Relearning Flashcards

When you create a note, nunci automatically generates multiple flashcards for you based on your single note. When you first study these flashcards, this is called *Learning*. After you study and successfully answer them a few times, they become *Review* flashcards. If you completely blank on a *Review* flashcard, it becomes a *Relearning* flashcard. Any given flashcard has different characteristics depending on if it is currently *Learning*, *Review*, or *Relearning*.

*Learning* flashcards are simple. They follow a fixed set of time intervals (defaulting at 10 minutes, 1 hour, and then 6 hours). When answering a *Learning* flashcard, you only have two options, as seen in *Figure 1*. If you answer a flashcard incorrectly (and therefore choose the 👎 option), your flashcard will reset to the first time interval (defaulting at 10 minutes). If you answer a flashcard correctly (and therefore choose the 👍 option), your flashcard will be shown at the next time interval (defaulting at 1 hour, then 6 hours, and so on). In order to move from a *Learning* flashcard to a *Review* flashcard, you must answer the flashcard correctly at each of the time intervals. After that, you will see the flashcard again after another time interval called the *Graduating Time Interval* (defaulting at 1 day), at which point it is now officially a *Review* flashcard.

*Review* flashcards are a little more nuanced. This is where our modified version of the [SuperMemo](https://en.wikipedia.org/wiki/SuperMemo) algorithm comes in. The time intervals are not fixed, but rather determined by our algorithm. When answering a *Review* flashcard, you have four options. Let's go through the options, from left to right. Selecting the first 😞 option, tells nunci that you had no clue how to answer a flashcard. This demotes the *Review* flashcard to a *Relearning* flashcard, which is almost identical to a learning flashcard. Selecting the 😕 and 🙂 options tells nunci that you recalled the answer, but might have had a lot or a little difficult, respectively. Selecting the last 😄 option tells nunci that you had no trouble at all when recalling the answer.

*Relearning* flashcards are identical to *Learning* flashcards, except that nunci remembers how you have studied the flashcard in the past. You still need to pass through all of the same time intervals as a *Learning* flashcard. However, once to move back to *Review*, you won't see the flashcard as often as a new *Review* flashcard. So, completely forgetting a *Review* flashcard does not reset the card back to step 0.

### Customization

Although the science of forgetting can be applied widely to every person on the planet, we are all a bit different in our memory and forgetting. This is why nunci gives you the ability to customize various aspects of our algorithm. Check out the settings under the *Study* section. There you will find options to configure everything we mentioned above and more :)

<br>

Stay tuned on our [Facebook](https://www.facebook.com/nunci-113432470463274) or [Instagram](https://www.instagram.com/nunci.app/) pages, or check back on [our blog](https://nunci.app/blog) for updates. We are looking forward to helping you on you language journey 😁