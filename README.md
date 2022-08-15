# Prpject-Binary-Search-Tree
Veri Yapıları ve Algoritmalar Dersi Binary Search Tree Projesi

## 1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları :

- Root : 7 olarak seçiyoruz
- 1. 7 > 5 olduğundan 5 7 nin sol tarafına geçer.
- [5,7,1,8,3,6,0,9,4,2]
- 2. 7>1 5>1 olduğundan 1 5 ve 7 nin sol tarafına geçer.
- [1,5,7,8,3,6,0,9,4,2]
- 3. 8>7 olduğundan sağ tarfında kalır ve bir sonraki işleme geçilir.
- 4. 7>3 5> olduğundan 3 5 ve 7 nin sol tarafına geçer.
- [1,3,5,7,8,6,0,9,4,2]
- 5. 7>6 olduğundan 6 7 nin sol tarafına geçer.
- [1,3,5,6,7,8,0,9,4,2]
- 6. '0' da yine sırasıyla 7,6,5,3,1 den kuçuk olduğu için en başa yazılır.
- [0,1,3,5,6,7,8,9,4,2]
- 7. '4' 7,6,5 den kucuk olduğu için 5 ten bir önce yazılır.
- [0,1,3,4,5,6,7,8,9,2]
- 8. '2' sayısıda yine 7,6,5,4,3 den kucuk olduğundan 3 den önce yerini alır.
- [0,1,2,3,4,5,6,7,8,9] 
