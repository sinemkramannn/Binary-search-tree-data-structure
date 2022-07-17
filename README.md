# Binary-search-tree-yeri-yap-ları
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
root 7 dir.
5, 7'in solunda bulur çünkü kendisinden küçüktür.
1, 5'ten küçüktür.7'den de küçüktür bu yüzden 7 nin solunda ve 5 inde solunda kalır.
8, 7'den büyüktür bu yüzden 7'nin sağında kalır.
3 ,7 den küçüktür.7'nin solunda kalır. 5'ten küçük 5 in solunda kalır.1'den büyüktür 1 in sağında kalır.
6, 7 den küçük 7 nin solunda kalır.1'den büyük olduğu için 1'in sağında kalır.
0, 7 den ve diğer rakamlardan küçük olduğu için 7 nin solunda kalır. Diğer rakamlarında solunda kalır.
9, 7 den büyüktür.7'nin sağında kalır.8 den de büyüktür.8'in sağında kalır.
4, 7 den küçüktür 7 nin solunda kalır 3'den büyük olduğu için 3'ün sağında kalır.
2, 7 den küçük olduğu için 7 nin solunda kalır.3 ten küçük olduğu için 3'ün solunda kalır.

sonuç olarak bu şekilde :

       7
     /   \
    5     8
   / \     \
  1   6     9  
 /  \
0    3
    /  \
    2   4
