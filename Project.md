# www.patika.dev
# Patika.DEV Insertion Sort Project

## [22,27,16,2,18,6] -> Insertion Sort
## 1 - Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
## 2 - Big-O gösterimini yazınız.
## 3 - Time Complexity: Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
## 4 - [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1- 
    [22,27,16,2,18,6] - (n)
    [2,27,16,22,18,6] - (n-1)
    [2,6,16,22,18,27] - (n-2)
    [2,6,16,18,22,27] - (n-3)

2- 
    (n)+(n-1)+(n-2)+(n-3)- - - - + 1

    n.(n+1)/2 = n²+n/2 = O(n²)

3- 
    Avarage Case

4-
    [7,3,5,8,2,9,4,15,6] - (n)
    [2,3,5,8,7,9,4,15,6] - (n-1)
    [2,3,4,8,7,9,5,15,6] - (n-2)
    [2,3,4,5,7,9,8,15,6] - (n-3)