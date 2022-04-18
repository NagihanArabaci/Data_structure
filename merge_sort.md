## [16,21,11,8,12,22] -> Merge Sort
### Dizinin sort türüne göre aşamaları:
- Diziyi tek eleman kalana kadar böl ve bölünenleri de kendi arasında sırala,birleştir:
- **16,21,11** || **8,12,22** (n/2)
- **16** || **21,11** || **8** || **12,22** (n/2)
- **16** || **11** || **21** || **8** || **12** || **22** (n/2)
- **16** || **11,21** || **8** || **12,22** (n/2)
- **11,16,21** || **8,12,22** (n/2)
- **8,11,12,16,21,22** (n/2) 
### Dizinin Big-O: O(nlogn)
