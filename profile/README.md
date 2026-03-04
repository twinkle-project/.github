# TWINKLE - digital TWIN continuum: a Key enabler for pervasive cyber-physicaL Environments

<p align="center">
  <img class="center" src="https://github.com/twinkle-project/twinkle-project.github.io/raw/main/assets/images/banner_white.png" width="80%">
</p>

🇮🇹 Twinkle is a project within the PRIN (Progetti di Ricerca di rilevante Interesse Nazionale) Program 2022 for Research projects of national interest. 

🇪🇺 The project has been funded by the European Union - Next Generation EU (Finanziato dall'Unione europea – Next Generation EU). 

Consortium: 

- University of Modena and Reggio Emilia - Prof. Marco Picone (Principal Investigator)
- University of Pisa - Prof. Antonio Virdis (Substitute Principal Investigator)
- University of Bologna - Cesena Campus - Prof. Alessandro Ricci (Unit Coordinator)

## Brief Project Description

Digital Twins (DT) are evolving from their original research field and emerging as a new cross-domain paradigm for design and implementing cyber-physical applications through the creation of synchronized software replicas of physical devices, products, and organizations, usually called Physical Assets (PAs). They are moving fast towards a widespread adoption beyond industrial and manufacturing contexts, as a general way to bridge the physical and the digital spaces, also thanks to the pervasive diffusion of Internet of Things (IoT) and Web technologies, that extends their applicability across challenging cross-domain use cases.
This challenging pervasive DT evolution calls for new software architectures and approaches featuring levels of flexibility beyond the ones provided by the solutions available in the state of the art that are building DTs mainly as passive components, without an interoperable modeling and through several platform-specific silos. Currently, each model is built from scratch without common methodologies and with the concrete risk to generate a strong vendor lock-in and to block the creation of a real open ecosystem where PAs, DTs and applications can cooperate through an effective service continuum.
To fully harness their potential, a new pervasive and open DT framework is required to both shape twins as active entities with their own behaviors and make them seamlessly collaborate with applications and services through distributed environments. On one side, there is the need for an effective modeling of DT core capabilities, life cycle and shadowing process to properly shape and describe the digitalization process and its quality. On the other hand, the design of DT driven applications should be enabled by an effective and seamless management of available computing, communication and storage resources to provide a continuum across cloud, fog and edge layers to deploy and orchestrate DT instances according to cyber-physical requirements and constraints.

Accordingly, the overall objective of the project is to investigate, define and experiment a new open and distributed DT platform -- here referred as Digital Twin Continuum (DTC) – to enable the design, deployment and maintenance of the next generation of intelligent cyber-physical applications focusing on 3 main research pillars: 

- DT As Service: envisioning a pervasive use of DTs as services virtualizing any relevant logical or physical assets to be consumed by an application layer on top, away from the DT-as-silo view;
- Ecosystems of DT: envisioning dynamic ecosystems of connected/linked DTs, mirroring complex dynamic ecosystems of inter-related PAs;
- Deployment Independence, envisioning the possibility to have a flexible and dynamic deployment of DTs at different network levels, from edge to cloud, according to need, optimizing orchestration, monitoring and performance across multiple execution points.

## Open Source Software Artifacts

The TWINKLE project has produced several open-source software artifacts implementing the Digital Twin Continuum concepts. 
These repositories are publicly available and demonstrate the theoretical and practical contributions of the project:

### [HWoDT - Hypermedia Web of Digital Twins](https://github.com/WebBased-WoDT)
A comprehensive framework for building interoperable Digital Twin ecosystems based on web standards and hypermedia principles. The HWoDT framework enables the creation of DTs that can be discovered and interacted with using standard web technologies, supporting the vision of ecosystems of connected DTs.

### [Digital Twin Continuum Platform Prototype](https://github.com/twinkle-project/dt-continuum-platform)
A proof-of-concept implementation of the DTC platform demonstrating the integration of middleware and infrastructure components. This prototype showcases the deployment and orchestration of DTs across the edge-cloud continuum.

### [Industrial Microfactory - Digital Twin Packages](https://github.com/twinkle-project/microfactory-digital-twin-packages)
Java-based implementation of Digital Twin packages for an industrial microfactory scenario, demonstrating the practical application of the DTC concepts in manufacturing environments.

### [Industrial Microfactory - Digital Twin Model](https://github.com/twinkle-project/microfactory-digital-twin-model)
Python-based Digital Twin model for the industrial microfactory use case, providing a reference implementation for DT modeling and cyber-physical synchronization.
