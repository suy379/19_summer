## User's pattern analysis of car-sharing company 
### By. Pattern Mining Team
Data-based insights were derived for more efficient business operation by analyzing company's operational data.  
`2019.07.~08.` **made by. Pattern Mining Team** (@[Edwin](https://github.com/Edwinpark), Mushroom, @[Sue](https://github.com/suy379))  
- 회사의 운영 데이터를 분석하여, 보다 효율적인 사업 운영을 위한 인사이트 도출
- 다양한 분석 시나리오 구상 및 실험
- 시나리오 구성 및 시뮬레이션을 통해 동적 가격 결정 시스템 아래 특정 이용 패턴의 할증에 대한 분석 및 제안 

---
## Part 1. 특정 zone에서 주로 쓰는 차종 비율이 정해져 있을까?
- 이용 목적에 따라(교통목적/여행지목적 등)
- 지역적 성격에 따라(여행/교통/업무 등)
  - 자체적인 조건을 설정해 데이터를 필터링하고 가설 검정 진행
  - 자체적인 가중치를 설정해 존 타입별 score 계산

## Part 2. User의 패턴 나누기
- 유저별, 존별, 예약건별 클러스터링 후, 클러스터별 어떤 특징(피처)이 두드러지는지?
- 평일 이용 패턴- 많이 나타난 수요들 패턴화
- 주말 이용 패턴
- 초회 이용자 패턴- 첫 이용은 어느 곳에서, 몇 시간동안 사용하며, 재사용은?

## Part 3. 시나리오 
- Part 2에서 알아본 user 패턴을 바탕으로, 사업적으로 더 이윤을 내기 위해 실행할 수 있는 시나리오 구상
- 특히 주말 수요에 초점 
- 할증을 할 수 있는 패턴을 자체적으로 선정(Lead_time), 할증률을 몇% 높일 때 줄어드는 수요와 예상 수익 시뮬레이션 
- 수치에 관해 보다 더 심화된 접근이 필요했다는 아쉬움, 어떤 장소의 어떤 기간에 가장 수요가 높아질 것이라는 예측도 첨가되었으면 더 좋은 분석이 되었을 듯.

<img src=https://user-images.githubusercontent.com/48719168/111274489-65f9cf80-8678-11eb-9675-a5f752979b77.jpg  width="400" height="450">
