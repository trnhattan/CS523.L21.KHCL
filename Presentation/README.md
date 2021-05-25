# CS523.L21.KHCL - Advanced data structure and algorithm
# Subject: Pattern Searching
## Overview:
- What is “String Pattern Matching”?

- First concepts: Naive approach (Bruth Force)

- Definitions
## Knuth - Morris - Pratt (KMP):
- Original idea.
- How to get “safe shift”?
- What is prefix function?

- Computing prefix function
![image](https://user-images.githubusercontent.com/63542739/119451934-fe3ebf80-bd5f-11eb-8b40-886b9fb1e87e.png)

- Time complexity:
![image](https://user-images.githubusercontent.com/63542739/119452067-21696f00-bd60-11eb-8f2d-a5d11b349d21.png)

- KMP's application:
<p align="center">
<img src="https://user-images.githubusercontent.com/63542739/119452191-41009780-bd60-11eb-8097-fce981ec13b9.png" alt="KMP's application">
</p>

- Pros and cons:
![image](https://user-images.githubusercontent.com/63542739/119452602-be2c0c80-bd60-11eb-8abb-7c7e6568ab0e.png)

## Rabin Karp:
- Rolling hash:
  - A rolling hash to be computed very quickly - the new hash value is rapidly calculated given only the old hash value.
  - O(1) time per hash.
<p align="center">
<img src="https://user-images.githubusercontent.com/63542739/119452907-15ca7800-bd61-11eb-9dbb-310e59847a75.png" alt="Rabin Karp's pseudo code">
<img src="https://user-images.githubusercontent.com/63542739/119453028-32ff4680-bd61-11eb-806d-fc89d03ebbb3.png" alt="Rabin Karp's code">
</p>

- Time complexity:
![image](https://user-images.githubusercontent.com/63542739/119453323-82457700-bd61-11eb-90c1-8ea86f046c8d.png)

- Pros and cons:
![image](https://user-images.githubusercontent.com/63542739/119453401-95f0dd80-bd61-11eb-838d-c931d7a4dab2.png)

- Rabin Karp's application:
A practical application of the algorithm is detecting plagiarism. Given source material, the algorithm can rapidly search through a paper for instances of sentences from the source material, ignoring details such as case and punctuation. Because of the abundance of the sought strings, single-string searching algorithms are impractical.

## Reference:
- [KMP Algorithm for Pattern Searching](https://www.geeksforgeeks.org/kmp-algorithm-for-pattern-searching/), geeksforgeeks.com
- [The MP and KMP Algorithms, Algorithms Based upon](https://studylib.net/doc/7580926/chapter-6-the-mp-and-kmp-algorithms--algorithms-based-upon), studylib.net.
- Gonzalo Navarro, Mathieu Raffinot, Flexible pattern matching in strings.
- [Algorithm on Strings](https://www.coursera.org/learn/algorithms-on-strings), University of California San Diego & HSE University, coursera.com.
- [Xử lý xâu](https://vnoi.info/wiki/algo/string/basic?fbclid=IwAR3hiG5C5T6LC-Em98HMz1N9dCs2MAnLcp5OqpsbsSoGzywhXxpht_pud3c), vnoi.info.
- [Knuth – Morris – Pratt (KMP)](https://vnoi.info/wiki/translate/wcipeg/kmp), vnoi.info.
- [Rabin Karp algorithm](https://www.geeksforgeeks.org/rabin-karp-algorithm-for-pattern-searching/), geeksforgeeks.com
- [Rabin Karp algorithm](https://en.wikipedia.org/wiki/Rabin%E2%80%93Karp_algorithm), Wikipedia.com
