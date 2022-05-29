# BINARY SEARCH TREE PROJECT for PATIKA.DEV
---
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Dizilim için Binary-Search Tree

* En baştaki sayı 7 olduğu için root 7'dir.
* Sırasıyla 7'den küçük sayılar sola, büyük sayılar ise sağa yazılır. Binary Search Tree oluşturulurken Roottan aşağı inildikçe (varsa) her bir alt satırdaki parent için sayı tekrar değerlendirilir.

* 7>5 olduğu için 5 sola yazılır.
```
        7
       /
      5
```
* 1<7 ve 1<5 olduğu için hem 5'in hem 7'nin soluna yazılır.

```
        7
       /
      5
     /
    1
```

* 7>8 olduğu için 7'nin sağına yazılır.

```
        7
       / \
      5   8
     /
    1
```

* 3<7 ve 3<5 olduğu için hem 5'in hem 7'nin soluna yazılır. Ancak 3>1 olduğu için 1'in sağına yazılır.

```
        7
       / \
      5   8
     /
    1  
     \
      3
```

* 6<7 ve 5<6 olduğu için önce 5'in sağına yazılır.

```
        7
       / \
      5   8
     / \
    1   6
     \
      3
```

* 0<7 ve 0<5 ve 0<1  olduğuna göre 0 en sola yazılır.

```
        7
       / \
      5   8
     / \   
    1   6
   / \
  0   3
```

* 7<9 ve 8<9 olduğuna göre 9 en sağa yazılır.

```
        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
```
* Sırasıyla 4<7 , 4<5 , 1<4 , 1<4 , 3<4 olduğuna göre 4 3ün altında sağa yazılır.

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
* Son olarak  2<7 , 2<5 , 1<2 , 2<3 olduğuna göre 2 3ün altında sola yazılır.

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
```
* İşlem tamamlandı.

---
### License
[MIT](https://choosealicense.com/licenses/mit/)
