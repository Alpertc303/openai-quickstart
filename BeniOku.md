# OpenAI Çabuk Başlangıç

<p align="center">
    <br> Türkçe | <a href="README-CN.md">中文</a>
</p>


Bu proje, büyük dil modelleri ve bunların Yapay Zeka Yönetim ve Kontrol (AIGC) senaryolarındaki uygulamalarıyla ilgilenen herkes için tek duraklı bir öğrenme kaynağı olarak tasarlanmıştır. Bu proje, teorik temeller, geliştirme temelleri ve uygulamalı örnekler sağlayarak bu en son konularda kapsamlı rehberlik sunar.

## Özellikler

- **Büyük Dil Modellerinin Teorik ve Gelişim Temelleri**: Mimarileri, eğitim yöntemleri, uygulamaları ve daha fazlası dahil olmak üzere GPT-4 gibi büyük dil modellerinin iç işleyişine derinlemesine dalın.

- **LangChain ile AIGC Uygulama Geliştirme**: Büyük dil modellerinin pratik uygulamasını gösteren AIGC uygulamaları geliştirmek için LangChain kullanan uygulamalı örnekler ve öğreticiler.

## Başlarken
Bu depoyu yerel makinenize klonlayarak başlayabilirsiniz:

```shell
git clone https://github.com/DjangoPeng/openai-quickstart.git
```

Ardından dizine gidin ve başlamak için ayrı ayrı modül talimatlarını izleyin.
## Takvim

