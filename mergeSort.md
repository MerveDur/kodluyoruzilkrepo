# Proje 2
## Soru 1
## [16,21,11,8,12,22] -> Merge Sort
## 1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
## 2-Big-O gösterimini yazınız.

## 1- 
    * [16,21,11,8,12,22] Dizi tek elemana düşene kadar ikiye bölünerek gider ve bu elemanlar arasında sıralaması yapılır daha sonra tekrar birleştirilir

    1-                            * [16,21,11,8,12,22]
    2-            * [16,21,11]                                *[8,12,22]
    3-        * [16,21]       *[11]                       *[8,12]        * [22]
    4-            * [11,16,21]                                 *[8,12,22]
    5-                            *[8,11,12,16,21,22]

## 2-
    Merge sort algoritmasının time complexity si : O(n*(logn)) 