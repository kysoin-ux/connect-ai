---
title: Nanoparticle Drug Delivery (나노입자 약물전달)
type: concept
created: 2026-05-18
updated: 2026-05-18
source_count: 1
tags: [nanomedicine, drug-delivery, EPR, targeting, pH-responsive]
---

# Nanoparticle Drug Delivery (나노입자 약물전달)

## 개요
나노입자(일반적으로 10–300 nm)를 이용하여 항암제 등 약물을 종양 조직에 선택적으로 전달하는 전략이다. 유정수 교수님 연구실의 **나노의학** 축의 핵심 개념.

## 핵심 원리

### 수동 표적화 (Passive Targeting)
EPR (Enhanced Permeability and Retention) 효과: 종양 혈관의 투과성 증가와 림프 배수 기능 저하로 인해 나노입자가 종양 조직에 선택적으로 축적됨.

### 능동 표적화 (Active Targeting)
나노입자 표면에 항체, 펩타이드, 리간드 등을 결합하여 종양 세포의 특이적 수용체를 인식. [[fucoidan]]의 경우 P-selectin을 자체적으로 표적화할 수 있는 장점이 있음.

### pH-감응 방출 (pH-Responsive Release)
종양 미세환경(pH ~5.5–6.5)과 정상 조직(pH 7.4)의 pH 차이를 이용하여 약물 방출을 제어. 산성 환경에서 방출이 가속되고, 생리적 pH에서는 방출이 억제되어 부작용 감소.

## 연구실 관련 사례

### Fucoidan 나노입자 + DOX (Kim et al. 2026)
- 입자 크기: ~100 nm (100 kGy 전자빔 조사)
- 봉입효율: 97.3%
- pH-감응: pH 7.4에서 35.7%, pH 5.5에서 45.2% 방출 (48시간)
- In vivo: EMT6 종양 부피 4배 억제 (vs PBS)
- 상세: [kim_2026_fucoidan_nanoparticles](../sources/kim_2026_fucoidan_nanoparticles.md)

## 주요 설계 파라미터
| 파라미터 | 목표값 | 측정법 |
|---|---|---|
| 입자 크기 | 50–200 nm (EPR 효과 최적) | DLS, TEM |
| PDI | < 0.3 (균일한 분포) | DLS |
| 제타 전위 | |절대값| > 15 mV (안정성) | DLS |
| 봉입효율 (EE%) | > 80% | UV-Vis 분광법 |
| pH-감응성 | pH 5.5에서 가속 방출 | 투석법 |

## 관련 페이지
- [[fucoidan]] — 천연 다당류 기반 나노캐리어
- [[doxorubicin]] — 대표적 탑재 항암제
- [[green_nanoparticle_synthesis]] — 친환경 합성 전략
