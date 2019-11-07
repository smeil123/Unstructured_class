


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

> 키워드 추출, 연관 키워드, 문서 분류, 개체의 관계 및 속성 추출

22
그래프
빈도의 차이를 계산해서 그래프로 그림
양끝쪽에 있는 단어 (babi, women)은 한쪽에서만 쓰고 다른쪽에서는 잘 사용하지 않은단어
중간에 있는 단어는 다른쪽도 쓰지만 한쪽이 그나마 더 많이 쓰는 단어(차이)

23
카테고리를 모르는 경우 -> Fully Automated Clustering, Computer Assisted Clulstering
카테고리를 모르고 카테고리가 여러개인 경우 -> LDA,..

24
텍스트를 이해하는데 도메인지식이 얼마나 중요하냐
LDA -> Vanilla topic model 까지 해주고 라벨링은 직접해야한다

38
TF - 단어 빈도수
IDF - 문서 2개에 특정 단어가 5000번 나오면 IDF = 2
문서 5000개에 걸쳐서 특정단어가 5000번나오면 IDF = 5000 이다

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY0ODA2NTk0MiwtMTA3MjM3MDMwLDE1OD
IxMTUwOTcsLTE3NTA4OTM3NDcsMTQzMjk0MjgyNiwtMTQwMjc5
NTU3MCwtMTY3MzM4NjE0OSwtMTY3NjU1MzI5M119
-->