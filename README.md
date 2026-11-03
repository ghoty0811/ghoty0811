# 안녕하세요! 개발자 고태영입니다. 👋

이미지 처리 기술과 인공지능 기술을 이용해 실제 환경의 소프트웨어를 구현하는 데 관심이 있습니다.

더 나아가 이를 로봇 시스템에 통합하는 것에도 흥미가 있습니다.

## 🛠 기술 스택

- Language: Python, C#
- AI / Computer Vision: YOLO, OpenCV, PyTorch
- Robotics: ROS2, Gazebo, TurtleBot, OAK-D
- Tools: Git, GitHub, Ubuntu

## 🚀 주요 프로젝트

### 🍹 1. Bar Robot — 협동로봇 기반 칵테일 제조·서빙

두산 협동로봇을 활용한 음료 제조 및 서빙 자동화 프로젝트

**기술 스택**
- Python, ROS2

**주요 구현**
- ROS2 기반 협동로봇 제어 프로그램 구성
- 로봇 관절 및 직교좌표 기반 동작 구현
- 음료 제조·서빙을 위한 작업 동작 구성
- 사용한 컵의 세척 동작 구현

[🔗 프로젝트 GitHub](https://github.com/ghoty0811/bar_robot)

---

### 🤖 2. Assistant Robot — 음성·비전 기반 생활 보조 로봇

음성 명령과 객체 인식을 결합한 협동로봇 기반 생활 보조 시스템

**기술 스택**
- Python, ROS2, YOLO, OpenCV, RealSense, LangChain

**주요 구현**
- 웨이크 워드 감지, STT 및 자연어 기반 명령 해석
- YOLO와 RealSense 카메라를 활용한 객체 탐지 및 위치 추정
- 카메라 좌표계와 로봇 좌표계 간 변환
- MediaPipe 손 인식을 활용한 사용자 대상 물체 전달
- ROS2 기반 로봇팔과 그리퍼 제어


[🔗 프로젝트 GitHub](https://github.com/ghoty0811/assistant_robot)

---

### 🚗 3. Auto Driving Sim — 자율주행 시뮬레이션

Gazebo 환경에서 영상 인식과 주행 제어를 연계한 TurtleBot3 자율주행 시스템

**기술 스택**
- Python, ROS2, Gazebo, OpenCV, YOLO

**주요 구현**
- YOLO 기반 교통 표지판 인식
- OpenCV 기반 차선 검출 및 PD 제어
- 교차로, 공사 구간, 주차, 터널 등 미션별 주행 로직
- 신호등 및 횡단보도 인식에 따른 정지 제어
- ROS2 Topic 기반 인식·판단·제어 모듈 연동

[🔗 프로젝트 GitHub](https://github.com/ghoty0811/auto_driving_sim)

---

### 🚙 4. Auto Driving Real — 실물 로봇 자율주행 및 Pick & Place

카메라 기반 주행 인식과 로봇팔 조작 기능을 결합한 서비스 로봇 프로젝트

**기술 스택**
- Python, C++, ROS2, OpenCV, MoveIt2, ArUco

**주요 구현**
- 영상 기반 차선 검출 및 주행 제어
- 신호등과 차단바 인식에 따른 정지·주행 판단
- ArUco 마커 기반 목표 위치 탐지 및 접근
- MoveIt2를 활용한 매니퓰레이터 제어
- 자율주행과 Pick & Place 동작 연계

[🔗 프로젝트 GitHub](https://github.com/ghoty0811/auto_driving_real)

---

### 🌊 1. 수상 부유물 탐지 시스템

수면 위의 쓰레기와 분실물을 구분하여 탐지하는 객체 탐지 시스템

**기술 스택**
- Python, YOLO, OpenCV, PyTorch

**주요 구현**
- 객체 탐지 모델 학습 및 성능 비교
- 데이터 증강 및 합성 데이터 생성
- 학습 하이퍼파라미터 최적화
- ByteTrack 기반 객체 추적

[🔗 프로젝트 GitHub](https://github.com/yj4976s-cpu/flowlink)

---

## 📫 Contact

- Email: ghoty0811@gmail.com
- GitHub: https://github.com/ghoty0811
