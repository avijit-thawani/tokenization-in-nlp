<!-- SURVEY:START -->

# Tokenization in NLP

A living survey of tokenization in NLP

**51** in Core · updated 2026-09-12

## Core

The papers in this survey.

| # | [Paper](views/core-by-title.md) | Venue | [Year](views/core-by-year.md) | [Cited by](views/core-by-citations.md) | Score &#9660; |
| ---: | --- | --- | ---: | ---: | ---: |
| 1 | [Canine: Pre-training an Efficient Tokenization-Free Encoder for Language Representation](https://www.semanticscholar.org/paper/969287b8a96e242793b11f0dbb99ec341228106f)<br><sub>J. Clark et al.</sub><br><sub>Canine is presented, a neural encoder that operates directly on character sequences—without explicit tokenization or vocabulary—and a pre-training strategy that operates either directly on characters or optionally uses subwords as a soft inductive bias.</sub> | Transactions of the Association for Computational Linguistics | 2021 | 333 | 100 |
| 2 | [ByT5: Towards a Token-Free Future with Pre-trained Byte-to-Byte Models](https://www.semanticscholar.org/paper/44ef6cf919250001836ed73c0d58b20ea1e2d308)<br><sub>Linting Xue et al.</sub><br><sub>This paper shows that a standard Transformer architecture can be used with minimal modifications to process byte sequences, characterize the trade-offs in terms of parameter count, training FLOPs, and inference speed, and shows that byte-level models are competitive with their token-level counterparts.</sub> | Transactions of the Association for Computational Linguistics | 2021 | 765 | 87 |
| 3 | [Between words and characters: A Brief History of Open-Vocabulary Modeling and Tokenization in NLP](https://www.semanticscholar.org/paper/d617f51833860dc50d202af7f80be71304b2e994)<br><sub>Sabrina J. Mielke et al.</sub><br><sub>It is concluded that there is and likely will never be a silver bullet singular solution for all applications and that thinking seriously about tokenization remains important for many applications.</sub> | arXiv.org | 2021 | 234 | 80 |
| 4 | [Charformer: Fast Character Transformers via Gradient-based Subword Tokenization](https://www.semanticscholar.org/paper/e79d1206292bc5e67ba19737d87d4b2ea4a37105)<br><sub>Yi Tay et al.</sub><br><sub>A soft gradient-based subword tokenization module (GBST) that automatically learns latent subword representations from characters in a data-driven fashion is introduced that paves the way for highly performant token-free models that are trained completely end-to-end.</sub> | International Conference on Learning Representations | 2021 | 221 | 73 |
| 5 | [Language Modelling with Pixels](https://www.semanticscholar.org/paper/23f4b6432b74e5db05da04e354341807f5044f7e)<br><sub>Phillip Rust et al.</sub><br><sub>PIXEL is a pretrained language model that renders text as images, making it possible to transfer representations across languages based on orthographic similarity or the co-activation of pixels, and is more robust than BERT to orthographic attacks and linguistic code-switching, further confirming the benefits of modelling language with pixels.</sub> | International Conference on Learning Representations | 2022 | 71 | 47 |
| 6 | [CharacterBERT: Reconciling ELMo and BERT for Word-Level Open-Vocabulary Representations From Characters](https://www.semanticscholar.org/paper/473921de1b52f98f34f37afd507e57366ff7d1ca)<br><sub>Hicham El Boukkouri et al.</sub><br><sub>This work proposes CharacterBERT, a new variant of BERT that drops the wordpiece system altogether and uses a Character-CNN module instead to represent entire words by consulting their characters, and shows that this new model improves the performance of Bert on a variety of medical domain tasks while at the same time producing robust, word-level, and open-vocabulary representations.</sub> | International Conference on Computational Linguistics | 2020 | 179 | 47 |
| 7 | [Incorporating Context into Subword Vocabularies](https://www.semanticscholar.org/paper/a0568d0bf4cbfcb5a17a20c576dfc421c4ccfb7c)<br><sub>Shaked Yehezkel, Yuval Pinter</sub><br><sub>SaGe, a tokenizer that tailors subwords for their downstream use by baking in the contextualized signal at the vocabulary creation phase, is presented, showing its robustness to language properties such as morphological exponence and agglutination.</sub> | Conference of the European Chapter of the Association for Computational Linguistics | 2022 | 17 | 30 |
| 8 | [Finding the Optimal Vocabulary Size for Neural Machine Translation](https://www.semanticscholar.org/paper/5e788c833321b12671206b96a438c0e5b1202027)<br><sub>Thamme Gowda, Jonathan May</sub><br><sub>This work casts neural machine translation as a classification task in an autoregressive setting and analyzes the limitations of both classification and autoregression components, and reveals an explanation for why certain vocabulary sizes are better than others.</sub> | Findings | 2020 | 95 | 30 |
| 9 | [What do tokens know about their characters and how do they know it?](https://www.semanticscholar.org/paper/9a1a9ae2fc2911f1f275702bef38aa8f79c86986)<br><sub>Ayush Kaushal, Kyle Mahowald</sub><br><sub>The mechanisms through which PLMs acquire English-language character information during training are investigated and it is argued that this knowledge is acquired through multiple phenomena, including a systematic relationship between particular characters and particular parts of speech, as well as natural variability in the tokenization of related strings.</sub> | North American Chapter of the Association for Computational Linguistics | 2022 | 52 | 27 |
| 10 | [The Hidden Folk: Linguistic Properties Encoded in Multilingual Contextual Character Representations](https://www.semanticscholar.org/paper/4044c062683533d92f598715afe2508be29c739c)<br><sub>Manex Agirrezabal, Sidsel Boldsen, Nora Hollenstein</sub><br><sub>The multilingual contextual CANINE model is probed, including Faroese as an additional zero-shot instance, and it is observed that some phonetic information is indeed encoded in the character representations, as consonants and vowels can be well distinguished using a linear classifier.</sub> | CAWL | 2023 | 2 | 27 |

[... and 41 more, sorted by score](views/core-by-score.md)

## ✨ Recs

<sub>Found by following the citation graph, not picked by hand. Refreshed daily. To accept one, paste its link into [`import/papers.txt`](import/papers.txt) and commit.</sub>

_Nothing yet._ Recs appear once several papers here share a citing paper, which usually needs around ten.

<!-- SURVEY:END -->

<!--
  Anything you write between the SURVEY:END marker above and the footer below
  is yours and is never overwritten. Notes, scope, open questions, a call for
  contributions -- all safe here.
-->

---

<!-- TEMPLATE-FOOTER:START -->

### Want your own living survey?

Click **Use this template**, add your papers, and a daily GitHub Action keeps
the tables above up to date. No hosting, no API keys. See **[SETUP.md](https://github.com/avijit-thawani/living-survey/blob/main/SETUP.md)**.

<!-- TEMPLATE-FOOTER:END -->
