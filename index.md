---
layout: minimal
title: Art of Scripting (code less, but better)
nav_order: 1
description: "About this stite"
permalink: /
toc: true
---


# Disciplined Scripting (code less, but better)
{: .fs-9 }

Tim Menzies, <timm@ieee.org>   
http://timm/fyi


{{ toc }}
<img width=400 align=right src="img/sam.png">


## <a name=abaout>About this tutorial</a>

<em>Show me some discipline,   
I'll show you mine.   
-- Jeremy Oxley </em>

Welcome to 
**Discplined Scripting (code less, but better)**.
If you're reading this, chances are you want to 
learn about how to code less, but do more. 
For example, all our examples will come from AI applications.
And you might be surprised just how easy it is to build
those intelligent tools.

I decided to write this because I needed to teach
all my "less, but better" 
experimental empirical software engineering  tips and tricks.
My professional life
is supervising people
completing
their Ph.D.s. 
The better those people get at scripting, the faster they can
try different ways to get "it" working. 
So in my school of scripting,
we don't code to deliver "it". Rather, we code to
explore different "its", then pick the best one.

These come in two parts

- **tips** for organizing code
- additional **smarts** for writing AI tools.


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




[^kohavi97]: Ron Kohavi, George H. John, Wrappers for feature subset selection, Artificial Intelligence, Volume 97, Issues 1–2, 1997, Pages 273-324,





