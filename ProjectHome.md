Introduction

Concurrent behaviour is an inherent part of the real world, with multiple events occurring simultaneously, each of which can interact and affect others. Traditional approaches within computer science tend towards a more idealistic viewpoint, representing sequential isolated behaviour, with concurrency considered as an afterthought. The area of concurrency theory instead focuses on concurrent processes and their interactions, making these considerations more central to the models created using such formalisms.

Modelling Phased Concurrent Environments

Imagine a small closed environment which models a microcosm of the world. Within it, individual processes communicate with each other. This can be thought of as synonomous with individuals conversing with one another in reality, in order to achieve their task. They can also act in isolation; such sequential behaviour is a subset of the overall concurrent behaviour modelled within this environment.

Behaviour is also governed by time, or at least, some notion of phasing. Although we have exact times, such as fourteen minutes past two o'clock, we rarely care about what the actual time. What is more important is that a particular event occurs at some point in time, or that a task needs to be completed by an arbitrary deadline. Thus, time can be more simply represented as a signal that our processes respond to as a whole, as opposed to the one-to-one communication activities previously mentioned.

As an example, consider an environment representing a factory. The individuals receive a particular task, and perform it, possibly interacting with their colleagues. At some point in time, this task is completed; there is no more work to be done, so each individual moves on to the new task simultaneously, at the occurrence of this signal.

The Big Wide World

This is all well and good, but to be able to model more complex systems, we need to think beyond these bounds. In this arena, the environment we just consider is just one of many, with possible nesting of these entities. The factory exists and operates with the larger environment of a city, with other buildings and individuals that have their own separate behaviour. The factory can be thought of a single component, which acts in its own way, but also has interactions with the wider world.

To further complicate things, it is possible for inviduals to move from one environment to another, where different rules apply. Further, environments themselves can change their location, taking on a different context which again affects the behaviour of their consituents.

The calculus of Typed Nomadic Time (TNT), and its realisation in the form of the tool, DynamiTE, is an attempt to provide a formal theory for such models, making use of existing research within the field of computer science and beyond. On this web site, you can find further details about this project along with other academic trivia.