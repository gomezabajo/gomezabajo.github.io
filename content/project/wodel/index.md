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
    name: Visit Project
    url: https://gomezabajo.github.io/Wodel/
image:
  caption: Wodel development environment
  focal_point: Smart
  filename: featured.jpg
#url_code: ""
---
**Wodel** is a domain-specific language for specifying and generating model mutants.

Wodel is **domain-independent** because it can generate mutants of models that conform to arbitrary metamodels.

Wodel provides **nine mutation primitives** for creating and deleting objects, redirecting references, modifying attributes, cloning elements, and retyping objects (changing an object's type to one of its sibling types), among other operations.

The engine **verifies that each generated mutant is a valid model** (i.e., that it conforms to the domain metamodel and satisfies its integrity constraints).