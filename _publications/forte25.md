---
title: "Attribute-based Communication over Pub/Sub: Transactional Coordination for Smart Systems"
collection: publications
category: conferences
permalink: /publication/forte25
excerpt: "This paper introduces a variant of the two phase commit protocol for implementing AbU's transactional semantics on a generic publisher/subscriber middleware."
date: 2025-06-17
venue: 'FORTE 2025 - 45th International Conference on Formal Techniques for Distributed Objects, Components, and Systems'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-95497-9_6'
citation: 'Comini, M., Gemolotto, L., Miculan, M. (2025). Attribute-Based Communication over Pub/Sub: Transactional Coordination for Smart Systems. In: Ferreira, C., Mezzina, C.A. (eds) Formal Techniques for Distributed Objects, Components, and Systems. FORTE 2025. Lecture Notes in Computer Science, vol 15732. Springer, Cham. https://doi.org/10.1007/978-3-031-95497-9_6'
---

IoT and smart systems frequently rely on _publish-subscribe_ (pub/sub) middlewares like MQTT or DDS. 
 However, current coordination solutions often lack formal rigour, posing risks in mission-critical applications, or suffer from excessive complexity, hindering practical deployment and increasing the likelihood of errors.  
This paper addresses these challenges by integrating AbU, a recently introduced formal model based on _Event-Condition-Action_ (ECA) rules and _attribute-based communication_, with standard pub/sub middlewares.  We present a synchronization protocol that leverages pub/sub primitives to implement AbU's transactional communication semantics.  We prove the correctness of this protocol, demonstrating that it accurately reflects the underlying system dynamics. This integration of a formal ECA-based programming model with pub/sub offers a compelling balance between rigorous guarantees and practical applicability for coordinating IoT and smart systems.