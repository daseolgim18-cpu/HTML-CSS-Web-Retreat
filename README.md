# Web Retreat

HTML5와 CSS3를 활용하여 제작한 **리트릿 소개·학습 일정·객실 예약 UI를 포함한 정적 웹페이지**입니다.  
HTML의 시맨틱 구조와 다양한 폼 요소, 테이블을 활용하고 CSS Grid/Flexbox 및 미디어 쿼리를 적용하여 화면을 구성했습니다.

---

## 프로젝트 개요

- **프로젝트명** : Web Retreat
- **개발 형태** : 개인 프로젝트
- **개발 목적** : HTML5 문서 구조와 CSS 레이아웃·스타일링 기초 학습 및 정적 웹페이지 구현
- **개발 환경** : VS Code
- **개발 언어** : HTML5, CSS3
- **구현 형태** : 정적 웹페이지
- **주요 화면** : 리트릿 소개, 학습 일정, 객실 예약 UI

---

## 주요 구현 내용

1. **상단 네비게이션 및 메인 비주얼 구성**
   - `Web Retreat`, 리트릿 소개, 학습 일정, 객실 예약 메뉴 구성
   - 리조트 이미지를 활용한 헤더 배경 영역 구현
   - Flexbox 기반 메뉴 정렬 및 Hover 스타일 적용

2. **웹 개발 학습 리트릿 소개 영역 구현**
   - 제목, 설명, 학습 항목 목록 구성
   - `strong`, `mark`, `pre` 등 HTML 태그 활용
   - 카드 형태의 콘텐츠 영역 스타일링

3. **주간 학습 일정 테이블 구현**
   - 주차, 주제, 실습 내용, 진행 방식 정보 구성
   - `rowspan`, `colspan`을 활용한 테이블 셀 병합
   - 학습 일정 정보를 표 형태로 직관적으로 표현

4. **객실 예약 입력 폼 UI 구현**
   - 성명, 전화번호, 이메일 입력 필드 구성
   - 도착 날짜, 객실 유형, 투숙 인원 선택 UI 구현
   - Radio Button, Checkbox, Textarea를 활용한 추가 옵션 입력 UI 구성
   - 예약 확정 및 입력 초기화 버튼 구현

5. **CSS 기반 레이아웃 및 반응형 UI 구현**
   - CSS Grid를 활용한 3단 콘텐츠 레이아웃 구성
   - Flexbox를 활용한 상단 메뉴 정렬
   - 입력 폼 Focus 및 버튼 Hover/Active 효과 적용
   - 미디어 쿼리를 활용해 태블릿·모바일 화면에서 레이아웃 변경

---

## 사용 기술 및 도구

- **HTML5**
  - Semantic Layout
  - List
  - Table
  - Form / Fieldset / Legend
  - Input / Select / Radio / Checkbox / Textarea
  - `rowspan` / `colspan`

- **CSS3**
  - CSS Grid
  - Flexbox
  - Box Model
  - Background Image
  - Pseudo Class
  - Transition
  - Media Query
  - Responsive Layout

- **개발 도구**
  - Visual Studio Code
  - Web Browser

---

## 프로젝트 구조

```text
HTML-CSS-Web-Retreat/
├─ README.md
├─ .gitignore
├─ index.html
├─ style.css
└─ travel.png
```

---

## 화면 구성

### 1. Header / Navigation
상단에 리조트 이미지를 배경으로 배치하고 네비게이션 메뉴를 구성했습니다.

```text
Web Retreat | 리트릿 소개 | 학습 일정 | 객실 예약
```

---

### 2. 리트릿 소개

웹 개발 학습 리트릿의 목적과 학습 내용을 보여주는 영역입니다.

- HTML5 & CSS 기초
- 실습 중심 프로젝트
- 웹 표준 학습
- HTML 문법 및 구조 학습

---

### 3. 주간 학습 일정

테이블을 활용하여 주차별 학습 내용을 구성했습니다.

```text
WEEK1
- Foundations
- 텍스트 및 목록 구조

WEEK2
- Applications
- 이력서 폼 & 멀티미디어
- 비디오 / 오디오 삽입
```

---

### 4. 객실 예약 UI

다양한 HTML Form 요소를 활용하여 객실 예약 입력 화면을 구성했습니다.

- 성명
- 전화번호
- 이메일
- 도착 날짜
- 객실 유형
- 투숙 인원
- 식사 서비스
- 리조트 픽업 서비스
- 레이트 체크아웃
- 기타 요청사항

> 본 프로젝트는 HTML/CSS 정적 페이지이므로 예약 정보가 서버나 데이터베이스에 실제 저장되는 기능은 포함하지 않습니다.

---

## 반응형 레이아웃

### Desktop
3개의 주요 콘텐츠 영역을 한 화면에 3단 Grid 형태로 배치합니다.

```text
[리트릿 소개] [학습 일정] [객실 예약]
```

### Tablet
화면 너비가 줄어들면 소개와 일정 영역을 2단으로 배치하고 예약 영역을 아래쪽 전체 너비로 배치합니다.

### Mobile
모든 콘텐츠 영역을 1단 구조로 변경하고 입력 폼과 버튼을 화면 너비에 맞게 배치합니다.

---

## 실행 방법

별도의 서버 설치나 빌드 과정이 필요하지 않습니다.

### 1. 프로젝트 다운로드

GitHub 저장소를 Clone하거나 ZIP 파일로 다운로드합니다.

### 2. 페이지 실행

`index.html` 파일을 웹 브라우저에서 실행합니다.

또는 VS Code의 Live Server 확장을 사용하는 경우 `index.html`을 Live Server로 실행할 수 있습니다.

---

## 구현 결과

- HTML5를 활용한 정적 웹페이지 문서 구조 작성
- 네비게이션·콘텐츠·테이블·예약 폼 UI 구성
- CSS Grid와 Flexbox를 활용한 레이아웃 구현
- 배경 이미지 및 카드 형태의 콘텐츠 디자인 적용
- 다양한 Form 요소를 활용한 사용자 입력 화면 구성
- Hover, Focus, Active 등 사용자 인터랙션 스타일 구현
- 미디어 쿼리를 활용한 반응형 화면 구성

---

## 프로젝트에서 학습한 내용

- HTML 문서의 기본 구조와 태그별 역할
- HTML Table 및 Form 요소 활용 방법
- CSS 선택자와 Box Model 적용 방법
- Grid와 Flexbox를 활용한 화면 배치
- 입력 요소별 CSS 스타일링
- 화면 크기에 따른 반응형 레이아웃 구현 방법
