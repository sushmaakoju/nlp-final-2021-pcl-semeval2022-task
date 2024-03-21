# nlp-final-2021-pcl-semeval2022-task

## NLP Fall 2021, CU Boulder Final project, December 2021 - SemEval 2022 PCL Task 4 

## Acknowledgements
We are thankful for the Prof. James H. Martin's lectures during Natural Language Processing course, University of Colorado Boulder.

### References: 

1. <a href="https://sites.google.com/view/pcl-detection-semeval2022/">SemEval 2022 Patronizing and Condescending Language Detection (PCL) Task 4</a>
2. <a href="https://github.com/Perez-AlmendrosC/dontpatronizeme">dontpatronizeme Dataset : Patronizing and Condescending Language Detection</a>

We are a team of 2: Sushma Akoju and Waad Alharthi. Each of us explored broadly among most approaches as discussed in homework. We attempt each of following approaches and conducted training and predictions for NER task: 

#### Sushma Akoju

 - Using pre-trained RoBERTa to finetune and classify **binary PCL** (HuggingFace) - **Sushma Akoju**
 - Using pre-trained SpanBERT, KeyBERT to finetune and classify **multi-label PCL** (Huggingface) -  **Sushma Akoju**
 - Determining words that contribute towards PCL and adding extra features and adding probability of agreement/disagreement for sampling with 10% shuffling between the two and used this as a feature. And explored other Custom Named Entity extraction approches for PCL words and worked out the
   classification (just by taking max number of PCL entities in a test sentence). (using SpaCY ) - **Sushma Akoju**
- Pairwise keyword influences were also explored but did not create a pipeline that would use this.
   
#### Waad Alharthi

 - Using pre-trained BERT to finetune and classify **binary** and **multi-label classification** PCL (HuggingFace) - **Waad Alharthi**
 - Using pre-trained BERT to finetune and classify **multi-label classification** PCL (HuggingFace) - **Waad Alharthi**

**SU**shma **A**koju (username: **sua**) - scores ranked 1 and **Waad** Alharthi (username: **Waad**) scores ranked 5 @ SemEval PCL task Round 1, Dec 2021.

![semeval-ranked-top-1](https://github.com/sushmaakoju/nlp-final-2021-pcl-semeval2022-task/assets/8979477/60caa229-23fd-4e9f-9985-6ab47ed8502b)

Note: We did not participate in the second round of SemEval 2022 due to my injury and other natural calamities.
