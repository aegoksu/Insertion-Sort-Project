# Insertion-Sort-Project

Patika Dev Profile: https://app.patika.dev/aegoksu


## PROJECT 1 
[22,27,16,2,18,6] -> Insertion Sort

  1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  2. Big-O gösterimini yazınız.
  3. Time Complexity: 
      -Average case: Aradığımız sayının ortada olması,
      -Worst case: Aradığımız sayının sonda olması, 
      -Best case: Aradığımız sayının dizinin en başında olması.
  4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


### 1. INSERTION SORT ###
Veri örüntüsüne göre en küçük sayı bulunuyor ve en sola alınarak ilerleniyor.
"According to the data pattern, the smallest number is found and it is moved forward by moving it to the left."

    [22, 27, 16, 2, 18, 6] 
    [*2|, 27, 16, *22, 18, 6]
    [2, *6|, 16, 22, 18, *27] 
    [2, 6, 16|, 22, 18, 27] 
    [2, 6, 16, *18|, *22, 27] 
    [2, 6, 16, 18, 22|, 27]
    
### 2. BIG-O ###

     O(n^2)
    
### 3. TIME COMPLEXITY ###

    Average case: The number we are looking for is in the middle.
    Worst case: The number we are looking for is at the end.
    Best case: The number we are looking for is at the beginning.

### 4. Which case will 18 be taken from after the series is sorted? Write. ###

    Average case -> [2, 6, 16, 18, 22, 27] 

### BONUS [7,3,5,8,2,9,4,15,6] ###
Write the first 4 steps of the array according to the Insertion Sort.

    First step: [2| , 3, 5, 8, 7, 9, 4, 15, 6]
    Second step: [2, 3| , 5, 8, 7, 9, 4, 15, 6]
    Third step: [2, 3, 4| , 8, 7, 9, 5, 15, 6]
    Fourth step: [2, 3, 4, 5| , 7, 9, 8, 15, 6]
