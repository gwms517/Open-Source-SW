# 실시간 얼굴인식을 활용한 모자이크 처리 (Mosaic using Real-time_face_detection)
Open Source SW Term Project - Team 32


## 기간 (Period)
> 2022.11.17 - 2022.12.12

## 설명 (Description)
### 사용자의 캠을 이용해서 얼굴인식을 한 뒤, 모자이크 처리를 할 수 있다
추가로, 모자이크 대신 사용자가 설정한 이미지를 이용해 얼굴을 가릴 수 있다

<br>
<br>

## 필요조건 (Requirements)
 1. python (3.9.12)
 2. opencv (4.6.0)
 3. numpy (1.23.4)
 4. haarcascade_frontalface_default.xml
 
 <br>
 
## 명령어 (Command)
> python mosaic.py --1 or --2 --(image)

<br>

## 결과 (Results)

* python mosaic.py --1 를 입력했을 때의 결과


<br>


![222](https://user-images.githubusercontent.com/112797580/206915188-18dab97e-e02d-4cc4-a426-9bf76cab8e5d.png)


<br>

#### 얼굴을 인식해서 모자이크를 한 모습

<br>

* python mosaic.py --2 입력 후 원하는 이미지를 입력했을 때의 결과



![111](https://user-images.githubusercontent.com/112797580/206915191-223f6481-e6a0-4aa0-9308-14e9b7f6854e.png)

<br>

#### 얼굴을 인식한 뒤, 원하는 이미지 파일을 모자이크 대신 삽입한 모습


<br>
<br>
<br>
<br>

## 참고자료 (References)
https://github.com/kimjinho1/Real-time-face-recognition-and-mosaic-using-deep-learning
