### DeadLock 교착 상태
- 프로세스가 발생 가능성이 없는 이벤트(자원)를 기다리는 경우를 의미한다. (Blocked/Asleep State에 존재함)
- Starvation과는 다름, Starvation은 프로세서를 기다리는 경우를 의미하며 할당 받을 가능성이 없는 것이 아니다.

#### DeadLock을 발생시킬 수 있는 자원
- Non-preemptible resources(비선점 자원, 빼앗을 수 없는 자원)
- Exclusiv allocation resources(상호배제,혼자서만 사용할 수 있는 자원)
- Serially-reusable Resources(시스템 내에 항상 존재하는 자원),
- Consumable Resources(프로세스가 사용한 이후 사라지는 자원, 해당 자원을 대상으로 하는 DeadLock 고려X 복잡함)

#### DeadLock의 발생 필요 조건 (모두 충족해야 데드락 발생)
- Exclusive use of resources(독점 자원, 공유 불가능 자원, 상호 배제)
- Non-preemptible resources(비선점 자원, 빼앗을 수 없는 자원)
- Hold and wait(자원을 하나 hold하고 다른 자원을 요청)
- Circular Wait(사이클 발생)

#### DeadLock 해결 방법
- DeadLock prevention method(교착상태 예방) - 비현실적
  - 모든 자원 공유, 선점 허용은 현실적으로 불가능
  - 필요 자원 한 번에 할당
    - Hold and Wait 제거
    - 동시에 모든 자원을 사용하지 않는 경우 자원 낭비
    - 대기 시간 증가
  - Circular wait 조건 제거
    - 자원들에게 순서 부여
    - 프로세스는 순서의 증가 방향으로만 자원 요청 가능
    - 자원 낭비 발생
- DeadLock avoidance mehtod(교착상태 회피)
- DeadLock detection and recovery method(교착상태 탐지 및 복구)



참고자료
```
https://youtu.be/xvoEsy2zJnc?si=ldAW3mo1wC-P4RE9
```
 
