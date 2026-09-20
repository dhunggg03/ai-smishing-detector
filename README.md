# ai-smishing-detector

# 🛡️ AI 기반 실시간 스미싱 및 피싱 URL 탐지 시스템
AI-Powered Smishing & Phishing URL Real-time Detector

# 📌 개요
 프로젝트는 일상생활에서 발생하는 지능형 스미싱 문자 및 피싱 URL로 인한 개인정보 유출 및 금전적 피해를 예방하기 위한 **실시간 탐지 및 경고 시스템**입니다. 정보보안 전공 지식과 인공지능(AI) 기술을 융합하여 실생활의 보안 위협을 해결하는 것을 목표로 합니다

# 🛠️ 기술 스택
* **Language & AI:** Python, Scikit-learn (머신러닝 기반 텍스트 및 URL 패턴 분석)
* **Backend API:** FastAPI / Flask
* **Frontend / Interface:** HTML, CSS, JavaScript (웹 기반 인터페이스)

# 🚀 주요 기능
1. **텍스트 및 URL 분석:** 의심스러운 문자 내용이나 단축 URL 입력 시 위험도(Phishing Score) 산출
2. **휴리스틱 및 AI 탐지:** 머신러닝 모델과 보안 규칙(Heuristic Analysis)을 결합한 다중 레이어 탐지
3. **실시간 경고 시스템:** 위험 등급(안전, 주의, 위험)에 따른 직관적인 차단 가이드 및 알림 제공

# 📁 프로젝트 구조
ai-smishing-detector/
data/               # 데이터셋 (Open-source Phishing/Smishing datasets)
models/             # 학습된 AI 모델 및 스크립트
backend/            # FastAPI / Flask API 서버 코드
frontend/           # 웹 인터페이스 (UI)
README.md           # 프로젝트 소개 문서

## 📅 개발 로드맵
* **Phase 1:** 환경 설정, Git 저장소 구축 및 오픈소스 데이터셋 수집
* **Phase 2:** 데이터 전처리, URL 특징 추출 및 AI 분류 모델 학습
* **Phase 3:** Backend API 구현 및 웹 UI 연동
* **Phase 4:** 통합 테스트, 성능 최적화 및 최종 보고서 작성




# 🛡️ AI-Powered Smishing & Phishing URL Real-time Detector

## 📌 Overview
This project is a **real-time detection and alert system** designed to prevent personal information leaks and financial damage caused by frequent intelligent smishing messages and phishing URLs in daily life. It aims to solve real-world security threats by converging information security major knowledge and Artificial Intelligence (AI) technologies

## 🛠️ Tech Stack
* **Language & AI:** Python, Scikit-learn (ML-based text & URL pattern analysis)
* **Backend API:** FastAPI / Flask
* **Frontend / Interface:** HTML, CSS, JavaScript (web-based interface)


## 🚀 Core Features
1. **Text & URL Analysis:** Calculates the risk score (Phishing Score) upon input of suspicious text messages or shortened URLs
2. **Heuristic & AI Detection:** Multi-layer detection combining machine learning models and security rule sets 
3. **Real-time Alert System:** Provides intuitive blocking guides and alerts based on risk levels 

## 📁 Project Structure
ai-smishing-detector/
data/               # Open-source Phishing/Smishing datasets
models/             # Trained AI models & scripts
backend/            # API server code (FastAPI / Flask)
frontend/           # Web interface (UI)
README.md           # Project documentation

## 📅 Development Roadmap
* **Phase 1:** Environment setup, Git repository initialization, and open-source dataset collection
* **Phase 2:** Data preprocessing, URL feature extraction, and AI classification model training
* **Phase 3:** Backend API implementation and Web UI integration
* **Phase 4:** Integration testing, performance optimization, and final report writing
