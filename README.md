# timesfm-study

Google Research의 시계열 파운데이션 모델 [TimesFM](https://github.com/google-research/timesfm)을
공부하고 태양광 발전량 예측에 적용해본 개인 기록입니다.

## 구성

- [`review.qmd`](review.qmd) — Foundation model(파운데이션 모델) 개념과 TimesFM을 정리한 발표자료 (Quarto Beamer)
- [`TimesFM.ipynb`](TimesFM.ipynb) — TimesFM 2.0 사용법 정리 (체크포인트 로딩, 하이퍼파라미터)
- [`timesfm_test.ipynb`](timesfm_test.ipynb) — 서울 태양광 발전량 데이터에 TimesFM 1.0/2.0을 적용한 테스트
- `latex/preamble.tex` — 발표자료 렌더링용 LaTeX preamble

## 배경

에너지 시계열 예측(ISF, International Symposium on Forecasting) 프로젝트를 하면서,
사전학습된 파운데이션 모델을 예측에 활용할 수 있을지 검토하며 정리한 자료입니다.

## Acknowledgement

This repository was developed with support from the 서울시립대학교 데이터 사이언스 플러스 차세대 융합인재 양성사업단 – http://dsplus.uos.ac.kr/
