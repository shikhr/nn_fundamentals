## Word2Vec with Negative Sampling

Word2vec is a technique in natural language processing (NLP) for obtaining vector representations of words.
These vectors capture information about the meaning of the word based on the surrounding(context) words.

[Word2Vec SkipGram with Negative Sampling](/Word2Vec_Negative_Sampling/word2vec-negativesampling.ipynb)


## Makemore models

Building and training autoregressive language models from scratch, following Andrej Karpathy's [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) series.

1. [Bigram](/makemore/01_Bigram.ipynb)
2. [Trigram](/makemore/02_Trigram.ipynb)
3. [Trigram Alternative](/makemore/03_Trigram_nn_alternative.ipynb)
4. [MLP](/makemore/04_MLP.ipynb)
5. [MLP 2](/makemore/05_MLP.ipynb)
6. [MLP with Modules](/makemore/06_MLP_modulified.ipynb)
7. [MLP](/makemore/06_MLP_waveNet.ipynb)
8. [RNN](/makemore/07_RNN_basic.ipynb)

## GPT

### [GPT Tokenizer(BPE)](/Gpt_Tokenizer/tokenizer.ipynb)
Tokenization is splitting text into smaller units called tokens that can be fed into the language model.
- character level (too small)
- word level (too big)
- subword level (balanced)
  - BPE (Algorithm which merges on argmax P(A,B), good for whitespaced languages)
  - WordPiece (Algorithm which merges on argmax P(A,B)/[P(A)*P(B)], good for whitespaced languages)
  - SentencePiece (Library containing optimized BPE, WordPiece, Unigram, good for non - whitespaced languages)
  - Unigram (All combinations of substrings, then reduce if least impact to maximising likelihood)



### [NanoGPT](/GPT_Scratch/NanoGPT.ipynb)

Transformer Decoder for autoregressive sequence to sequence modelling.

<img  height="300" src="https://39669.cdn.cke-cs.com/rQvD3VnunXZu34m86e5f/images/fd85b5616410867221db3acd185fd0716d4660f7734e8714.png/w_1980" alt="gpt2" />


## [Vision Transformer](/ViT/vit-base-model.ipynb)

<img  height="300" src="https://n.sinaimg.cn/spider20211231/460/w749h511/20211231/a173-135448e57102e910ffac73b744570366.gif" alt="ViT" />

<img height="300" src="https://theaisummer.com/static/aa65d942973255da238052d8cdfa4fcd/7d4ec/the-transformer-block-vit.png" alt="encoder" />


