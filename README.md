## Projenin kodlarına [buraya tıklayarak](https://colab.research.google.com/drive/1JJ2U_lN_2oaerinyd7RRujsKWo2dyhhr) ulaşabilirsiniz.
# Dlib ile Yüz Tespiti ve Bulanıklaştırma Projesi

## Açıklama
Bu proje, `dlib` kütüphanesi kullanarak resimlerdeki yüzleri tespit eden ve ardından bu yüzleri bulanıklaştıran bir Python uygulamasıdır. Uygulama, kullanıcıların gizliliğini korumak amacıyla yüzlerin görüntüden kaldırılmasını sağlar. Dlib, yüz tespiti ve makine öğrenimi uygulamaları için güçlü bir kütüphanedir.

## Özellikler
- **Yüz Tespiti**: Dlib'in ön yüz dedektörü ile görüntülerdeki yüzleri tespit eder.
- **Bulanıklaştırma**: Tespit edilen yüzlerin etrafındaki bölgeyi bulanıklaştırarak gizlilik sağlar.
- **Görselleştirme**: Tespit edilen yüzlerin etrafında dikdörtgen çizer.
- **Kolay Kullanım**: Basit ve anlaşılır bir kod yapısı ile kullanıcı dostu bir deneyim sunar.

## Kullanılan Teknolojiler

### İstemci
- **Python**: Proje Python dilinde geliştirilmiştir.
- **OpenCV**: Görüntü işleme ve analizi için kullanılan popüler bir kütüphane.
- **dlib**: Yüz tespiti ve makine öğrenimi uygulamaları için kullanılan bir kütüphane.
- **Google Colab**: Proje, bulut tabanlı bir ortamda çalıştırıldığı için kullanıcılar için erişim kolaylığı sağlar.

### Sunucu
- **Yerel Sunucu**: Proje, istemci tarafında çalıştırıldığından, herhangi bir sunucu yapılandırması gerektirmemektedir. Google Colab, kullanıcının yerel makinesinde kurulum yapmadan projeyi çalıştırmasına olanak tanır.


## Kurulum
Projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. **Google Colab'a Giriş**: Google hesabınızla [Google Colab](https://colab.research.google.com/) platformuna gidin.
2. **Yeni Bir Notebook Oluşturun**: "New Notebook" seçeneğine tıklayarak yeni bir çalışma alanı oluşturun.
3. **Gerekli Kütüphaneleri Yükleme**:
   Aşağıdaki kodu çalıştırarak gerekli kütüphaneleri yükleyin:
   ```python
   !pip install dlib opencv-python
4. **Resim Dosyasını Yükleme**: test1.jpg adında bir resim dosyasını Colab ortamınıza yükleyin. Alternatif olarak, kendi resim dosyanızın yolunu image_path değişkenine atayabilirsiniz.

## Kullanım
Yüz tespiti ve blurlama işlemini gerçekleştirmek için kodu çalıştırın.

