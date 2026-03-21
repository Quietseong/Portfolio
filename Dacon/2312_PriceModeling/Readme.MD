# RFM 클러스터링 기반 수익 극대화 가격 모델링

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

## 개요

콘서트홀 클래식 공연 거래 데이터(약 190만 건)를 기반으로, **RFM(Recency, Frequency, Monetary) 분석**과 **클러스터링**을 활용하여 고객 세그먼트별 최적 가격 전략을 도출한 프로젝트입니다.

## 분석 파이프라인

| 단계 | 내용 |
|------|------|
| 데이터 전처리 | 클래식 공연 + 콘서트홀 필터링 (190만 → 10.7만 건) |
| 피처 엔지니어링 | 멤버십 카테고리 통합, 연령·성별·멤버십 파생변수 생성 |
| 통계 검정 | 카이제곱검정을 통한 범주형 변수 간 연관성 분석 |
| 클러스터링 | 고객 특성 기반 그룹화 및 세그먼트 도출 |
| 가격 모델링 | 세그먼트별 수익 극대화 가격 포인트 산출 |
| 시각화 | Tableau 대시보드를 통한 인터랙티브 결과 시각화 |

## 자료

- [**분석 코드** (Jupyter Notebook)](https://github.com/Quietseong/Portfolio/blob/main/Dacon/2312_PriceModeling/Capstone_analysis.ipynb)
- [**인터랙티브 대시보드** (Tableau)](https://quietseong.github.io/Portfolio/price-modeling.html)

## Tableau Dashboard

> 아래 이미지를 클릭하면 인터랙티브 대시보드로 이동합니다.

[![Revenue Maximizing Price Point](https://public.tableau.com/static/images/RF/RFMwithML/Revenue_Maximizing_Price_point/1_rss.png)](https://quietseong.github.io/Portfolio/price-modeling.html)
