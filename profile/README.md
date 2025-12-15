# 🚀 LSM-Opt: Large-Scale Model Optimization Framework

**LSM-Opt**는 이종 AI 반도체 환경(GPU, NPU, PIM 등)에서 **초거대 AI 모델을 효율적으로 실행하기 위한 최적화 코드 변환 프레임워크**입니다.

본 프로젝트는 모델 분석부터 연산 그래프 최적화, 하드웨어 특화 코드 생성, 실행 런타임 및 메타데이터 관리까지의 **End-to-End 최적화 파이프라인**을 제공합니다.

---

## ✨ Key Features

- 🔍 초거대 AI 모델 분석 및 변환 계획 수립
- 🧠 프레임워크 독립적 연산 그래프(IR) 생성 및 최적화
- ⚙️ AI 반도체별 하드웨어 특화 코드 자동 생성
- 🚀 고성능 실행 런타임 및 실시간 모니터링
- 🗂️ 모델·하드웨어·커널·실행 이력 메타데이터 관리
- 🔁 재현 가능한 변환·실행 파이프라인 제공

---

## 🏗️ Overall Architecture

```
MAP  →  (GOP  ⟷  HCG)  →  RUN
  ↘───────────────↘
           MDM
```

| Module | Description |
|------|-------------|
| MAP | Model Analysis & Planning Engine |
| GOP | Graph Optimization Engine |
| HCG | Hardware-Specific Code Generation |
| RUN | Optimized Execution Runtime |
| MDM | Metadata Management Layer |

---

## 📦 Repository Structure

| Repository | Role |
|----------|------|
| MAP | Model structure analysis & HW-aware planning |
| GOP | IR generation & graph optimization |
| HCG | Mixed precision & HW-specific code generation |
| RUN | Runtime execution & monitoring |
| MDM | Metadata, benchmark & kernel repository |

---

## 📜 License

Apache License 2.0 (TBD)

