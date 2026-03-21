# K-ETS 탄소배출권 데이터 분석

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

## 개요

환경부·한국환경공단·한국에너지공단의 공공데이터를 기반으로, 한국 탄소배출권거래제(K-ETS) 배출량 현황 분석 및 최적 구매 전략을 도출한 데이터 분석 프로젝트입니다.

> 전체 시스템(풀스택 대시보드)은 [K-ETS_Dashboard](https://github.com/Quietseong/K-ETS_Dashboard) 레포에서 확인할 수 있습니다.

## 분석 파이프라인

| 단계 | 내용 |
|------|------|
| 데이터 수집 | 환경부·한국환경공단·한국에너지공단 공공데이터 (CSV/Excel) |
| 전처리 | 국가 온실가스 인벤토리 정제, 업체별 배출량·할당량 매핑 |
| 탐색적 분석 | 연도별 배출량 추이, 지역별 CO2 분포, KAU24 시장 데이터 분석 |
| 구매 전략 분석 | 최적 매수 타이밍 산출, 감축 vs 구매 ROI 비교, 헤징 전략 도출 |
| AI 분석 | LLM 기반 코드 자동 생성으로 CSV 데이터 직접 분석 (RAG 파이프라인) |
| 시각화 | Plotly 인터랙티브 차트 + Tableau 대시보드 |

## 주요 분석 결과

- **배출량 현황**: 연도별 국가 온실가스 배출량 추이 및 지역별 CO2 분포 시각화
- **시장 분석**: KAU24 배출권 시장 가격 동향 및 거래량 패턴 분석
- **구매 전략**: 업체별 할당량 대비 실배출량 기반 최적 매수 타이밍 도출
- **AI 인사이트**: RAG 파이프라인을 활용한 정책 문서 기반 심층 분석

## 자료

- [**전체 프로젝트** (풀스택 대시보드)](https://github.com/Quietseong/K-ETS_Dashboard)
- [**인터랙티브 대시보드** (Tableau)](https://quietseong.github.io/Portfolio/k-ets-dashboard.html)

## Tableau Dashboard

> 아래 이미지를 클릭하면 인터랙티브 대시보드로 이동합니다.

[![배출권 대시보드](https://public.tableau.com/static/images/_1/_17498945051960/sheet0/1_rss.png)](https://quietseong.github.io/Portfolio/k-ets-dashboard.html)
