# DE32_LAST_DANCE

## Team4

- 맞춤형 추천 기능을 포함하는 통합형 국내 여행지 추천/계획 서비스
- https://github.com/TripCok

## 팀원

- `PM (Project Manager)`: 이정훈
- `AC (Agile Coach)`: 최하람
- `TL (Technical Leader)`: - 김령래
- `AA (Application Administrator)` - 정세현
- `예능부장`: 김예지

## 기능 및 서비스

### 테마별 사용자 맞춤 서비스
- 사용자 클릭 이벤트 로그를 활용한 국내 여행지 추천(실시간)
- 사용자의 선호도 데이터(찜, 즐겨찾기, 여행지 선택 시 우선적 고려 사항 설문 정보 등)를 활용한 국내 여행지 추천(배치)
### 관리자 페이지
- 모델 정확도(Score) 정보 제공(대시보드)
- 한달, 하루 별로 데이터를 취합하여 보여주는 서비스 제공
### 모임 관련 서비스
- 모임 방 참가자들의 여행 성향을 취합하여 여행지를 추천 받는 서비스

## 기술 스택

- 협업 툴 : Git, GitHub, Slack, Notion
- 데이터베이스 : MySQL
- DA : 
  - Crawling : Python(Selenium), VS Code
  - EDA : Python(Numpy, Pandas, Plotly, Folium, WordCloud), Colab
  - AI : Python(TensorFlow, Pytorch, Scikit-Learn), Colab
- BE :
  -  IDE : Intelij
  - Framework : Spring Boot
  - IDE, Lib, FW 미정
- FE  : 
  - HTML(BootStrap), VS Code
  - CSS(TailWind, Font-Awesome), VS Code
  - JS(React, Node.js, ESLint), VS Code
- ETC : Docker, Linux Ubuntu 22.04 Server LTS, k8s
