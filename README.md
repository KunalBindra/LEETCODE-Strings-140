# LEETCODE-Strings-140
This code is a Java solution for the Word Break II problem. The problem involves breaking a given string into words from a dictionary in all possible ways. The function `wordBreak` takes a string `s` and a list of strings `wordDict` as input and returns a list of strings containing all possible word breaks.

The code initializes a HashSet `wordSet` from the input word dictionary to quickly check if a word exists in the dictionary. It also initializes a HashMap `mem` to store the results of previously computed word breaks.

The `wordBreak` function recursively breaks down the input string `s` into prefixes and suffixes, checking if the prefix is a valid word. If so, it recursively calls itself on the suffix and adds the prefix to the resulting list of word breaks.

Once all possible word breaks for the input string `s` are computed, they are stored in the `mem` map to avoid recomputing the same results.

Overall, the code efficiently solves the Word Break II problem through recursion and memoization.
