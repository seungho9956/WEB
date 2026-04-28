# 🏎️ Automotive Embedded SW Engineer | Jeong Seungho

> **"High-Reliability VPC BSW & Automotive Embedded Specialist"**
> 4년 차 자동차 임베디드 시스템/소프트웨어 엔지니어로, 통합 제어기(VPC)의 기본 소프트웨어 설계 및 차량 시스템 검증 엔지니어로 성장하고 있습니다.

---

### 🛡️ Core Competencies

| Category | Skills & Tools |
| :--- | :--- |
| **Embedded BSW** | `C`, `AUTOSAR`, `RTOS (OSEK/VDX)`, `C++`, `Memory Optimization` |
| **Automotive Protocol** | `CAN / CAN-FD`, `Ethernet (DoIP)`, `UDS (ISO 14229)`, `J1939` |
| **Development Process** | `ASPICE`, `ISO 26262 (Functional Safety)`, `Code Review (Gerrit/GitLab)` |
| **Verification Tools** | `CANoe`, `Vector CAST`, `TESSY`, `Lauterbach Trace32`, 'INCA'|

---

### 📂 Key Projects

####  Next-Gen Vehicle Platform Controller (VPC) BSW Development for HEV/ICE vehicle
* **Role:** Lead BSW Developer / System Integration
* **Highlight:** 차량 통합 제어기 플랫폼의 안정적인 구동을 위한 BSW 드라이버 스택 설계 및 통합
* **Achievements:**
  - 차량 통신 메시지 데이터 정합성 관리 (DLC,CRC,T-out 등 진단 API 개발 및 구현)
  - 실시간성 보장을 위한 태스크 스케줄링 최적화 및 CPU 로드율 관리
  - 마이크로 컨트롤러 코어 동작성 관리 - MPU (Memory Protection Unit) 리셋 관리
  - API 메모리 배치 관리 (ASIL/QM 영역에 대한 호출 방지 및 구현 방안 설계) 
  - UDS 진단통신 서비스 관리 (진단 서비스별 Callback API를 활용한 응답 검증)
  - 차량 양산 데이터 학습값 관리 (Application Software의 데이터 입력 값 유효성에 따른 진단통신 긍정/부정 통신 응답 검증 및 설계)
  - 시스템 사양 설계 문서화 (회로 진단, 양산데이터, 통신 인터페이스 I/O, API 표준화)
    <img width="1408" height="768" alt="Gemini_Generated_Image_6k0eq06k0eq06k0e" src="https://github.com/user-attachments/assets/3c81635b-b165-4139-a275-06d03f231f5d" />



####  V2I(Vehicle-to-Infrastructure) Communication & Simulation
* **Role:** Research Engineer (ICT Information Fusion Center)
* **Highlight:** SAE J2735 표준 기반의 V2I 통신 데이터 처리 로직 개발 및 시뮬레이션 환경 구축
* **Tech:** `C`, `SAE J2735`, `V2I`, `Vector CANoe.Car2x`, `SPaT Message`
* **Key Achievements:**
    * **Standard Protocol Implementation:** SAE J2735 통신 규약을 준수하는 메시지 파싱 및 데이터 처리 미들웨어 개발
    * **Traffic Infrastructure Integration:** 실시간 신호 정보(SPaT: Signal Phase and Timing) 데이터 분석 및 차량 제어 로직 인터페이스 구현
    * **Advanced Simulation:** **Vector CANoe.Car2x**를 활용한 가상 도로 시나리오 기반의 신호 제어 및 V2X 메시지 송수신 검증
    * **Quality & Validation:** 복잡한 교차로 환경에서의 패킷 지연 및 유실 상황을 고려한 통신 신뢰성 테스트 수행
<img width="2816" height="1536" alt="Gemini_Generated_Image_h4ic41h4ic41h4ic" src="https://github.com/user-attachments/assets/f392ad91-a415-4327-9853-6e1b4748ef99" />



#### 🤖 AGV(Automated Guided Vehicle) Safety System Development
* **Role:** Embedded SW Developer
* **Highlight:** ROS 기반 레이저 센서 데이터 분석을 통한 AGV 세이프티 존(Safety Zone) 및 장애물 인지 시스템 개발
* **Tech:** `C++`, `ROS (Robot Operating System)`, `LiDAR (Laser Sensor)`, `AGV`, `Obstacle Detection`
* **Key Achievements:**
    * **Real-time Sensor Integration:** LiDAR 레이저 센서의 Raw 데이터를 수집하고 처리하는 ROS 노드 설계 및 C++ 기반 로직 구현
    * LaserScan 메시지로부터 수신된 Polar Coordinate(거리, 각도) 데이터를 AGV 중심의 **Cartesian Coordinate(x, y)**로 변환하여 기하학적 연산 기반 마련
    * **Dynamic Safety Zone Configuration:** AGV의 주행 속도 및 방향에 따른 가변적 세이프티 존 설정 및 객체 접근 감지 알고리즘 최적화
    * **Collision Avoidance Logic:** 세이프티 존 내 물체 진입 시 즉각적인 인지 및 비상 정지/감속 제어 인터페이스 개발
    * **Performance Tuning:** 센서 데이터 필터링 가공을 통해 인지 노이즈를 최소화하고 실시간 탐지 신뢰성 확보



### 📬 Contact & Links

- 📧 **Email:** SEUNGHO9956@GMAIL.COM

