---
blogpost: true
date: 2023-03-16
category: Talk
tags: [dask, pandas, coiled, performance]
author: Hendrik Makait
excerpt: 2
---
# Talk: Shuffling Large Data at Constant Memory in Dask | Dask Demo Day 2023-03

:::{video} https://www.youtube.com/watch?v=-clDr7dqONE&t=588s
:::

## Abstract

**Debugging is hard. Distributed debugging is hell.**

Dask is a popular library for parallel and distributed computing in Python.
In this demo, we showcase the recent scalability and performance improvements in the `dask.dataframe` API that were enabled by my work on the new P2P shuffling system.
