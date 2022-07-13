[22,27,16,2,18,6] -> Insertion Sort

### 1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

 [22|, 27, 16, 2, 18, 6]  -  n   
 [22, 27|, 16, 2, 18, 6]  -  n-1  
 [16, 22, 27|, 2, 18, 6]  -  n-2  
 [2, 16, 22, 27|, 18, 6]  -  n-3   
 [2, 16, 18, 22, 27|, 6]  -  1  
 [2, 6, 16, 18, 22, 27]   
 
 
### 2) Big-O gösterimini yazınız.

Best case    : O(n)
Average case : O(n^2)
Worst case   : O(n^2)


### 3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Worst case: [27, 22, 18, 16, 6, 2]  
Best case: [2, 6, 16, 18, 22, 27]


### 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average Case

### 5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

   [7| , 3, 5, 8, 2, 9, 4, 15, 6]
   [3, 7| , 5, 8, 2, 9, 4, 15, 6]
   [3, 5, 7| , 8, 2, 9, 4, 15, 6]
   [3, 5, 7, 8| , 2, 9, 4, 15, 6]
