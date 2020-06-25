---
layout: post
image:  assets/images/conference/2020-09-04-kubecologne.jpg
title:  Architectural Caching Patterns for Kubernetes
conference: KubeCologne
conference-link: https://kubecologne.io/
place: Cologne, Germany (moved online)
tags: [Talk]
event: https://kubecologne.io/
upcoming: true
---

Kubernetes brings new ideas of how to organize the caching layer for your applications. You can still use the old-but-good client-server topology, but now there is much more than that. This session will start with the known distributed caching topologies: embedded, client-server, and cloud. Then, I'll present Kubernetes-only caching strategies, including:
- Sidecar Caching
- Reverse Proxy Caching with Nginx
- Reverse Proxy Sidecar Caching with Hazelcast
- Envoy-level caching with Service Mesh

In this session you'll see:
- A walk-through of all caching topologies you can use in Kubernetes
- Pros and Cons of each solution
- The future of caching in container-based environments