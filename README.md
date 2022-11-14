# BINARY SEARCH TREE
....

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

**ROOT : 5 olarak belirledim.

 3, 5 den küçük soluna gelir
 1, 5 den küçük soluna 3 ten küçük onunda soluna 
 7, 5 den büyük sağına
 4, 5 den büyük sağ 
 2, 5 den küçük soluna 1 den büyük sağına
 0, 5,2 den küçük soluna 2 den de küçük soluna
 6, 5 den büyük sağına 7 den küçük soluna
 8, 5 den büyük sağına 
 9, 5 ve 8 den büyük sağına

                       5
                    /     \
                  3         7
               /  \      /   \ 
             1      4    6      8
            /                     \
          / \                       9
         0   2
