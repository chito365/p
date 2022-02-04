---
id: 5772
title: Distributed System Tutorial Lessons
date: 2015-12-06T20:18:00+00:00
author: chito
layout: post
guid: http://www.afriqueunique.org/2015/12/06/12273142/
permalink: /2015/12/06/distributed-system-tutorial-lessons/
swp_pinterest_image_url:
  - ""
post_views_count:
  - "100"
bs_social_share_facebook:
  - "0"
bs_social_share_twitter:
  - "0"
bs_social_share_reddit:
  - "0"
bs_social_share_google_plus:
  - "0"
bs_social_share_linkedin:
  - "0"
bs_social_share_interval:
  - "1568414241"
categories:
  - LEARNING
---
<div>
  Distributed System?
</div>

<div>
</div>

<div>
  A collection of (probably heterogeneous) automata whose distribution is transparent to
</div>

<div>
  the user so that the system appears as one local machine. This is in contrast to a network,
</div>

<div>
  where the user is aware that there are several machines, and their location, storage
</div>

<div>
  replication, load balancing and functionality is not transparent. Distributed systems
</div>

<div>
  usually use some kind of client-server organization.
</div>

<div>
</div>

<div>
  • A distributed system is a collection of independent computers that
</div>

<div>
  appear to the users of the system as a single computer.
</div>

<div>
  [Andrew Tanenbaum]
</div>

<div>
  • A distributed system is several computers doing something together.
</div>

<div>
  Thus, a distributed system has three primary characteristics: multiple
</div>

<div>
  computers, interconnections, and shared state.
</div>

<div>
  [Michael Schroeder]
</div>

<div>
</div>

<div>
  Exampes:
</div>

<div>
</div>

<div>
  • Client-Server (NFS)
</div>

<div>
  • The Web
</div>

<div>
  • The Internet
</div>

<div>
  • A wireless network
</div>

<div>
  • DNS
</div>

<div>
  • Gnutella or BitTorrent (peer to peer overlays)
</div>

<div>
  • A “cloud”, e.g., Amazon EC2/S3, Microsoft Azure
</div>

<div>
  • A datacenter, e.g., NCSA, a Google datacenter, The Planet
</div>

<div>
  Can you name some examples of
</div>

<div>
  Distributed Systems?
</div>

<div>
  (First lecture slide)
</div>

<div>
  What is a Distributed System.
</div>

<div>
</div>

<div>
  Problems:{
</div>

<div>
</div>

<div>
</div>

<div>
  basic:
</div>

<div>
  Failure Detectors
</div>

<div>
  • Time and Synchronization
</div>

<div>
  • Global States and Snapshots
</div>

<div>
  • Multicast Communications
</div>

<div>
  • Mutual Exclusion
</div>

<div>
  • Leader Election
</div>

<div>
  • Impossibility of Consensus
</div>

<div>
  • Gossiping
</div>

<div>
</div>

<div>
  cloud computing:
</div>

<div>
  • Peer to peer systems – Napster, Gnutella
</div>

<div>
  Chord
</div>

<div>
  • Cloud Computing
</div>

<div>
  • Networking and Routing
</div>

<div>
  What lies beneath:
</div>

<div>
  • Sensor Networks
</div>

<div>
  • Measurements from real systems
</div>

<div>
  • Datacenter Disaster Case Studies }
</div>

<div>
</div>

<div>
  Common Goals:
</div>

<div>
</div>

<div>
  – Heterogeneity – can the system handle a large variety of types of PCs and devices?
</div>

<div>
  – Robustness – is the system resilient to host crashes and failures, and to the network
</div>

<div>
  dropping messages?
</div>

<div>
  – Availability – are data+services always there for clients?
</div>

<div>
  – Transparency – can the system hide its internal workings from the users?
</div>

<div>
  – Concurrency – can the server handle multiple clients simultaneously?
</div>

<div>
  – Efficiency – is the service fast enough? Does it utilize 100% of all resources?
</div>

<div>
  – Scalability – can it handle 100 million nodes without degrading service?
</div>

<div>
  (nodes=clients and/or servers) How about 6 B? More?
</div>

<div>
  – Security – can the system withstand hacker attacks?
</div>

<div>
  – Openness – is the system extensible?
</div>

<div>
  – (Also: consistency, CAP, partition-tolerance, ACID, BASE, and others … )
</div>

<div>
</div>

<div>
  problems:
</div>

<div>
</div>

<div>
  • Failure Detectors
</div>

<div>
  • Time and Synchronization
</div>

<div>
  • Global States and Snapshots
</div>

<div>
  • Multicast Communications
</div>

<div>
  • Mutual Exclusion
</div>

<div>
  • Leader Election
</div>

<div>
  • Impossibility of Consensus
</div>

<div>
  • Gossiping
</div>

<div>
  • Peer to peer systems – Napster, Gnutella
</div>

<div>
  Chord
</div>

<div>
  • Cloud Computing
</div>

<div>
  • Sensor Networks
</div>

<div>
  • Measurements from real systems
</div>

<div>
  • Datacenter Disaster Case Studies
</div>

<div>
  • Networking and Routing
</div>

<div>
  Core Material of this course
</div>

<div>
  Related to CS 525 (Advanced
</div>

<div>
  Distributed Systems
</div>

<div>
  Offered Spring 2015)
</div>

<div>
  Related to
</div>

<div>
  CS 438/439/538
</div>

<div>
  • RPCs & Distributed Objects
</div>

<div>
  • Concurrency Control
</div>

<div>
  • 2PC and Paxos
</div>

<div>
  • Replication Control
</div>

<div>
  • Key-value and NoSQL stores
</div>

<div>
  • Stream Processing
</div>

<div>
  • Graph processing
</div>

<div>
  • Self-stabilization
</div>

<div>
  • Distributed File Systems
</div>

<div>
  • Distributed Shared Memory
</div>

<div>
  • Security
</div>

<div>
  Problems we have seen in
</div>

<div>
  Class
</div>

<div>
  (and their relation to other courses)
</div>

<div>
  Core Material of this course
</div>

<div>
  Related to CS 411/CS 511
</div>

<div>
  Related to CS 423/523
</div>

<div>
  Related to CS 421/CS 433
</div>

<div>
  Related to CS 525
</div>

<div>
  CS525: Adv
</div>

<div>
</div>

<div>
</div>

<div>
</div>

<div>
</div>

<div>
</div>