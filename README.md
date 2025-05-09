# 🎧 Moodlog - 감정 기반 노래 추천 블로그

> 사용자의 감정을 분석하여 맞춤형 노래를 추천하고, 다른 사람들과 소통할 수 있는 감성 블로그 플랫폼입니다.

---

## 🛠️ 기술 스택

### 📌 Backend
- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- OAuth2 (카카오 로그인)
- H2 Database (개발용)

### 🎨 Frontend
- React.js (팀원 작업 예정)

---

## 🧩 주요 기능

| 기능 | 설명 |
|------|------|
| ✅ 회원가입 / 로그인 / 로그아웃 | 일반 로그인 + 카카오 소셜 로그인 지원 |
| ✅ 게시글 작성 | 감정 기반 글 작성, 자동 저장 기능 |
| ✅ 텍스트 분석 | 감정 분석 후 노래 추천 (AI 연동 예정) |
| ✅ 댓글 / 공감 | 타인 글에 댓글, 좋아요 |
| ✅ 팔로우 | 관심 사용자 이웃 추가 |
| ✅ 검색 기능 | 사용자, 게시글 등 검색 |
| ✅ 마이페이지 | 프로필, 환경설정, 테마 변경 가능 |
| ✅ 플레이리스트 공유 | 추천 노래 모아 공유하기 |

---

## 🚀 프로젝트 구조
📁 Devstream/
├── moodlog/         # 백엔드 (Spring Boot)
│   ├── src/
│   ├── build.gradle
│   └── ...          # 백엔드 관련 파일들
├── frontend/        # 프론트엔드 (React, 팀원 작업 예정)
│   ├── src/
│   ├── public/
│   └── package.json
├── assets/          # 이미지, 와이어프레임, 리드미용 자료
│   └── kakao-login.png
├── .gitignore       # 공통 Git 설정
└── README.md        # 팀 프로젝트 전체 설명 문서

