# Merge Short 

## [16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Adımlar | Böl-Birleştir
-- | --
Adım 1 Böl | [16,21,11] - [8,12,22]
Adım 2 Böl | [16,21] - [11] - [8,12] - [22]
Adım 3 Böl | [16] - [21] - [11] - [8] - [12] - [22]
Adım 4 Birleştir | [16,21] - [11] - [8,12] - [22]
Adım 5 Birleştir| [11,16,21] - [8,12,22]
Adım 6 Birleştir | [8,11,12,16,21,22]

2. Big-O gösterimini yazınız.

 O(nlogn)
