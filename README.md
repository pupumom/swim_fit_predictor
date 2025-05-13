<p align="center">
  <img src="imgs/swimfit_thumbnail.png" alt="SwimFitPredictor Thumbnail" width="700"/><br/>
  <em>수집한 수영복 리뷰 데이터 (키, 몸무게, 사이즈, 리뷰 텍스트 포함)</em>
</p>

# 🩱 SwimFitPredictor

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Last Commit](https://img.shields.io/github/last-commit/pupumom/swim_fit_predictor?style=flat)
![Repo Size](https://img.shields.io/github/repo-size/pupumom/swim_fit_predictor)

**수영복 리뷰 데이터를 기반으로 사이즈 추천 모델을 개발하기 위한 데이터 수집 프로젝트입니다.**  
가나스윔 사이트의 리뷰를 크롤링하여 키, 몸무게, 평소 착용 사이즈, 구매 사이즈 등 정보를 수집했습니다.

---

## 📌 주요 기능
- Selenium을 활용한 iframe 기반 리뷰 크롤링
- 사용자 정보 및 사이즈 관련 텍스트 정제
- 사이즈 추천 모델 구축을 위한 사전 데이터 확보

---

## 🛠 기술 스택
- Python
- Selenium
- pandas, tqdm
- imageio, scikit-image
- BeautifulSoup4

---

## 📁 디렉토리 구조
``` 
swim_fit_predictor/
├── notebook/
│ └── review_crawling.ipynb
├── data/ 
│ └── swim_reviews_0510.csv
├── imgs/ 
├── .gitignore
├── requirements.txt
└── README.md
``` 

---

## ⚠️ 참고 사항
- 본 프로젝트는 **학습 및 포트폴리오 목적**으로 진행되었으며, 크롤링 대상 사이트의 로봇 배제 정책 및 약관을 존중합니다.

