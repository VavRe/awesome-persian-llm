# Awesome Persian LLM [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for Large Language Models (LLMs) focused on Persian (Farsi) language, including papers, models, datasets, evaluations, leaderboards, platforms, and tools.

Persian (Farsi) is spoken by over 100 million people worldwide, primarily in Iran, Afghanistan, and Tajikistan. This repository aims to gather all relevant resources for developing and researching LLMs for the Persian language.

## Contents

- [Papers](#papers)
- [Models](#models)
- [Datasets](#datasets)
- [Evaluations](#evaluations)
- [Leaderboards](#leaderboards)
- [Platforms](#platforms)
- [Tools](#tools)
- [Contributing](#contributing)
- [License](#license)

## Papers

### Language Models
- [ParsBERT: Transformer-based Model for Persian Language Understanding](https://arxiv.org/abs/2005.12515) - First BERT-based model specifically pre-trained on Persian corpora
- [PersianGPT: GPT-2 for Persian Language](https://github.com/hooshvare/parsbert) - GPT-2 adaptation for Persian text generation
- [mBERT and Multilingual Models](https://arxiv.org/abs/1810.04805) - BERT's multilingual model including Persian
- [XLM-RoBERTa](https://arxiv.org/abs/1911.02116) - Cross-lingual pre-trained model supporting Persian

### Persian NLP Research
- [Persian Text Processing](https://aclanthology.org/) - Various papers on Persian language processing
- [Neural Machine Translation for Persian](https://arxiv.org/abs/1809.00157) - NMT approaches for Persian
- [Persian Named Entity Recognition](https://arxiv.org/abs/2003.09811) - NER techniques for Persian text

### Multilingual LLMs Including Persian
- [BLOOM: A 176B-Parameter Open-Access Multilingual Language Model](https://arxiv.org/abs/2211.05100) - Large multilingual model including Persian
- [Aya Model: An Open-Access Multilingual LLM](https://arxiv.org/abs/2402.07827) - Massively multilingual instruction-tuned model with Persian support
- [mT5: Massively Multilingual Text-to-Text Transformer](https://arxiv.org/abs/2010.11934) - Multilingual T5 including Persian

## Models

### Persian-Specific Models
- [ParsBERT](https://github.com/hooshvare/parsbert) - BERT model pre-trained on Persian corpora (148M parameters)
- [PersianGPT](https://github.com/hooshvare/parsbert) - GPT-2 model for Persian text generation
- [ParsiNLU Models](https://github.com/persiannlp/parsinlu) - Models trained on ParsiNLU benchmark
- [Persian BERT by HooshvareLab](https://huggingface.co/HooshvareLab/bert-fa-base-uncased) - Base Persian BERT model
- [Persian RoBERTa](https://huggingface.co/HooshvareLab/roberta-fa-base) - RoBERTa for Persian

### Multilingual Models with Persian Support
- [mBERT](https://huggingface.co/bert-base-multilingual-cased) - Multilingual BERT including Persian
- [XLM-RoBERTa](https://huggingface.co/xlm-roberta-base) - Cross-lingual RoBERTa supporting 100+ languages
- [mT5](https://huggingface.co/google/mt5-base) - Multilingual T5 model
- [BLOOM](https://huggingface.co/bigscience/bloom) - 176B parameter multilingual model
- [Aya-101](https://huggingface.co/CohereForAI/aya-101) - Massively multilingual generative LLM covering 101 languages including Persian
- [Aya-23](https://huggingface.co/CohereForAI/aya-23-8B) - Improved multilingual model with enhanced Persian support
- [GPT-3.5-turbo](https://platform.openai.com/docs/models) - OpenAI's model with Persian capabilities
- [GPT-4](https://openai.com/gpt-4) - Advanced model with strong Persian understanding
- [Claude](https://www.anthropic.com/claude) - Anthropic's model supporting Persian
- [Gemini](https://deepmind.google/technologies/gemini/) - Google's multilingual model including Persian

### Fine-tuned Persian Models
- [Persian Question Answering Models](https://huggingface.co/models?language=fa&pipeline_tag=question-answering) - QA models for Persian
- [Persian Sentiment Analysis Models](https://huggingface.co/models?language=fa&pipeline_tag=text-classification) - Sentiment classifiers
- [Persian NER Models](https://huggingface.co/models?language=fa&pipeline_tag=token-classification) - Named Entity Recognition

## Datasets

### Pre-training Corpora
- [Persian Wikipedia Dump](https://dumps.wikimedia.org/fawiki/) - Complete Persian Wikipedia corpus
- [CC100-Persian](http://data.statmt.org/cc-100/) - Persian subset of Common Crawl
- [OSCAR-Persian](https://oscar-corpus.com/) - Large Persian web corpus
- [mC4-Persian](https://huggingface.co/datasets/mc4) - Multilingual C4 Persian subset
- [Persian Pile](https://github.com/persiannlp/persian-pile) - Curated collection of Persian texts

### Instruction/Chat Datasets
- [ParsiNLU](https://github.com/persiannlp/parsinlu) - Persian reading comprehension and NLU benchmark
- [Persian Alpaca](https://huggingface.co/datasets/hosseinkz/persian-alpaca) - Persian instruction-following dataset
- [Aya Dataset](https://huggingface.co/datasets/CohereForAI/aya_dataset) - Multilingual instruction dataset including Persian
- [Persian ChatGPT Instructions](https://github.com/persian-llm/persian-instructions) - Collection of Persian instructions

### Task-Specific Datasets
- [PersianNER](https://github.com/HaniehP/PersianNER) - Named Entity Recognition dataset
- [Persian Sentiment Analysis](https://github.com/hooshvare/persian-sentiment-analysis) - Sentiment classification datasets
- [PerSent](https://github.com/phosseini/PerSent) - Persian sentiment corpus
- [Digikala User Reviews](https://github.com/hooshvare/digikala-sentiment) - E-commerce review dataset
- [Persian News](https://huggingface.co/datasets/persian_news) - News article classification
- [Arman Persian NER](https://github.com/HaniehP/PersianNER) - Comprehensive NER corpus
- [PEYMA](https://github.com/persiannlp/peyma) - Persian paraphrase dataset
- [FarsTail](https://github.com/dml-qom/FarsTail) - Persian natural language inference

### Question Answering
- [Persian SQuAD](https://github.com/persiannlp/persian-squad) - Persian reading comprehension
- [PersianQA](https://github.com/sajjjadayobi/PersianQA) - Question answering dataset
- [ParsiNLU Reading Comprehension](https://github.com/persiannlp/parsinlu) - RC subset of ParsiNLU

### Translation
- [TEP: Tehran English-Persian Parallel Corpus](https://github.com/mirfan899/TEP) - Parallel corpus
- [Mizan English-Persian Corpus](https://github.com/omidkashefi/Mizan) - Literary translation corpus
- [OPUS Persian Corpora](https://opus.nlpl.eu/) - Various parallel corpora including Persian

## Evaluations

### Benchmarks
- [ParsiNLU](https://github.com/persiannlp/parsinlu) - Comprehensive Persian NLU benchmark with multiple tasks
  - Reading comprehension
  - Multiple choice QA
  - Entailment
  - Sentiment analysis
- [FarsBench](https://github.com/persiannlp/farsbench) - Evaluation suite for Persian LLMs
- [Persian GLUE](https://github.com/persian-glue) - Collection of Persian NLU tasks

### Evaluation Metrics
- [PersianBLEU](https://github.com/persian-nlp/persian-bleu) - BLEU metric for Persian text
- [Persian ROUGE](https://github.com/persian-nlp/persian-rouge) - ROUGE implementation for Persian
- [ParsBERT Evaluation Tools](https://github.com/hooshvare/parsbert#evaluation) - Evaluation utilities

### Human Evaluation
- [Persian LLM Arena](https://github.com/persian-llm/arena) - Human preference evaluation platform
- [Chatbot Arena Persian](https://chat.lmsys.org/) - Multilingual chatbot comparison including Persian

## Leaderboards

### Persian-Specific Leaderboards
- [ParsiNLU Leaderboard](https://github.com/persiannlp/parsinlu#leaderboard) - Performance on ParsiNLU benchmark tasks
- [Persian NER Leaderboard](https://paperswithcode.com/dataset/arman) - NER task performance
- [Persian Sentiment Analysis Leaderboard](https://paperswithcode.com/task/sentiment-analysis/latest?lang=persian) - Sentiment classification results

### Multilingual Leaderboards Including Persian
- [XTREME Leaderboard](https://sites.research.google/xtreme) - Cross-lingual understanding benchmark
- [FLORES Leaderboard](https://github.com/facebookresearch/flores) - Machine translation including Persian
- [MASSIVE Leaderboard](https://github.com/alexa/massive) - Multilingual NLU including Persian
- [Chatbot Arena](https://chat.lmsys.org/leaderboard) - LLM performance comparison with Persian support

### Papers with Code
- [Persian NLP Tasks](https://paperswithcode.com/language/persian) - Various Persian NLP leaderboards

## Platforms

### Cloud AI Platforms
- [Google Cloud AI](https://cloud.google.com/ai) - Supports Persian via Gemini and translation APIs
- [Azure AI](https://azure.microsoft.com/en-us/products/ai-services) - Persian language support in Cognitive Services
- [AWS AI Services](https://aws.amazon.com/machine-learning/) - Persian support in Comprehend and Translate
- [Hugging Face](https://huggingface.co/) - Host and deploy Persian models

### Persian-Focused Platforms
- [HooshvareLab](https://hooshvare.com/) - Persian NLP and AI research lab
- [Roshan AI](https://roshan.ai/) - Persian conversational AI platform
- [ParsiAI](https://parsiai.com/) - Persian AI solutions
- [DigiKala AI](https://digikala.com/) - E-commerce AI with Persian NLP

### Research Platforms
- [Persian NLP Group](https://github.com/persiannlp) - Open-source Persian NLP resources
- [Dadmatools](https://github.com/Dadmatech/dadmatools) - Persian language processing toolkit

### API Services
- [ParsBERT API](https://github.com/hooshvare/parsbert-api) - REST API for Persian BERT
- [Persian NLP APIs](https://github.com/persian-nlp) - Collection of Persian NLP services
- [OpenAI API](https://platform.openai.com/) - GPT models with Persian support
- [Cohere API](https://cohere.com/) - Aya models with Persian capabilities

## Tools

### Text Processing
- [Hazm](https://github.com/sobhe/hazm) - Python library for Persian text processing
  - Tokenization, stemming, lemmatization
  - POS tagging, dependency parsing
  - Normalization and spell checking
- [Parsivar](https://github.com/ICTRC/Parsivar) - Persian text processing toolkit
- [PolyGlot](https://github.com/aboSamoor/polyglot) - Multilingual NLP toolkit with Persian support
- [PersianStemmer](https://github.com/persian-tools/persian-stemmer) - Persian stemming library

### Tokenizers
- [SentencePiece](https://github.com/google/sentencepiece) - Unsupervised tokenizer supporting Persian
- [Byte-Pair Encoding (BPE)](https://github.com/rsennrich/subword-nmt) - Subword tokenization
- [Persian Tokenizer](https://github.com/persian-nlp/persian-tokenizer) - Rule-based Persian tokenizer

### Frameworks and Libraries
- [Transformers](https://github.com/huggingface/transformers) - State-of-the-art NLP models including Persian
- [Dadmatools](https://github.com/Dadmatech/dadmatools) - Complete Persian NLP pipeline
- [Persian NLP](https://github.com/persian-nlp) - Collection of Persian NLP tools
- [vLLM](https://github.com/vllm-project/vllm) - Fast LLM inference supporting Persian models

### Training Tools
- [DeepSpeed](https://github.com/microsoft/DeepSpeed) - Distributed training optimization
- [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) - Large-scale language model training
- [Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) - Fine-tuning toolkit for LLMs
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - Easy LLM fine-tuning with Persian support

### Annotation Tools
- [Label Studio](https://github.com/heartexlabs/label-studio) - Data labeling platform with Persian support
- [Doccano](https://github.com/doccano/doccano) - Open-source text annotation tool
- [BRAT](https://brat.nlplab.org/) - Annotation tool for NLP tasks

### Evaluation Tools
- [LMQL](https://github.com/eth-sri/lmql) - Query language for LLMs
- [LangChain](https://github.com/langchain-ai/langchain) - Building applications with LLMs
- [PromptBench](https://github.com/microsoft/promptbench) - LLM evaluation framework

### Benchmarking
- [EleutherAI LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) - LLM evaluation framework
- [BIG-bench](https://github.com/google/BIG-bench) - Benchmark for LLMs
- [HELM](https://github.com/stanford-crfm/helm) - Holistic evaluation of language models

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To contribute:
1. Fork this repository
2. Add your resource in the appropriate section
3. Ensure the resource is relevant to Persian LLM
4. Follow the existing format
5. Submit a pull request

### Guidelines
- Resources should be specifically relevant to Persian/Farsi language or have significant Persian support
- Add one resource per pull request
- Use the following format: `[Name](link) - Description`
- Check your spelling and grammar
- Ensure links are working
- Add resources in alphabetical order within sections

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
