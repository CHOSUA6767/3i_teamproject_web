# 🎥 3 Idiots (세 얼간이) - Web Design Portfolio

## 📖 프로젝트 소개
이 프로젝트는 영화 **'세 얼간이(3 Idiots)'**를 주제로 제작된 웹 디자인 포트폴리오 사이트입니다.
메인 페이지의 비디오 배경, 인터랙티브한 내비게이션, 그리고 Chart.js를 활용한 데이터 시각화 페이지 등을 통해 영화의 등장인물, 줄거리, 평점 분석 등을 효과적으로 전달하도록 구성되었습니다.

## 👨‍👩‍👧‍👦 팀원 및 담당 역할 (Team & Roles)
* **박다찬:** 메인 페이지(`index.html`), 줄거리 페이지 기획 및 구현
* **홍현진:** 등장인물 소개 페이지(`sub_rancho.html` 등 캐릭터 전반) 구현
* **조수아:** 후기평 및 평점 분석 페이지(`sub_netizen_ratings.html`, `sub_critic_reviews.html`) 구현

## 🛠 사용 기술 (Tech Stack)
* **Core:** HTML5, CSS3, JavaScript (ES5/ES6)
* **Libraries & Plugins:**
    * **jQuery (v1.12.3):** DOM 조작 및 이벤트 처리
    * **WOW.js:** 스크롤에 따른 요소 등장 애니메이션 구현
    * **Swiper.js:** 슬라이드 기능 구현
    * **Chart.js:** 평론가 평점 데이터 시각화 (Radar, Bar Chart)
    * **Tailwind CSS (CDN):** 평론가 페이지의 스타일링 보조
* **Fonts:** Google Fonts (Noto Sans KR, Anton)

## ✨ 주요 기능 (Key Features)

### 1. 메인 페이지 (Main)
* **Video Background:** `video` 태그를 활용하여 영화 하이라이트 영상을 배경으로 재생, 몰입감을 높였습니다.
* **Black Theme UI:** 영화의 시네마틱한 분위기에 맞춰 전체적으로 어두운(Black) 톤의 UI를 적용했습니다.

### 2. 등장인물 소개 (Characters)
* 란초, 파르한, 라주, 차투르, 피아 등 주요 캐릭터별 서브 페이지를 구성했습니다.
* 각 캐릭터의 이미지와 명대사, 성격 분석 텍스트를 레이아웃에 맞춰 배치했습니다.

### 3. 평점 및 리뷰 분석 (Reviews & Analytics)
* **네티즌 평점:** 실제 관람객 평점 데이터를 막대그래프 이미지 등으로 시각화하여 배치했습니다.
* **평론가 평점 (Chart.js):** Chart.js 라이브러리를 사용하여 평론가 점수(Bar Chart)와 키워드 분석(Radar Chart)을 동적으로 렌더링했습니다.

### 4. UI/UX
* **Dropdown Navigation:** 마우스 오버 시 하위 메뉴와 이미지가 함께 나타나는 직관적인 GNB(Global Navigation Bar)를 구현했습니다.
* **Responsive Layout:** 컨테이너 기반의 중앙 정렬 레이아웃을 사용했습니다.

## 📂 파일 구조 (File Structure)

```text
📦 3-Idiots-Project
 ┣ 📂 css/                # 스타일 시트 (reset, style, swiper 등)
 ┣ 📂 images/             # 이미지 및 비디오 리소스
 ┣ 📂 js/                 # 자바스크립트 파일
 ┃ ┣ 📂 plugin/           # jQuery, WOW, Swiper 등 라이브러리
 ┃ ┗ function.js          # 공통 기능 스크립트
 ┣ 📜 index.html          # 메인 페이지 (담당: 박다찬)
 ┣ 📜 sub_recruit.html    # 줄거리 페이지 (담당: 박다찬)
 ┣ 📜 sub_rancho.html     # 캐릭터 - 란초 (담당: 홍현진)
 ┣ 📜 sub_farhan.html     # 캐릭터 - 파르한 (담당: 홍현진)
 ┣ 📜 sub_raju.html       # 캐릭터 - 라주 (담당: 홍현진)
 ┣ 📜 sub_chatur.html     # 캐릭터 - 차투르 (담당: 홍현진)
 ┣ 📜 sub_pia.html        # 캐릭터 - 피아 (담당: 홍현진)
 ┣ 📜 sub_netizen_ratings.html # 네티즌 평점 (담당: 조수아)
 ┣ 📜 sub_critic_reviews.html  # 평론가 평점 분석 (담당: 조수아)
 ┗ 📜 README.md           # 프로젝트 설명 파일
