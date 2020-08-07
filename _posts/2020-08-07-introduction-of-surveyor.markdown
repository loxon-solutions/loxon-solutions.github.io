---
layout: post
title:  "Introduction of Surveyor"
date:   2020-08-07 11:28:52 +0200
categories: tech documentation surveyor
author: Dávid Kovács
---

Surveyor is a simple tool which we use internally for generating documentation diagrams from the code. We are just at the beginning of the road, but the generation of the documentation is a really interesting topic and we wanted to keep this conversation as open as possible.

This post is about the major motivations behind Surveyor.

## What is documentation?

In the waterfall development methodology the implementation phase relies on a deeply detailed documentation (the specification), which acts as the single source of truth, the code itself must implement it with a 100% accuracy.

So basically the functional documentation of the software is available *before* the software itself, programmers have to "transform" the documentation to code.

In the agile era the role of the documentation is completely different. As the pace of the deployment iterations increases, the specification itself breaks up to vast of *not-so-detailed* pieces, coming from discussions, memos, emails etc. The requirements are no longer constructed into a single documentation which could be the single source of truth, so this role remains to the code itself.

This also means that the functional documentation requires extra effort at the end of the implementation phase, but it has another, interesting consequence too: while the transformation from specification to code is not trivial or automatizable, the same thing does not necessarily right to the other way.

## Generation of the functional documentation

...
