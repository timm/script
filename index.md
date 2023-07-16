---
layout: minimal
title:  "Disciplined Scripting (for XAI):  Code Less, but better"
nav_order: 1
description: "About this stite"
permalink: /
toc: true
---

# Timm's Tips and Tricks for Smarter Scripting

Code less

use non-parametric

use symbols.

find the keys

DRY not WET. rule of 3

let constraints guide your exploration (not the other way around)

self-documenting code. comments, type hits, parse comments from settings, self-documenting mak files

return not zero for errors

write tests

write little languages (regex, column headers, argparse)

# Disciplined Scripting (for XAI):  Code Less, but Better
{: .fs-9 }

Tim Menzies, <timm@ieee.org>   
http://timm/fyi


{{ toc }}


## <a name=abaout>About this tutorial</a>

<em>Show me some discipline,   
I'll show you mine.   
-- Jeremy Oxley </em>

<img width=400 align=right src="img/sam.png">

Welcome to 
**Discplined Scripting (for XAI): Code Less, but Better**.
If you're reading this, chances are you want to 
learn how to code less, but do more.  
Or you want to learn how easy it it to
make AI 
applications explainable. Either way, 
you might be surprised just how easy it will be to build
intelligent, explainable tools.

I needed to write this because I had to teach
all my "less, but better" 
tips and tricks.
My professional life
is supervising people
completing
their Ph.D.s (in _SE for AI_ and _AI for SE_). 
The better those people get at scripting, the faster they can
try different ways to get "it" working. 
So in this school of scripting,
we don't code to deliver "it". Rather, we code to
explore different "its", then pick the best one.

Also,
this is a _disciplined_ approach so along the way,
we will touch on many aspects of software engineering. So you can expect
two kinds of content here:

- **tips** for organizing code
- as well as **tricks** for writing XAI tools.


## <a name=simple>Why I bekieve in simplicty

The general rule of thumb is that tabular data
can be reduced to around 25% of its columns
and rows

So one way to simplify anything is to
delete what is spurious until you are
left with the essential.


This quest for the-simplest-tool-possible
is not very fashionable these days.
At the time of this writing there is much
buzz about generatative AI-- which requires


We take  other people's
work then
throw away stuff until 
 things stop working.
Again
and again and again we keep finding that
this core 
can be very simple indeed.
There's deep theoretical reasons why
that is so [^INTRINSIC] [^PROTOTYPES] [^SSL]
but the practical upshot is that very
simple methods can be remarkably effective.

[^INTRINSIC]: One mantra of machine learning is that higher dimensional data can be reduced to a _lower dimensional manifold_ with little to no loss in signal.  For example, suppose some balls are lying on the floor of a room. Even though that room has three dimensions (height, with, depth), the balls are only using two (since they are ignoring the height dimension).  To say that another way,  the number of _used_ dimensions can actually be (much) smaller than the number of _possible_ dimensions.  Often, tabular data with $C$ columns can be reduced to $C/4$ columns, or even much less [^kohavi97]. 

[^PROTOTYPES]: When we learn a model from a table of data, we prefer    to use _well-supported_ aspects of the data; i.e. aspects that appear multiple times.
If you think about it, this means that $R$ row
really contains $r \subset R$ of exemplary rows 
(and the others are just variations on a theme).

[^PROTOTYPES]: asdas

[^SSL]: adass



[^kohavi97]: Ron Kohavi, George H. John, Wrappers for feature subset selection, Artificial Intelligence, Volume 97, Issues 1–2, 1997, Pages 273-324,





