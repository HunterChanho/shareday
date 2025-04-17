## 🛠️ Tech Stack

### Frontend
- **React** (with Vite) – 빠른 빌드와 개발 환경
- **TypeScript** – 정적 타입 지원으로 안정성 향상 (선택 시)
- **Tailwind CSS** – 간결하고 유연한 스타일링 (선택 시)
- **Axios / Fetch API** – 백엔드와의 데이터 통신

### Backend
- **Kotlin** – 간결하고 안정적인 JVM 언어
- **Spring Boot** – RESTful API 제공 및 서버 구조
- **Spring Data MongoDB** – MongoDB와의 간단한 연결

### Database
- **MongoDB Atlas** – 클라우드 기반 NoSQL 데이터베이스
  - 일정 데이터 및 유저 정보 저장
  - 자유로운 구조와 확장성

### Deployment & DevOps
- **Render** – 백엔드 배포 및 CI/CD 지원
- **Vercel / Netlify** – 프론트엔드 정적 파일 배포
- **GitHub** – 버전 관리 및 자동 배포 트리거

---

이 스택은 간단한 2인용 일정 공유 앱을 MVP 형태로 빠르게 개발하고  
필요 시 확장 가능한 구조로 설계되어 있습니다.


## 📲 PWA Support

ShareDay는 PWA(Progressive Web App)를 지원하도록 설계되었습니다.  
브라우저에서도 앱처럼 설치하고 사용할 수 있어, 앱스토어 없이도 편리하게 접속 가능합니다.

### PWA 특징
- 홈 화면에 설치 가능 (모바일/PC 모두)
- 전체화면 모드로 앱처럼 작동
- 인터넷 연결 없이도 작동 가능 (옵션)
- 앱스토어 등록 없이 개인 간 공유 용이

### 개발 예정 스택
- [`vite-plugin-pwa`](https://github.com/vite-pwa/vite-plugin-pwa)
- Custom Manifest (`manifest.json`) 설정
- Service Worker 자동 생성 및 캐싱 지원

> 설치 아이콘은 `public/pwa-icon-192.png`, `public/pwa-icon-512.png` 에 위치  
> Vercel 또는 Netlify로 배포 시 자동으로 설치 가능 상태 감지

🚧 현재는 기본 설정만 작성되어 있으며, 향후 구현 예정입니다.
