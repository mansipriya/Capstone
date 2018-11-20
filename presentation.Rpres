Text Prediction Application
========================================================
author: Mansi Priya
date: November 19th, 2018
transition: rotate

What Is This About ?!
========================================================
<b>It's tough to predict the future but not words!</b>

Commonly, prediction is tightly associated with prevention. However prediction today is about the future!

Applications derived from `word based statistical model` has helped improve mankind's quality of life.

For examples,

1. [<b>SwiftKey Keyboard</b>](https://swiftkey.com/en) predicts the next word (as user types) that makes compostion task on mobile a breeze!

2. [<b>Text-To-Speech Synthesize</b>](https://en.wikipedia.org/wiki/Speech_synthesis) assists in speech construction when challenged by disability and breaks down physical communication boundaries. (E.g. Stephen Hawking)

How It Works ?
========================================================

`Markov Chain Model` represents each word as transitional state with probability. An intuitive example, word "B" has 30% chance to transit to word "A".As an example below, word "B" has 30% chance to transit to word "A".

   | A | B |
---|---|---|
 A | 0.6 | 0.4 |
 B | 0.3 | 0.7 |
     

`Add-1 Smoothing` is applied to distribute probability mass to produce a less-biased prediction model.

`Shiny Application` embeds the `model` described above; along with the `Prediction Executor` and `User Interface`. The `High Level Architecture` as below,
The `High Level Architecture` as below,

![High Level Architecture](images/high-level-architecture.png)

Too Easy !
========================================================
Type some text in the box! Results come instantly!

![User Interface](images/user-interface-2.png)

What's Next ?
========================================================
The prediction model is somewhat skewed. Possible improvements are,

1. Increase Corpus size and/or type.
2. Increase machine resources - create more complex model.
3. Increase Shiny io resources - host more complex text prediction application.

Give this Text Prediction Application a try [here](https://mansi.shinyapps.io/MyProject/).

For more detailed information about the implementation, you may see [here](https://github.com/mansipriya/Capstone).
