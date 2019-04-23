---
title: Codebase Overview
category: troubleshooting
order: 7
---

If you are trying to troubleshoot an Accumulo problem, you should first try and find help within Accumulo's documentation. The Accumulo
website's [search tool](https://accumulo.apache.org/search/) can help in finding relevant documentation.

If you cannot find relevant documentation for your problem, you might want to review Accumulo's code to learn more about the code that
is causing the problem and find a potential solution for it. This documentation provides an overview of Accumulo's codebase to get you
started.

## Master

The {% ghc server/master/src/main/java/org/apache/accumulo/master/Master.java %} has the following responsibilities:

  * Assign and balance tablets to Tablet Servers using a {% ghc server/master/src/main/java/org/apache/accumulo/master/TabletBalancer.java %}
  * Coordinate log recoveries and report general status



## Tablet Server


## Monitor


## Tracers


