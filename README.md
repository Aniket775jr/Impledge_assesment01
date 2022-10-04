# Impledge_assesment01

1. As we know that input word limit may be very large, so in order to process 
   it effectively i use trie out of nested HashMap, UnorderedMap, dict structures.

2. First of all read all the words line by line from given input file and append in words array.
   Then make trie of these words and sort them according length. 
 
3. Find the largest compound word by passing each words to longestCompoundWord function. Then remove that word and
   we can find second largest compounded word in same way.
   
4. Inside LongestCompoundFunction first find , 0th letter and match it with trie, if not matched return False
   else return True and recursively called the same function for nect character of same word.
   
5. In order to calculate time, i use time module and easily calculated total elapsed time by subtracting initial 
   time with final time.
 


