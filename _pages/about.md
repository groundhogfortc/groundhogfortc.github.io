---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Overview of Groundhog</p>

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

Threshold cryptosystems (TCs), developed to eliminate single points of failure in applications such as key management-as-a-service, signature schemes, encrypted data storage and even blockchain applications, rely on the assump- tion that an adversary does not corrupt more than a fixed number of nodes in a network. This assumption, once broken, can lead to the entire system being compromised.

In the Groundhog project, we present a systems-level solution, viz., a reboot-based framework, Groundhog, that adds a layer of resiliency on top of threshold cryptosystems; our framework ensures the system can be protected against malicious (mobile) adversaries that can corrupt up all but one device in the network. Groundhog ensures that a sufficient number of honest devices is always available to ensure the availability of the entire system.

Groundhog is generalizable to multiple threshold cryptosystems — we demonstrate this by integrating it with two well-known TC protocols — the Distributed Symmetric key Encryption system (DiSE) and the Boneh, Lynn and Shacham Distributed Signatures (BLS) system.