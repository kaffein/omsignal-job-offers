OMsignal Site Reliability Engineer [REMOTE or LOCAL]
====================================================

Headquarters: Montreal | http://www.omsignal.com

OMsignal is made possible by the expertise of Smart Textile experts,
Data/Bio Scientists, Hardware, Firmware and
Software Engineers.

What we do
----------

[![](http://img.youtube.com/vi/MDa_af2pAdo/0.jpg)](//www.youtube.com/embed/MDa_af2pAdo)

OMsignal is an exciting Montreal start-up developing a revolutionary
line of bio-sensing clothes that connect seamlessly
to smartphones. The company is at the intersection of the wearable
technology, well-being and fashion markets.

We are a well-funded startup [1] working to deliver a smart biometric
shirt. You can read more about our mission on [2].
And for those who followed the US Open 2014, we are the technology
behind Ralph Laurent Polo Tech :

[![](http://img.youtube.com/vi/zipGvqaSJiE/0.jpg)](//www.youtube.com/embed/zipGvqaSJiE)

What we are looking for
-----------------------

We are looking for a Site Reliability Engineer who can
help us operate and scale a reactive, event-driven system based
on bleeding edge technologies (`Scala`, `Akka`, `Spray`, `Reactive Programming` [3],
`iOS`, `Swift`, `Docker`...), a modern architectural
style (`Micro Services`, `CQRS`, `Event Sourcing`, `Eventual Consistency`),
and a clean codebase (`Clean Code`, `Domain Driven Design`…).

On the Op side of the things, we use `Docker` and `Ruby` to automate everything.
We orchestrate our docker-ready micro services using an internal ruby tool that we call
`omfleet`, based on the ideas of CoreOs's fleet and consul.io.

And we use `InfluxDB` for timeseries and metrics.

The Technologies we currently use
---------------------------------

 - Backend : `Scala`, `Akka`, `Akka Persistence`, `Spray`, `ReactiveMongo`, `SBT`, `Kafka`, `ZooKeeper`
 - Web : `NodeJS`, `AngularJS`
 - iOS : `Swift`, `Objective C`, `ReactiveCocoa`, `Core Bluetooth`, `CocoaPods`
 - DevOps : `Ubuntu`, `Docker`, `Ruby`, `Amazon AWS/EC2`
 - Project management: `git`/`github`

The `iOS` stack is more sophisticated than the average iOS App.
It includes a `Pub/Sub` system similar
to `Apache Kafka` (that we call iOS Kafka internally),
makes heavy use of
asynchronous programming + `CQRS`/`Event Sourcing` and
computes biometric algorithms and reports.

Our culture
-----------

We get some inspiration from the Open Source model to
achieve high-cohesion (within teams) and
low-coupling (between teams) : small, empowered teams,
systematic pull requests, developer autonomy.

Our software engineering practices are also influenced
by Antifragile [4] principles
(Small is Beautiful, Less is more, Hormesis principle,
evolutionary darwinism, over-compensation ...)

And if you are on the Paleo diet, like hiking/camping or
enjoy a good raclette you will certainly find friends here!

Next step
---------

If you are curious about the project and want to explore
opportunities working with us, you can
 - reach out to dev@omsignal.com
 - come hang out on IRC (`irc.freenode.net #omsignal`) to ask your questions

If you have a `github`/`bitbucket` account, we would love to take
a look at what you like doing
(even if you feel ashamed of it in retrospective -- explain us
what you would improve now)


Footnotes
---------
 - [1] http://www.omsignal.com/blogs/omsignal-blog/14669049-omsignal-raises-10-million-series-a-round-from-bessemer-venture-partners
 - [2] http://venturebeat.com/2014/04/16/brave-new-wearable-world-crowdsourcing-health-and-the-coming-battle-of-bio-signals/
 - [3] http://www.reactivemanifesto.org/
 - [4] http://www.amazon.com/Antifragile-Things-That-Disorder-Incerto/dp/0812979680/ref=sr_1_1?ie=UTF8&qid=1416355343&sr=8-1&keywords=Antifragile
