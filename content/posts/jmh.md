---
title: "Code Performance Monitoring with JMH"
date: 2022-02-03T10:53:30-08:00
draft: false 
---

At Calypso, my assignment was to implement a solution that would
enable the Financial Engineering team to monitor code performance,
catching performance degredations in curve generation before they
were shipped to clients. With the help of preliminary research, I
found that the tool we needed was Java Microbenchmark Harness.

## Java Benchmark Harness

The Java Benchmark Harness is developed by the same team behind
the OpenJDK project. It's purpose is to test specific methods 
a configurable number of times against benchmark numbers and
determine where the performance gains and degredations are, with
detailed numbers for each. 

