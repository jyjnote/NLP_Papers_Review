# 🤗강의 소개🤗(Course Introduction) <sub>-강사:정재연-<sub>
안녕하세요! 여러분께 소개할 강의는 "Inflearn 자연어 A To Z"입니다. 이 강의는 인공지능의 한 분야인 자연어 처리(NLP)를 깊이 있게 다루며, 자연어 논문 리뷰 및 코드 구현을 통해 실질적인 이해를 돕습니다.

강사 정재연과 함께 진행하는 이 강의에서는 최신 자연어 처리 기술과 모델을 학습할 수 있습니다. 모든 코드는 PyTorch로 제작되었으며, 실습 데이터를 통해 직접 실험할 수 있습니다. 딥러닝의 기초부터 시작해, BERT, GPT, Transformer 등 대표적인 NLP 모델을 다루며, 논문과의 연관성을 강조합니다.

특히, 이 강의는 자연어 처리 분야에서 전문가가 되고자 하는 분들, 인공지능에 관심이 많고 대학원 진학을 목표로 깊이 있는 공부를 원하는 분들에게 최적화되어 있습니다. 여러분이 자연어 처리의 전문가로 성장할 수 있도록, 최신 연구와 실습을 통해 깊이 있는 학습 경험을 제공합니다.

해당 레파지토리는 <strong style="color: yellow;">인공지능</strong>의 한 분야인 <strong style="color: yellow;">자연어(NLP)</strong>를 다루는 저장소입니다.<br>
>- [주요한]() `자연어 논문 리뷰 및 코드 구현`입니다.<br>
>- 모든 코드는 ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
가 아닌![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) 제작했습니다.
>- [비전]() 및 [음성](), [강화 학습]()와 같은 다른 분야는 다루지 않습니다.<br>
>- 대표적인 모델만을 다루고 `할루시네이션, 파라미터 튜닝 체인지` 같은 알고리즘은 깊게 리뷰하지 않습니다.

다음 해당 논문 주제 클릭 시
 [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/여기에_노트북_URL을_입력하세요)에서 코드를 공유합니다. (`미구현`)

## 2024-05-26<br>
 현재 모든 파일을 다운 받고 본인 로컬에서 실험을 할 수 있습니다.
 ... 논문과 연관지여서 추가 할 것임...

**<strong style="color: yellow;">폴더 구조**<br>
```
|-- basic (딥런닝 기초 실습입니다. 누구나 따라 할 수 있습니다. 여기서 기초를 공부하면 됩니다.)
|-- data (실습에서 사용할 데이터입니다.)
    |-- cats_and_dogs
        |-- test
            |-- cats
            |-- dogs
        |-- train
            |-- cats
            |-- dogs
    |-- meat
        |-- test
        |-- train
|-- NLP_codes (본격 NLP을 위한 코드입니다. 논문과 연관 시켜서 보면 됩니다.)
|-- weight (학습된 가중치를 저장하는 곳입니다.)
    |-- cats_and_dogs
    |-- imdb
    |-- naver_stock
    |-- titanic
```
|**논문 주제**|**참고문헌**|
|---|----|
[Bag of Words]()
[TF-IDF]()
[Embedding]()
[Sequence]()
[Mamba]()
[Attention]()
[Attention RNN]()
[Transformer]()
[ELMo]()
[BERT]()
[GPT1]()
[GPT2]()
[ALBERT]()
[RoBERTa]()
[ELECTRA]()
