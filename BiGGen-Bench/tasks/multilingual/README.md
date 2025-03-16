7 tasks related to assessing the Multilingual capabilities of LLMs.

We only consider scenarios of generating the output on the target language. Specifically, we consider 5 languages: Chinese, Korean, Indonesian, Bengali, and Swahili. If the output is in English, we consider giving it a low score (refer to accidental translation [here](https://arxiv.org/abs/2010.11934)).

We plan to hire professional translators laterwards, so during the annotation period, please write the input and output in the target language by utilizing GPT-4.

Yet, it would be essential to check whether the phrases, cultural aspects you're trying to test is valid (this is more knowledge related work).

Name | Description | Data Annotator (Group A) | Data Reviewer (Group A) | Data Annotator (Group B) | Related paper 
---- | ----------- | -------------------- | -------------------- | --------------- | --------------- |
[poem_writing](poem_writing/) | Tasks that test if the language model could fluently write a poem using the target language (e.g., Haiku) | Jinkyung Jo | Dongkeun Yoon, Seungone Kim | ? | [link](https://arxiv.org/abs/2205.12393) [link2](https://arxiv.org/abs/1906.08733) |
[humor_understanding](humor_understanding/) | Tasks that test whether the model could generate a joke written in the target language. | Jinkyung Jo | Dongkeun Yoon, Seungone Kim | ? | [link](https://arxiv.org/abs/2312.02439) |
[historical_text_comprehension](historical_text_comprehension/) | Tasks that require comprehend about a historical text written in a target language and explain about it. | Jinkyung Jo | Dongkeun Yoon, Seungone Kim | ? | [link](https://arxiv.org/abs/2309.04766) |
[cultural_awareness](cultural_awareness/) | Tasks that require to understand the culture of the country that uses the target language | Jinkyung Jo | Dongkeun Yoon, Seungone Kim | ? | [link1](https://arxiv.org/abs/2311.01012) [link2](https://arxiv.org/abs/2307.01370)
[multilingual_reasoning](multilingual_reasoning/) | Tasks require to reason with another language except English | Dongkeun Yoon | Seongyoon Lee, Yoonjoo Lee | ? | [link](https://arxiv.org/abs/2210.03057) |
[robust_translation](robust_translation/) | Tasks that examine whether the translation is natural enough for a native speaker of the target language to comprehend. Instead of a simple sentence, the input sentence should require an understanding of the culture or semantics of the target language (and the country that uses that language). | Dongkeun Yoon | Seongyoon Lee, Yoonjoo Lee | ? | [link1](https://arxiv.org/abs/2305.04118) [link2](https://arxiv.org/abs/2311.02851) |
[global_opinions](global_opinions/) | Tasks that test the biases of models in terms of understanding the political viewpoints and values across different countries | Dongkeun Yoon | Seongyoon Lee, Yoonjoo Lee | ? | [link](https://arxiv.org/abs/2306.16388)