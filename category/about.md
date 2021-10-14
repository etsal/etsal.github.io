---
layout: category
title: About
---

I am a fourth year PhD student at the University of Waterloo, working with Professor [Ali Mashtizadeh](https://rcs.uwaterloo.ca/~ali). 

During my PhD I have been leading the [Aurora](https://rcs.uwaterloo.ca/aurora/) project. Aurora is a fully UNIX compatible Single Level Store. Aurora's design goal is to transparently persist applications without developer effort. It does so by continuously checkpointing them and flushing these checkpoints to the disk. Aurora uses fast storage devices to do these checkpoints at a high frequency for fine grained persistence. Aurora also provides an explicit API for developers to optionally optimize checkpointing.

I am currently exploring new system designs on top of Aurora's persistent application abstraction. These systems include a serverless computing platform and a debugging framework. I am also developing Aurora aware applications that use Aurora's API to combine strong persistence guarantees with high performance.

Before coming to the University of Waterloo I did my undergrad at the National Technical University of Athens (NTUA). My undergrad thesis was on utmem, an API that exposes the transcendent memory paravirtualized mechanism directly to a guest Linux VM's applications.
