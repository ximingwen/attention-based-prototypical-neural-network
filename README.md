# attention-based-prototypical-neural-network

## base-paper:

1. << Interactively Providing Explanations for Transformer Language Models>>  
code available at https://github.com/felifri/XAITransformer

2. << ProtoTEx: Explaining Model Decisions with Prototype Tensors >>    
code available at https://github.com/anubrata/ProtoTEx

3. << ProtoAttend: Attention-Based Prototypical Learning >>     (attention)  
code available at https://github.com/google-research/google-research/blob/master/protoattend/README.md

4. << Concept Bottleneck Models >>  
code available at https://github.com/yewsiang/ConceptBottleneck

5. << Interpretable-by-Design Text Classification with Iteratively Generated Concept Bottleneck >>   (CBM+LLM)  

6. << Language in a Bottle: Language Model Guided Concept Bottlenecks for Interpretable Image Classification >>   (CMB+LLM)  



论文1，2是一种原型网络， 论文3给加了attention（另一种原型网络结构）, 论文5、6是在论文4的基础上加了LLM, 或许可以借鉴论文3加attention的方式， 或者5、6用LLMaugment的方式改进1、2, 供参考。  
数据集参考论文1：  
Yelp：https://www.yelp.com/dataset   
Movie: https://www.cs.cornell.edu/people/pabo/movie-review-data/  
Toxicity https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge  

