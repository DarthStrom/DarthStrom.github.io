---
layout: post
title:  "Extrospective: Pair Programming is Dead, Long Live Pair Programming"
---

Intro(spective)
---------------
I know I called this an extrospective, but first allow me to introspect a bit.

I have been programming professionally for 8 years, but have only really started trying to improve my craftsmanship for the past 3 or so.  As part of that journey I switched from a government job to consulting.  My current company has a culture that values many Extreme Programming engineering practices including pair programming.

I came into the job with an open mind and the realization that pair programming would take time and effort to become comfortable with.  After 2 years of pair programming full time, I am still not comfortable.  In fact, it's possible I will never be comfortable with it.  As an introvert, 40 hours a week of social interaction can be draining [1][1].  Another contributing factor to my discomfort is imposter syndrome.  One of the things I used to be able to use to combat imposter syndrome was looking back at value I had produced - this becomes more difficult if you are always working with people.  If you have imposter syndrome your mind has a way of telling you that the work could have been done without you.

Obviously there are many merits to pair programming that make it worth overcoming these hurdles.  And I much prefer the environment of "always pair" to the environment of "never pair", but I would like to take the rest of this post to explore the idea of a middle way.  There must be situations where it is better to pair and other situations where it is not.

Some Benefits
-------------
- **Fast feedback**: Pair programming is like a real time code review. Every decision you make even before you even type it in is vetted by another team member.  This can save you having to redo something that made it into code review.
- **Knowledge sharing**: Two people become intimately familiar with the code and the decisions behind it.  Pairing on future work can be done strategically to expand knowledge of the codebase throughout the team.
- **Collective code ownership**: If more than one person wrote every line of code, it leads to a feeling that the whole team owns the codebase.
- **Team cohesion**: The members of the team are constantly working together.  This provides motivation for everyone to get along and enjoy each other's company.
- **Increased quality**: This one makes perfect sense and I had assumed it to be true, but as we'll see later there are situations where it may not be.

Some Drawbacks
--------------
- **Learning curve**: Pair programming is a skill on its own and takes time and effort to learn to become effective at it.
- **Cost**: Having two people work on each task costs twice as much, right?  Well not exactly, but we'll explore that.
- **Scheduling**: Aligning schedules can be challenging in a flexible schedule environment.
- **Can exacerbate imposter syndrome**: I mentioned this in the intro as something I struggle with. Pairing can cause a feeling of a lack of personal accomplishment.
- **Remote work more difficult**: Many people are attracted to programming for the possibility of being able to work remotely.  Pair programming makes this more difficult.  The tooling is getting there with things like Screenhero and tmux, but nothing beats sitting down at the same machine as your pair.
- **Not as much typing**: Most programmers enjoy coding (I suppose that's pure speculation). For those that do, pairing reduces the amount they get to code by half.  Granted, the important part about programming is probably the thinking that happens before the typing.  That doesn't change the fact that typing it in is enjoyable.
- **Speed mismatch**: If a pair has mismatched speeds it can lead to frustration for the person that wants to go faster or disengagement for the person that can't go as fast.
- **Limits exploration**: This may not be true for everyone, but I find myself less willing to explore a creative idea while pairing.
- **Limits tooling**: If a pair consists of an Emacs user and a Vim user then one of the two will not get to use their tool of choice.  Personally, I use the Colemak keyboard layout and had to buy a special keyboard instead of being able to change the layout through software.

[1]: http://www.amazon.com/gp/product/0307352153/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0307352153&linkCode=as2&tag=darth07-20&linkId=LJ45SNCXPSVLSXKQ  "Quiet: The Power of Introverts in a World That Can't Stop Talking"
