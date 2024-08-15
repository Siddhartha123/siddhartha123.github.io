---
layout: post
title: Eviction based attacks on randomized cache architecture
description: To secure the caches from conflict based attacks, randomized caches have been proposed like CEASER, CEASER-S etc. which perform random mapping of cache sets as well as support access/eviction based remapping of sets. In this work, we demonstrate that such a design is also vulnerable to side-channel attacks by exploiting the knowledge of replacement policy (LRU) to form eviction sets using minimal number of evictions. The proposed algorithm has O(n) complexity and hence as effective as Group Elimination Method for access based remapping. We show that only with highly idealistic assumptions for the adversary, a prime+probe attack is possible on a simple victim trace. We also analyse the extent of success of prime+probe attack for various configurations obtained by varying the remap rate and number of partitions. <strong><a href="/assets/pdf/cs773_project_report.pdf">[Report]</a> &nbsp; <a href="https://github.com/Rajiv2605/CEASER_S_backup/tree/prime_probe_ceaser">[Code]</a></strong>
redirect: none
importance: 4
categories: 
layout: post
date: 2022-05-05
tags: 
# thumbnail: assets/img/gardening/portulaca_1-480.webp
---
