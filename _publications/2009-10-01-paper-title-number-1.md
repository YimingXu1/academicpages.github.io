---
title: "Fine-Grained Label Learning via Siamese Network for Cross-modal Information Retrieval"
collection: publications
permalink: /publication/FG-CMIR
author: '**Yiming Xu**, Jing Yu, Jingjing Guo, Yue Hu, and Jianlong Tan'
excerpt: 'This paper is about Hard Examples Mining of Cross-modal Information Retrieval'

date: 2019-06-13
venue: 'ICCS'

paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-22741-8_22'

---
Cross-modal information retrieval aims to search for semantically relevant data from various modalities when given a query from one modality. For text-image retrieval, a common solution is to map texts and images into a common semantic space and measure their similarity directly. Both the positive and negative examples are used for common semantic space learning. Existing work treats the positive/negative text-image pairs as equally positive/negative. However, we observe that many positive examples resemble the negative ones in some degrees and vice versa. These “hard examples” are challenging for existing models. 

In this paper, we aim to assign fine-grained labels for the examples to capture the degrees of “hardness”, thus enhancing cross-modal correlation learning. Specifically, we propose a siamese network on both the positive and negative examples to obtain their semantic similarities. For each positive/negative example, we use the text description of the image in the example to calculate its similarity with the text in the example. Based on these similarities, we assign fine-grained labels to both the positives and negatives and introduce these labels to a pairwise similarity loss function. The loss function benefits from the labels to increase the influence of hard examples on the similarity learning while maximizing the similarity of relevant text-image pairs and minimizing the similarity of irrelevant pairs. We conduct extensive experiments on the English Wikipedia, Chinese Wikipedia, and TVGraz datasets. Compared with state-of-the-art models, our model achieves significant improvement on the retrieval performance by incorporating with fine-grained labels.

[Download paper here](https://link.springer.com/chapter/10.1007/978-3-030-22741-8_22)

**Xu Y.**, Yu J., Guo J., Hu Y., Tan J. (2019) Fine-Grained Label Learning via Siamese Network for Cross-modal Information Retrieval. In: Rodrigues J. et al. (eds) Computational Science – ICCS 2019. ICCS 2019. Lecture Notes in Computer Science, vol 11537. Springer, Cham.
