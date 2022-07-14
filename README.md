# insertion_sort

1.insertion_sort asamalari
[22,27,16,2,18,6]   (n)
[2|,27,16,22,18,6]  (n-1)
[2,6|,16,22,18,27]  (n-2)
[2,6,16,18|,22,27]  (1)

2.Big-O Notation
O(n^2)

3.Time Complexity
Best Case: O(n)
Average Case: O(n^2)
Worst Case: O(n^2)

4. Dizi sıralandıktan sonra 18 sayısı ortada olduğu için Average Case kapsamındadır.



-->[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı:
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
