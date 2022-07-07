# MERGE SORT PROJESİ [Patika Hesabım](https://app.patika.dev/semanuryabaci)

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

### 1. Sorunun Cevabı

                          [16,21,11,8,12,22]
                            /            \
                       [16,21,11]      [8,12,22]
                         /   \           /   \
                     [16,21]  [11]     [8,12] [22]
                     /    \     \      /   \     \
                   [16]  [21]  [11]  [8]  [12]  [22]
                     \    /     /     \    /     / 
                    [16,21]  [11]    [8,12]   [22]
                        \     /         \      /
                      [11,16,21]        [8,12,22]
                           \                /
                           [8,11,12,16,21,22]
                           
### 2. Sorunun Cevabı

**Merge Sort Algoritması Big-O Gösterimi:** O(nlogn) 
