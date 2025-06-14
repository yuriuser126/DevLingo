# DevLingo 🧠💬

> 개발자 밈, 속어, 용어를 모아 정리한 인터랙티브 웹사전
---

## 🌐 데모
[https://devlingo.vercel.app](https://devlingo.vercel.app)

---

## 📘 프로젝트 개요

| 항목       | 내용                                                                                 |
|------------|--------------------------------------------------------------------------------------|
| **소개**   | 개발자들 사이에서 자주 쓰이는 밈, 속어, 전문 용어들을 재미있게 정리하고 공유하는 웹 기반 커뮤니티 사전입니다. |
| **목적**   | 개발자 커뮤니티 공감대 형성 및 정보 공유, 풀스택 개발 능력 및 AI 협업 활용 역량 어필 |
| **배포처** | [https://devlingo.vercel.app](https://devlingo.vercel.app)                           |

---

## 🛠️ 주요 기술 스택

| 구분       | 기술 및 도구                                      |
|------------|--------------------------------------------------|
| Frontend   | Next.js, Tailwind CSS, Framer Motion             |
| Backend/API| Supabase (DB & Auth), REST API                    |
| 인증       | GitHub OAuth (NextAuth.js)                        |
| 배포       | Vercel, GitHub Actions (CI/CD)                    |
| 기타 도구  | ChatGPT (기획·아이디어), Figma, Swagger          |

---

## ✨ 주요 기능

| 기능                    | 설명                                                       |
|-------------------------|------------------------------------------------------------|
| 개발자 용어/밈 카드 뷰 | 다양한 개발자 밈과 용어를 카드 형태로 보여줍니다.           |
| 검색 및 필터            | 슬랭, 기술용어, 밈 등 카테고리별로 쉽게 검색하고 필터링 가능 |
| 사용자 제안             | GitHub 로그인 후 용어 및 밈 추가 제안 가능                   |
| 랜덤 보기               | 무작위 용어/밈 카드로 새로운 재미 제공                      |
| REST API 제공           | `/api/terms`, `/api/memes`로 데이터 제공                     |
| 밈 생성기               | 사용자가 직접 밈을 생성할 수 있는 기능 (준비 중)              |
| 인기 콘텐츠 탭         | 조회수 기반 인기 밈 및 용어 확인 가능                         |

---

## 📂 프로젝트 구조

```
DevLingo/
├── components/       # 재사용 가능한 UI 컴포넌트
│   ├── Card.tsx
│   ├── Header.tsx
│   └── ...
├── lib/              # API 호출, 유틸 함수 등 라이브러리성 코드
│   ├── api.ts
│   └── helpers.ts
├── pages/            # Next.js 페이지 라우팅
│   ├── api/          # 서버리스 API 엔드포인트
│   │   ├── terms.ts
│   │   └── memes.ts
│   ├── index.tsx     # 메인 페이지
│   ├── terms.tsx     # 용어 목록 페이지
│   └── memes.tsx     # 밈 목록 페이지
├── public/           # 정적 파일 (이미지, 폰트 등)
│   └── memes/
├── styles/           # 글로벌 및 모듈별 스타일
│   ├── globals.css
│   └── tailwind.css
├── .gitignore
├── next.config.js    # Next.js 설정 파일
├── package.json
└── README.md
```



---

## 🤖 AI 협업 기록

| 구분       | 활용 내용                                    |
|------------|---------------------------------------------|
| 기획 단계  | 기능 아이디어, UX 흐름 설계 협업             |
| 데이터 준비| 용어 예시 자동 생성 및 정리 도움              |
| 문서화     | README 구조 설계 및 API 문서 작성 도움       |

---

## 🚀 향후 개발 계획

- 밈 생성기 기능 완성  
- 모바일 최적화 강화  
- 관리자 기능 (용어 승인 시스템)  
- 커뮤니티 기능 (댓글, 투표 등)  

---

## 📜 라이선스

MIT License

---

## 🧑‍💻 개발자 정보

| 이름         | 역할                              |
|--------------|-----------------------------------|
| [YuriSung] | 기획, 프론트엔드, 백엔드, 배포, 문서화 |

---

## 💬 기여 안내

> 본 프로젝트는 재미와 정보 제공을 위한 오픈 소스입니다.  
> 누구나 밈 및 용어를 제안할 수 있으며, PR 환영! 😄






