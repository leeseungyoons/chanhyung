
# 광고 없는 찐맛집 추천 앱

이 프로젝트는 광고 없이 신뢰할 수 있는 맛집 정보를 제공하는 앱입니다. 서울을 중심으로, 여러 리뷰 플랫폼(네이버, 카카오맵, 구글 지도)에서 높은 평점을 받은 음식점들만을 추천하여 사용자가 만족스러운 식사를 할 수 있도록 돕습니다.

## 프로젝트 개요

1. **맛집 정보 수집**: 네이버, 카카오맵, 구글 지도에서 평균 평점이 4.5점 이상인 맛집만을 추천합니다.
2. **광고 없는 정보 제공**: 광고나 상업적 요소를 배제하고 오직 사용자 리뷰와 평가에만 의존하여 맛집 정보를 제공합니다.
3. **사용자 중심**: 사용자가 직접 맛집을 저장하고 관리할 수 있는 기능을 제공합니다. 

## 주요 기능

- **맛집 검색**: 사용자가 입력한 주소를 기준으로 반경 2km 내의 음식점을 검색합니다.
- **리뷰 종합**: 세 개의 플랫폼(네이버, 카카오맵, 구글 지도)에서 얻은 리뷰를 바탕으로 신뢰할 수 있는 맛집만을 추천합니다.
- **지도 기반 표시**: 음식점의 위치를 지도에 표시하고, 간편한 경로 안내 기능을 제공합니다.

## 설치 및 실행

### 설치 방법

1. 이 프로젝트를 클론합니다:

   ```bash
   git clone https://github.com/yourusername/restaurant-app.git
   ```

2. 필요한 라이브러리를 설치합니다:

   ```bash
   pip install -r requirements.txt
   ```

3. Streamlit 앱을 실행합니다:

   ```bash
   streamlit run chan.py
   ```

## 사용 방법

1. 앱을 실행하고, **상세한 주소**를 입력한 후 **음식점 찾기** 버튼을 클릭합니다.
2. 지도에 주변 음식점들이 표시되며, 각 음식점의 상세 정보를 볼 수 있습니다.
3. 클릭 시 해당 음식점에 대한 추가 정보를 볼 수 있는 링크를 제공합니다.

## 기술 스택

- **Frontend**: Streamlit
- **Backend**: Node.js, Express, Python (API 연동)
- **지도 API**: Kakao 지도 API
- **데이터**: 네이버, 카카오맵, 구글 지도 리뷰 데이터

## 개발 목표

- 신뢰할 수 있는 맛집 정보 제공
- 사용자 맞춤형 추천 기능 구현
- 광고 없는 진짜 맛집 추천 서비스

## 팀원 역할

- **이승윤**: 서버 및 데이터베이스 설계, 외부 API 통합, 추천 알고리즘 개발
- **김찬형**: 사용자 인터페이스 설계 및 모바일 앱 개발
