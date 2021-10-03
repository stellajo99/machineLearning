Machine Learning 1-6 : 모델은 판단을 해주는 도구. 모델을 학습시키고 이를 이용해 추측을 할 수 있다.

Machine Learning 1-10 : 데이터를 표로 나타내서 사용한다.

Machine Learning 1-13 : 독립변수는 원인이다. 종속변수는 결과다. 독립변수와 종속변수의 관계를 인과관계라고 한다.

![스크린샷(69)](https://user-images.githubusercontent.com/81244049/135757340-ab4ed8de-0f24-47d0-8e43-063dc305d7ed.png)

Machine Learning 1-15 : 지도학습(supervised learning)은 기계를 가르치는 것. 데이터로 컴퓨터를 학습시켜서 모델을 만드는 방식. 비지도학습은 지도학습에 포함되지 않는 방법들임. 기계에게 데이터에 대한 통찰력을 부여하는 방법이라고 볼 수 있다. 데이터의 성격을 파악하거나 데이터를 정리정돈하는 데 주로 사용된다. 강화학습은 학습을 통해 능력을 향상시킨다. 결과에 따라 상이나 벌을 받으며 더 좋은 방향으로 나아간다.

Machine Learning 1-16 : 지도학습은 과거의 데이터로부터 학습해서 결과를 예측하는 데 주로 사용된다. 지도학습을 위해서는 과거의 데이터가 필요하고 데이터를 독립변수와 종속변수로 분리해서 그 관계를 컴퓨터에게 학습시키면 컴퓨터는 그 관계를 설명할 수 있는 공식을 만들어 낸다. 이 공식을 모델이라고 한다. 데이터가 많을수록, 정확할수록 좋은 모델이 된다.

Machine Learning 1-17 : 지도학습은 크게 분류와 회귀로 나뉜다. 예측하고 싶은 종속변수가 숫자일 때 보통 회귀라는 방법을 사용한다. 


Machine Learning 1-18 : 종속변수가 숫자가 아니라 글자 등일 경우 회귀가 아니라 분류를 사용한다. "가지고 있는 데이터에 독립변수와 종속변수가 있고, 종속변수가 숫자일 때 회귀를 이용하면 됩니다. 종속변수가 이름일 때 분류를 이용하면 됩니다."

Machine Learning 1-19 : 비지도학습은 군집화, 변환, 연관의 사례로 나뉜다. 군집화는 비슷한 것들을 찾아서 그룹을 만드는 것이다. 그룹을 만드는 것이 군집화, 어떤 대상이 어떤 그룹에 속하는지를 판단하는 것이다. 좌표 평면에 나타내서 가까운 것들끼리 묶는 방식으로 군집을 찾을 수 있다. 군집화라는 도구에 1000만개의 관측치를 입력하고 100개의 클러스터 수가 필요하다고 알려주면 각각의 클러스터 당 서로 다른 개수의 관측치를 가지고 있는 100개의 클러스터를 만들어 준다. 표 상에서 비슷한 행을 찾아내는 것이 군집화이다.


Machine Learning 1-19 : 비지도학습에 속하는 연관 규칙 학습은 연관성을 파악해서 추천 알고리즘 등에 사용될 수 있다. 표 상에서 연관이 있는 열들을 찾아주는 것이 연관규칙이다.

Machine Learning 1-21 : 비지도학습은 데이터의 성격을 파악하는 것이 목적이다. 독립 변수와 종속 변수를 구분하는 것이 중요하지 않다. 지도학습은 과거의 데이터를 바탕으로 미래를 추측하는 것이 목적이므로 원인인 독립변수와 결과인 종속변수가 꼭 필요하다.

Machine Learning 1-22 : 강화학습은 일단 해보면서 경험을 통해 실력을 키워나간다. 행동의 결과가 유리한 것이었다면 상을 받고 불리한 것이었다면 벌을 받는다. 이 과정을 매우 많이 반복하면 더 많은 보상을 받을 수 있는 더 좋은 답을 찾을 수 있다는 것이 핵심 아이디어. 상태에 따라 더 많은 보상을 받을 수 있는 행동을 에이전트가 할 수 있도록 하는 정책을 만드는 것이 목적이다.
