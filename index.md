### Semantic Self-segmentation for Abstractive Summarization of Long Legal Documents in Low-resource Regimes

The quadratic memory complexity of pre-trained transformers limits the summarization of long documents in a low-budget GPU scenario. State-of-the-art models truncate the input in such low-resource regimes, thus discarding and ignoring potential summary-relevant contents that lead to a performance drop. Further, such information loss is generally destructive for semantic text analytics in the legal domain. In this paper, we propose a novel semantic self-segmentation (Se3) for long document summarization in low-resource regimes, namely (i) to process longer inputs than the model memory capacity and (ii) to produce accurate summaries even with few labeled data. Se3 allows transformers to summarize the entire input regardless of the size by segmenting a labeled document into shorter and high-correlated source-target pairs. Experiments, whose results are evaluated with several accuracy measures, show that generative transformers combined with Se3 significantly boost ROUGE summarization scores. Se3 achieves new state-of-the-art results on two popular legal corpora in both low-resource regimes of data scarcity and GPU memory limited to 12GB. Finally, we perform ablation studies to evaluate how the different components of our system contribute to the performance gain.


### WebApp

[Se3 Web Application]



### Support or Contact

The team is made up of: 
* Dr. Luca Ragazzi (PhD Student) (l.ragazzi@unibo.it)
* Prof. Gianluca Moro (PhD) (gianluca.moro@unibo.it)

_Department of Computer Science and Engineering, University of Bologna, Campus of Cesena._
