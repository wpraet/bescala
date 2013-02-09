---
comments: true
date: 2012-10-01 19:36:44
layout: post
slug: meetup-october-10th
title: 'Meetup October 10th - Molecule: Using Monadic and Streaming I/O to Compose
  Process Networks on the JVM'
wordpress_id: 175
categories:
- Events
- Scala
---

Writing and maintaining concurrent applications that exploit parallelism in multicore environment is a challenging task on the JVM. In absence of coroutines, programming against non-blocking I/O interfaces forces developers to give up traditional control structures offered transparently by native threads such as termination management and exception handling. Managing these explicitly in a program often turns out into a maintenance nightmare for any non-trivial application. Moreover, in absence of good scheduling strategies, the performance of concurrent applications that exhibit a high amount of context switches may degrade significantly when they are scheduled over more than one thread. 

In this talk, we present Molecule, a domain specific language in Scala and a runtime library for developing concurrent applications on the JVM. Molecule applications are designed as process networks that communicate over strongly typed channel interfaces. Molecule abstracts user-level threads that interact over non-blocking interfaces behind a monad that takes care of automatic resource management and exception handling. Its strongly typed channel interfaces can be manipulated as lazy streams in functional programming languages, which contribute to increase the overall expressiveness of lightweight processes. Its runtime implement a flow parallel scheduler that eliminates thread context switches when processes communicate sequentially. We will illustrate its expressiveness and performance benefits over several examples during the talk.

This BeScala meetup is proposed and hosted by [Alcatel-Lucent](http://www.alcatel-lucent.com/be) in Antwerp.
Our host, Sébastien Bocq, will also be presenting this framework at the [OOPSLA conference](http://splashcon.org/2012/program/oopsla-research-papers/466-concurrency-ii) 

For organisation reasons, you **must** [register](http://bescala.fikket.com/event/molecule) on the Fikket page and registrations will end Tuesday October 9th at 17h00.
Also on the day of the event registration at the Alcatel-Lucent front desk must happen before 19h00.

Direction:
Copernicuslaan 50
2018 Antwerpen
Belgium

[http://www.alcatel-lucent.com/be](http://www.alcatel-lucent.com/be)


