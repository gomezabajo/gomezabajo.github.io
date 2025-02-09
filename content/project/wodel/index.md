---
#slides: example
#url_pdf: ""
summary: A domain-specific language for model mutation
#url_video: ""
date: 2016-04-27T00:00:00.000Z
#external_link: ""
#url_slides: ""
title: Wodel
tags:
  - Wodel
links:
  - icon: check
    icon_pack: fas
    name: Check
    url: https://gomezabajo.github.io/Wodel/
image:
  caption: Wodel development environment
  focal_point: Smart
  filename: featured.jpg
#url_code: ""
---
**Wodel** is a Domain-Specific Language for the specification and generation of model mutants.

Wodel is **domain-independent**, as it can be used to generate mutants of models conforming to arbitrary meta-models.

Wodel provides **nine mutation primitives** for object creation and deletion, reference redirection, attribute modification, cloning, and retyping (change the type of an object to one of its siblings types), among others.

The engine **verifies that each generated mutant is a valid model** (i.e., it conforms to the domain meta-model and satisfies its integrity constraints).