| Tarih       | Tarif (Açıklama)                                                                                                                                                                                                        | Kurs Materyaller                                                                          | Etkinlikler                                                                    |
|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Wed Jul 12 **Hafta 1** | Fundamentals of Large Models: Evolution of Theory and Technology <br/> - An Initial Exploration of Large Models: Origin and Development <br/> - Warm-up: Decoding Attention Mechanism <br/> - Milestone of Transformation: The Rise of Transformer <br/> - Taking Different Paths: The Choices of GPT and Bert | Suggested Readings:<br/>- [Attention Mechanism: Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)<br/>- [An Attentive Survey of Attention Models](https://arxiv.org/abs/1904.02874)<br/>- [Transformer: Attention is All you Need](https://arxiv.org/abs/1706.03762)<br/>- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805) | [[Homework](docs/homework_01.md)] |
| Sun Jul 16 | The GPT Model Family: From Start to Present <br/> - From GPT-1 to GPT-3.5: The Evolution <br/> - ChatGPT: Where It Wins <br/> - GPT-4: A New Beginning <br/>Prompt Learning <br/> - Chain-of-Thought (CoT): The Pioneering Work <br/> - Self-Consistency: Multi-path Reasoning <br/> - Tree-of-Thoughts (ToT): Continuing the Story | Suggested Readings:<br/>- [GPT-1: Improving Language Understanding by Generative Pre-training](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)<br/>- [GPT-2: Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)<br/>- [GPT-3: Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)<br/><br/><br/>Additional Readings:<br/>- [GPT-4: Architecture, Infrastructure, Training Dataset, Costs, Vision, MoE](https://www.semianalysis.com/p/gpt-4-architecture-infrastructure)<br/>- [GPTs are GPTs: An Early Look at the Labor Market Impact Potential of Large Language Models](https://arxiv.org/abs/2303.10130)<br/>- [Sparks of Artificial General Intelligence: Early experiments with GPT-4](https://arxiv.org/abs/2303.12712)<br/><br/> | [[Homework](docs/homework_02.md)] |
| Wed Jul 19 **Week 2** | Fundamentals of Large Model Development: OpenAI Embedding <br/> - The Eve of General Artificial Intelligence <br/> - "Three Worlds" and "Turing Test" <br/> - Computer Data Representation <br/> - Representation Learning and Embedding <br/> Embeddings Dev 101 <br/> - Course Project: GitHub openai-quickstart <br/> - Getting Started with OpenAI Embeddings                      | Suggested Readings:<br/>- [Representation Learning: A Review and New Perspectives](https://arxiv.org/abs/1206.5538)<br/>- [Word2Vec: Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781)<br/>- [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/pubs/glove.pdf)<br/><br/>Additional Readings:<br/><br/>- [Improving Distributional Similarity with Lessons Learned from Word Embeddings](http://www.aclweb.org/anthology/Q15-1016)<br/>- [Evaluation methods for unsupervised word embeddings](http://www.aclweb.org/anthology/D15-1036) | [[Homework](docs/homework_03.md)]<br/>Code:<br/>[[embedding](openai_api/embedding.ipynb)] |
| Sun Jul 23 | OpenAI Large Model Development and Application Practice <br/> - OpenAI Large Model Development Guide <br/> - Overview of OpenAI Language Models <br/> - OpenAI GPT-4, GPT-3.5, GPT-3, Moderation <br/> - OpenAI Token Billing and Calculation <br/>OpenAI API Introduction and Practice <br/> - OpenAI Models API <br/> - OpenAI Completions API  <br/> - OpenAI Chat Completions API <br/> - Completions vs Chat Completions <br/>OpenAI Large Model Application Practice <br/> - Initial Exploration of Text Completion <br/> - Initial Exploration of Chatbots | Suggested Readings:<br/><br/>- [OpenAI Models](https://platform.openai.com/docs/models)<br/>- [OpenAI Completions API](https://platform.openai.com/docs/guides/gpt/completions-api)<br/>- [OpenAI Chat Completions API](https://platform.openai.com/docs/guides/gpt/chat-completions-api) | Code:<br/>[[models](openai_api/models.ipynb)] <br/>[[tiktoken](openai_api/count_tokens_with_tiktoken.ipynb)] |
| Wed Jul 26 **Week 3** | Best Practices for Applying Large AI Models <br/> - How to Improve the Efficiency and Quality of GPT Model Use <br/> - Best Practices for Applying Large AI Models <br/>   - Text Creation and Generation<br/>   - Article Abstract and Summary <br/>    - Novel Generation and Content Supervision <br/>    - Executing Complex Tasks Step by Step <br/>    - Evaluating the Quality of Model Output <br/>    - Constructing Training Annotation Data <br/>    - Code Debugging Assistant <br/> - New Features： Function Calling Introduction and Practical Application | Suggested Readings <br/> - [GPT Best Practices](https://platform.openai.com/docs/guides/gpt-best-practices) <br/> - [Function Calling](https://platform.openai.com/docs/guides/gpt/function-calling) | Code： <br/> [Function Calling](openai_api/function_call.ipynb) |
| Sun Jul 30 | Practical: OpenAI-Translator <br/> - Market demand analysis for OpenAI-Translator <br/> - Product definition and feature planning for OpenAI-Translator <br/> - Technical solutions and architecture design for OpenAI-Translator <br/> - OpenAI module design <br/> - OpenAI-Translator practical application <br/> | | Code: <br/> [pdfplumber](openai_translator/pdfplumber.ipynb) |


## Katkıda Bulunmak

Katkılar, açık kaynak topluluğunu; öğrenmek, yaratmak ve ilham vermek için harika bir yer yapan şeylerdir. Herhangi yaptığınız bir katkı gerçekten takdir edilir. Herhangi bir öneriniz veya özellik isteğiniz varsa, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açın.

<a href='https://github.com/repo-reviews/repo-reviews.github.io/blob/main/create.md' target="_blank"><img alt='Github' src='https://img.shields.io/badge/review_me-100000?style=flat&logo=Github&logoColor=white&labelColor=888888&color=555555'/></a>

## Lisans

This project is licensed under the terms of the Apache-2.0 License . See the [LICENSE](LICENSE) file for details.

## İletişime Geç

Django Peng - pjt73651@email.com

Proje Linki: https://github.com/DjangoPeng/openai-quickstart
