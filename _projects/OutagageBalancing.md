---
layout: default
idx: 1
title: Outage Balancing for Femtocell Networks
Keywords: Non-convex Optimization, Mixed-Interger Programming Problem, Non-linear Perron-Frobenius Theorem, Heterogeneous Networks
---

<p> <img src="/images/systemModel.png" style="float:right;width:300px;height:220px"> Given channel statistics information either locally at each femtocell base-station (FBS) or 
collected at some control node, we aim at optimizing certain system parameters based on the outage probability for FUEs and MUEs.
In a two-tier heterogenous network, interference comes from both the intra-tier (femto-to-femto, macro-to-macro)
 and cross-tier (femto-to-macro, macro-to-femto). Based on similar model, we managed to solve the following two problems</p>
<ol>
        <li>With resource allocation fixed, jointly optimize the rate allocation and power allocation for each link. </li>
        <li>With rate requirement fixed,  jointly optimizing resource allocation and power allocation for each link. </li>
</ol>
In both cases, we try to optimize outage-probability based network metrics, which provide certain fairness among
base-stations as well.