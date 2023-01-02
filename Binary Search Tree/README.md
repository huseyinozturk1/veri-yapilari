# Binary Search Tree Projesi

* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

----
## Sonuç:

* Binary Search Tree de mantık bir root seçilir bu roota göre gelen sayılar büyük ise sağ tarafına, küçük ise sol tarafına yazılır.

* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizideki root sayımız 5 olsun.

* 3 sayısı 5 sayısından küçük olduğu için soluna 7 sayısı 5 sayısından büyük olduğu için sağına yazarız.
````
      5
     / \
    3   7
````
* 2 sayısı 3 sayısından küçük olduğu için soluna 4 sayısı 3 sayısından büyük olduğu için sağına yazarız. Aynı şekilde 6 sayısı 7 sayısından küçük olduğu için soluna 8 sayısı 7 sayısından büyük olduğu için sağına yazarız.
````
        5
       / \
      /   \
     3     7
    / \   / \ 
   2   4 6   8
   ````

* Son olarak 1 ve 9 sayılarımızı ekleyerek Binary Search Tree yapımızı oluşturalım.

````
        5
       / \
      /   \
     3     7
    / \   / \ 
   2   4 6   8
  /           \ 
 1             9 
 ```` 

