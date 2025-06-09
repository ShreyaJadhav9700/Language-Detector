🔑 Key Parts:
nltk & stopwords:

nltk provides a list of common stopwords (like the, is, le, la) for many languages.

These are used to compare with user input.

detect_language(text):

Splits the input text into words.

For each language, checks how many words in the text match that language’s stopwords.

The language with the most matches is likely the one used.

User Input:

Takes a sentence from the user and prints the most likely language.

✅ Example Use Case:
You input "Bonjour, comment ça va?" → Code detects French
