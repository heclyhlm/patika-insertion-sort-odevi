# patika-insertion-sort-odevi
[22,27,16,2,18,6] -> Insertion Sort

Insertion sort için ilk elemanı sıralı kabul ediyorum ve sıranın 2.sinden ilerliyorum

[27] , elemanı [22]'den büyük olduğu için orada kalıyor. 16'dan devam ediyorum

[16], [22] den küçük olduğu için onu en başa alıyorum ve sıralı liste şöyle oluyor;

[16, 22,27, 2, 18, 6] 

[2]den devam ediyorum 2,16'dan küçük olduğu için onu 16'nın soluna alıyorum. Yeni sıra;

[2, 16, 22, 27, 18, 6] 

[18] den devam ediyorum 16' dan büyük bu nedenle 16'nın sağına alıyorum:

[2, 16, 18, 22, 27, 6]

daha sonra son eleman 6 kalıyor ve 2'den büyük olduğu için 2'nin sağına yazıyorum

**Sonuç= [2,6,16,18,22,27]**


Time Complexity: Aradığımız 18 sayısının durumunu gösterir
18, dizinin ortasında olduğu için **average case**



# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı


1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
   
   
