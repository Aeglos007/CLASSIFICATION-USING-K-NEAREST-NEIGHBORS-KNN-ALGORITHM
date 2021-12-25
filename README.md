# KNN-Algo
CLASSIFICATION USING K-NEAREST NEIGHBORS (KNN) ALGORITHM 

//The platform, version, and programming language used 

1)KNN ile sınıflandırma 
1.1 Algoritma 


2) Banknot sınıflandırma
 2.1) Kodlar 
 ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/raycast-untitled.png)
 2.2) Ekran görüntüleri 

  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/Aspose.Words.891b2d01-03c1-4bea-93d8-b1f4382ea76b.008.jpeg)

2.3) Açıklama 

Bu bölümde bizden istenen tabloyu oluşturmak için WriteTheMoneys adlı bir fonksiyon oluşturduk bu fonk. test edilmiş para veya paraları  içeren bir parametre ile yine bu test paralarına komşu olan en yakın k tane parayı içeren bir parametre daha alır.Komşuları içeren parametre for döngüsüne sokulur.Print ve format yardımıyla bilgiler ekrana yazdırılır.Finalde söz konusu banknotun tahmini türü ekrana yazdırılır. 

3) Başarı ölçümü 
  3.1) Kodlar 
  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/raycast-untitled%20(1).png)



  3.2 Ekran görüntüleri 

  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/Aspose.Words.891b2d01-03c1-4bea-93d8-b1f4382ea76b.009.jpeg)

  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/Aspose.Words.891b2d01-03c1-4bea-93d8-b1f4382ea76b.010.jpeg)

  3.3) Açıklama 

  SuccessTesting fonksiyonunu oluşturdum.Fonksiyon veritibanındaki verileri 2 boyutlu liste olarak alıyor.İlk olarak paraları parametre olarak aldık. Sonra test için k değişkenini alıyorum bunu başarı testi fonksiyonuna gönderiyorum .Sahte paralarla gerçekleri 2 ayrı listeye atıyoruz.Sonra her iki testin elemanlarının son 100’ünü ayırıyoruz.Geriye kalanları test paralarıyla teker teker karşılaştırmak için saklıyorum.Test paraları for döngüsüne girer.Oradan da her para için kNN fonksiyonu çağırılır.kNN fonk.da o anki test parası haricinde kalan paralarla karşılaştırmak için sakladığımız bütün paralar liste olarak gönderilir ve daha önceden test için  aldığımız k değişkeni de kNN fonk.a parametre olarak eklenir.kNN fonkdan dönen sonuç bir değişkene atanır.Değişken WriteTheMoneys fonk.una gönderilirek sonuçların yazdırılması sağlanır.Bu işlerden sonra söz konusu banknotun gerçek türü  konsola yazdırılır.Ek olarak for döngüsüne söz konusu banknotun gerçek değeri ile kNN tarafından oluşturulmuş tahmini değerin eşit olma koşulunu belirten bir if eklenir. Bu if yapısı her seferinde gerçek değeri ile tahmini değerinin birbirine eşit olduğu paraları tutan değişkenin sayısını bir arttırır.Bu işlem for döngüsü sayesinde 200 test parasının tamamına yapılır.Finalde gerçek değeri ile tahmini değerinin örtüştüğü paraların tüm test paralarına oranı  yazdırılır. 

4) Listeleme
  4.1) Kodlar 
  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/raycast-untitled%20(2).png)



  4.2) Ekran görüntüleri 

  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/Aspose.Words.891b2d01-03c1-4bea-93d8-b1f4382ea76b.011.jpeg)

  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/Aspose.Words.891b2d01-03c1-4bea-93d8-b1f4382ea76b.012.jpeg)

  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/Aspose.Words.891b2d01-03c1-4bea-93d8-b1f4382ea76b.013.jpeg)

  ![](https://github.com/Aeglos007/CLASSIFICATION-USING-K-NEAREST-NEIGHBORS-KNN-ALGORITHM/blob/main/images/Aspose.Words.891b2d01-03c1-4bea-93d8-b1f4382ea76b.014.jpeg)

  4.3) Açıklama 

  WriteTheDataBase kısmında veri olarak paraları alıyorum.Paralardan oluşan listeyi for döngüsüne koydum.Format ve print yardımıyla yazdırmış oldum. 
