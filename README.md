# 🚦 스마트 AI 신호등 - GreenLight

![Version](https://img.shields.io/badge/version-1.0.0-green)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 📌 프로젝트 소개
**스마트 AI 신호등(GreenLight)**은 **야간 보행자의 안전**을 보장하기 위해 **AI 기반 객체 인식 기술**을 활용하여 **실시간 신호 제어 및 경고 서비스를 제공**하는 프로젝트입니다.  
교통사고 발생률이 높은 야간 시간대에 **보행자와 운전자의 안전을 동시에 확보**하고, **데이터 기반의 교통 관리 효율성을 증진**하는 것을 목표로 합니다.

### 🎯 프로젝트 개요
- **아이디어 주제**: 야간 보행자를 보호하기 위한 스마트 AI 신호등
- **개발 목표**:
  - 실시간 객체 감지를 통한 **신호 제어 및 위반 차량 감지**
  - **데이터 시각화를 통한 교통 현황 분석 및 관리 효율화**
- **개발 배경**:
  - **야간 보행자의 가시성 저하로 인한 교통사고 증가**
  - **기존 점멸 신호등의 한계 극복 및 스마트시티 연계 가능성**

---

## 🖼️ 로고 및 이미지
![GreenLight](https://github.com/user-attachments/assets/5bf3d89f-c13e-4925-874c-a70cc746de35)

---

## 🛠 기술 스택
| 분야         | 기술 스택 |
|-------------|------------------------------------------------|
| **Frontend** | JavaScript, HTML, CSS, Bootstrap |
| **Backend** | Django (웹 애플리케이션 개발 및 RESTful API) |
| **Database** | MySQL (pymysql 연결) |
| **AI 모델링** | YOLOv10, OpenCV, NumPy, Sort (실시간 객체 탐지 및 추적) |
| **데이터 시각화** | Matplotlib (교통 데이터 시각화) |
| **기타** | gTTS (음성 경고 시스템) |

---

## 📑 주요 화면 구성
- **메인 화면**: AI 객체 감지에 따른 신호등 제어 및 위반 차량 경고
- **분석 화면**: 차량 및 보행자 데이터 시각화 대시보드
- **관리자 화면**: 교통 데이터 관리 및 통계 확인
- **설정 화면**: 음성 알림 및 신호 제어 설정

---

## 🌟 핵심 기능
✔ **AI 객체 탐지 및 실시간 신호 제어**  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 YOLOv10 모델을 활용한 보행자 및 차량 감지  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 감지된 객체에 따라 실시간 신호등 전환 및 제어  

✔ **위반 차량 감지 및 경고 시스템**  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 신호 위반 및 속도 위반 차량 자동 감지  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 gTTS를 통한 음성 알림 및 신호 전환  

✔ **데이터 수집 및 시각화**  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 차량 및 보행자 통행량, 위반 비율 데이터 자동 저장  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 대시보드를 통한 교통 데이터 시각화 및 통계 분석  

✔ **스마트 시티 연계 가능성**  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 교통 데이터 축적 및 통계 분석  
&nbsp;&nbsp;&nbsp;&nbsp;🔹 국토교통부 및 경찰청 시스템과의 연계 가능  

---

## 🔧 프로젝트 구성도

### 1️⃣ 소프트웨어 구성도
![소프트웨어 구성도](https://github.com/user-attachments/assets/47f389f0-d1a7-42ba-8087-f369a52cd82d)

### 2️⃣ 서비스 흐름도: 신호 체계 로직
![서비스 흐름도](https://github.com/user-attachments/assets/84bf46c6-4ff1-4384-8699-4cb244e7c724)

### 3️⃣ 하드웨어 구성도
![하드웨어 구성도](https://github.com/user-attachments/assets/91b90fa0-52f4-4b97-b634-73f0a8b68c34)

---
