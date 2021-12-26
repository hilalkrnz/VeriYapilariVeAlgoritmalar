# VeriYapilariVeAlgoritmalar
Bu repository [Patika](https://app.patika.dev/moduller/veri-yapilari-ve-algoritmalar) Veri Yapıları ve Algoritmalar eğitimi için hazırlamıştır.

<details><summary>Ödev1</summary>
<p>
  
  [22,27,16,2,18,6] -> Insertion Sort
  
 ###### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  ```
[22,27,16,2,18,6] -> (n)
[2,27,16,22,18,6] -> (n-1)
[2,6,16,22,18,27] -> (n-2)
[2,6,16,18,22,27] -> (1)
  ```
 ###### 2. Big-O gösterimini yazınız.
  ```
  = n + (n-1) + (n-2) + 1
  = n * (n+1) / 2
  = O(n^2)
  ```
 ###### 3. Time Complexity:
  ######  - Average case: Aradığımız sayının ortada olması
  ```
  [2,6,16,18,22,27] -> 16 - 18
  ```
   ######  - Worst case: Aradığımız sayının sonda olması
  ```
   [2,6,16,18,22,27] -> 27
  ```
   ######  - Best case: Aradığımız sayının dizinin en başında olması
  ```
  [2,6,16,18,22,27] -> 2
  ```
###### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   ```
  Average Case
   ```
###### 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
  ```
  [7,3,5,8,2,9,4,15,6] -> n
  [2,3,5,8,7,9,4,15,6] -> (n-1)
  [2,3,4,8,7,9,5,15,6] -> (n-2)
  [2,3,4,5,7,9,8,15,6] -> (n-3)
  ```
  </p>
</details>

  <details><summary>Ödev2</summary>
<p>
  
  [16,21,11,8,12,22] -> Merge Sort
  
###### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
  ```
          [16,21,11,8,12,22]
       [16,21,11]      [8,12,22]
      [16]  [21,11]   [8]  [12,22]
    [16]  [21]  [11]  [8]  [12]  [22]
  -------------------------------------
      [16]  [11,21]   [8] [12,22]
        [11,16,21]   [8,12,22]
          [8,11,12,16,21,22]
  ```
 ###### 2. Big-O gösterimini yazınız.
  ```
  O(nlogn)
  ```
  </p>
</details>

  <details><summary>Ödev3</summary>
<p>
  
  [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
  ```
  Verilem dizi küçükten büyüğe sıralanır -> [0,1,2,3,4,5,6,7,8,9]
  Root 5 seçilir.
  Roottan yani 5'ten büyük elemanlar sağına, küçük elamanlar ise soluna koyulur ve bir ağaç yapısı oluşturulur.  
  ```
  
  
  
  
  
  


