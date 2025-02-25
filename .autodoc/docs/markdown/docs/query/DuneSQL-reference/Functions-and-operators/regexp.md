[View code on GitHub](https://dune.com/docs/query/DuneSQL-reference/Functions-and-operators/regexp.md)

The app technical guide covers the usage of regular expression functions in the Dune Docs project. The guide explains the syntax used in the Java pattern and highlights the differences in the implementation of the regular expression functions in the project. The guide provides examples of how to use each function in the project.

The guide covers the following functions:

- regexp_count(): Returns the number of occurrences of a pattern in a string.
- regexp_extract_all(): Returns an array of all substrings that match a pattern in a string.
- regexp_extract(): Returns the first substring that matches a pattern in a string.
- regexp_like(): Determines if a pattern is contained within a string.
- regexp_position(): Returns the index of the nth occurrence of a pattern in a string.
- regexp_replace(): Replaces substrings that match a pattern in a string with a replacement string or a function.
- regexp_split(): Splits a string using a pattern and returns an array.

The guide also explains the differences in the implementation of Unicode character classes, blocks, and categories in the project. The guide provides examples of how to use each function with different parameters.

Overall, the app technical guide provides a comprehensive explanation of how to use regular expression functions in the Dune Docs project. The guide is useful for developers who want to implement regular expressions in their code.
## Questions: 
 1. What is the syntax used for regular expressions in this app?
- The app uses Java pattern syntax for regular expressions, with a few exceptions.

2. Are there any limitations or unsupported features for regular expressions in this app?
- Yes, there are several limitations and unsupported features for regular expressions in this app, such as incorrect handling of boundaries for a non-spacing mark without a base character and lack of support for surrogate pairs.

3. What are the available functions for working with regular expressions in this app?
- The available functions for working with regular expressions in this app include regexp_count, regexp_extract_all, regexp_extract, regexp_like, regexp_position, regexp_replace, and regexp_split.