---
title: Hands-On Session
layout: default

navigation_weight: 3
---

# Hands-On Session

In the following, we will guide you through all the steps required to model, deploy, and execute a hybrid quantum application using workflows.

The application is intended to automate route planning for package delivery drivers.
Thus, it includes splitting a graph with destinations to receive sub-graphs for each driver based on the truck capacity and the number and size of available packages.
For each driver, the optimal route is calculated for the sub-graph using the distances between the various destinations.

To solve this problem, the hybrid quantum application comprises classical pre- and post-processing steps, as well as the execution of two variational quantum algorithms.
Thereby, we will use the widely-known [Quantum Approximate Optimization Algorithm (QAOA)](https://arxiv.org/pdf/1411.4028.pdf).

The use case utilizes the Quantum Workflow Modeler and Quokka:

* [Quantum Workflow Modeler](https://github.com/PlanQK/workflow-modeler): A graphical BPMN modeler to define, transform, and deploy quantum workflows.
* [Quokka](https://github.com/UST-QuAntiL/Quokka): A microservice ecosystem enabling a service-based execution of quantum algorithms.

## Setup

The code required for the hands-on session is available [here](https://github.com/UST-QuAntiL/QuantME-UseCases/tree/master/2023-icwe).

As the hands-on session requires pushing your implementation from different steps to enable their reuse, start with forking the repository.
In the following we will refer to the GitHub user to which the fork belongs as ``$GITHUB_USER``.

Afterwards, clone the repository and navigate to the ``2023-icwe`` folder:

```
git clone https://github.com/$GITHUB_USER/QuantME-UseCases.git
cd 2023-icwe
```

TODO
