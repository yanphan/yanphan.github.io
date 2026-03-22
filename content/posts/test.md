+++
title = 'Thử nghiệm nhận diện khuôn mặt với OpenCV'
showTableOfContents= true
math = true
date = 2026-03-22
draft = false
tags = ["Computer Vision", "OpenCV", "Python"]
+++

Hôm nay chúng ta sẽ thử nghiệm một đoạn code cơ bản. Blowfish hiển thị code block cực kỳ đẹp mắt.

## 1. Đoạn code Python
### 3. Hello
```python
import cv2

# Tải pre-trained model
face_cascade = cv2.CascadeClassifier('haarcascade_frontalface_default.xml')

# Đọc ảnh
img = cv2.imread('test.jpg')
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)

```
$$ f(x) = \int_{-\infty}^{\infty} \hat{f}(\xi) e^{2 \pi i \xi x} d\xi $$