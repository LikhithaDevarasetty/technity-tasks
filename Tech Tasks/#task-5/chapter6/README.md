CHAPTER 6:-

• Escape characters are special characters used in strings to represent characters that are difficult or impossible to type directly, such as newline or tab characters.
• \n represents a newline character, and \t represents a tab character.
• You can use a double backslash \ to represent a single backslash character in a string.
• The string is valid because the single quote character within the double-quoted string doesn't conflict with the string's outer double quotes. Alternatively, you could use single quotes around the entire string: 'Howl's Moving Castle'.
• You can use triple-quoted strings (''' or """) to write strings with newlines in them.
• Expression evaluations:
• 'Hello, world!'[1] -> 'e'
• 'Hello, world!'[0:5] -> 'Hello'
• 'Hello, world!'[:5] -> 'Hello'
• 'Hello, world!'[3:] -> 'lo, world!'
• Expression evaluations:
• 'Hello'.upper() -> 'HELLO'
• 'Hello'.upper().isupper() -> True
• 'Hello'.upper().lower() -> 'hello'
• Expression evaluations:
• 'Remember, remember, the fifth of November.'.split() -> ['Remember,', 'remember,', 'the', 'fifth', 'of', 'November.']
• '-'.join('There can be only one.'.split()) -> 'There-can-be-only-one.'
• String methods for justification:
• Right-justify: rjust()
• Left-justify: ljust()
• Center: center()
• You can use the strip() method to remove whitespace characters from the beginning and end of a string. To remove only leading or trailing whitespace, you can use lstrip() and rstrip() respectively.
