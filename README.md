# Awesome Buryat NLP
A list of resources and tools for Buryat language

## Pretrained models

| Model | Author/Org | Size/Specs | Description |
| :--- | :--- | :--- | :--- |
| [Buryat mGPT 1.3B](https://huggingface.co/ai-forever/mGPT-1.3B-buryat) | **AI Forever (Sber AI)** | **1.3B parameters** | Language model for Buryat trained on wikipedia (fine-tuned mGPT-XL) |
| [LaBSE](https://huggingface.co/lingtrain/labse-buryat) | **Lingtrain** | **768-dim embeddings** | Sentence-transformers model for mapping sentences to vector space |
| [Bert](https://huggingface.co/AdapterHub/bert-base-multilingual-cased_bxr_wiki_pfeiffer) | **AdapterHub (Jonas Pfeiffer)** | **Adapter** | Adapter for `bert-base-multilingual-cased`, trained on bxr/wiki |
| [mBart](https://huggingface.co/SaranaAbidueva/mbart50_bxr_ru_v1) | **Sarana Abidueva** | **~600M parameters** | Fine-tuned `mbart-large-50` for Buryat-Russian translation |
| [burvec](https://github.com/vaskonov/burvec) | **V.P. Konovalov, Z.B. Tumunbayarova** | **50/100/500-dim** | Word embeddings (Word2Vec/GloVe/FastText) trained on small corpora |
| [Stanford NLP](https://stanfordnlp.github.io/stanfordnlp/models.html) | **StanfordNLP Group** | **Pipeline** | Official support for Buryat (`bxr`) in Stanza pipeline (Tokenization, POS, Lemmatization) |
| [Wav2Vec](https://huggingface.co/kibaraki/wav2vec2-large-xlsr-53-shinekhen-buryat) | **kibaraki** | **~300M parameters** | ASR model based on `wav2vec2-large-xlsr-53`, trained on Shinekhen dialect |

## Datasets

| Dataset | Author/Org | Size/Stats |
| :--- | :--- | :--- |
| [Universal Dependencies](https://github.com/UniversalDependencies/UD_Buryat-BDT) | **UD Contributors (E. Skribnik et al.)** | **927 sentences, ~10k tokens** (Treebank `bxr_bdt`) |
| [Buryat monocorpus](https://huggingface.co/datasets/SaranaAbidueva/buryat_monocorpus) | **Sarana Abidueva** | **Monolingual text collection** |
| [Buryat-russian corpus](https://huggingface.co/datasets/SaranaAbidueva/buryat-russian_parallel_corpus) | **S. Abidueva, D. Baturova (2023)** | **41k pairs** (19.4k sentences + 20k word pairs) |
| [Buryat-russian corpus 2](https://huggingface.co/datasets/lingtrain/buryat-russian) | **Lingtrain** | **1,332 sentence pairs** (Parallel corpus) |

## Dictionaries

- [Burlang](https://burlang.ru/) (**Burlang Team**) — Electronic dictionary and learning platform.

## Online resources

- [Buryat national corpus](https://buryat.web-corpora.net) (**IMBT SO RAN**, L.D. Badmaeva et al.) — **~3 million tokens**. Includes morphological annotation (85% coverage).
- [Wikipedia](https://bxr.wikipedia.org/wiki) (**Community**) — **2900+ articles**. Buryat wikipedia.
