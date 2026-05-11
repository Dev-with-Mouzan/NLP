# BPE (Byte Pair Encoding) in NLP

## What is BPE?

**Byte Pair Encoding (BPE)** is a data compression algorithm adapted for subword tokenization in Natural Language Processing. It was introduced by Gage (1994) for text compression and later adopted by Sennrich et al. (2016) for Neural Machine Translation.

## How BPE Works

1. **Start with character-level tokens**: Split all words into individual characters
2. **Count frequency of adjacent pairs**: Find the most common pair of adjacent tokens
3. **Merge the most frequent pair**: Replace all occurrences of that pair with a new single token
4. **Repeat**: Continue until reaching the desired vocabulary size

## Example

```
Original word: "lowlowerlowest"
Character sequence: l o w _ l o w e r _ l o w e s t

Step 1: Count pairs → "lo" appears 3 times (most frequent)
Step 2: Merge "lo" → l ow _ l ow e r _ l ow e s t
Step 3: Continue merging...
```

## Why BPE in NLP?

| Problem | BPE Solution |
|---------|--------------|
| Unknown words (OOV) | Breaks rare words into known subword units |
| Large vocabulary | Compact vocabulary through merge operations |
| Morphology | Captures word parts like prefixes/suffixes |

## BPE vs Word-level Tokenization

| Aspect | Word-level | BPE |
|--------|------------|-----|
| Vocab size | Large (100K+) | Smaller (~30K) |
| OOV handling | Cannot process | Splits into subwords |
| Memory | High | Lower |

## Applications

- **Machine Translation** (GNMT, Marian NMT)
- **Language Models** (GPT, BERT use subword tokenizers based on BPE)
- **Text Generation**
- **Word Embeddings**

## Common Variants

1. **WordPiece** - Used by Google (BERT)
2. **SentencePiece** - Language-agnostic, treats text as byte sequence
3. **Unigram Language Model** - Used by T5, ALBERT

## Advantages

- Handles any language without language-specific preprocessing
- Reduces OOV problem significantly
- Balances between character and word level representations

## Disadvantages

- Merged tokens may not align with semantic units
- Training is slow for large datasets
- Vocabulary size is a hyperparameter requiring tuning
