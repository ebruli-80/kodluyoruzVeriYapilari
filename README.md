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
