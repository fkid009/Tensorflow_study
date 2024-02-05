# Tensorflow_study
딥러닝을 파이썬의 ```Tensorflow```를 이용해 구현하기 위해 만들어졌습니다.
기본적으로 ```Subclassing API```를 기반으로 코드를 구성하였습니다.
이러한 이유는 다음과 같습니다.
* Sequential API, Functional API, Subclassing API 중 모델 구축 방법에 있어서 가장 자유도가 높음.

저는 현재 추천 시스템을 연구하고 있습니다. 이때 추천 모델은 기존 방법과 달리 새로운 프레임워크를 구성해야하는 상황이 다수 발생합니다.
따라서, 저만의 모델을 구성해야 하기 때문에 이러한 API를 선택했습니다.
