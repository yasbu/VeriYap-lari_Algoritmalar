# PROJE 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


**1. Adım**
Root (7)'dir

**2. Adım**
(5) sayısı (7)'den küçük olduğundan solunda bulunur

      7
     /
    5
**3. Adım**
(1) sayısı (7) ve (5)'den küçük olduğundan (5)'in soluna yerleşir.

        7
       /
      5
     /
    1
**4. Adım**
(8) sayısı (7)'den büyük olduğundan sağına yerleşir

        7
       / \
      5   8
     /
    1

**5. Adım**
(3) sayısı (7),(5)'ten küçük olduğundan sola ve (1)'den büyük olduğundan sağına yerleşir.

        7
       / \
      5   8
     /
    1
     \
      3  

**6. Adım**
(6) sayısı (7)'den küçük olduğundan sola ve (5)'ten büyük olduğundan (5)in sağına yerlerşir.

        7
       / \
      5   8
     / \
    1   6
     \
      3  

**7. Adım**
(0) sayısı (1)'in soluna yerleşir.

          7
         / \
        5   8
       / \
      1   6
     / \
    0   3  

**8. Adım**
(9) sayısı (8)'in sağına yerleşir.

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3  

**9. Adım**
(4) sayısı (3)'ün sağına yerleşir.

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
         \
          4  

**10. Adım**
(2) sayısı (3)'ün soluna yerleşir.

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4 