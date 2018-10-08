# Breaking the Scalability Barrier of Causal Broadcast in Large and Dynamic Systems [[pdf]](https://hal.inria.fr/hal-01778901/document)

_Keywords: Causal order, broadcast, large and dynamic, distributed systems_

_Authors: Brice Nédelec, Pascal Molli, Achour Mostéfaoui_

Many distributed protocols and applications rely on causal broadcast
to ensure consistency criteria.  However, none of causality tracking
state-of-the-art approaches scale in large and dynamic systems.  This
paper presents a new non-blocking causal broadcast protocol suited for
dynamic systems.  The proposed protocol outperforms state-of-the-art
in size of messages, execution time complexity, and local space
complexity. Most importantly, messages piggyback control information
the size of which is constant.  We prove that for both static and
dynamic systems.  Consequently, large and dynamic systems can finally
afford causal broadcast.

## Acknowledgements

This work was partially funded by the French ANR projects O'Browser
([ANR-16-CE25-0005-01](http://www.agence-nationale-recherche.fr/Projet-ANR-16-CE25-0005)),
and Descartes
([ANR-16-CE40-0023](http://www.agence-nationale-recherche.fr/Projet-ANR-16-CE40-0023)).
