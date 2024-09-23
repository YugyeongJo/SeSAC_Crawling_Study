# 📚 SeSAC_Crawling_Study

## 📖 소개

SeSAC Crawling Study 레포지토리는 학습한 웹크롤링 관련 내용을 정리한 것입니다. 주요 개념과 기법들을 다루며, 학습 과정에서 다룬 내용들을 기록하고 있습니다.

### 학습 내용

|구분|학습 내용|
|--|--|
|** **||

## 🛠️ 기술 스택

|<center>VScode</center>|<center>Python</center>|<center>Pandas</center>|<center>Sklearn</center>|<center>Matplotlib</center>|<center>Seaborn</center>|
|--|--|--|--|--|--|
|<p align="center"><img alt="vscode" src="./icons/VSCode-Light.svg" width="48"></p>|<p align="center"><img alt="html" src="./icons/Python-Dark.svg" width="48"></p>|<p align="center"><img alt="html" src="./icons/Pandas.png" width="48"></p>|<p align="center"><img alt="html" src="./icons/ScikitLearn-Dark.svg" width="48"></p>|<p align="center"><img alt="html" src="./icons/matplotlib.png" width="48"></p>|<p align="center"><img alt="html" src="./icons/Seaborn.jpg" width="48"></p>|
|<img src="https://img.shields.io/badge/visual studio code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">|<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">|<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">|<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">|<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">|<img src="https://img.shields.io/badge/Seaborn-%237fb3d5.svg?style=for-the-badge&logo=Seaborn&logoColor=black">|


## 📂 Directory Structure

```plaintext
SeSAC_Crawling_Study/
├── README.md 
├── icons/
├── skeleton/
│   ├── basic_crawling.py
│   ├── bit_complex_crawling.py
│   ├── async_crawling.py
│   ├── code2info.pickle
│   ├── web_control.js
│   ├── async_transfer/
│   │        ├──bit_complex_crawling.py
│   │        └──abit_complex_crawling.py
│   ├── playwright/
│   │        └── playwright_tutorial.py
│   └── korail_quest/
│            └── korail_reservation.py
└── async/
    ├── async_before.py  
    └── async_after.py
```

## 💻 skeleton
|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|crawling|[basic_crawling.py](./skeleton/basic_crawling.py)|BeautifulSoup을 활용한 웹크롤링 실습||
|02|crawling|[bit_complex_crawling.py](./skeleton/bit_complex_crawling.py)|네이버 뉴스 기자 리스트 웹크롤링 실습||
|03|async|[bit_complex_crawling.py](./skeleton/bit_complex_crawling.py)|async을 활용한 네이버 뷰스 기자 리스트 웹크롤링 실습||
|04|pickle file|[code2info.pickle](./skeleton/code2info.pickle)|pickle을 통한 file caching||
|05|js file|[web_control.js](./skeleton/web_control.js)|js 기본 문법 정리||

<details open>
<summary> async_transfer </summary
|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|async|[bit_complex_crawling.py](./skeleton/async_transfer/bit_complex_crawling.py)|네이버 뉴스 기자 리스트 웹크롤링 실습 비동기 전||
|02|async|[abit_complex_crawling.py](./skeleton/async_transfer/abit_complex_crawling.py)|네이버 뉴스 기자 리스트 웹크롤링 실습 비동기 후||

</details>

<details open>
<summary> playwright </summary
|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|playwright|[playwright_tutorial.py](./skeleton/playwright/playwright_tutorial.py)|playwright 학습||

</details>

<details open>
<summary> korail_quest </summary
|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|실습|[korail_reservation.py](./skeleton/korail_quest/korail_reservation.py)|korail 기차표 예매 실습||

</details>

## 📝 async
|번호|구분|파일|설명|비고|
|--|--|--|--|--|
|01|async|[async_before.py](./async/async_before.py)|async 전 실행시간 실습||
|02|async|[async_after.py](./async/async_after.py)|async 후 실행시간 실습||
