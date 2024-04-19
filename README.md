# DSA_Swift
Data structures and Algorithms in the Swift Language
1. Two pointers & co
   - Palindrome : A palindrome is a word, phrase, or sequence of characters that reads the same backward as forward.
   -  Constraints
      - 1 <= s.length <= 2 x 10^5
      - The string s will contain English uppercase and lowercase letters, digits, and spaces.
        
   - PseudoCode
      - Initialize two pointers at the beginning and end of the string
      - Check whether or not the current pair of charcters is identical.
      - If they are not identical, return FALSE. Otherwise move both pointers by one index toward the middle.
      - Keep traversing them toward the middle until they meet.
      - If we reach the middle of the string without finding a mismatch, return TRUE.
