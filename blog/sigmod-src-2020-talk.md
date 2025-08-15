---
blogpost: true
date: 2020-06-17
category: Talk
tags: [rdma, pmem, modern hardware, message broker, scalability]
author: Hendrik Makait
excerpt: 1
---
# Rethinking Message Brokers on RDMA and NVM | ACM SIGMOD 2020 SRC

:::{video} https://www.youtube.com/watch?v=9Lpa_qOStSE
:::

## Abstract
Modern stream processing setups heavily rely on message brokers such as Apache Kafka or Apache Pulsar.
These systems act as buffers and re-readable sources for downstream systems or applications.
They are typically deployed on separate servers, requiring extra resources, and achieve persistence through disk-based storage, limiting achievable throughput.
In our paper, we present Ghostwriter, a message broker that utilizes remote direct memory access (RDMA) and non-volatile memory (NVM) for highly efficient message transfer and storage.
Utilizing the hardware characteristics of RDMA and NVM, we achieve data throughput that is only limited
by the underlying hardware, while reducing computation and disaggregating storage and data transfer coordination.
Ghostwriter achieves performance improvements of up to an order of magnitude in throughput and latency over state-of-the-art solutions.
