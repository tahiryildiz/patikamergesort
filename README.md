# patikamergesort
Merge Sort Projesi

### Girdi
[16,21,11,8,12,22] 

### İstenenler
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

### 1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Dizi tek eleman kalana kadar bölünüyor.
[16,21,11,8,12,22] 

[16,21] [11] [8,12] [22]

[16] [21] [11] [8] [12] [22]

Sonra birleştiriliyor

[16,21] [11] [8] [12,22]

[11,16,21] [8,12,22]

[8,11,12,16,21,22] 

### 2- Big-O gösterimini yazınız.

O(nLogn)