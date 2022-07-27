# Merge Sort Projesi #

[16,21,11,8,12,22] -----> Merge Sort

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2) Big-O gösterimini yazınız.


SORT TÜRÜNE GÖRE AŞAMALARI

[16,21,11,8,12,22] 

İlk olarak dizi ikiye bölünmelidir.

[16,21,11] ve [8,12,22] 

Tek eleman kalıncaya kadar bölünmeye devam edilir.

[16],[21,11]  ve  [8],[12,22]

Küçükten büyüğe birleştirme işlemi yapılır.

[16] - [21], [11]  ve  [8] - [12], [22] 

Kendi aralarında birleştirme devam eder.

[16] - [11,21]  ve  [8] - [12,22]  

[11,16,21] ve [8,12,22] 

Sıralamanın son hali bu şekildedir.

[8,11,12,16,21,22] 

*Big O Gösterimi

Her adımda n kadar işlem yapılmaktadır. 

Yukarıdan aşağı işlem sayısı 2^x = n ----> logn olduğu için O(nlogn)

https://app.patika.dev/
