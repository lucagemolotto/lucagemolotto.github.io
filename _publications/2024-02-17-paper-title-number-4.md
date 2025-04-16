---
title: "Attribute-based Communication over Pub/Sub: Transactional Coordination for Smart Systems"
collection: publications
category: conferences
permalink: /publication/2025-04-04-paper-title-number-1
excerpt: 'In this paper we propose a protocol to implement AbU on a general pub/sub middleware.'
date: 2024-04-04
venue: 'FORTE 2025 - 45th International Conference on Formal Techniques for Distributed Objects, Components, and Systems'
paperurl: 'TBD'
citation: 'TBD'
---

IoT and smart systems frequently rely on \emph{publish-subscribe} (pub/sub) middlewares like MQTT or DDS. 
 However, current coordination solutions often lack formal rigour, posing risks in mission-critical applications, or suffer from excessive complexity, hindering practical deployment and increasing the likelihood of errors.  
This paper addresses these challenges by integrating AbU, a recently introduced formal model based on \emph{Event-Condition-Action} (ECA) rules and \emph{attribute-based communication}, with standard pub/sub middlewares.  We present a synchronization protocol that leverages pub/sub primitives to implement AbU's transactional communication semantics.  We prove the correctness of this protocol, demonstrating that it accurately reflects the underlying system dynamics. This integration of a formal ECA-based programming model with pub/sub offers a compelling balance between rigorous guarantees and practical applicability for coordinating IoT and smart systems.