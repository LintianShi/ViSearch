# ViSearch

This is the repository of a research project **ViSearch**, which is a framework for weak consistency measurement of replicated data type. 

It is includes two components:

* [ViSearch Checker](https://github.com/AnonymousAccountForPaperReview/ViSearch/tree/main/checker): measures the consistency level of a history of replicated 
* [ViSearch Experiment](https://github.com/AnonymousAccountForPaperReview/ViSearch/tree/main/experiment): experiments that interact with database and generate histories
  * [CRDT-Redis-Experiment](https://github.com/AnonymousAccountForPaperReview/Redis-CRDT-Experiment): experiments on CRDT-Redis [[1]](https://github.com/elem-azar-unis/CRDT-Redis), a open-source project of several Conflict-Free Replicated Data Types (CRDTs) implemented based on Redis(6.0.5).
  * [Riak-Experiment](https://github.com/AnonymousAccountForPaperReview/Riak-CRDT-Experiment): experiments on Riak's data types [[2]](https://docs.riak.com/riak/kv/2.2.3/developing/data-types/index.html). 

# Run ViSearch

If you want to measure consistency level of a history, see [ViSearch Checker](https://github.com/AnonymousAccountForPaperReview/ViSearch/tree/main/checker). 

If you want to adjust configuration of experiment, or generate new histories, see [ViSearch Experiment](https://github.com/AnonymousAccountForPaperReview/ViSearch/tree/main/experiment). 

You can see some histories collected from our experiments in this repository [ViSearch-Traces](https://github.com/AnonymousAccountForPaperReview/ViSearch-Traces).