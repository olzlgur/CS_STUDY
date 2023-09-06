### Spinlock
- 정수 변수
- 초기화, P(), V() 연산으로만 접근 가능(연산은 atomic한 연산 - OS가 보장)
- P가 lock, V가 unlock을 의미한다. 
- 전체가 한 사이클에 수행됨

![KakaoTalk_Photo_2023-09-06-18-25-29](https://github.com/olzlgur/CS_STUDY/assets/77485914/6fc12142-89e1-40fe-ba03-a9f516baa8da)

#### Spinlock의 특징
- 멀티 프로세서 시스템에서 사용 가능
- Busy Waiting

