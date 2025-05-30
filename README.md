# 🎮 2025 대선 시뮬레이터

미연시(비주얼 노벨) 스타일로 2025년 대선 후보들을 만나보는 웹 게임입니다.

## 🎯 게임 소개

꿈속 세계에서 천사 고양이와 함께 각 후보의 방을 둘러보며 정책을 알아가는 인터랙티브 게임입니다.

2025년 대선, 게임으로 재미있게 알아보세요!

## 💡 왜 만들었나요?

- **정치에 대한 관심 증대**: 게임을 통해 재미있게 정치 정보를 접할 수 있도록
- **젊은 세대 참여**: 미연시 스타일로 젊은 층의 선거 참여 독려
- **정보 접근성**: 복잡한 정책을 쉽고 재미있게 전달
- **중립적 정보 제공**: 각 후보의 정책을 균등하게 소개

## 🛠️ 기술 스택 & 구현 기능

### Frontend Framework
- **Flutter Web**: 크로스 플랫폼 웹 개발 프레임워크
- **Dart**: 타입 안전성과 성능을 제공하는 프로그래밍 언어

### 게임 시스템
- **StatefulWidget**: 게임 상태 관리 (대화 진행, 방문 기록 등)
- **Navigator**: 5개 씬 간 부드러운 화면 전환
- **PageRouteBuilder**: 페이드 인/아웃 애니메이션 효과
- **GestureDetector**: 터치/클릭 인터랙션 처리

### 사운드 시스템
- **HTML5 Audio API**: 웹 브라우저 네이티브 오디오 재생
- **Stream 기반 상태 관리**: 모든 화면에서 BGM 상태 실시간 동기화
- **자동 루프 재생**: 끊김 없는 배경음악 제공

### 데이터 관리
- **로컬 상태**: Set<String>으로 방문한 후보 추적
- **정적 데이터**: 후보 정보와 정책을 코드 내 구조화
- **이미지 에셋**: 배경, 아바타, 오브젝트 이미지 최적화 관리

---

**문의사항이 있다면 이쪽으로 연락주세요! jangjia01234@gmail.com**
