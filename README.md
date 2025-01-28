Rice Leaf Disease Detection with Federated Learning
---
Bu proje, federated learning teknikleri kullanarak pirinç yaprağı hastalıklarının tespiti üzerine yapılan bir çalışmayı özetlemektedir.<br> Yapılan çalışmanın sonuçları, "Optimization Based Rice Leaf Disease Classification in Federated Learning" başlıklı makale ile karşılaştırılmış ve benzer performans elde edilmiştir. Aşağıda, kullanılan yöntemler, sonuçlar ve bu sonuçların makale ile olan uyumu detaylı bir şekilde açıklanmaktadır. <br>

Çalışmada, pirinç yaprağı hastalıklarını sınıflandırmak için kullanılan veri seti çeşitli görüntü işleme teknikleriyle ön işlenmiştir<br>

##Precision (Kesinlik) 

Çalışmamda elde edilen kesinlik değerleri, makalede belirtilen değerlerle uyumludur ve bazı epoch'larda (örneğin 40. ve 80. epoch'larda) makale değerlerinden daha yüksek sonuçlar göstermektedir. Bu durum, çalışmamın doğruluk açısından oldukça etkili olduğunu ortaya koymaktadır. 

Recall (Hatırlama) 

Hatırlama değerleri de benzer şekilde makalede belirtilen değerlere yakındır ve bazı epoch'larda (örneğin 40. ve 80. epoch'larda) daha yüksek sonuçlar elde edilmiştir. Bu, çalışmamın hastalıkları tanımada yüksek bir başarıya sahip olduğunu göstermektedir. 

F1 Score 

F1 skorları, çalışmamın hem kesinlik hem de hatırlama performansını yansıttığından, çalışmamın sonuçları makale ile büyük ölçüde uyumludur. Özellikle 40. ve 80. epoch'larda makale değerlerini aşarak daha iyi performans göstermiştir. 

MSE (Ortalama Kare Hatası) 

Bu çalışmanın MSE değerleri, makalede belirtilen değerlerle uyumludur ve bazı epoch'larda (örneğin 40. ve 80. epoch'larda) daha düşük sonuçlar göstermektedir. Bu, çalışmamın hata oranının düşük olduğunu ve doğru sınıflandırma yaptığını göstermektedir. 

RMSE (Kök Ortalama Kare Hatası) 

RMSE değerleri de benzer şekilde makale ile uyumludur. İlk epoch'ta biraz daha yüksek olsa da, sonraki epoch'larda makale ile uyumlu sonuçlar vermektedir. 
