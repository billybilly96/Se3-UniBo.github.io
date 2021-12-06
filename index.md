Paper accepted at AAAI22


## Abstract
The quadratic memory complexity of transformers limits the summarization of long documents in a low computational resource scenario. State-of-the-art models truncate the input, thus discarding and ignoring potential summary-relevant contents that lead to a performance drop. Furthermore, such loss is generally destructive for semantic text analytics in the legal domain. In this paper, we propose a novel semantic self-segmentation (Se3) approach for long document summarization to address the critical problems of low-resource regimes, namely (i) to process longer inputs than the GPU memory capacity and (ii) to produce accurate summaries even with few labeled data. Se3 segments a long input into semantically coherent chunks, allowing transformers to summarize long documents without truncation by summarizing each chunk and concatenating the results. Experimental results show that our proposed approach significantly improves the performance of transformers, mainly in low-resource summarization, achieving new state-of-the-art results on two legal datasets. Finally, we perform ablation studies to assess how the different components of our method contribute to the performance gain.


## Web Application

It will be available soon!



## Team and Contacts

* Dr. Luca Ragazzi (PhD Student) - l.ragazzi@unibo.it
* Prof. Gianluca Moro (PhD) - gianluca.moro@unibo.it

_Department of Computer Science and Engineering, University of Bologna, Campus of Cesena_
