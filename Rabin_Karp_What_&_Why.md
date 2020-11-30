## Rabin-Karp Algorithm

Rabin-Karp Algorithm is a Pattern Searching Algorithm which is used to find if a pattern (substring) is present in a string and return the indices of its occurrences.

![Pattern-Searching-2-1](https://user-images.githubusercontent.com/43854410/100616957-d7b74300-333f-11eb-9462-6575d296f0c7.png)
<br>
<h6>Image Source: GeeksForGeeks</h6>

Like the Naive Algorithm, Rabin-Karp algorithm also slides the pattern one by one. But unlike the Naive algorithm, Rabin Karp algorithm matches the hash value of the pattern with the hash value of current substring of text, and if the hash values match then only it starts matching individual characters. So Rabin Karp algorithm needs to calculate hash values for following strings.
1) Pattern itself. 
2) All the substrings of the text of length m. 
