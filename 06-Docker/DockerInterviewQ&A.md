# Docker Interview questions 
* Why were physical servers inefficient?
* Why virtualization came?
* Why containers came after VMs?
* Why containers are faster?
* Explain VM vs Container using BookMyShow?


using Linux technologies:

Namespaces → isolation
cgroups → CPU/RAM control
OverlayFS → image layers

These are the hidden technologies behind Docker.


Q1: Difference between manual and streamlined containerization?

Answer:

Manual containerization requires manually configuring application dependencies and environments, while streamlined containerization uses Dockerfiles/images to automate packaging and deployment.

Q2: Why streamlined containerization became popular?

Answer:

Because it improves:

consistency
reproducibility
scalability
automation
deployment speed