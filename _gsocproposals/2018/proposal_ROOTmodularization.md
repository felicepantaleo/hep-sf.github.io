---
title: ROOT Package Manager
layout: gsoc_proposal
project: ROOT
year: 2018
organization: CERN
---

## Description

The [ROOT](https://root.cern/) is a framework for data processing, born at CERN, at the heart of the research on high-energy physics. Every day, thousands of physicists use ROOT applications to analyze their data or to perform simulations. The ROOT software framework is foundational for the HEP ecosystem, providing capabilities such as IO, a C++ interpreter, GUI, and math libraries. It uses object-oriented concepts and build-time modules to layer between components. We believe additional layering formalisms will benefit ROOT and its users.

Currently, ROOT is being built and integrated altogether. We would like to start building and integrating ROOT modules in groups or one by one. This requires introducing a few layering mechanisms, extending the functionality of the existing package manager prototype and generalizing the implementation to fit external to ROOT packages.

For further information please read our proposal: [Proposal](https://github.com/root-project/root-evolution/blob/master/proposals/0001-modularization.md)


## Expected results
* Enhance the package manager to work with already built packages
* Teach ROOT how to communicate with its package manager
* Enhance the existing CMake build system rules to enable lazy building of packages
* Rethink the continuous integration system in term of a package-oriented system


## Requirements
C++, Python, CMake, Git, TravisCI.

## Mentors
  * [Brian Bockelman](mailto:bbockelm@cse.unl.edu)
  * [Oksana Shadura](mailto:oksana.shadura@cern.ch)
  * [Vassil Vassilev](mailto:vasil.georgiev.vasilev@cern.ch)

## Links
  * [ROOT](https://root.cern/)
