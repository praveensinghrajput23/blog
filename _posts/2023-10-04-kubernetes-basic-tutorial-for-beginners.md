---
title: "Kubernetes Basics: Tutorial for Beginners"
date: 2023-10-04
categories:
  - tutorial
tags:
  - kubernetes
  - orchestration

toc: true
toc_sticky: true
toc_label: "Table of Contents"
excerpt: Have you ever marveled at the magic behind your computer screen, wondering how the software you use daily comes to life? In an age where technology seamlessly integrates
---

![image-center]({{site.url}}/blog/assets/how-program-executes/Computer-programmer.jpeg){: .align-center}

# History of Kubernetes (K8s)

Kubernetes, often abbreviated as K8s, has a fascinating history rooted in the world of container orchestration. It was originally developed by Google, drawing inspiration from their internal Borg system, which managed their vast array of containers and workloads. Google open-sourced Kubernetes in 2014, handing it over to the Cloud Native Computing Foundation (CNCF). Since then, it has rapidly evolved as the practical, widely accepted, and commonly used standard for container orchestration.

## What is Kubernetes?

- Kubernetes a.k.a K8s is the leading container orchestration tool and it's open source.

* Designed as a loosely coupled collection of components centered around deploying, maintaining, and scaling workloads.

* Vendor-neutral ( Runs on all providers).

* Backed by a huge community.

## What K8s can do?

- Service discovery and load balancing
- Storage orchestration
  - Local or Cloud based
- Automated rollouts and rollbacks
- Self-healing
- Secret and configuration management
- Use the same API across on-premise and every cloud providers

## What k8s can't do?

- Does not deploy source code
- Does not build your application
- Does not provide application-level services

  - Message buses, databases, caches, etc.

  Kubernetes provides a powerful solution for automating the deployment, scaling, and management of containerized applications, revolutionizing the way developers and operations teams handle complex container workloads in a distributed and scalable fashion. .
  {: .notice--info}
