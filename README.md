# Bigram SpellChecker
Spellchecker for Sanskrit text using Bigram Modelling

## 1 Tokenization

Run the tokenizer on the corpus.

```
python indic_tokenizer.py --i  corpus.txt --o corpus_tokenised.txt --l hin
```

## 2 SpellCheck

Call find_max_edit_likelihood(sentence, index) in BigramModelSpellCheck.py to run the checker for the word at the given index in the sentence. (context-based spellcheck)

```
python BigramModelSpellCheck.py
```

A ranked list of word suggestions is generated as substitute for the given word in the sentence.
