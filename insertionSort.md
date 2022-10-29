# Project 2
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 

|Steps|Divided & Merged Schema|
|:--:|:--:|
| Seçili diziyi sol ve sağ alt dizilere böl              |[16,21,11,8,12,22]|
| Divide2                                                |[16,21,11] - [8,12,22]|
| Divide3                                                |[16] - [21,11] - [8] - [12,22]|
| Divide4                                                |[16] - [21] - [11] - [8] - [12] - [22]|
| Bunları sıralı bir şekilde aynı şekilde birleştirin    |[16] - [21,11] - [8] - [12,22]|
| Merge2                                                 |[11,16,21] - [8,12,22]|
| Merge3                                                 |[8,11,12,16,21,22]|

2. Write the Big-O notation.

> O(nlogn)