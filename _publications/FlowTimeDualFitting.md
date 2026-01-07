---
title: "An Optimal Online Algorithm for Robust Flow Time Scheduling"
collection: "publications"
category: "conferences"
permalink: "/publication/flow-time-dual-fitting"
excerpt: "Robust flow time scheduling."
date: "2026-01-09"
venue: "SODA 2026"
paperurl: "https://ocmyk2.github.io/files/FlowTimeDualFitting.pdf"
---

The problem of minimizing the total flow time on a single machine is one of the few problems for which we can give an optimal online algorithm: just schedule the job with the shortest remaining processing time (SRPT). However, this requires knowledge of the true running time $p_j$ of each job $j$.

Azar, Leonardi, and Touitou recently asked: what if we are given estimates $\hat p_j$ for each job, such that the multiplicative error between $p_j$ and $\hat p_j$ (called the distortion) is at most $\mu$? It is easy to construct examples where no algorithm can be $o(\mu)$-competitive; can we get $O(\mu)$ competitiveness?

We show how to achieve this asymptotically optimal result, improving on the previous best result of $O(\mu \log \mu)$. Moreover, we give a very simple algorithm to get this tight bound of $O(\mu)$; the previous ZigZag algorithm was relatively more involved.

Our proof is via a dual-fitting argument based on the idea of a reduced instance: we consider an LP relaxation based on knapsack-cover inequalities, and show a solution with a large dual value. Our ideas can also be extended to give alternative dual-fitting arguments for previously analyzed algorithms (like SRPT, ZigZag, and others for minimizing the total flow time, and the Bansal–Dhamdhere algorithm for weighted flow-time minimization).
