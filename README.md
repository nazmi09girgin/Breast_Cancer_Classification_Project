# Breast Cancer Classification Project
Bu proje, Breast Cancer Wisconsin (Diagnostic) Data Set'ini kullanarak, meme kanserinin teşhisini yapmayı amaçlayan çeşitli makine öğrenimi modelleri uygulamaktadır. Veri seti, kanserli tümörlerin teşhisini iki sınıfa ayırır: Benign (iyi huylu) ve Malignant (kötü huylu). Proje, bu verileri kullanarak farklı sınıflandırma algoritmalarının performansını karşılaştırmaktadır.

 Veri Setinin Genel Özellikleri:  
 
Veri Kümesi Adı: Breast Cancer Wisconsin (Diagnostic)  
Toplam Gözlem (satır) Sayısı: 569  
Toplam Özellik (sütun) Sayısı: 32 (ID ve tanı dahil)  
Hedef (target) Değişkeni: diagnosis (M = malignant, B = benign)  

Veri setindeki özellikler, tümör hücrelerinin çekirdeği üzerinde yapılan görüntü işleme analizlerinden elde edilmiştir. Her hücre için şu üç temel istatistiksel ölçüm çıkarılmıştır:  

Mean (ortalama) değerleri  
Standard error (standart hata) değerleri  
"Worst" (en büyük 3 değer ortalaması)  


Proje Adımları:  

1)Veri yükleme ve ön işleme

2)Verinin analiz edilmesi ve görselleştirilmesi

3)Veri setinin eğitim ve test setlerine bölünmesi

4)Verilerin standartlaştırılması

5)Farklı makine öğrenimi modellerinin uygulanması:  
 Logistic Regression  
 K-Nearest Neighbors (KNN)  
 Decision Tree  
 Random Forest  

6)Modellerin performansının değerlendirilmesi ve karşılaştırılması

7)Sonuçların görselleştirilmesi (Confusion Matrix)  

Sonuç:  
Bu projede kullanılan makine öğrenimi modellerinin doğruluk oranları karşılaştırılarak ve her model için Confusion Matrix çıktıları görselleştirilmiştir. Elde edilen sonuçlar doğrultusunda, meme kanseri teşhisi için en uygun model belirlenmiştir.
