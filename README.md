-# patika_dev_insertion_sort_projesi
+{patika.dev] (https://www.patika.dev/tr)
+
+
+## {22,27,16,2,18,6]-> insertion sort

+## 1.Yukarı'da verilen diziyi sort türüne göre yazınız
+     - {22,27,16,2,18,6}   n
+     - {2,27,16,22,18,6}   n-1
+     - {2,6,16,22,18,27}   n-2
+     - {2,6,16,18,22,27}    1
+
+## 2.Big-O gösterimini yazınız.
+     -(n.(n+1))/2
+     -(n^2+n)/2
+     - O(n^2)

+## 3.time complexity:
+   - Avarge case: Aradığımız sayının ortada olması
+   - Wort case: Aradığımız sayının sonda olması
+   - Best case: Aradığımız sayının dizinin en başında olması
+
## 4.Dizi sıralandıktan sonra 18 sayıs hangi case kapsamına gire.
    - {2,6,16,18,22,17} Dizinin sıralanmış hali
    - Aradığımız sayı dizinin ortasında bulunuyor case olarak avarge case dir
    
    {7,3,5,8,2,9,4,15,6,} insertıon Sort'a göre ilk 4 adımı
    -{7,3,5,8,2,9,4,15,6} n
    -{2,7,5,8,3,9,4,15,6} n-1
    -{2,3,5,8,7,9,4,15,6} n-2
    -{2,3,4,8,7,9,5,15,6} n-3
