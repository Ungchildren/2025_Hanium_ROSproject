# 2025_Hanium_ROSproject
2025 한이음 드림업 공모전 장려상 수상 

## Link

## Background
본 프로젝트는 Optical Flow 분석과 IMU 데이터를 융합하고, 칼만 필터(Kalman Filter)를
적용하여 VIO 기반 차량 위치 추정 시스템을 개발하는 것을 목표로 한다. IMU 센서는 가속도 및
각속도 데이터를 활용하여 차량의 자세(Orientation)와 속도 변화를 측정한다. Optical Flow와
IMU 데이터를 결합하여 센서별 단점을 보완하고, 칼만 필터를 통해 위치 추정의 정확도를
향상시킨다. 또한, Jetson Orin Nano에서 MATLAB 기반 VIO 알고리즘을 실행하여 실시간
데이터 처리를 최적화하며, 실시간 웹 모니터링 시스템을 구축하여 Optical Flow 및 IMU 센서
데이터를 클라우드 서버로 전송하고 웹 대시보드를 통해 실시간 시각화 및 분석이 가능하도록
구현한다. 웹 대시보드에서는 차량의 이동 궤적, 속도 그래프, 센서 데이터 변화를 실시간으로
시각화할 수 있으며, 기록된 데이터를 바탕으로 후처리 분석도 지원한다. 이를 통해 GPS가
불안정한 환경에서도 차량의 이동 경로를 정밀하게 추정할 수 있는 VIO 기반 위치 추정 시스템을
개발한다.

## Environment Setup

## Flow Diagram

## Built With
