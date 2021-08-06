# KMP-Algorithim
KMP algorithm preprocesses pat[] and constructs an auxiliary lps[] of size m 
(same as size of pattern) which is used to skip characters while matching.
The KMP matching algorithm uses degenerating property (pattern having same sub-patterns appearing more than once in the pattern) 
of the pattern and improves the worst case complexity to O(n). The basic idea behind KMP’s algorithm is:
whenever we detect a mismatch (after some matches), we already know some of the characters in the text of the next window. 
