# Lets-EDA

#### 매 주말 고수들의 분석을 따라하며 노하우를 습득하는 repo

To get used to EDA.
These are the records of my practices of EDA with various datasets.

## 첫번째 프로젝트 : PUBG Finish Placement Prediction (Kernels Only) : EDA part

- To learn how the experts do EDA I follow their work. 전문가들의 EDA 방법을 따라가며 노하우를 습득하려 함.
- URL : http://www.kaggle.com/deffro/eda-is-fun/notebook

	- 02/01
		- 진행사항
			첫번째 단인 The killers 부분을 진행했다. Target 변수인 winPlacePerc와 kills의 관계를 분석
			킬과 승리는 상당한 상관관계를 가졌다. (얼마인지 기록할 것 : )
	- 02/02
		- 진행사항
			두번째 단인 The runners를 진행했다. 이동거리와 승리의 연관성이 가장 높았다.
	- 02/08-09
		- 각 단 혹은 분석단계마다 raw_data를 딥카피해서 새로운 변수에 사용한다. raw를 유지하기 위한 방법.
		- 의미는 알겠는데 이 사람은 좀 자주 복사를 했다. data가 900mb짜리였는데 계속해서 복사를 해대니 은근 시간이 많이 걸렸다.
		
	- 느낀점
		- *최대한 데이터는 작은 단위로 유지하면서 빠르게 빠르게 사용하는 방법에 익숙해져야 할듯*
		- 나라면 분석의 가장 첫단에서 Heatmap을 그려보겠다. 한눈에 타겟과 모든 변수의 상관관계를 파악할 수 있는 가장 빠른 방법라고 생각한다.
		


## 두번째 프로젝트 : Telco Customer Churn : My first own EDA project

- URL: https://www.kaggle.com/blastchar/telco-customer-churn

	- 02/15
		- 많이 익숙해졌다고 생각했지만 막상 프로젝트를 진행하려니 무엇을 해야 할지 막막했다. 무작정 명령어를 치는 것 보다 어느정도 guide line을 설정하고 이에 맞는 코드를 짜는 훈련이 필요하다고 느꼈다. 물론, 어쩌면 단순한 경험치 부족으로 인한 문제일 수 있지만 데이터 탐색과 함께 분석의 전반적인 방향을 설정하는 습관을 들여야겠다.

	- 느낀점
		- 확률, 통계, 검정을 배울수록 분포의 비교, 수치의 비교만을 통해서 결론을 도출한다는 것이 매우 부정확한 일이란 것을 알았다.
		- 시각화, 혹은 스코어만 높이기 보다는 통계 검정을 통해서 논리를 다지는 습관 필요.
		
 
