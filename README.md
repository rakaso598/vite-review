# 영화 정보 탐색 웹 애플리케이션

이 프로젝트는 React를 사용하여 영화 데이터 API로부터 정보를 가져와 사용자에게 보여주는 웹 애플리케이션입니다. 사용자는 영화 목록을 보고, 정렬하고, 더 많은 영화를 불러오는 등의 탐색 기능을 사용할 수 있습니다.

## 주요 기능

- **영화 목록 표시:**
  - 영화 데이터 API로부터 영화 정보를 가져와 목록 형태로 표시합니다.
  - 영화 정보는 평점(rating) 또는 작성일(createdAt) 순으로 정렬할 수 있습니다.
  - 페이지네이션을 통해 많은 영화 정보를 효율적으로 표시합니다.
  - 영화 목록을 불러오는 과정에서 로딩 상태 및 오류 메시지를 표시하여 사용자 경험을 향상시킵니다.
- **영화 정보 정렬:**
  - 최신순 또는 평점순으로 영화 정보를 정렬하여 사용자가 원하는 정보를 쉽게 찾을 수 있도록 합니다.
- **더보기 기능:**
  - 더보기 버튼을 통해 추가적인 영화 정보를 불러와 표시합니다.
- **영화 정보 탐색:**
  - 사용자는 다양한 방법으로 영화정보를 탐색할수 있습니다.

## 주요 컴포넌트

- **App.jsx:**
  - 전체 애플리케이션의 상태 관리 및 레이아웃을 담당합니다.
  - 영화 목록, 정렬 버튼, 더보기 버튼 등을 포함합니다.
  - `getReviews` API를 통해 영화 데이터를 가져오고, 상태를 업데이트합니다.
- **ReviewList.jsx:**
  - 영화 목록을 표시하는 컴포넌트입니다.
  - 각 영화 항목을 표시하고, 삭제 기능을 제공합니다.
- **ReviewForm.jsx:**
  - 파일 업로드 기능을 포함하고 있습니다.
- **FileInput.jsx:**
  - 이미지 파일(PNG, JPEG)만 선택할 수 있도록 제한합니다.
- **api.js:**
  - 서버와의 통신을 담당하는 API 함수를 포함합니다.
  - `getReviews` 함수를 통해 영화 데이터를 가져옵니다.

## 주제 및 목표

- **영화 데이터 표시 및 관리:**
  - 영화 데이터 API를 활용하여 영화 정보를 효과적으로 표시하고 관리하는 웹 애플리케이션을 개발합니다.
- **API 데이터 활용:**
  - 외부 API로부터 데이터를 가져와 웹 애플리케이션에 표시하는 방법을 학습합니다.
- **상태 관리 및 비동기 처리:**
  - React의 `useState`, `useEffect` 훅을 사용하여 상태를 관리하고, 비동기 API 호출을 처리합니다.
- **컴포넌트 기반 개발:**
  - 컴포넌트 기반으로 애플리케이션을 구성하여 재사용성과 유지보수성을 높입니다.
- **사용자 경험 향상:**
  - 로딩 상태, 오류 메시지, 페이지네이션 등을 통해 사용자 경험을 향상시킵니다.

## 핵심 수정 사항

- 이 프로젝트는 사용자 리뷰 관리 앱이 아닌, 영화 데이터 API를 활용한 영화 정보 표시 및 탐색 앱입니다.
- ReviewForm.jsx는 파일업로드 기능을 포함하고 있습니다.
