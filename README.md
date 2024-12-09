# 골라조

## 프로젝트명 : PICK PARADE
- **이상형 월드컵 이란?**
  - 토너먼트 방식으로 주제에 맞추어 자신이 더 선호하는, 또는 더 비선호하는 것을 골라 최종 승자를 가리는 일종의 vs놀이.

---
### 👤 구성원 & 역할
|이름|역할|
|--|--|
|[종복](https://github.com/JONGBOK1)|이상형 월드컵 만들기 툴 제작 🔧|,
|[명진](https://github.com/wamong)|이상형 월드컵 만들기 툴 제작 🔧|,
|[유진](https://github.com/jojeongin313)|웹사이트 html로 제작 🖱|, 
|[정인](https://github.com/jojeongin313)|웹사이트 html로 제작 🖱|,
|[민서](https://github.com/alstj003)|자료조사,깃허브 정리 📷|, 
|[순규](https://github.com/soon15)|자료조사 📷|,
|[수민](https://github.com/jinsumin81)|깃허브 관리 및 정리 ⚙|,

---

## 👀소프트웨어 아키텍처

### 1. 사용자 흐름
- **로그인** → **이상형 월드컵 만들기 클릭** → **사진 업로드** → **이름 입력 후 저장** → **대회 타이틀 입력 후 저장** → **대회 선택 및 라운드 수 선택** → **경기 진행** → **최종 우승자 결정**
- **마이페이지에서 제작한 월드컵 확인 및 실행가능** → **월드컵을 삭제하거나 제목 수정 가능**
  
### 2. 주요 구성 요소
- **사용자 인터페이스(UI)**
  - 로그인 페이지
  - 이상형 월드컵 제작 페이지
  - 사진 업로드 및 이름 입력 페이지
  - 대회 타이틀 입력 페이지
  - 대회 목록 화면
  - 라운드 진행 화면

### 3. 프로세스 흐름
1. 사용자가 **로그인** 후 **이상형 월드컵 만들기**를 선택합니다.
2. 사용자가 후보 사진을 업로드하고, 각 사진에 이름을 입력한 후 **저장**합니다.
3. 대회 타이틀을 입력한 후 저장되며, 목록에서 해당 대회를 선택합니다.
4. 사용자가 라운드 수를 선택하고 **대회를 시작**합니다.
5. 각 라운드에서 사용자는 두 사진 중 선택을 진행하고, 선택된 사진은 다음 라운드로 진출합니다.
6. 마지막 라운드에서 우승자가 결정됩니다.

### ※ DB를 사용하지 않고 가상의 사용자를 사용
- 홈페이지 로그인시 아래 두 ID중 하나를 선택하여 사용
|번호|아이디|비밀번호|
|--|--|--|
|1|rhffkwh|1234|
|2|dhthth|5678|

### 🧭 자세한 실행 방법
- 해당 저장소 우측상단의 녹색 [<>code] 버튼을 눌러 팝업의 'Download ZIP'선택
- 원하는 위치에 압축을 풀고 '이상형 월드컵 페이지'폴더 내의 '홈 화면.html'을 더블클릭하여 실행
- '이상형 월드컵 사진'내 사진 및 소장중인 사진을 이용하여 자유롭게 이상형 월드컵을 제작
  
---

## 🏛️ 프로젝트 소개

### 제작배경
최근 이상형 월드컵의 인기가 증가함에 따라 사용자 수가 증가하는 중입니다.
제작자의 입장으로 직접 제작하는것을 메인으로 다뤄, 더욱 다양한 주제를 통해 사용자의 니즈를 충족해, 수요에 맞게 공급하는 목적을 지니고있습니다. <br><br>
이상형 월드컵을 직접 생성함으로써 자신이 알고 싶은 분야에 대한 사람들의 수요를 알 수 있습니다.<br><br>
이상형 월드컵은 사용자에게 재미있고 가벼운 선택 게임을 통해 자신이 선호하는 것을 발견하고 공유할 수 있는 경험을 제공하는 것입니다. 사용자는 주어진 주제(예: 음식, 연예인, 취미 등)에 따라 둘 중 하나를 선택하는 과정을 반복하면서 자신의 취향을 직관적으로 탐색할 수 있습니다. 이 과정에서 사용자들은 자신이 좋아하는 것에 대해 더 깊이 생각하거나, 의외의 선택을 통해 새로운 발견을 하기도 합니다. 또한, 최종 결과를 다른 사람들과 공유하며 공감대를 형성하거나 취향의 다양성을 즐길 수 있습니다.

### 목표
1. **참여도 증가**: 사용자들이 흥미를 느끼고 쉽게 참여할 수 있도록 직관적이고 재미있는 인터페이스를 제공합니다.
2. **소셜 상호작용 증진**: 사용자들이 직접 만든 이상형 월드컵을 스스로 참여할 수 있는 기능을 제공합니다.
3. **사용자 맞춤화**: 사용자가 원하는 다양한 후보 사진을 사용하여 사용자들이 맞춤형 콘텐츠를 제작하고 관리할 수 있도록 합니다.
4. **데이터 관리 및 분석**: 사용자가 만든 이상형 월드컵의 참여 데이터와 결과를 체계적으로 관리할 수 있도록 합니다.

### 과제
**1. 요구사항 분석 및 기획**
- 사용자 경험(UX)과 사용자 인터페이스(UI)를 고려하여 기능과 요구사항을 분석합니다.
- 주요 기능: 로그인, 사진 업로드, 후보 이름 입력, 대회 생성 및 타이틀 설정, 라운드 선택, 결과 선택 및 우승자 결정.

**2. 프로토타입 디자인**
- 초기 디자인 스케치를 통해 사용자 흐름을 시각화하고 UI/UX 요소를 기획합니다.
- 각 페이지의 레이아웃과 기능을 구체화하여 프로토타입을 제작합니다.

**3. 개발 환경 설정**
- 백엔드(서버 사이드)와 프론트엔드(클라이언트 사이드) 개발을 위한 환경을 설정합니다.
- 데이터베이스 모델링을 포함한 백엔드 로직 설계 및 구현을 시작합니다.

**4. 기능 구현 및 통합**
- 사용자 로그인 및 인증 기능 구현.
- 사진 업로드 및 관리 기능 개발.
- 대회 생성, 후보 입력 및 라운드 진행 로직 구현.
- 최종 우승자를 선택하는 코드 작성 및 테스트.

**5. 테스트 및 디버깅**
- 각 기능을 단위 테스트 및 통합 테스트를 통해 오류를 발견하고 수정합니다.
- 사용자 인터페이스(UI)와 사용성 테스트를 통해 직관성과 편리함을 검증합니다.

**6. 지속적인 개선**
- 사용자 데이터를 분석하고 새로운 기능을 도입하여 프로젝트를 지속적으로 업데이트합니다.
- 사용자 경험을 향상시키기 위해 디자인과 기능을 개선합니다.

---

## 📆 프로젝트 기간
**2024-11-11 ~ 2024-12-06**

---

## 🛠️ 프로젝트 관리 및 협업 도구
1. **GitHub Wiki**: 프로젝트 개요, 추진 일정, 협업 규칙 문서화
2. **GitHub Projects**: 칸반 보드를 통한 작업 관리 및 상태 추적
3. **GitHub Milestones**: 주요 목표와 일정 관리
4. **GitHub Issues**: 버그, 기능 요청 등을 체계적으로 관리
5. **GitHub Actions**: 자동 라벨링 및 작업 관리


