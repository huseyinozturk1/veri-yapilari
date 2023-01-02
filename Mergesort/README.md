# Merge Sort Projesi

* [16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.
----
## Sonuç:

* Merge Sort'larda sayı dizisinde ki sayılar ortadan ikiye bölünerek birer birim olana kadar parçalanır. Birleşme esnasında ise küçükten büyüğe doğru sıralanarak işlemini tamamlar.

* Yani;
```
[16,21,11]-[8,12,22]

[16]-[21,11]---[8][12,22]

[16]-[21]-[11]---[8]-[12]-[22]

[16]-[11,21]---[8]-[12,22]

[11,16,21]---[8,12,22]

[8,11,12,16,21,22] olarak diziyi tamamlarız.
````

* Big-O n(logn) olur.