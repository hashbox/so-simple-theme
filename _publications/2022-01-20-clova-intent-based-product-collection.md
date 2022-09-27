---
collection: publications
title: "Intent-based Product Collections for E-commerce using Pretrained Language Models"
authors: "Hiun Kim, Jisu Jeong, Kyung-Min Kim, Dongjun Lee, Hyun Dong Lee, Dongpil Seo, <U>Jeeseung Han</U>, Dong Wook Park, Ji Ae Heo, Rak Yeong Kim"
publication: "2021 International Conference on Data Mining Workshops (ICDMW)"
keywords: "Product Collections, E-Commerce, Pretrained Language Models"
year: January, 2022
link: "https://ieeexplore.ieee.org/abstract/document/9679879"
---

| **Authors**           | {{page.authors}}      |
| **Year**              | {{page.year}}         |
| **Keywords**          | {{page.keywords}}     |
| **Publication**       | {{page.publication}}  |
| **Link**              | [Link]({{page.link}}) |

# Abstract
Building a shopping product collection has been primarily a human job. With the manual efforts of craftsmanship, experts collect related but diverse products with common shopping intent that are effective when displayed together, e.g., backpacks, laptop bags, and messenger bags for freshman bag gifts. Automatically constructing a collection requires an ML system to learn a complex relationship between the customer’s intent and the product’s attributes. However, there have been challenging points, such as 1) long and complicated intent sentences, 2) rich and diverse product attributes, and 3) a huge semantic gap between them, making the problem difficult. In this paper, we use a pretrained language model (PLM) that leverages textual attributes of web-scale products to make intent-based product collections. Specifically, we train a BERT with triplet loss by setting an intent sentence to an anchor and corresponding products to positive examples. Also, we improve the performance of the model by search-based negative sampling and category-wise positive pair augmentation. Our model significantly outperforms the search-based baseline model for intent-based product matching in offline evaluations. Furthermore, online experimental results on our e-commerce platform show that the PLM-based method can construct collections of products with increased CTR, CVR, and order-diversity compared to expert-crafted collections.
