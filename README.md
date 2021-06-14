# NLP with Transformers
This repository contains implementation of various NLP tasks using the vanilla Transformers.

1)  Text Summarization

For this a simple Transformer was used as mentioned above. The main idea was to input a article and get a summary in return. Since the architechture in itself is simple and the model used as a smaller one compared to the original transformer model it doesn't provide good results, but it works as a proof of concept. 
Below you can see the model performing well on this piece of text:
<img src="/results/summary1.png"></img>

However there are many cases where the modle fails. Below is an example of one:

<img src="/results/summary2.png"></img>


2) Machine Translation

Here I have tried to implement a simple translation model from english to hindi. Despite the huge differences in these languages the model actually managed to learn some relations and give somewhat good results. 

Below are two translations made by the model. While the first sentence was part of the dataset, the second sentecne was typed by me and the model still does a somewhat job despite being a simple baseline model.

<img src="/results/translate1.png"></img>
