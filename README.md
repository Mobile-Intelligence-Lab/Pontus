# Pontus

In modern data-intensive environments, real-time detection of persistent items—those consistently appearing over time—is essential for ensuring system reliability, security, and correctness. Persistent items can signal critical threats such as stealthy DDoS or botnet attacks. However, analyzing both frequent and infrequent persistent items at high data rates is challenging, as storing every item for processing is impractical.  

We introduce **Pontus**, a novel approach leveraging an approximate data structure (sketch) for efficient and accurate persistent item detection. Our method enables fast, precise lookups and can be easily adapted for other persistence-based detection tasks with minor modifications. This repository contains both a C++ implementation for software evaluation and a P4/Tofino-based implementation for in-network deployment. Each folder includes documentation on how to run the code and the environment setup required for execution.
