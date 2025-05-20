# Convi Frontend

Convi Frontend는 Git 커밋 컨벤션 자동화 도구인 Convi의 프론트엔드 애플리케이션입니다.  
커밋 메시지 컨벤션 생성기(Lint Buddy), AI 기반 커밋 메시지 추천 도구(Commit Buddy), 자동 코드 리뷰 기능(Review Buddy)에 대한 소개와 설명법을 담고 있으며, 커밋 메시지 컨벤션 생성기(Lint Buddy) 기능을 제공합니다.

## ⚙️ 기술 스택

- **프레임워크**: Next.js
- **CSS 프레임워크**: Shadcn
- **언어**: TypeScript
- **스타일링**: Tailwind CSS
- **상태관리**: Zustand

## 📦 설치 및 실행
```shell
# 의존성 설치
npm install

# 개발 서버 실행
npm run dev

# 프로덕션 빌드
npm run build
npm run start
```

## 📁 디렉토리 구조 (요약)
```shell
├── app/             # Next.js App Router 구성
├── components/      # UI 컴포넌트 모음
├── features/        # 기능 단위 폴더
├── store/           # Zustand 기반 전역 상태 관리
├── public/          # 정적 자산
├── @types/          # 타입 정의
```
