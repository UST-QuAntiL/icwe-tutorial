---
title: About
layout: default

navigation_weight: 1
---

This website hosts the material of the tutorial "A Practical Introduction for Developing and Operating Hybrid Quantum Applications", which will be held in Alicante (Spain) during the 2023 edition of the [International Conference on Web Engineering (ICWE)](https://icwe2023.webengineering.org/).

# Abstract

With the increasing number of quantum computers available via the cloud, the research area of quantum software engineering is emerging.
Its goal is the investigation of concepts and guidelines to develop and operate hybrid quantum applications, ensuring engineering principles such as modularity, reuse, and maintainability.
In this tutorial, we provide an overview of state-of-the-art concepts and techniques in quantum computing, as well as quantum software engineering.
It includes an introduction of selected essential quantum algorithms, limitations of current quantum computers, and a lifecycle for hybrid quantum applications.
Furthermore, we show how the service-oriented development of hybrid quantum applications increases their modularity and reusability.
Finally, we demonstrate the orchestration of the required classical and quantum programs using workflows and their automated deployment.

# Motivation 

Quantum computers enable a computational advantage over classical computers by exploiting quantum mechanical phenomena, such as entanglement and superposition [[4]](#4).
However, the capabilities of today's quantum computers are limited by high error rates and the number of provided qubits [[5]](#5).
Multiple providers offer quantum computers with different characteristics, so choosing the most suitable one for the use case at hand can significantly improve performance [[6]](#6).
Since many traditional tasks, such as data persistence, are not suitable for quantum computers, they serve as co-processors for specific problems [[7]](#7).
Integrating and orchestrating the various classical and quantum programs comprising a hybrid quantum application is crucial [[3]](#3).
Workflows are a proven approach to orchestrate hybrid quantum applications, as they enable the construction of scalable and robust applications [[8]](#8).
To facilitate the development of quantum applications, it is good practice to modularize their functionalities in small packages [[1]](#1).
Modularization enables, e.g., distributed deployment of the functionalities to benefit from heterogeneous cloud offerings depending on the user's requirements [[2]](#2) and their reuse when composing new quantum applications [[9]](#9).

# Intended Audience

Attendees of this tutorial do not require any previous knowledge of quantum computing or quantum software engineering.
The tutorial aims to impart basic knowledge about designing, developing, deploying, and executing hybrid quantum applications.
Therefore, it empowers attendees to use current quantum computers in different application areas and evaluate their suitability.

# Technical Requirements

For the practical part of the tutorial, a laptop with Docker and Docker Compose installed is required.
Furthermore, to evaluate the modeled hybrid quantum application on state-of-the-art quantum computers, we utilize IBMQ and the SDK Qiskit.
Thus, an IBMQ account is needed, which can be created free of charge.
Alternatively, a local simulator can be used as described in the tutorial materials.

# Learning Goals

Attendees will have obtained knowledge on:

- A holistic overview of quantum computing, promising application areas, and the basics of quantum software engineering.
- Hybrid quantum applications and their corresponding lifecycle.
- The importance of selecting a suitable quantum computer for a given quantum program and how to automate this process.
- Modular development of hybrid quantum applications, their orchestration using workflows, and automatic deployment using TOSCA.

## References

<a id="1">[1]</a> Beisel, M., Barzen, J., Garhofer, S., Leymann, F., Truger, F., Weder, B., Yussupov, V.: **Quokka: A Service Ecosystem for Workflow-Based Execution of Variational Quantum Algorithms.** In: Service-Oriented Computing – ICSOC 2022 Workshops. Springer (2023)  
<a id="2">[2]</a> Binz, T., Breitenbücher, U., Haupt, F., Kopp, O., Leymann, F., Nowak, A., Wagner, S.: **OpenTOSCA – A Runtime for TOSCA-based Cloud Applications.** In: Proceedings of the 11th International Conference on Service-Oriented Computing (ICSOC). vol. 8274, pp. 692–695. Springer (2013)  
<a id="3">[3]</a> Gemeinhardt, F., Garmendia, A., Wimmer, M.: **Towards Model-Driven Quantum Software Engineering.** In: 2021 IEEE/ACM 2nd International Workshop on Quantum Software Engineering (Q-SE). pp. 13–15 (2021)  
<a id="4">[4]</a> Nielsen, M.A., Chuang, I.: **Quantum Computation and Quantum Information.** AAPT (2010)  
<a id="5">[5]</a> Preskill, J.: **Quantum Computing in the NISQ era and beyond.** Quantum 2, 79 (2018)  
<a id="6">[6]</a> Salm, M., Barzen, J., Breitenbücher, U., Leymann, F., Weder, B., Wild, K.: **The NISQ Analyzer: Automating the Selection of Quantum Computers for Quantum Algorithms.** In: Proceedings of the 14th Symposium and Summer School on Service-Oriented Computing (SummerSOC). pp. 66–85. Springer (2020)  
<a id="7">[7]</a> Weder, B., Barzen, J., Leymann, F., Vietz, D.: **Quantum Software Development Lifecycle**, pp. 61–83. Springer (2022)  
<a id="8">[8]</a> Weder, B., Breitenbücher, U., Leymann, F., Wild, K.: **Integrating Quantum Computing into Workflow Modeling and Execution.** In: Proceedings of the 13th IEEE/ACM International Conference on Utility and Cloud Computing (UCC). pp. 279–291. IEEE Computer Society (2020)  
<a id="9">[9]</a> Zhao, J.: **Quantum Software Engineering: Landscapes and Horizons.** arXiv preprint arXiv:2007.07047 (2020)

