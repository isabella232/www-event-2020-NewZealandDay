---
layout: full-width
title: OWASP NZ Day Training
displaytext: 
tags: nzday2020
---

[![Conference Web Banner](../../assets/images/Web_Banner-OWASP_NZ_Day_2020.jpg)](/www-event-2020-NewZealandDay)

[Back to Pre-Conference TrainingPage](/www-event-2020-NewZealandDay/training/)
{: style="text-align: right; font-size: small;" }

[Back to Conference Home Page](/www-event-2020-NewZealandDay)
{: style="text-align: right; font-size: small;" }

# Attacking and Defending Containerised Applications and Serverless Tech

## Two-Day Interactive Training - OWASP New Zealand Day 2020

## Abstract

Both attacking and securing an infrastructure, or applications leveraging containers/serverless technology, require a specific skill set and a deep understanding of the underlying architecture. This training will be extremely hands-on, to help you understand all there is to attack and secure containerised and serverless applications.

## Overview

With organisations rapidly moving toward micro-service architectures for their applications, container and serverless technologies seem to be taking over at a rapid rate. Leading container technologies like Docker have risen in popularity and have been widely used, because they have help package and deploy consistent-state applications. Serverless and orchestration technologies, such as Kubernetes, support massive scale-up. This, in turn, can massively increase the overall attack surface, unless security is given the attention required.

Security continues to remain a key challenge that both organisations and security practitioners faced with containerised and serverless deployments. While container-orchestrated deployments may be vulnerable to security threats that plague typical application deployments, they face several specific security threats related to: the containerisation daemon, shared kernel, shared resources, secrets management, insecure configurations, role management issues, and many more! Serverless deployments, on the other hand, face risks such as: insecure serverless deployment configurations, inadequate function monitoring and logging, broken authentication, function event data injection, and insecure application secrets storage. Attacking an infrastructure, or applications leveraging containers and serverless technology, requires a specific skill-set and a deep understanding of the underlying architecture.

This training has been created with the objective of understanding both offensive and defensive security for container-orchestrated and serverless deployments. It will be a two-day program detailing specific theory elements, with extensive hands-on exercises modeling real-world threat scenarios. Attendees will learn ways in which containerised and serverless deployments can be attacked, so they can understand how to make them secure yet scalable, efficient, and effective.

## Target Audience 

This course is aimed at Developers, DevOps Engineers, Penetration Testers, Security Practitioners, and other who use container or serverless technology as part of their product deployments, and want to gain a good understanding on how to secure their services and deployments. 

## Course Details 

**Dates:** Wednesday and Thursday, 19-20 February 2020

**Time:** 8:45 a.m. to 5:30 p.m. each day

**Course Fee:** NZ $1,250.00 (plus EventBrite fees)

**Registration Site:** https://owaspnz2020-training.eventbrite.com

**Prerequisite Skills:**

* Students should have a basic understanding of Linux environment and know their way around the terminal
* A basic understanding of ‘OWASP TOP-10 Vulnerabilities’ and ‘Basics of Docker’ will be helpful, but not necessary

**Attendees Should Bring:** 

* Attendees should bring a laptop, with an updated browser for accessing the lab environment(s). We have observed that Chrome or Firefox works best.
* All the hands-on labs will be run on cloud environments that can be provisioned on-demand using our lab management system during the training.
 
**Attendees Will Be Provided:**

* All course materials (slides, code, and setup files) will be available to download during the training
* Access to the lab management system we use for labs, which has been widely appreciated

