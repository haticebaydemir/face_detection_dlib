## Projenin kodlarına [buraya tıklayarak](https://colab.research.google.com/drive/1JJ2U_lN_2oaerinyd7RRujsKWo2dyhhr#scrollTo=sy_WYLkLW0Vq) ulaşabilirsiniz.
# face_detection_dlib
```pip install dlib```
```from google.colab.patches import cv2_imshow
import cv2
import dlib #dlib, yüz tespiti ve diğer makine öğrenimi uygulamaları için kullanılır.

# Resmi yükle
image_path = 'test1.jpg'  # Fotoğrafı buraya girin
img = cv2.imread(image_path)
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)

# Dlib'in yüz dedektörü modelini yükle
detector = dlib.get_frontal_face_detector()

# Yüzleri tespit et
faces = detector(gray)

# Tespit edilen yüzleri çerçeve içine al
for face in faces:
    x1, y1, x2, y2 = face.left(), face.top(), face.right(), face.bottom()
    cv2.rectangle(img, (x1, y1), (x2, y2), (255, 0, 0), 2)

# Sonucu göster
cv2_imshow(img)
```
