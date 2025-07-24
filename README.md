### **1. 기술 스택 섹션 추가**
markdown
## 🛠️ 기술 스택

### Frontend
- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Data Fetching**: React Query (@tanstack/react-query)
- **UI Animation**: Framer Motion, GSAP
- **Audio Processing**: Pitchfinder, audiobuffer-to-wav
- **Charts**: ApexCharts, Chart.js

### Backend Integration
- **Real-time Communication**: Server-Sent Events (SSE)
- **HTTP Client**: Axios
- **Authentication**: Google OAuth, Firebase
- **File Upload**: FormData with audio processing


### **2. 프로젝트 구조 섹션**
markdown
## �� 프로젝트 구조

src/
├── app/                    # Next.js App Router
│   ├── api/               # API 라우트 (YouTube 프록시, 오디오 프록시)
│   ├── dubbing/           # 더빙 페이지
│   ├── duetdubbing/       # 듀엣 더빙 페이지
│   └── ...
├── components/            # UI 컴포넌트
│   ├── dubbing/          # 더빙 관련 컴포넌트
│   ├── result/           # 결과 표시 컴포넌트
│   ├── graph/            # 피치 그래프 컴포넌트
│   └── ...
├── hooks/                # 커스텀 훅
├── services/             # API 서비스
├── store/                # Zustand 상태 관리
└── utils/                # 유틸리티 함수


### **4. 설치 및 실행 가이드**
markdown
## �� 설치 및 실행

### 필수 요구사항
- Node.js 18+ 
- npm 또는 yarn

### 설치
bash
npm install
### 개발 서버 실행
bash
npm run dev
### 빌드
bash
npm run build
npm start



### 오디오 녹음 문제
마이크 권한이 거부된 경우 브라우저 설정에서 권한을 허용해주세요.

### 성능 개선