**Instructors:** Pavan Kumar and Sharath Kumar Ramdas, [we45](https://www.we45.com we45)   

## Course Topics

The training includes, but is not limited to, the following topic areas in Container Security and Serverless Deployment:

* Introduction to Container Technology
* Deep-dive into Container Technology
* Introduction to Docker and other container engines
* Containerised Deployments and Container Orchestration Technologies
* Container Threat Model
* Attacking Containers and Security deep-dive
* Container Orchestration Deep-dive
* Introduction to Kubernetes
* Threat Model of Orchestration technologies
* Attacking Kubernetes
* Kubernetes Defense-in-Depth and Vulnerability Assessment
* Logging & Monitoring Orchestrated deployments
* Introduction to Serverless
* Deploying Application to AWS Lambda
* Serverless Threat-Model
* Attacking a Serverless Stack
* Serverless Security Deep-dive

## Detailed Course Outline

### Day 1 - Wednesday

**Evolution to Container Technology, and Container Tech Deep-Dive**

* Introduction to Container Technology
  * Namespace
  * Cgroups
  ** Mount
* Hands-on Lab: Setting up a minimal container

**Introduction to Containerised Deployments - Understanding and getting comfortable using Docker**

* An introduction to containers
  * LXC and Linux containers
  * Introducing Docker images and containers
* Deep dive into Docker
  * Docker commands and cheat sheet
  * Hands-on exercises:
    * Docker commands
    * Dockerfile
    * Images
    * Docker Compose
  * Hands-on: Docker Compose commands

**Threat Landscape - An Introduction to possible threats and attack surface when using Containers for Deployments**

* Threat model for containerised deployments
  * Daemon-related threats
  * Network-related threats** OS and Kernel threats
  * Threats with application libraries
  * Threats from containerised applications
* Traditional threat modelling for containers, using STRIDE

**Attacking and Securing Containers**

* Attacking containers and containerised deployments
* Hands-on exercises:
  * Container breakout
  * Exploiting insecure configurations
  * OS- and Kernel-level exploits
  * Trojanised Docker image
* Container security deep dive
* Hands-on:
  * AppArmor/SecComp
  * Restricting capabilities
  * Analysing Docker images
* Container security mitigations
* Hands-on: Container vulnerability assessment
  * Clair
  * Dagda
  * Anchore
* Docker-bench

**Introduction to Kubernetes**

* Understanding Kubernetes components and architecture
* Hands-on: Exploring Kubernetes Cluster, deploying application to Kubernetes

### Day 2 - Thursday

**Attacking Kubernetes Cluster**

* Kubernetes threat model
* Hands-on:
  * Attacking application deployed on Kubernetes
  * Exploiting a vulnerable Kubernetes cluster

**Kubernetes security deep dive**

* Kubernetes security mind map
* Hands-on: Ideal security journey - Kubernetes
  * Pod Security
  * Access Control
  * Secrets Management

* Hands-on: Kubernetes vulnerability assessment
  * Kube-sec
  * Kube-hunter
  * Kube-bench

* Hands-on: Logging and monitoring
  * Resource utilisation
  * Malicious behavioural activity monitor

**Serverless Introduction**

* Understanding serverless and Function-as-a-Service (FAAS)
* Introduction to AWS Lambda, and other serverless options
* Hands-on: Deploying a serverless application

**Attacking Serverless Applications**

* [https://www.owasp.org/images/5/5c/OWASP-Top-10-Serverless-Interpretation-en.pdf OWASP Top 10 for Serverless Applications] (PDF)
* Hands-on: Attacking serverless applications
  * Injection-based attacks
  * Broken authentication attacks
  * Deserialisation attacks
  * Securing serverless applications
  * Identity and access management (IAM)
  * Secrets management
  * Logging and monitoring functions

* Hands-on: Serverless vulnerability assessment
  * Static code analysis (SCA)
  * Static application security testing (SAST)
  * Dynamic application security testing (DAST)

## Your Instructors

**Pavan Kumar** - Pavan is a Senior Security Lead at we45. He has worked and led multiple penetration testing projects of web, mobile applications, and Infrastructure for Fortune 500 companies in different domains such as data storage, manufacturing and E-commerce. He has done in-depth research on AWS cloud services and is an expert in identifying vulnerabilities related to AWS cloud.

Pavan has identified several critical P1 flaws in private Bug Bounty programs. He has also written custom scripts to automate multiple reconnaissance activities done during audits of applications.  He has also conducted trainings and spoken in multiple meetup events on his research associated with new vulnerability discovery and exploits. Pavan participates in multiple CTF events (Defcon, HacktheBox, etc.) and has worked on creating Intentionally Vulnerable Applications for CTF competitions and Secure Code Training.

**Sharath Kumar Ramdas** - Sharath is the Lead Solutions Engineer at we45. He has architected and developed multiple solutions around security engineering, including an Application Vulnerability Correlation tool called Orchestron. As part of his experience with Application Security, Sharath has developed integrations for multiple security products including DAST, SAST, SCA and Cloud environments.

Sharath has extensive experience with Cloud Deployments and Container Native Deployments. As part of his role in a security organization, he has led teams that have created intentionally vulnerable apps for CTF competitions both inside and outside we45.

Sharath is a speaker at multiple meetups around Cloud, Containers, Python, DevOps and DevSecOps. He is also the co-author of the Container Security Training Program from we45.
