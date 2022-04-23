# Tokenization
### The meaning of the text could easily be interpreted by analyzing the words present in the text!
Given a character sequence and a defined document unit, tokenization is the task of chopping it up into pieces, called *tokens* , perhaps at the same time throwing away certain characters, such as punctuation. Here is an example of tokenization:

![image](https://user-images.githubusercontent.com/78906545/164943424-7d5d91bb-46a2-4cac-aa5f-cabb8e041c0b.png)

These tokens are often loosely referred to as terms or words, but it is sometimes important to make a type/token distinction. A **token** is an instance of a sequence of characters in some particular document that are grouped together as a useful semantic unit for processing. A **type** is the class of all tokens containing the same character sequence. A **term** is a (perhaps normalized) type that is included in the IR system's dictionary. The set of index terms could be entirely distinct from the tokens.
# Refrence
https://nlp.stanford.edu/IR-book/html/htmledition/tokenization-1.html
