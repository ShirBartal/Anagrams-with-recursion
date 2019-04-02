The purpose of this project is to practice the way of thinking of using recursion.
It's important to understand that this method of calculating the anagrams of a given word with recursion is very inefficient.
In a real-world project I would use dynamic programming to solve this problem, and convert the recursive function to simple for loops.
However, this project has taught me a creative way of thinking, which contributed a lot to my skills as a programmer.
It was more of a challenge rather than an official work.
Also, a less time consuming way (but probably as efficient as calculating it with dynamic programming) would be simply using the standard library to find the permutation.
This project also uses reading from a file, in order to keep track and store to the array only of the permutation which are a part of the English dictionary, and that is called an anagram.
This code works for most cases, but as you can see, there was one exception, edge case that is not covered.
All the tests pass except for test 4 (described as one of the assert functions) - not checking if I am we are overflowing the dictionary's array  (out of boundaries).
Would love to get help on fixing this bug.
