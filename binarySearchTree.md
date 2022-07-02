# Proje 3
## Soru 1
## 1- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
## Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## 1- 
    *[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 1. eleman pivot seçildi.
    *               7   pivot seçildi
    *[5,1,3,6,0,4,2]                   *[8,9]
    *               5 pivot seçildi
    *[1,3,0,4,2]                       *[6]
    *               1 pivot seçildi
    *[0]                                *[3,4,2]   
    *               3 pivot seçildi
    *[2]                                *[4]    



    Çizimi:
                                  7
                                /   \
                               5     8
                             /   \    \
                            1     6    9
                          /   \
                         0     3
                             /   \
                            2     4