# GPT-2-Refined
This is a personal research project building a similar LLM like ChatGPT, based on the GPT-2 paper and the lecture videos from Andrej Karpathy.

I basically start from an empty file and work my way to a reproduction of the GPT-2 (124M) model. While the GPT-2 (124M) model probably trained for quite some time back in the day (2019, ~5 years ago), today, reproducing it is a matter of approx ~1hr and ~$10 but you will need a cloud GPU box.

GPT-2 is a simple language model, trained on internet documents, and all they do is "dream" internet documents. So this repo does not cover Chat finetuning, and you can't talk to it like you can talk to ChatGPT.

## Dataset and Evaluation

This model trains on the Fine Web dataset which does not contain the same amount of data that the GPT-2 contains since it ignores code and mathematical problems.

On the HellaSwag evaluation the model actually performs better than the GPT-2 model itself and comes close to the GPT-3 model of OpenAI.

## Supplementary Links

OpenAI GPT-2 paper: https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf

OpenAI GPT-3 paper: https://arxiv.org/abs/2005.14165

Andrej Karpathy Lecture: https://youtu.be/l8pRSuU81PU?si=al_fqqQDxW7f4QUL


