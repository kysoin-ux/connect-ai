---
title: Electron Beam Irradiation
type: entity
created: 2026-05-18
updated: 2026-05-18
source_count: 1
tags: [radiation, synthesis, green-chemistry, cross-linking, nanoparticle]
---

# Electron Beam Irradiation (전자빔 조사)

## 기본 정보
- **분류:** 이온화 방사선 (ionizing radiation)의 일종
- **특징:** 화학 시약 없이 고분자의 가교(cross-linking), 그래프팅(grafting), 나노입자 형성 가능
- **장점:** 무독성, 고순도, 스케일업 가능, 실온 수용액 반응
- **시설:** EB Tech Co., Ltd. (Biomedical Manufacturing Technology Center) 등 전용 가속기 필요

## 나노입자 합성 메커니즘
[[fucoidan]] 나노입자 합성 시 다음 과정이 동시에 진행된다:

1. **물의 방사분해:** H₂O → eaq⁻ (수화전자) + OH• (하이드록실 라디칼)
2. **라디칼 생성:** OH•가 fucoidan의 sulfate 그룹(R-O-SO₃⁻)과 반응 → SO₃⁻• (황산 라디칼)
3. **가교 (Cross-linking):** SO₃⁻•가 hydroxyl/alcohol 그룹 산화 → alkoxy 라디칼(RO•) → ether 결합(R-O-R) 형성
4. **분해 (Chain scission):** 활성산소종에 의한 hydroperoxide 형성 → β-scission
5. **경쟁 반응:** chain scission : cross-linking ≈ 4.3 : 1 (Kilb 모델, ρ = 4.3)

저농도에서는 분자내 가교 우세 → 이산 나노입자 형성. 고농도(20–30%)에서는 분자간 가교 우세 → 벌크 겔 형성.

## 조사 조건 (Kim et al. 2026)
| 선량 범위 | Beam Current | 컨베이어 속도 |
|---|---|---|
| 저선량 (1, 3, 5 kGy) | 1.73 mA | 15 m/min |
| 중선량 (10, 30, 50 kGy) | 4.56 mA | 4 m/min |
| 고선량 (100, 200, 300 kGy) | 5.30 mA | 0.5 m/min |

에너지: 5 MeV, 온도: 25°C.

## 우리 연구실과의 관련성
전자빔 조사는 방사선 기술이라는 점에서 연구실의 **방사성 동위원소 기반 분자영상** 연구(4번 축)와 기술적 기반을 공유한다. 또한 [[green_nanoparticle_synthesis]] 전략으로서 다른 다당류/생체고분자 나노입자 합성에도 확장 가능하다.

## 관련 페이지
- [[fucoidan]] — 전자빔으로 합성된 나노입자의 원료
- [[green_nanoparticle_synthesis]] — 친환경 합성 개념
- [kim_2026_fucoidan_nanoparticles](../sources/kim_2026_fucoidan_nanoparticles.md) — 원본 논문
