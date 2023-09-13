# Binary Search Tree Project

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1-) Dizisinin Binary-Search-Tree aşamalarını yazınız.
```
Root 7
Root 5 --> Soluna 
Root 1 --> Soluna --> 5'nin soluna
Root 8 --> Sağına 
Root 3 --> Soluna --> 5'nin Soluna --> 1'nin Sağına
Root 6 --> Soluna --> 5'nin sağına
Root 0 --> Soluna --> 5'nin soluna --> 1'nin Soluna
Root 9 --> Sağına --> 8'nin sağına 
Root 4 --> Soluna --> 5'nin soluna --> 1'nin sağına --> 3'ün sağına
Root 2 --> Soluna --> 5'nin soluna --> 1'ni soluna --> 3'ün soluna
```
-----------------------

# Dizinin Şema İle Gösterimi

               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
            / \
           2   4