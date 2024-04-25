# 프로젝트명
- DC Motor PI Contorl

## 프로젝트 배경 및 필요성
### 2.1 프로젝트 배경
- Aurix TC275기반 코딩을 통해 DC Motor PI 제어를 함.
- STM을 이용해 Encoder Pulse Count 알고리즘 구현

### 2.2 프로젝트 목적
- GTM으로 PWM의 frequency, conuntDir, CM0, CM1, CN0를 설정함으로써 PWM원리와 구현을 해볼 수 있음.
- STM으로 1ms, 10ms, 50ms 등 내가 원하는 타이머를 구현하고 이 타이머를 이용해 Encoder Tick 수를 세고, PI제어를 함으로써 STM의 기능과 구현을 해볼 수 있음.
- Encoder State를 이용해 Encoder Pulse Count를 구현하고 이것을 rad/s로 변환함으로써 Closed loop PI 제어를 할 수 있음.
