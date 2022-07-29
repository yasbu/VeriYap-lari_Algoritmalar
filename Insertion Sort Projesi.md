# PROJE 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1. Verilen Dizinin Sort Türüne Göre Aşamaları

**1. Adım:** İlk sayıdan bahsettiğimiz için ( 22 ) kendi başına sıralıdır. Hiç bir işlem yapmadan devam eder.

22 | 27 16 2 18 6

**2. Adım:** (22) sayısı (27) sayısından küçük olduğundan bir işlem yapılmaz. 

22 27 | 16 2 18 6

**3. Adım:** (16) sayısı öncelikle (27) ile kıyaslanır. (16) küçük olduğundan yer değiştirir. (16) sonra (22) ile kıyaslanır ve küçük olduğundan yer değiştirir. 

22 27 16 | 2 18 6 ==> 22 16 27 | 2 18 6 ==> 16 22 27 | 2 18 6