# PROJE 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1. Verilen Dizinin Sort Türüne Göre Aşamaları

**1. Adım (n):** İlk sayıdan bahsettiğimiz için ( 22 ) kendi başına sıralıdır. Hiç bir işlem yapmadan devam eder.

22 | 27 16 2 18 6

**2. Adım (n-1):** (22) sayısı (27) sayısından küçük olduğundan bir işlem yapılmaz. 

22 27 | 16 2 18 6

**3. Adım (n-2):** (16) sayısı öncelikle (27) ile kıyaslanır. (16) küçük olduğundan yer değiştirir. (16) sonra (22) ile kıyaslanır ve küçük olduğundan yer değiştirir. 

22 27 16 | 2 18 6 ==> 22 16 27 | 2 18 6 ==> 16 22 27 | 2 18 6

**4. Adım (n-3):**

16 22 27 2 | 18 6 ==> 16 22 2 27 | 18 6 ==> 16 2 22 27 | 18 6 ==> 2 16 22 27 | 18 6

**5. Adım (n-4):**

2 16 22 27 18 | 6 ==> 2 16 22 18 27 | 6 ==> 2 16 18 22 27 | 6

**6. Adım (1):**

2 16 18 22 27 6 ==> 2 16 18 22 6 27 ...==>... [2,6,16,18,22,27]


## 2. Big-O Gösteri

(n(n-1))/2 = (n^2-n))/2 ==> O(n^2)

## 3. Time Complexity

**Average case:** O(n^2)

**Worst case:** O(n^2)

**Best case:** O(n)

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

[2,6,16,18,22,27] sayı setinde (18) sayısı ortada olduğundan average case kapsamında yer alır

## 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

7 | 3 5 8 2 9 4 15 6 ... (1. işlem)

3 7 | 5 8 2 9 4 15 6 ... (2. işlem)

3 5 7 | 8 2 9 4 15 6 ... (3. işlem)

3 5 7 8 | 2 9 4 15 6 ... (4. işlem)