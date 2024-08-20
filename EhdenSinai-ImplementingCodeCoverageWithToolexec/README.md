# Implementing Code Coverage With `-toolexec` - Ehden Sinai, Contrast Security

## Talk Description

Why should you use my custom code coverage tool? You shouldn’t; the one built into Go is great and you should just use that. However, writing our own from scratch is a great way to pull back the curtain on a widely used feature of the Go toolchain, and we can learn a lot from doing it. This talk will blitz through how Go’s -cover flag works, what Go does when you tell it to build a program, and how we can use -toolexec to edit builds and add our own basic instrumentation. This will be a quick introduction to some of the inner workings of the build tool we all know and love, and I hope to leave you with the desire and confidence to try to explore it on your own.

## Speaker Info

Ehden is a software developer who has spent most of his career tinkering with instrumentation and trying to find ways for one piece of software to worm its way into another. He’s been using Go for fun since 2016 and managed to convince his job to let him use it for work in 2019.

## Supporting Material

A PDF version of the slides from this talk are available [here](./EhdenSinai-CodeCovLightning.pdf)
