This repo contains the following work related to the assignment given by SaiDL.

1) CoreML

2) State Space Models

I have attached ipynb files and Latex documentation for both of them . However I will covering brief details about some of my observations.

---------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------

1)CoreML
This project involved the implementation of APL frameworks to check robustness in case of noisy datasets.I was aware of losses but didn't know their classifications, such as active and passive loss. So, I familiarised myself with all the mentioned losses. After reviewing the paper, I realized why this framework is being tested. It helps us find a middle ground between both types of losses so that we don't overshoot by using just one of them.

I prepared the dataset accordingly for symmetrical and asymmetrical noise. Initially i expected better performance on asymmetrical data as in these the changes we made for any class was fixed so it was deterministic. However, I realised that not to be the case,I tried to dig deeper into it; what I found was symmetric noise is easier to handle due to uniformity; asymmetric noise poses more significant challenges due to structured bias and class imbalance. However, I am still not entirely sure or convinced why this is the case.

2)SSM
Unlike the CoreML project, I had never heard of SSM before . So initially, I went through various blogs to understand what they are (maths was daunting; I tried to get the intuition behind most maths used in the paper). I was going through an Updated version of CS231n by Umichigan(taught by the same instructor).
I covered the Attention mechanism behind Transformers to get a broad idea. Then, I referred to blogs by the Author and Annotated the S4 paper.These two provided a sufficient understanding of SSM.
For the training part, I couldn't replicate the paper's results. The number of layers I used, Epochs,and other parameters were pretty less compared to that in the paper, but I still trained it various times with varying parameters to have Proof of Work.
