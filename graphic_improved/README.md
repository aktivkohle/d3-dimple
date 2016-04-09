Here this is my more sensible re-make of [this chart.](http://flowingdata.com/2010/05/14/wait-something-isnt-right-here/) 

This chart is a depiction of perceived and actual substance use in a survey of a thousand students. It is quite a mess, a reminder about how little journalists care about the truth. The height of the bars is unconnected to the printed values. They seem to want to convey that perception is far greater than reality with substance use, but want to depict that so badly they can't even maintain some honesty by linking the numbers to the graphic. Even the zero height bars seem to have a height. A bar with 30.9% is higher than a bar of 56.9%, nothing seems to really add up to 100%. Okay, perhaps the surveys had a certain proportion of _didn't respond._ The alcohol numbers do come close, adding up to 98%, which can be interpreted to mean that almost all the surveyed hold an opinion on their own and their peer's _use_ of alcohol.
_____________________

### Creating a better graphic

As far as making this data work nicely with a dimple.js visualisation, it was necessary to put the numbers into a csv in tall format. Bar for the _perceived_ results are made less opaque than the actual one although you can tell whats what by hovering the mouse anyway. It was quite easy to mix the dimple.js templates to get the legend up the top of the standard stacked-bar template. I tried a few other ways of altering some of the bars before using a d3 selector, there might be another way.

### What does it actually show?

Okay, they were right even if they fudged the length of the bars, perceived is greater than actual in all cases. Can see comparing the purple and the green in the alcohol section that they have an exagerated idea of how many not-quite-alcoholics there are but it's only out by a factor of about two. The actual use of the harder substances is close to zero as it should be. ~50% and ~30% respectively of the surveyed believe that their peers are taking cocaine or opiates up to ten days a month when both figures are actually closer to zero, they must be talking about it more than they are doing it which is good. 