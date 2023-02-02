# Binary Search Tree

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Binary Search Tree Aşamaları
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisini soldan okumaya başlıyoruz.

İlk olarak 7 rakamından başlayıp, bunun Kök Boğum(Root Node) olduğunu düşünerek ilerleyelim.

```
7
```
```
   7
  /
 5 
```
```
    7
   /
  5
 /
1 
```
```
    7
   / \
  5   8
 /
1 
```
```
    7
   / \
  5   8
 / 
1  
 \
  3
```
```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
