# 프로젝트 기술문서
[ricoshin.github.io/drone-project](http://ricoshin.github.io/drone-project)

## 프로젝트명
주변 환경 인식 및 자율비행 드론 시스템 구축

## 개발환경
- FCU와 companion computer를 통합한 Linux-based MAV 기반(Erle-brain2) 
- Debian / C++ / ROS (Robot Operating System)
- mavros 패키지를 매개로 Autopilot(APM/PX4) 원격제어

## 프로젝트 목표
-  Wi-Fi 로 실시간 영상 전송 / 원격 머신에서 고비용 연산처리 / 제어신호 리턴 
-  Gazebo를 이용한 시뮬레이션 (자율비행 알고리즘 테스트) 
-  Caffe를 ROS package로 wrap하여 원격지에서 실시간 object detection 
-  Kalman filter를 통한 state estimation
-  PTAM을 이용한 드론 pose예측 및 호버링 유지
-  LSD-SLAM을 이용한 주변 환경 매핑
