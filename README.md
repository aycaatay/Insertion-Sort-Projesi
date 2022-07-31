# Insertion-Sort-Projesi
# [22,27,16,2,18,6] -> Insertion Sort
# Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
# ÇÖZÜM: En küçük eleman bulunur (2) ve başa yazılır, 22 ile 2 sayıları yer değiştirir.
# [2,27,16,22,18,6] sonrasında 2.satıra geçilir ve 2. en küçük sayıya bakılır(6) ve yer değiştirir. 
# [2,6,16,22,18,27] 
# [2,6,16,18,22,27]
# Big-O gösterimini yazınız.
# # ÇÖZÜM:n+(n-1)+(n-2)+.....+1 => n(n+1)/2= (n^2+n)/2 katsayısı en büyük olan n^2 olduğu için O(n^2)
# Time Complexity:
# ÇÖZÜM: O(n^2)
# Average case: Aradığımız sayının ortada olması:
# ÇÖZÜM: O(n^2) [2,6,16,18,22,27]
# Worst case: Aradığımız sayının sonda olması: 
# ÇÖZÜM: O(n^2) [27,22,18,16,6,2]
# Best case: Aradığımız sayının dizinin en başında olması.
# ÇÖZÜM: O(n) [2,6,16,18,22,27] Aradığımız sayıyı ilkinde bulmamız.
# Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
# ÇÖZÜM: 18 sayısı 4.sırada olduğu için average case kapsamına girer.
# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
# ÇÖZÜM: en küçük eleman (2) en başa gelir.
# 1.[2,3,5,8,7,9,4,15,6] 
# 2.[2,3,5,8,7,9,4,15,6] 2'den sonraki en küçük eleman olan 3 sabit kalır. Sonrasında 4 gelir.
# 3.[2,3,4,8,7,9,5,15,6]
# 4.[2,3,4,5,7,9,8,15,6] ilk 4 aşama bu şekilde sıralanır.
# www.patika.dev
