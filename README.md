# MEPC83-Simulator
::MEPC83차 회의 결과에 따른 선박 규제를 계산해볼 수 있는 시뮬레이터::

**LINK**: https://wjgoarxiv.github.io/MEPC83-Simulator/

<br/>

## ✨ 핵심 특징

MEPC 83 규제 영향 분석 시뮬레이터는 선박 관계자가 새로운 규제(GFI, CII)의 영향을 가장 쉽고 빠르게 계산하도록 돕는 인터렉티브 웹사이트입니다.

-   **쉬운 자동 계산**: 연료 사용량 (tonne)만 입력하면 GFI와 CII를 자동으로 계산합니다.
-   **직관적인 시각화**: `p5.js` 인터랙티브 차트로 연도별 규제 준수 현황을 한눈에 파악합니다.
-   **투명한 계산 과정**: '계산 과정 보기'를 통해 IMO 공식 기반의 모든 계산 과정을 투명하게 공개합니다.
-   **고급 인터랙션**: GSAP 기반의 동적 애니메이션으로 몰입감 있는 경험을 제공합니다.
-   **반응형 디자인**: 어떤 기기에서든 최적화된 화면으로 이용할 수 있습니다.

<br/>

## 🚀 주요 기능

| 기능 | 설명 |
|---|---|
| **GFI 자동 계산** | 연료별 사용량(tonne) 입력 시 Well-to-Wake 기준 GHG Fuel Intensity 자동 계산. 전문가를 위한 직접 입력 옵션도 제공. |
| **CII 등급 자동 예측** | 선종, 재화중량(DWT), 운항 거리 정보 기반 연도별 CII 예상 등급(A-E) 자동 제시. |
| **인터랙티브 차트** | p5.js 기반 동적 차트에서 GFI 준수 상태를 연도별 목표치와 시각적으로 비교. |
| **상세 계산 과정 팝업** | GFI, 비용, CII가 어떤 공식과 계수로 계산되었는지 상세 정보 확인. |
| **정보 사이드바** | GFI, CII, RU/SU 등 규제 용어를 설명하는 사이드바 제공. |

<br/>

## 🛠️ 사용 기술

-   **Core**: `HTML`, `CSS`, `JavaScript`
-   **Styling**: `Tailwind CSS`
-   **Interactive Graphics**: `p5.js`
-   **Animation**: `GSAP (GreenSock Animation Platform)`
-   **Math Rendering**: `KaTeX`

<br/>