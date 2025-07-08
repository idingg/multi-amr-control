# ROS2를 이용한 다중 자율주행 로봇 시뮬레이션 및 웹 기반 관제 시스템

이 프로젝트는 TurtleBot3, 드론 등 다양한 AMR(Autonomous Mobile Robot) 및 드론의 협동 제어와 시뮬레이션을 위한 시스템입니다. 경로 계획, 다중 로봇 네비게이션, 웹 기반 모니터링, 목표물 탐지 및 알림 등 다양한 기능을 제공합니다.

## 주요 기능
### 1. Vision AI 기반 인간 탐지 및 네비게이션 (human_detect_navi)
- YOLOv11 기반 객체 탐지로 실시간 인간 위치 인식
- 탐지 결과를 활용한 웹 기반 관제시스템에 알림 표시

### 2. 다중 로봇 시뮬레이션 (turtlebot3_multi_robot)
- Gazebo 환경에서 다수의 TurtleBot3 시뮬레이션 및 네비게이션
- ROS2 Nav2 패키지와 연동한 경로 계획 및 장애물 회피

### 3. 드론 시뮬레이션 및 제어 (sjtu_drone)
- 드론의 시뮬레이션, 스폰, 초기화, 환경 리셋 등 자동화
- Gazebo 및 RViz2를 통한 시각화

### 4. 웹 기반 다중 로봇 모니터링 (web_amr_control)
- 실시간 로봇 위치, 맵, 로봇 상태, 탐지 내역 등을 웹 기반 대시보드로 시각화
- Flask 기반

## 사용 기술
- 로봇 프레임워크: <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white">
- 프로그래밍 언어: <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
- 컴퓨터 비젼: <img src="https://img.shields.io/badge/-YOLO-FFCC00?style=for-the-badge&logo=yolo&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white">
- 시뮬레이션/시각화: <img src="https://img.shields.io/badge/Gazebo-F5820D?style=for-the-badge&logo=gazebo&logoColor=white"> <img src="https://img.shields.io/badge/RViz-22314E?style=for-the-badge&logo=ros&logoColor=white">
- 웹 서버: <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white">
- 데이터베이스: <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white">

## 활용 분야
- 재난 시 인명 탐색
- 이동식 CCTV 및 침입 탐지 시스템
- 스마트 팩토리 물류 자동화
- 실내외 자율주행

## 향후 개선 방향
- config.json 등 설정 파일 도입으로 간편화
- 다양한 로봇 모델 및 센서 추가 기능
- 웹 관제 시스템에서 로봇 제어 기능 추가 등 고도화

## 발표 자료 주요 내용
![AMR 인명 발견](https://github.com/idingg/multi-amr-control/blob/main/images/1.png?raw=true)
![드론 인명 발견](https://github.com/idingg/multi-amr-control/blob/main/images/2.png?raw=true)
![위치 실시간 표시](https://github.com/idingg/multi-amr-control/blob/main/images/3.png?raw=true)
![Log 저장 및 출력](https://github.com/idingg/multi-amr-control/blob/main/images/4.png?raw=true)
![YOLOv11 사용](https://github.com/idingg/multi-amr-control/blob/main/images/5.png?raw=true)
![인명 탐지 시 ROS2 통신 내용](https://github.com/idingg/multi-amr-control/blob/main/images/6.png?raw=true)
![네이게이션 ROS2 통신 내용](https://github.com/idingg/multi-amr-control/blob/main/images/7.png?raw=true)
![시뮬레이션 맵 생성](https://github.com/idingg/multi-amr-control/blob/main/images/8.png?raw=true)

## 시연 영상
[video_presentation.webm](https://github.com/user-attachments/assets/aa27f33f-cd50-472c-8323-be0de2d0d5bd)

[video_navigation.webm](https://github.com/user-attachments/assets/da1854ea-867b-4a69-86b8-0c4426e45c73)
