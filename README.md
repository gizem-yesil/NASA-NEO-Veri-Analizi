# **Nasa Nearest Earth Objects Veri Analizi**


![41JPdO1w93L _AC_UF1000,1000_QL80_](https://github.com/user-attachments/assets/232c9247-594e-43ea-a87b-fc6d336ac0fc)

Bu proje, **Global AI Hub Aygaz Veri Analizi Bootcamp** kapsamında verilen veri seti üzerinde analiz yapmak amacıyla geliştirilmiştir. Projede Python ve popüler veri analizi kütüphaneleri kullanılarak, veri görselleştirme ve çıkarımlar elde etme işlemleri gerçekleştirilmiştir.


# Proje Özeti

- NASA NEO(Nearest Earth Objects) merkezi tarafından kaydedilen 90836 gök cismi hakkındaki bazı nitelikler incelenmiştir.
- Analiz edilen veri setinde hicbir eksik deger (null) bulunmamaktadir.
- Veriler, gök cisimlerinin Dünya'ya olan uzaklıkları, çapları, parlaklıkları, tehlikeli olup olmadıkları gibi özellikleri bulundurmaktadır.


# Veriye Genel Bakış

| Sütun              | Veri Sayısı | Veri Tipi |
|--------------------|-------------|-----------|
| id                 | 90836       | int64     |
| name               | 90836       | object    |
| est_diameter_min   | 90836       | float64   |
| est_diameter_max   | 90836       | float64   |
| relative_velocity  | 90836       | float64   |
| miss_distance      | 90836       | float64   |
| orbiting_body      | 90836       | object    |
| sentry_object      | 90836       | bool      |
| absolute_magnitude | 90836       | float64   |
| hazardous          | 90836       | bool      |


# Kullanılan Teknolojiler

Proje aşağıdaki Python kütüphanelerini kullanmaktadır:

- **Numpy**: Matematiksel işlemler ve dizilerle çalışma.
- **Pandas**: Veri işleme ve analiz.
- **Matplotlib**: Veri görselleştirme.
- **Seaborn**: Gelişmiş görselleştirme.


 # Projenin Amacı ve Yöntemi

 Projede, NASA'nın kayıt altına aldığı, Dünya yakınlarındaki gök cisimleri hakkındaki bazı nitelikler yer almaktadır. Analizin amacı, bu gök cisimlerinin Dünya'ya olan etkilerinin tespit edilmesinde bakılan parametreleri incelemek, tehlikeli-tehlikesiz olarak sınıflandırılmasında kullanılacak bir sınıflandırma ML modelinden önce veriyi , veri analizi teknikleriyle anlamaktır.

Kaggle Linki: https://www.kaggle.com/code/gizemyesil/global-ai-hub-aygaz-veri-analizi-bootcamp
