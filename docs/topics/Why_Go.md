# Why Go?

## Overview

Relative to the alternatives, golang is:

* simple to develop with.
* quick to run.
* simple to deploy (using AppEngine).
* inexpensive to deploy and run.

## Go is very well thought out.

Go has been designed to compile and deploy fast, and the strong static typing makes it "computer friendly". But the [Go language also considers developer psychology](https://medium.com/@egonelbre/psychology-of-code-readability-d23b1ff1258a).

## Matchups

Everyone has their favorite language, and there are many reasons to choose one language over another. Go (as of August 2019) gets a lot of positive reviews from developers coming from many different starting points and our ad-hoc searches of "go vs <language X>" found a lot of "Why we moved from X to go" style articles no (first page at least) instances of movement in the other direction.

In particular, some of the top hits were [Go > Node](https://medium.com/codezillas/want-to-be-a-best-web-developer-learn-golang-not-node-js-69b4166d1449), [Go > Scala](https://movio.co/blog/migrate-Scala-to-Go/), [Go > Python](https://hackernoon.com/5-reasons-why-we-switched-from-python-to-go-4414d5f42690), more [Go > Python](https://dzone.com/articles/golang-vs-python-which-one-to-choose), [Go > Kotlin > Ruby](https://engineering.wework.com/choosing-a-language-stack-cac3726928f6), and [Go > Java](https://blog.spiralscout.com/when-to-use-go-vs-java-one-programmers-take-on-two-top-languages-59617f30be5e).

Rust, which seems to come closest to giving go some competition, is still, on balance, behind go. The first result from "go vs rust" concludes [Go > Rust](https://matthias-endler.de/2017/go-vs-rust/), and the rest are mostly pro-Go (e.g., the [next](https://codeburst.io/should-i-rust-or-should-i-go-59a298e00ea9) [two](https://sdtimes.com/softwaredev/the-developers-dilemma-choosing-between-go-and-rust/)).

Of course, it's not all Go, all the time. Node, for instance, is [probably more widely known](https://medium.com/@blogger.ashishsharma/golang-vs-node-js-comparison-and-why-developers-prefer-node-js-9e669319df52). Some would also argue that [Node is faster for MVP prototyping](https://artjoker.net/blog/go-vs-nodejs-in-building-microservices-an-exhausting-comparison/). (On that point, we have found that static typing and strong-compile time checks have plenty of positive benefits during MVP and, of course, we don't usually plan to throw away the MVP and rebuild everything, so you'd have to factor in switching costs.)

You can also find plenty of commentary on problems with go, but in terms of development teams that have tried both or moved from to the other, it's pretty much one-way.
