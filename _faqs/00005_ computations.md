---
title: What is a computation?
date: 2018-03-24 00:00:00 Z
layout: faq
---
For our purposes, a **computation** is a conditionally ordered set of operations that occur inside a computational system.  **Computational systems** consist of a state space together with a platform that can monitor the state space and perform conditionally ordered operations on the state space.  A **state space** is defined to be a vector of physical measurements of things in the real world.  A **platform** is a set of physical operators together with a control mechanism that allows the platform to do conditionally ordered operations that change the state space.  Platforms can be microcontrollers, computers, robots, humans, etc., and any connected network of platforms.  

**Algorithms** are used to model and study the computations performed by computational systems.  Algorithms use an unambiguous language to define the state space, and the effect of operations on the state space.  Using the language specified, an algorithm tells us how to produce a computation that will 'move' the computational system from an initial state with certain properties to an end state with certain properties.  Algorithms are implemented on computational platforms in a language the platform understands using information and operations avialable to the platform.
