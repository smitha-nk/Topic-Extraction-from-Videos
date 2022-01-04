# Topic Extraction from Video Transcriptions

In this paper,  we aim at developing a topic extractor on video transcriptions. 
We approach to use 3 Topic models namely LDA, LSA & NMF 
We analyse the true number of topics with LDA & with this now known true no of topics we model LSA & NMF.
Experimental results on the real-life multimodal dataset MuSe-CaR demonstrates that our approach extracts coherent and 
meaningful topics.
Furthermore, we successfully demonstrate the generalisability of our approach on a pure text review dataset.


Overview of this repository:

- src:
      This folder contains all the python source code for the study,
      use the requirements file to download all necessary libraries.

- data:
    This folder includes the training data set (including the labels) of MuSe - CaR 
    as well as the CitySearch Car Review data set (training and test set) from 
    ([http://www.cs.cmu.edu/~mehrbod/RR/][http://www.cs.cmu.edu/~mehrbod/RR/]). 
    All existing pre-calculated models are in this folder.
  

Executing Instructions:

This can be run from main.ipynp file. The daatset name has to be set and everything else has to be executed.
