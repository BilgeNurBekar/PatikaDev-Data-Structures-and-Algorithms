# Patika.dev Binary Search Projesi 

[Patika.dev](https://www.patika.dev/tr)


## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Aşamalar

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizimiz soldan okunmaya başlanır. lk elemanımız root olur. Bundan sonra rootumuzdan küçük olan sayılarımızı sola büyük
olanları sağına yerleştirerek ilerleyeceğiz. 

Yeni sayımızı alt nodelara göre yeniden büyüklük küçüklük durumuna göre şekildeki gibi yerleştiririz.

*        7
        /
       5






*        7
        / 
       5   
      /
     1




*        7
        / \
       5   8
      /
     1       




*        7
        / \
       5   8
      / 
     1  
      \
       3      




*        7
        / \
       5   8
      / \
     1   6
      \
       3




*        7
        / \
       5   8
      / \
     1   6
    / \
   0   3




*        7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3




*        7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
        \
         4
         



*        7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
      / \
     2   4





       