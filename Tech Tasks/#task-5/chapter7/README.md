CHAPTER 7:-

• The re.compile() function creates Regex objects in Python's re module.
• Raw strings (preceded by r) are often used with Regex objects to avoid having to escape backslashes twice. They treat backslashes as literal characters instead of escape characters.
• The search() method returns a Match object if the pattern is found in the searched string, otherwise, it returns None.
• You can use the group() method on a Match object to get the actual strings that match the pattern. group(0) is the entire matched text, and group(1), group(2), etc. refer to the capture groups.
• In the regex r'(\d\d\d)-(\d\d\d-\d\d\d\d)':
• Group 0 covers the entire matched text.
• Group 1 covers the first three digits.
• Group 2 covers the second set of three digits and the final four digits.
• To match parentheses and period characters literally, you need to escape them with a backslash: ( for ( and . for ..
• The findall() method returns a list of strings when the regex has no groups, and it returns a list of tuples of strings when the regex has groups.
• The | character in regular expressions is used to signify an alternation, allowing you to match one expression or another.
• The ? character signifies:
• Making the preceding element in the regex optional.
• Non-greedy matching when used after *, +, ?, or {} quantifiers.
• In regular expressions:
• + means "one or more occurrences."
• * means "zero or more occurrences."
• {3} specifies exactly 3 occurrences, while {3,5} specifies a range of 3 to 5 occurrences.
• Shorthand character classes in regular expressions:
• \d matches any digit.
• \w matches any word character (alphanumeric and underscore).
