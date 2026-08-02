from collections import Counter
import string
with open("sample_text.txt", "r") as file:
    text = file.read()
text = text.lower()
text = text.translate(str.maketrans("", "", string.punctuation))
words = text.split()
frequency = Counter(words)
print("Word Frequency Distribution:\n")
for word, count in frequency.items():
    print(word, ":", count)
