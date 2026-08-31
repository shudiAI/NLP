# Lab 2 – Text Pre-processing and Regular Expressions

In this lab, I will complete tasks related to regular expressions and text tokenization. The main tasks include extracting hashtags from text, using `re.compile()`, using `re.split()`, and tokenizing text with spaCy and NLTK.

## `re.compile()`

`re.compile()` is used to create a regular expression pattern that can be reused later.

It is useful because it makes the code cleaner and more organized, especially when the same pattern is used more than once.

## `re.split()`

`re.split()` is used to split text based on a specific regular expression pattern.

For example, it can split a string whenever one or more digits appear.

## `spacy.load()`

`spacy.load()` is used to load a trained spaCy language model, such as `en_core_web_sm`.

This model allows spaCy to process text and perform tasks such as tokenization.

## NLTK vs spaCy

Both NLTK and spaCy can be used for tokenization.

NLTK mainly provides simple text-processing tools and returns tokens as strings, while spaCy provides tokens with additional linguistic information and is designed for more advanced NLP processing.
