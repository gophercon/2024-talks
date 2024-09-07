# Processing Millions of Events Per Second Reliably Using Generics - Alan Braithwaite, RunReveal

## Talk Description

Kawa is an event processing package for Go that enables scalable and reliable
processing of arbitrary streaming data by utilizing generics for type-safe
serialization. Kawa's design was influenced by years of experience building
massive event pipelines at Cloudflare and Twilio. In this talk, I share the
lessons learned building countless event pipelines in Go, and the design
principles behind Kawa that enable delightful developer experiences when
writing streaming event processors.

## Speaker Info

Alan built Cloudflare's and Segment's event pipelines in Go which processed
millions of events per second. Using this experience, he's built libraries to
reliably and efficiently process events at scale. He's now using his knowledge
to help ensure no breach goes undetected at RunReveal.  He hopes to one day
earn the coveted black badge at DEFCON.

## Supporting Materials

The library this talk is introducing can be found at
[github.com/runreveal/kawa](https://github.com/runreveal/kawa).

A PDF version of the slides from this talk are available [here](./Kawa.pdf)

The Concurrency is not Parallelism talk by Rob Pike that inspired the design of
this library can be found [here](https://go.dev/blog/waza-talk).

