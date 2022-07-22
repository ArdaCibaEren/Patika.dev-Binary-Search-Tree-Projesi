# Patika.dev Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Dizisinin Binary Search Tree Aşamaları
* Root dizinin en solundaki 7 seçilir. 7'den büyük olan sayılar sağ tarafına, küçük olanlar sol tarafına yazılır.

``` 
1.adım
              7
             /
            5
            
2.adım           
              7
             /
            5
           /
          1
         
3.adım        
             7
            / \
           5   8
          /
         1   
         
4.adım         
             7
            / \
           5   8
          /
         1
          \
           3
           
5.adım           
              7
             / \
            5   8
           / \
          1   6
           \
            3
            
6.adım             
              7
             / \
            5   8
           / \
          1   6
         / \
        0   3
        
7.adım        
              7
             / \
            5   8
           / \   \
          1   6   9
         / \
        0   3
        
8.adım        
               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
              \
               4

Son adım
               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
            / \
           2   4