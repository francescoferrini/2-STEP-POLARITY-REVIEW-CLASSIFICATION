# 2-STEP POLARITY REVIEW CLASSIFICATION

Implementation of poalarity classification of review using a 2 step approach:
1) Firstly all objective classified sentences are deleted since I assumed they don't contribute to the polarity classification
2) Then polarity classification is applied using different approaches

## Model pipeline
<img width="813" alt="Model_pipeline" src="https://user-images.githubusercontent.com/51090995/141203041-b72a97a1-0094-4355-9e00-1567f1d21588.png">

## Dataset
### Subjectivity extraction
For subjectivity extraction I used subjectivity dataset from Cornell University
Citation info:
```
This data was first used in Bo Pang and Lillian Lee,
A Sentimental Education: Sentiment Analysis Using Subjectivity Summarization 
Based on Minimum Cuts'', Proceedings of the ACL, 2004.

@InProceedings{Pang+Lee:04a,
  author =       {Bo Pang and Lillian Lee},
  title =        {A Sentimental Education: Sentiment Analysis Using Subjectivity Summarization Based on Minimum Cuts},
  booktitle =    "Proceedings of the ACL",
  year =         2004
}
```
### Polarity classification
For polarity classification I used movie dataset from nltk


