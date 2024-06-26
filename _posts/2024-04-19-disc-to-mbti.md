---
layout: default
title: DISC to MBTI Algorithm
---
<!--more-->
# DISC to MBTI

<p align="center"><b>My friend Holden (CombineSoldier14) REALLY helped with this--Check out his blog post <a href="https://combinesoldier14.blogspot.com/2024/03/how-i-wrote-algorithm-that-converts.html">here</a>!</b></p>

[DISC][disc-wikipedia] and [MBTI][mbti-wikipedia] are quite similar, and trying to solve the same problem:
Putting all 8 billion people's personalities in something we can share.  MBTI does this via 4-letter codes,
but DISC takes a different approach...  Here is how it works:

## How does DISC work?
DISC uses numerical values for all four letters:

* D stands for Dominance
* I stands for Influencing
* S stands for Steadiness
* C stands for Compliance

DISC works similarly to MBTI, with people not giving their actual numbers, rather, we say *"High D"*, *"Low S"*,
etc.  For the record, "High" means anything over 60, "Low" means anything under 40, and "Medium" means anything
over 40 but under 60.

## How does MBTI work?
MBTI uses two possible values for each letter in your MBTI type.  It works like this:

* Index 1: I/E
  * **I** stands for Introverted
  * **E** stands for Extraverted
* Index 2: S/N
  * **S** stands for Sensing *(Although [16personalities.com][16p] calls it Observant)*
  * **N** stands for Intuitive
* Index 3: T/F
  * **T** stands for Thinking
  * **F** stands for Feeling
* Index 4: P/J
  * **P** stands for Prospecting
  * **J** stands for Judging

Slap all of those together and you get your MBTI type.  For example, mine is [ENTP][16p-entp]
because of the traits *Extraverted, Intuitive, Thinking, and Prospecting*.

*Note: That's a VERY high-level description of MBTI - Check [this article][what-is-mbti] for more information!*

## How can we convert them?
MBTI and DISC share lots of key similarities, yes, but they also share many differences that must be smoothed
out when converting.

## Let's get converting!
### Introverted or Extraverted
This one is very easy.  Being Introverted *(I)*, or Extraverted *(E)*, can be determined using your *Influencing* score.
This connection is put in your Indigo Report, so this is undeniable.

* **Low I** = Introverted
* **High I** = Extraverted

### Intuitive or Sensing
This can be determined based on your *Compliance* score.  This is difficult, but it's said that High C's are very observant,
and quite analytical.  

* **Low C** = Intuitive
* **High C** = Sensing


### Thinking or Feeling
This can be debatable, but we think that High D is Thinking, and low D is feeling.  This can sound a bit far-fetched so
hear me out-- Low D people tend to be more empathetic and emotion.  This makes High D people Thinkers.

* **Low D** = Feeling
* **High D** = Thinking

There ya go!  We now have a system to convert MBTI to DISC!  I will also include a converter that can be found [here](/mbti/disc-to-mbti-converter)!
Have fun and start converting!

Cheers,
- Damien Boisvert (AlphaGameDeveloper)

[16p]: https://16personalities.com
[16p-entp]: https://16personalities.com/entp-personality
[what-is-mbti]: https://www.simplypsychology.org/the-myers-briggs-type-indicator.html
[mbti-wikipedia]: https://en.wikipedia.org/wiki/Myers-Briggs_Type_Indicator
[disc-wikipedia]: https://en.wikipedia.org/wiki/DISC_assessment
