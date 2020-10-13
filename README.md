# 🤡Text2Hip
* 본 저장소는 평어체의 문장 또는 단어를 딥러닝을 통해 **힙합스럽게** 탈바꿈해주는 ***Text-to-Hip*** 알고리즘을 정리한 공간입니다.
* '힙린이(힙합 입문자😁)'들의 힙합 작사를 돕자는 취지로 진행한 프로젝트입니다.

## 🏃‍♂️프로젝트 기간
* 2020.05~2020.07

## 🐱‍🚀프로젝트 결과
- 프로젝트 소개 영상: https://cafe.naver.com/bitamin123/1586
- [영상을 다운로드](https://github.com/iloveslowfood/Text2Hip/raw/master/Presentation.mp4)해서 보실 수도 있습니다.
- 메인 컨텐츠
  - `LDA`: 텍스트로부터 핵심 문장 또는 키워드를 추출합니다.
  - `Transformer`: LDA를 통해 추출한 핵심 내용을 힙합스럽게 변환합니다.
  - `Rhyme Optimization`: 한국어 음운 규칙을 기반으로 개발한 라임 최적화 알고리즘을 통해 Transformer로부터 얻은 힙합 가사의 운율을 극대화합니다.
![image](https://user-images.githubusercontent.com/53327766/87830869-f9e28400-c8bc-11ea-892b-5d7e5f4bcc68.png)
![image](https://user-images.githubusercontent.com/53327766/87831333-2ba81a80-c8be-11ea-9faf-b28fd63081b9.png)

## 👩‍👧‍👧프로젝트 참여 인원
* 고지형, 김상희, 배진수, 황호진

## 👀실치 및 학습
* Clone repository
`git clone https://github.com/bogus215/TextToHip.git`

* Construct environment
`pip install -r requirements.txt`  

* Train
`cd ./TextToHip/Transformer`  
`python run.py`
