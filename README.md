# Abstract

Facial expression recognition is a challenging task in the domain of deep learning. Ensuring good performance is the cornerstone of the research problem related to transfer learning and domain adaptation. In the facial expression recognition task, a well-performing deep neural network model trained on one dataset (source domain) typically underperforms when subjected to a different but relevant dataset (target domain). This under-performance is the result of facial expression variation across different domains, even in the case of same expression. In our case, we have Western faces as source domain and Pakistani faces as target domain. Further problem arises in using Pakistani
faces is the lack of samples, and co-existence of different ethnicity in the region. In our approach, we used different approaches to address the problem of domain adaptation.
WGAN failed to produce expected results, whereas CycleGAN and feature-based domain adaptive models performed reasonably good on our data. We were able to get very close to the baseline results using domain adaptation approaches used and even got slightly better accuracy for VGG16 in one of the approach.


