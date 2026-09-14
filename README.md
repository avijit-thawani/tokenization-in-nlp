<!-- SURVEY:START -->

# Tokenization in NLP

A living survey of tokenization in NLP

**51** in Core · **25** Recs · updated 2026-09-14

## Core

The papers in this survey.

| # | [Paper](views/core-by-title.md) | Venue | [Year](views/core-by-year.md) | [Cited by](views/core-by-citations.md) | Score &#9660; |
| ---: | --- | --- | ---: | ---: | ---: |
| 1 | [Canine: Pre-training an Efficient Tokenization-Free Encoder for Language Representation](https://www.semanticscholar.org/paper/969287b8a96e242793b11f0dbb99ec341228106f)<br><sub>J. Clark et al.</sub><br><sub>Canine is presented, a neural encoder that operates directly on character sequences—without explicit tokenization or vocabulary—and a pre-training strategy that operates either directly on characters or optionally uses subwords as a soft inductive bias.</sub> | Transactions of the Association for Computational Linguistics | 2021 | 333 | 100 |
| 2 | [ByT5: Towards a Token-Free Future with Pre-trained Byte-to-Byte Models](https://www.semanticscholar.org/paper/44ef6cf919250001836ed73c0d58b20ea1e2d308)<br><sub>Linting Xue et al.</sub><br><sub>This paper shows that a standard Transformer architecture can be used with minimal modifications to process byte sequences, characterize the trade-offs in terms of parameter count, training FLOPs, and inference speed, and shows that byte-level models are competitive with their token-level counterparts.</sub> | Transactions of the Association for Computational Linguistics | 2021 | 765 | 87 |
| 3 | [Between words and characters: A Brief History of Open-Vocabulary Modeling and Tokenization in NLP](https://www.semanticscholar.org/paper/d617f51833860dc50d202af7f80be71304b2e994)<br><sub>Sabrina J. Mielke et al.</sub><br><sub>It is concluded that there is and likely will never be a silver bullet singular solution for all applications and that thinking seriously about tokenization remains important for many applications.</sub> | arXiv.org | 2021 | 234 | 80 |
| 4 | [Charformer: Fast Character Transformers via Gradient-based Subword Tokenization](https://www.semanticscholar.org/paper/e79d1206292bc5e67ba19737d87d4b2ea4a37105)<br><sub>Yi Tay et al.</sub><br><sub>A soft gradient-based subword tokenization module (GBST) that automatically learns latent subword representations from characters in a data-driven fashion is introduced that paves the way for highly performant token-free models that are trained completely end-to-end.</sub> | International Conference on Learning Representations | 2021 | 221 | 73 |
| 5 | [Language Modelling with Pixels](https://www.semanticscholar.org/paper/23f4b6432b74e5db05da04e354341807f5044f7e)<br><sub>Phillip Rust et al.</sub><br><sub>PIXEL is a pretrained language model that renders text as images, making it possible to transfer representations across languages based on orthographic similarity or the co-activation of pixels, and is more robust than BERT to orthographic attacks and linguistic code-switching, further confirming the benefits of modelling language with pixels.</sub> | International Conference on Learning Representations | 2022 | 71 | 47 |

<sub>… and 46 more. View all, sorted by [Score](views/core-by-score.md) · [Year](views/core-by-year.md) · [Cited by](views/core-by-citations.md) · [Title](views/core-by-title.md).</sub>

## ✨ Recs

<sub>Found by following the citation graph — a deterministic algorithm you can tune, not an LLM. Refreshed daily. Use the **Decide** column to accept or reject one.</sub>

### New in the past month

| # | [Paper](views/recs-by-title.md) | Venue | [Year](views/recs-by-year.md) | [Cited by](views/recs-by-citations.md) | Score &#9660; | Why | Decide |
| ---: | --- | --- | ---: | ---: | ---: | --- | --- |
| 1 | [Dynamic Multi-Byte Prediction With Hierarchical Language Models](https://www.semanticscholar.org/paper/95462c2e9d2b2e6ee6ccc4a90965683e3fe92ee8)<br><sub>Abraham Toluwase Owodunni et al.</sub><br><sub>It is shown that multi-byte prediction strikes a Pareto-optimal trade-off across multiple generative tasks, instruction following, question answering, summarization, and machine translation, achieving the best trade-off between performance and inference throughput.</sub> | - | 2026 | 0 | 45 | cites 5 in Core | [review #26](https://github.com/avijit-thawani/tokenization-in-nlp/pull/26) |
| 2 | [How Do Language Models Represent and Use Phonological Information for Allomorph Selection?](https://www.semanticscholar.org/paper/f6cdf5780286a250be0b5f10110d159a5a205900)<br><sub>Sangwoo Kim, Sang-Ah Lee</sub> | - | 2026 | 0 | 36 | cites 4 in Core | [review #27](https://github.com/avijit-thawani/tokenization-in-nlp/pull/27) |
| 3 | [Seeing the Unseen: Visual Similarity for Pixel Language Model Adaptation](https://www.semanticscholar.org/paper/57bb68920ac6cb78f64a888fe809aed7e4d77865)<br><sub>Ran Zhang, Miryam de Lhoneux, Wessel Poelman</sub><br><sub>These metrics and case study offer empirical observations that could help inform data selection and script adaptation choices when working with pixel-based models in similar low-resource settings.</sub> | - | 2026 | 0 | 36 | cites 4 in Core | [review #28](https://github.com/avijit-thawani/tokenization-in-nlp/pull/28) |
| 4 | [Vowel Signs Are Not Letters: A Pre-tokenization Ceiling on Multilingual Tokenizer Fertility](https://www.semanticscholar.org/paper/ddfe9c9bb77816ab10d60001636ddd32ab4e0ef8)<br><sub>S. Regmi, Siddhartha Pudasaini, Chetan Phakami Pun</sub><br><sub>Byte-level BPE tokenizers that use the HuggingFace ByteLevel pre-tokenizer inherit GPT-2's word regex, where a word is defined as \p{L}+, one or more Unicode letters, which splits each word at every vowel sign, and formalises this effect as a training-free lower bound on fertility.</sub> | - | 2026 | 1 | 27 | cites 3 in Core | [review #29](https://github.com/avijit-thawani/tokenization-in-nlp/pull/29) |
| 5 | [What Tokens are Learned when Tokenization is Optimized Jointly with Language Modeling?](https://www.semanticscholar.org/paper/31f4e442e3aa058e814887ee9b2241ea4b17435d)<br><sub>Saketh Reddy Vemula, Parameswari Krishnamurthy</sub><br><sub>This work analyzes what tokens are learned when tokenization is jointly optimized with language modeling, and finds tokenizer-free approaches optimize for contextual and computational efficiency rather than strict morphological structure, resulting in fundamentally different yet effective vocabularies for downstream NLP.</sub> | - | 2026 | 0 | 27 | cites 3 in Core | [review #31](https://github.com/avijit-thawani/tokenization-in-nlp/pull/31) |

<sub>… and 3 more. View all, sorted by [Score](views/recs-by-score.md) · [Year](views/recs-by-year.md) · [Cited by](views/recs-by-citations.md) · [Title](views/recs-by-title.md).</sub>

### New in the past year

| # | [Paper](views/recs-by-title.md) | Venue | [Year](views/recs-by-year.md) | [Cited by](views/recs-by-citations.md) | Score &#9660; | Why | Decide |
| ---: | --- | --- | ---: | ---: | ---: | --- | --- |
| 1 | [UTF-8 Plumbing: Byte-level Tokenizers Unavoidably Enable LLMs to Generate Ill-formed UTF-8](https://www.semanticscholar.org/paper/66e13b987c86e9c40b10b27672c83848f316609a)<br><sub>Preston Firestone et al.</sub><br><sub>This paper formalizes tokenization using monoid theory and proves that tokenizers whose vocabularies contain tokens that are ill-formed UTF-8 can always produce sequences that are ill-formed UTF-8.</sub> | arXiv.org | 2025 | 5 | 100 | cites 11 in Core | [review #3](https://github.com/avijit-thawani/tokenization-in-nlp/pull/3) |
| 2 | [Stop Taking Tokenizers for Granted: They Are Core Design Decisions in Large Language Models](https://www.semanticscholar.org/paper/b880a2e08e4a102fd7e5c031504145cfb80bd282)<br><sub>Sawsan Alqahtani et al.</sub><br><sub>This paper reframes tokenization as a core modeling decision rather than a preprocessing step, and argues for a context-aware framework that integrates tokenizer and model co-design, guided by linguistic, domain, and deployment considerations.</sub> | Conference of the European Chapter of the Association for Computational Linguistics | 2026 | 5 | 73 | cites 8 in Core | [add](https://github.com/avijit-thawani/tokenization-in-nlp/issues/new?labels=add-paper&title=Add%20paper%3A%20Stop%20Taking%20Tokenizers%20for%20Granted%3A%20They%20Are%20Core%20Design%20Decisions%20in%20Large%20Lan&body=https%3A%2F%2Farxiv.org%2Fabs%2F2601.13260) · [drop](https://github.com/avijit-thawani/tokenization-in-nlp/issues/new?labels=drop-paper&title=Drop%20paper%3A%20Stop%20Taking%20Tokenizers%20for%20Granted%3A%20They%20Are%20Core%20Design%20Decisions%20in%20Large%20La&body=b880a2e08e4a102fd7e5c031504145cfb80bd282) |
| 3 | [Bolmo: Byteifying the Next Generation of Language Models](https://www.semanticscholar.org/paper/bcf94ad307cdaea3e72fe64ddf3cb710b1f0ef3a)<br><sub>Benjamin Minixhofer et al.</sub><br><sub>Bolmo is introduced, a family of fully open byte-level LLMs that approach the capabilities of subword-based systems, demonstrating that models operating on raw text encodings can scale competitively while offering advantages in domains requiring fine-grained textual understanding.</sub> | arXiv.org | 2025 | 8 | 64 | cites 7 in Core | [review #45](https://github.com/avijit-thawani/tokenization-in-nlp/pull/45) |
| 4 | [Proxy Compression for Language Modeling](https://www.semanticscholar.org/paper/0c71a9182e0e4af9fa4315c0267a62b216ebc934)<br><sub>Lin Zheng et al.</sub><br><sub>This work introduces proxy compression, an alternative training scheme that preserves the efficiency benefits of compressed inputs while providing an end-to-end, raw-byte interface at inference time, and substantially improves training efficiency and significantly outperforms pure byte-level baselines given fixed compute budgets.</sub> | arXiv.org | 2026 | 3 | 64 | cites 7 in Core | [review #46](https://github.com/avijit-thawani/tokenization-in-nlp/pull/46) |
| 5 | [Fast Byte Latent Transformer](https://www.semanticscholar.org/paper/a662b8d7e294424e97f1732d254bd971221621f3)<br><sub>Julie Kallini et al.</sub><br><sub>This work introduces BLT Diffusion (BLT-D), a new model and the authors' fastest BLT variant, trained with an auxiliary block-wise diffusion objective alongside the standard next-byte prediction loss, and proposes two extensions inspired by speculative decoding that trade some of this speed for higher generation quality.</sub> | arXiv.org | 2026 | 1 | 64 | cites 7 in Core | [review #35](https://github.com/avijit-thawani/tokenization-in-nlp/pull/35) |

<sub>… and 5 more. View all, sorted by [Score](views/recs-by-score.md) · [Year](views/recs-by-year.md) · [Cited by](views/recs-by-citations.md) · [Title](views/recs-by-title.md).</sub>

### Most connected, any year

| # | [Paper](views/recs-by-title.md) | Venue | [Year](views/recs-by-year.md) | [Cited by](views/recs-by-citations.md) | Score &#9660; | Why | Decide |
| ---: | --- | --- | ---: | ---: | ---: | --- | --- |
| 1 | [Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates](https://www.semanticscholar.org/paper/e73bd7f9bdc262b9b7fb60ca0d5230d3ab0fad5e)<br><sub>Taku Kudo</sub><br><sub>A simple regularization method is presented, subword regularization, which trains the model with multiple subword segmentations probabilistically sampled during training, and a new sub word segmentation algorithm based on a unigram language model is proposed.</sub> | Annual Meeting of the Association for Computational Linguistics | 2018 | 1413 | 100 | cited by 30 in Core | [review #1](https://github.com/avijit-thawani/tokenization-in-nlp/pull/1) |
| 2 | [Learn Your Tokens: Word-Pooled Tokenization for Language Modeling](https://www.semanticscholar.org/paper/a401510c434b2274b299e9444085df0b18808aaa)<br><sub>Avijit Thawani et al.</sub><br><sub>This paper considers an alternative 'learn your tokens' scheme which utilizes the word boundary to pool bytes/characters into word representations, which are fed to the primary language model, before again decoding individual characters/bytes per word in parallel.</sub> | Conference on Empirical Methods in Natural Language Processing | 2023 | 13 | 100 | cites 11 in Core | [review #2](https://github.com/avijit-thawani/tokenization-in-nlp/pull/2) |
| 3 | [Neural Machine Translation of Rare Words with Subword Units](https://www.semanticscholar.org/paper/1518039b5001f1836565215eb047526b3ac7f462)<br><sub>Rico Sennrich, B. Haddow, Alexandra Birch</sub><br><sub>This paper introduces a simpler and more effective approach, making the NMT model capable of open-vocabulary translation by encoding rare and unknown words as sequences of subword units, and empirically shows that subword models improve over a back-off dictionary baseline for the WMT 15 translation tasks English-German and English-Russian by 1.3 BLEU.</sub> | Annual Meeting of the Association for Computational Linguistics | 2015 | 9002 | 90 | cited by 39 in Core | [review #4](https://github.com/avijit-thawani/tokenization-in-nlp/pull/4) |
| 4 | [Retrofitting (Large) Language Models with Dynamic Tokenization](https://www.semanticscholar.org/paper/1068dfc3985863ad692cd59a48596847aac8754f)<br><sub>Darius Feher, Benjamin Minixhofer, Ivan Vuli'c</sub><br><sub>This work proposes retrofitting LMs with dynamic tokenization: a way to dynamically decide on token boundaries based on the input text via a subword-merging algorithm inspired by byte-pair encoding that can mitigate the limitations of static tokenization.</sub> | arXiv.org | 2024 | 19 | 82 | cites 9 in Core | [review #5](https://github.com/avijit-thawani/tokenization-in-nlp/pull/5) |
| 5 | [Inducing Character-level Structure in Subword-based Language Models with Type-level Interchange Intervention Training](https://www.semanticscholar.org/paper/205cc15fca6963b355e4c071071368e874ee103e)<br><sub>Jing Huang et al.</sub><br><sub>This work develops a causal intervention framework to learn robust and interpretable character representations inside subword-based language models and introduces a suite of character-level tasks that systematically vary in their dependence on meaning and sequence-level context.</sub> | Annual Meeting of the Association for Computational Linguistics | 2022 | 17 | 82 | cites 9 in Core | [review #6](https://github.com/avijit-thawani/tokenization-in-nlp/pull/6) |

<sub>… and 2 more. View all, sorted by [Score](views/recs-by-score.md) · [Year](views/recs-by-year.md) · [Cited by](views/recs-by-citations.md) · [Title](views/recs-by-title.md).</sub>

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
the tables above up to date. Everything lives in your own repo — no website, no
backend, no database, no API keys — and the Recs come from a citation graph
algorithm you can tune, not from an LLM. See **[SETUP.md](https://github.com/avijit-thawani/living-survey/blob/main/SETUP.md)**.

<!-- TEMPLATE-FOOTER:END -->
