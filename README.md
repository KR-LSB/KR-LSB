# 안녕하세요, 이승병입니다 👋

<div align="center">

**ML Engineer | 실전 프로젝트로 증명하는 개발자**

🏆 **분당서울대병원 의료 AI 데이터톤 6위 / 100팀** (상위 6%)  
⚡ **0.08초 RAG 시스템** 구축 | 🎯 **97% ICD-10 코딩 정확도** 달성

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FKR-LSB&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Profile+Views&edge_flat=false)](https://github.com/KR-LSB)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:leesb9535@naver.com)

</div>

---

## 🎯 About Me

```
🎓 협성대학교 소프트웨어공학과 (2026.02 졸업 예정)
💼 ML Engineer / Data Engineer / AI Research Engineer 구직 중
🏥 Medical AI & LLM 파인튜닝 전문
📍 Seoul, South Korea
```

### 💡 What I Do
- **의료 AI**: 실제 병원 데이터로 검증된 퇴원요약 자동 생성 시스템 개발
- **LLM Fine-tuning**: Llama-3.1-8B 파인튜닝으로 97% 정확도 달성
- **RAG 시스템**: 0.08초 응답시간, 82.3% 캐시 히트율의 프로덕션 시스템 구현
- **AI Agent**: LangGraph 기반 Human-in-the-loop 안전한 에이전트 설계
- **MLOps**: AWS GPU 인스턴스에서 대규모 모델 최적화 및 배포 경험

---

## 🏆 주요 성과

<table>
<tr>
<td>

### 🥈 데이터톤 6위 / 100팀
SNUBH 의료 AI 데이터톤  
**상위 6% **

</td>
<td>

### 🎯 97% 정확도
ICD-10 자동 코딩 정확도  
**의료진 시간 80% 절감**

</td>
<td>

### ⚡ 0.08초 응답
RAG 기반 요리 어시스턴트  
**82.3% 캐시 히트율**

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

### 💻 AI/ML & Backend
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
</p>

### ☁️ Cloud & Infrastructure
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

### 🎨 Frontend
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
</p>

---

## 🚀 Featured Projects

### 🏥 [MARS - Medical AI Record Summarization](https://github.com/KR-LSB/MARS)

> **🏆 분당서울대병원 의료 AI 데이터톤 6위 / 100팀**

<img src="https://img.shields.io/badge/EXAONE%207.8B-blue?style=flat-square"/> <img src="https://img.shields.io/badge/AWS%20L4%20GPU-orange?style=flat-square"/> <img src="https://img.shields.io/badge/LoRA-green?style=flat-square"/> <img src="https://img.shields.io/badge/Medical%20AI-red?style=flat-square"/>

#### 🚀 **Key Performance (예선 & 본선)**
| 구분 | Task | Model | Performance |
|:---:|:---:|:---:|:---|
| **Diagnosis** | **ICD-10 코드 예측** | `Llama-3.1-8B` | • **F1 Score 0.919** (Baseline 0.624 대비 **47.2%↑**) <br> • **완전 불일치율 0%** 달성 |
| **Generation** | **퇴원 요약지 생성** | `EXAONE-3.5-7.8B` | • **Lightweight RAG** 도입으로 할루시네이션 최소화 <br> • 평균 생성 시간 **33초/건** (입력 4k / 출력 1.5k 토큰) |

#### 🎯 핵심 성과
- ✅ **정확도 97%**: ICD-10 자동 코딩 (의료진 검토 시간 80% 절감)
- ✅ **효율성**: 환자당 평균 15분 → 3분으로 단축
- ✅ **규모**: 4개 진료과 399명 환자 데이터 처리
- ✅ **최적화**: AWS L4 GPU 환경에서 토큰 감소

#### 💡 기술적 도전
```
기술적 도전: 제한된 자원 하의 RAG최적화

문제: 24GB VRAM 단일 GPU 환경에서 긴 문맥의 의료 데이터를 처리할 때 발생하는 OOM 및 핵심 정보 누락
해결: 진료과별 키워드 가중치 RAG 알고리즘 개발, 입력 토큰을 동적으로 조절
결과: Fine-tuing 없이도 도메인 전문 지식을 반영한 고품질 퇴원 요약 자동화 및 안정적 파이프라인 구축
```

**Tech**: `PyTorch` `EXAONE` `RAG` `AWS L4` `Medical AI`

---

### 🏥 [Medical AI Agent - Human-in-the-loop EMR System](https://github.com/KR-LSB/medical-ai-agent)

> **🛡️ LangGraph 기반 안전한 의료 데이터 접근 에이전트**

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square"/> <img src="https://img.shields.io/badge/Llama%203.1-blue?style=flat-square"/> <img src="https://img.shields.io/badge/Human--in--the--loop-red?style=flat-square"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square"/>

**EMR 데이터 기반 진단 보조 시스템** - 민감한 환자 정보 접근 시 사람의 승인을 요구하는 Safety Pattern 구현

#### 🎯 핵심 성과
- ✅ **Safety First**: `interrupt_before` 패턴으로 민감 데이터 접근 전 승인 요청
- ✅ **State Management**: LangGraph의 Checkpointer로 대화 상태 저장/복원
- ✅ **Local LLM**: Ollama + Llama 3.1 8B (외부 API 의존 제거)
- ✅ **Full-Stack Demo**: Streamlit UI + SQLite EMR 연동

#### 💡 아키텍처
```
User Query → LLM Reasoning → Tool Call 결정
                                   │
                           🛑 INTERRUPT
                                   │
                   ┌───────────────┴───────────────┐
                   │      Human Review UI          │
                   │  [✅ Approve]  [❌ Reject]    │
                   └───────────────────────────────┘
```

**Tech**: `LangGraph` `LangChain` `Llama 3.1` `Streamlit` `SQLite` `Human-in-the-loop`

---

### 🍳 [Dalgurak - AI Cooking Assistant](https://github.com/KR-LSB/dalgurak)

> **⚡ 0.08초 응답시간 | 82.3% 캐시 히트율**

<img src="https://img.shields.io/badge/LangChain-blue?style=flat-square"/> <img src="https://img.shields.io/badge/ChromaDB-purple?style=flat-square"/> <img src="https://img.shields.io/badge/React-cyan?style=flat-square"/> <img src="https://img.shields.io/badge/Spring%20Boot-green?style=flat-square"/>

**RAG 기반 실시간 레시피 추천 시스템** (졸업 프로젝트)

#### 🎯 핵심 성과
- ✅ **응답 속도**: 평균 0.08초 (업계 평균 0.5~1.0초 대비 **10배 향상**)
- ✅ **캐싱**: Redis 기반 82.3% 캐시 히트율
- ✅ **데이터**: 7,500+ 레시피 시맨틱 검색 구현
- ✅ **풀스택**: React + Spring Boot 통합 개발

#### 💡 성능 최적화
```
Before: 평균 1.2초 응답
After: 평균 0.08초 응답 (15배 개선)

방법: ChromaDB 인덱싱 + Redis 캐싱 + 비동기 처리
```

**Tech**: `LangChain` `ChromaDB` `RAG` `Redis` `React` `Spring Boot`

---

### ⚽ [작성 준비중][K-League Predictor](https://github.com/KR-LSB/kleague-predictor)

> 앙상블 기반 축구 경기 결과 예측 시스템

<img src="https://img.shields.io/badge/XGBoost-orange?style=flat-square"/> <img src="https://img.shields.io/badge/Ensemble-green?style=flat-square"/> <img src="https://img.shields.io/badge/Feature%20Engineering-blue?style=flat-square"/>

**Tech**: `XGBoost` `Random Forest` `Feature Engineering` `Data Analysis`

---

## 📊 GitHub Stats

<div align="center">

![승병's GitHub stats](https://github-readme-stats.vercel.app/api?username=KR-LSB&show_icons=true&theme=radical)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=KR-LSB&layout=compact&theme=radical)](https://github.com/KR-LSB)

</div>

---

## 📜 Certifications

| 자격증 | 발급기관 | 취득일 |
|-------|---------|-------|
| **ADsP** (데이터분석 준전문가) | 한국데이터산업진흥원 | 12월 |
| **SQLD** (SQL 개발자) | 한국데이터산업진흥원 | 11월 |

---

## 📫 Contact Me

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:leesb9535@naver.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KR-LSB)

**"문제를 정의하고, 데이터로 검증하며, 코드로 구현합니다"**

</div>

---

<div align="center">

*⭐️ 마음에 드는 프로젝트가 있다면 Star를 눌러주세요!*

</div>
