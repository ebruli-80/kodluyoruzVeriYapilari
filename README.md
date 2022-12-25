## Proje 1
[22,27,16,2,18,6]=> İnsertion short
ikinci sıradaki elemanı şeçiyoruz solundaki elemanla karşılaştırıyoruz 27 22'den küçükmü? 
27 22 'den küçük olmadığı için yer değiştirme olmuyor. Şimdi 27'yi 16 ile karşılaştırıyoruz, 16 27 den küçük mü?
evet küçük sırayla 16 önce 27 sonrada 22 den de küçük olduğu için en başa yerleşti. Artık dizimiz [16,22,27,2,18,6] şeklinde oldu. 
şimdi 27 yi 2 ile karşılaştırıyoruz 2 küçük sırayla sola doğru karılaştırarak uygun sıraya yerleştiriyoruz.
 [2,16,22,27,18,6] 18 27 den küçük mü? Evet 27 ve 18 yer değiştirir, 18 22 den küçük mü? evet yer değiştirir 18 16 dan küçük mü? hayır olduğu yerde kalır.
[2,16,18,22,27,6] son olarak 27 6 ile karşılaştırılır. dizinin son hali [2,6,16,18,22,27] şeklindedir.

## Big-O Gösterimi
O(n^2) dir.
## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
18 sayısı dizinin son elemanına yakın olduğu için Worst case' e girer.
## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
ilk eleman dizinin diğer elemanlarıyla karşılaştırılarak en küçük sayı bulunur ve ilk elemanla yer değiştirir.
[2,3,5,8,7,9,4,15,6] 1. sıralama
şimdi 3 ü diğerleriyle karşılaştırıyoruz.dizinin kalan kısmında kendinden küçük eleman olmadığı için yerinde kalıyor.
[2,3,5,8,7,9,4,15,6] 2. sıralama
sırada 5 var dizinin geri kalanıyla karşılaştırılır kendinden küçük 4'ü bulur daha küçük eleman olmadığı için yer değiştirir.
[2,3,4,8,7,9,5,15,6] 3.sıralama
[2,3,4,5,7,9,8,15,6] 4. sıralama



# Proje 2
### [16,21,11,8,12,22] -> Merge Sort dizinin sort türüne göre aşamalarını yazınız.
Üçlü gruplar şeklinde iki parçaya bölünür.
[16,21,11|8,12,22] şeklinde
bu gruplarda ikili şekilde ayrılır.
[16,21] [11] [8,12] [22] şeklini alır.
iki elemana kadar düştüğü için artık kendi içlerinde sıralanır ve birleştirilir.
[11,16,21] [8,12,22] şeklinde sıralandı ve birleştirildi.
[8,11,12,16,21,22] şeklinde sıralanmış oldu.
### Big-O gösterimini yazınız.
O(n log n) diziyi parçalayıp tekrar birleştirildiği için bütün durumları n log n dir. dolayısıyla big o su da n log n oldu.


## Proje 3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
 7 root düğümü. 5 ekleniyor ağaca 7 den küçük olduğu için sola ekleniyor.
 sonra 1 ekleniyor 7 den ve 5 ten küçük olduğu için en sola yerleşiyor.
 8 ekleniyor 7 den büyük olduğu için sağına yerleşir. 3 eklenir 1 in sağına yerleşir 6 5 in sağına yerleşir.
 0 1 in soluna yerleşir. 9 eklenir 8 in sağına yerleşir. 4 eklenir 3 ün sağına yerleşir.
 2 eklenir 3 ün soluna yerleşir.
