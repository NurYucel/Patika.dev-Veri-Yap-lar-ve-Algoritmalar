# Binary Search Tree Projesi
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 
 
 ---
 
 ### 1.Yukarı verilen dizinin binary search tree türüne göre aşamalarını yazınız.
 
 
 ```
 root=7
 5 sayısı 7'den küçük olduğu için ağacın soluna eklenir.
    7
  /
5

1 sayısı 5 ve 7'den küçük olduğu için 5'in soluna eklenir.
        7
      /
    5
  /
1

8 sayısı 7'den büyük olduğu için 7'nin sağına yazılır.
        7
      /  \
    5      8
  /
1

3 sayısı 7 ve 5!ten küçük 1'den büyük, 1'in sağına yazılır.
        7
      /  \
    5      8
  /
1
  \
    3

6 sayısı 7'den küçük 5'ten büyük, 5'in sağına yazılır.
        7
      /  \
    5      8
  /  \
1      6
  \
    3

0 sayısı 7,5,1'den küçük,1'in soluna yaızlır.
            7
          /  \
        5      8
      /  \
    1      6
   / \
  0    3

9 sayısı 7 ve 8'den büyük, 8'in sağına yazılır.
            7
          /  \
        5      8
      /  \      \
    1      6     9
   / \
  0    3
    
4 sayısı 7 ve 5'ten küçük 1 ve 3'ten büyük, 3'ün sağına yazılır.
            7
          /  \
        5      8
      /  \      \
    1      6     9
   / \
  0    3
        \
         4

2 sayısı 7ve 5'ten küçük 1'den büyük, 3'ten küçük,3'ün soluna yazılır.
            7
          /  \
        5      8
      /  \      \
    1      6     9
   / \
  0    3
      / \
     2    4    

 ```

[Patika.dev](https://www.patika.dev/tr)