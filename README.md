# Merge Sort Projesi www.patika.dev

**Patika - Veri Yapıları ve Algoritmalar Dersinin Merge Sort Projesidir www.patika.dev**

## Merge Sort Projesi

----------------------------

   [16,21,11,8,12,22] -> Merge sort
   
### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

    1. Aşama =>     [16,21,11]  [8,12,22] -> İlk önce dizimizi ikiye bölerek başlıyoruz.
    2. Aşama =>   [16] [21,11]  [8,12] [22] -> Tek eleman kalana kadar bölmeye devam ediyoruz.
    3. Aşama => [16] [21] [11]  [8] [12] [22] -> Elemanları tamamen parçaladığımızda sıralama işlemine geçiyoruz.
    4. Aşama =>   [16] [11,21]  [8,12] [22] -> Adım adım birleştiriyoruz.
    5. Aşama =>     [11,16,21]  [8,12,22] -> Bütün elemanlar sıralı hale gelene kadar birleştirmeye deva ediyoruz.
    6. Aşama =>       [8,11,12,16,21,22] -> Artık dizinimiz sıralı hale geldiği için işlemi burada bitiriyoruz.
    
----------------------------
 
### 2. Big-O gösterimini yazınız.

- Big-O gösterimi **O(nlogn)** şeklindedir.
