# 상장기업 가치평가 모델 아카이브

이 저장소는 여러 상장기업을 대상으로 작성한 **탐색적 가치평가 워크북**을 보관합니다. 각 파일은 공개정보와 분석 가정을 구조화해 기업가치를 검토하기 위한 연구 자료이며, 투자 추천이나 확정적 주가 예측을 제공하지 않습니다.

## 파일 목록

| 기업 / 티커 | 파일 |
|---|---|
| Core Scientific / CORZ | `CORZ_Full_Valuation_Model_2026-08-07.xlsx` |
| Nebius Group / NBIS | `NBIS_Valuation_Model_v1.xlsx` |
| Sea Limited / SE | `SE_Full_Valuation_Model_2026-08-07.xlsx` |
| TeraWulf / WULF | `WULF_Full_Valuation_Model_2026-08-07.xlsx` |
| YPF / YPF | `YPF_Full_Valuation_Model_2026-08-07.xlsx` |

## 용어 사용 원칙

- **모델 추정가치(model-implied value):** 입력 가정과 선택한 방법론에서 계산된 값입니다. 객관적으로 확정된 `진짜 가치`를 뜻하지 않습니다.
- **가치평가 범위(valuation range):** 시나리오와 민감도에 따른 결과 구간입니다. 단일 숫자보다 가정 불확실성을 더 잘 보여줍니다.
- **전망(forecast):** 명시된 기간, 산출 근거, 갱신 기준이 있는 추정치에만 사용합니다. 단순 시나리오는 `가정` 또는 `시나리오`로 표시합니다.
- **목표주가(price target):** 기준일, 평가기간, 촉매, 리스크가 함께 정의된 경우에 사용합니다. 그렇지 않으면 `모델 추정가치`라는 표현을 우선합니다.
- **DCF / SOTP / rNAV / 멀티플:** 실제 워크북에서 해당 계산법을 구현한 경우에만 방법론 이름을 붙입니다. 저장소 전체에 하나의 방법론을 일괄 적용했다고 가정하지 않습니다.
- **촉매(catalyst):** 시장이 가치평가 격차를 재평가하게 할 수 있는 사건이나 정보입니다. 촉매의 존재가 가격 반응이나 실현 시점을 보장하지는 않습니다.

## 워크북 검토 체크리스트

1. 기준일과 사용한 시장가격을 확인합니다.
2. 원자료와 회사 가이던스, 분석가 가정을 구분합니다.
3. 매출, 마진, 자본지출, 할인율, 말기가치 등 핵심 가정을 점검합니다.
4. 기본·상승·하락 시나리오와 민감도를 비교합니다.
5. 순부채, 희석주식 수, 비지배지분 등 기업가치에서 주주가치로 이어지는 조정을 확인합니다.
6. 실제 실적이나 새로운 공시가 발표되면 기준일과 가정을 갱신합니다.

## 이용 시 유의사항

- 워크북은 감사받은 재무모형이 아니며 오류나 누락이 있을 수 있습니다.
- 과거 자료와 가정에 기반한 계산 결과는 미래 수익률을 보장하지 않습니다.
- 모델 간 가정과 구조가 다를 수 있으므로 기업 간 결과를 단순 비교해서는 안 됩니다.
- 본 저장소의 자료는 연구·교육·포트폴리오 목적이며 투자자문이나 매매 추천이 아닙니다.

---

## English summary

This private repository is an archive of exploratory public-equity valuation workbooks for CORZ, NBIS, SE, WULF, and YPF. Outputs should be read as **model-implied values or valuation ranges conditional on stated assumptions**, not as objective fair values, guaranteed forecasts, or investment recommendations.

Method labels such as DCF, SOTP, rNAV, or multiples should be used only where the relevant workbook actually implements that method. A price target should also state its as-of date, horizon, catalysts, and key risks; otherwise, `model-implied valuation estimate` is the preferred term.
