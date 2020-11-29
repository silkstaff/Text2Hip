# 🎙Text2Hip
* 본 저장소는 평어체의 문장 또는 단어를 딥러닝을 통해 **힙합스럽게** 탈바꿈하는 ***Text-to-Hip*** 프로젝트를 정리한 공간입니다.
* '힙린이(힙합 입문자😁)'들의 힙합 작사를 돕자는 취지로 진행한 프로젝트입니다.

## 🏃‍♂️프로젝트 기간
* 2020.06~2020.07

## 🐱‍🚀프로젝트 결과
- 프로젝트 소개 영상: https://cafe.naver.com/bitamin123/1586
- 발표 자료는 [여기](https://github.com/iloveslowfood/Text2Hip/blob/master/Presentation.pdf)에서 보실 수 있습니다.
- [발표 영상 다운로드](https://github.com/iloveslowfood/Text2Hip/raw/master/Presentation.mp4)
- 주요 내용  
  `LDA`: 텍스트로부터 핵심 키워드를 추출합니다.  
  `Transformer`: LDA를 통해 추출한 핵심 내용을 힙합스럽게 변환합니다.  
  `Rhyme Optimization`: 한국어 음운 규칙을 기반으로 개발한 라임 최적화 알고리즘을 통해 Transformer로부터 얻은 힙합 가사의 운율을 극대화합니다.   
  
![](https://user-images.githubusercontent.com/48649606/95861043-dafc6c80-0d9b-11eb-8eb4-94b778e3b3ff.png)
![](https://user-images.githubusercontent.com/48649606/95860966-be603480-0d9b-11eb-8bb6-276d987336d5.png)
![](https://user-images.githubusercontent.com/48649606/95861125-fa939500-0d9b-11eb-9af4-f924328e1cdf.png)

## 👩‍👧‍👧프로젝트 참여 인원
* [고지형](https://github.com/iloveslowfood), 김상희, 배진수, 황호진

## 👀실치 및 학습
* Clone repository  
`git clone https://github.com/bogus215/TextToHip.git`

* Construct environment  
`pip install -r requirements.txt`  

* Train  
`cd ./TextToHip/Transformer`  
`python run.py`
