import nltk
from nltk.tokenize import sent_tokenize, word_tokenize

example_text = "Hello Mr. Bean, how are you ?The weather is great, and Python is awesome. The sky is pinkish-blue. You shouldn't eat cardboard."

print(word_tokenize(example_text))
