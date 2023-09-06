CHAPTER 5:-

• An empty dictionary is represented by {}.
• A dictionary value with a key 'foo' and a value 42 looks like {'foo': 42}.
• The main difference between a dictionary and a list is that a dictionary stores values as key-value pairs, while a list stores values in an ordered sequence.
• If you try to access spam['foo'] when spam is {'bar': 100}, a KeyError will be raised since the key 'foo' is not present in the dictionary.
• If a dictionary is stored in spam, 'cat' in spam checks if the key 'cat' exists in the dictionary, while 'cat' in spam.keys() does the same thing, checking for the presence of the key 'cat'.
• If a dictionary is stored in spam, 'cat' in spam checks if there's a key 'cat' in the dictionary, while 'cat' in spam.values() checks if there's a value 'cat' in any of the dictionary's values.
