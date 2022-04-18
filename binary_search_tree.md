## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
### root-> 8 olarak belirlendi.
- 7 değeri 7<8 => root-sol-> 7
- 5 değeri 5<7 => root-sol-sol-> 5
- 1 değeri 1<5 => root-sol-sol-sol-> 1
- 3 değeri 3<5 & 3>1 => root-sol-sol-sağ->3 
- 6 değeri 6<7 & 6>5 => root-sol-sağ-> 6
- 0 değeri 0<1 => root-sol-sol-sol-sol-> 0
- 9 değeri 8<9 => root-sağ-> 9
- 4 değeri 4<5 & 4>3 => root-sol-sol-sağ-sağ-> 4
- 2 değeri 2<3 & 2>1 => root-sol-sol-sağ-sol-> 2