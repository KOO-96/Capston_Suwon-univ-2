# Capston_Suwon-univ-2.

# 최종발표    
중간 발표단계    
Title: 패션 아이템을 활용한 추천 알고리즘  
Data : Fashion mnist dataset   

CNN딥러닝을 이용한 classification   
result : 20epoch, 91%   

최종 발표 -> 실제 패션이미지를 활용하여 진행    
Title : 패션 아이템 Object Detection + 아이템 추천   
Data : iMaterialist Challenge(Fashion) [[Link.]](https://www.kaggle.com/c/imaterialist-challenge-fashion-2018/code)

Main : Mask R-CNN을 이용한 Object Detection

### Object Detection(객체 검출)란?
여러 객체에 대하여 각 객체가 무엇인지 분류하는 _Classification_ 문제와 그 객체가 어디에 위치하는지 위치 정보를 나타내는 _Localization_   

CNN -> 객체의 회귀와 분류가 가능하다 but 제한적인 객체탐지로 많은 객체를 탐지하기에는 한계점이 있다. 

R-CNN(Regions with Convolutional Neural Network)
