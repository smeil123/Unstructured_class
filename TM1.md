


빈도로부터 의미를 추론: 벡터스페이스 모델을 사용해서 의미를 이해 하는 논문이 엄청 유명하다
> Bag of words hypothesis
> 
문서들이 유사한 의미를 갖는다
영어는 단어의 순서가 상당히 중요(어미변화가 없는 언어이기 때문에)한데, 컬럼벡터로는 이를 표현하지 못한다
> Distributional hypothesis(분포가설)

동일한 위치에 등장하는 단어들은 비슷한 의미를 갖는다
> Extended Distributional hypothesis(확장된 분포 가설)

> Latent Relation Hypothesis

백오브워드(2-mode)를 1-mode로 바꿈 
단어간의 관계를 표현

윈도우 슬라이딩하며 기준이 되는 단어를 기준으로 함께 나오는 단어를 카운트
* 제출이라는 단어와 함께 많이 나온것 : 마감, 내일(연관검색어라고 생각)

## Tokenization

거리가 가까우면 유사하고 멀면 다르다

## Text  Mining

Natural Language Processing : 앞글자를 보고 뒤에 단어가 나올 확률을 이용해서 문장의 구조를 태깅하는 방법
하지만 우리는 구조보단 의미에 관심이 있기에 pass


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MzM3MzYzMDQsLTE3NTA4OTM3NDcsMT
QzMjk0MjgyNiwtMTQwMjc5NTU3MCwtMTY3MzM4NjE0OSwtMTY3
NjU1MzI5M119
-->