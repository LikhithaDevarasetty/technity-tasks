CHAPTER 4:-

• [] represents an empty list in Python.
• To assign 'hello' as the third value in the list stored in the variable spam:
• spam[2] = 'hello'
• spam[int(int('3' * 2) // 11)] evaluates to 'd'.
• spam[-1] evaluates to 'd'.
• spam[:2] evaluates to ['a', 'b'].
• bacon.index('cat') evaluates to 1.
• After bacon.append(99), the list value in bacon becomes [3.14, 'cat', 11, 'cat', True, 99].
• After bacon.remove('cat'), the list value in bacon becomes [3.14, 11, 'cat', True, 99].
• List concatenation operator: + List replication operator: *
• The append() method adds a value to the end of the list. The insert() method inserts a value at a specific index in the list.
• Two ways to remove values from a list are using the remove() method and the del statement.
• Both list values and string values can be indexed and sliced. They can also be looped over using loops like for.
• Lists are mutable (can be modified), while tuples are immutable (cannot be modified).
• Tuple containing the integer value 42: (42,)
• To get the tuple form of a list value: tuple(some_list) To get the list form of a tuple value: list(some_tuple)
• Variables that "contain" list values store references (pointers) to the memory location where the list data is stored.
• copy.copy() performs a shallow copy of a list, meaning it creates a new list, but the elements within it may still refer to the same objects as the original list. copy.deepcopy() performs a deep copy, creating entirely new objects for the copied list, including all nested objects.
