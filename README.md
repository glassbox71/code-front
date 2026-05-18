# Code Front - AWS 실습 플랫폼
#aww 연동예정임
AWS 클라우드 서비스를 체계적으로 학습하고 실습할 수 있는 프론트엔드 플랫폼입니다.

## 🎯 프로젝트 개요

**Code Front**는 AWS 관련 개념을 이해하고 실제 프로젝트에 적용해보는 것을 돕는 인터랙티브 러닝 플랫폼입니다.

### 주요 기능

- 📚 **AWS 서비스 튜토리얼** - EC2, S3, Lambda, RDS 등 핵심 서비스 학습
- 🔬 **핸즈온 실습** - 실제 환경에서 AWS 리소스 생성 및 관리
- 💡 **실시간 코드 에디터** - 브라우저 내에서 코드 작성 및 테스트
- 📊 **진행도 추적** - 학습 현황 및 완료한 실습 기록
- 🏆 **과제 및 평가** - 개인 역량 검증

## 🚀 시작하기

### 필수 요구사항

- Node.js 16+ 
- npm 또는 yarn
- AWS 계정
- 최신 버전의 웹 브라우저 (Chrome, Firefox, Safari)

### 설치

```bash
# 저장소 클론
git clone https://github.com/glassbox71/code-front.git

# 디렉토리 이동
cd code-front

# 의존성 설치
npm install

# 개발 서버 시작
npm run dev
```

브라우저에서 `http://localhost:3000` 접속

## 📖 주요 섹션

### 1. **AWS 기초**
- AWS 개요 및 글로벌 인프라
- 리전(Region)과 가용성 영역(AZ) 이해
- 신원 및 액세스 관리(IAM)

### 2. **컴퓨팅 서비스**
- EC2 인스턴스 생성 및 관리
- Auto Scaling 설정
- Lambda 함수 개발

### 3. **스토리지 서비스**
- S3 버킷 생성 및 객체 관리
- CloudFront 배포 설정
- EBS 볼륨 관리

### 4. **데이터베이스**
- RDS 인스턴스 프로비저닝
- DynamoDB 테이블 작성
- 백업 및 재해 복구

### 5. **네트워킹**
- VPC 구성 및 서브넷 설정
- 보안 그룹 및 네트워크 ACL
- Route 53 DNS 관리

## 📁 프로젝트 구조

```
code-front/
├── public/              # 정적 자산
├── src/
│   ├── components/      # React 컴포넌트
│   ├── pages/          # 페이지 컴포넌트
│   ├── services/       # AWS API 호출
│   ├── utils/          # 유틸리티 함수
│   ├── styles/         # CSS 스타일
│   └── App.jsx         # 메인 앱 컴포넌트
├── .env.example        # 환경 변수 템플릿
├── package.json        # 프로젝트 의존성
└── README.md          # 이 파일
```

## ⚙️ 환경 설정

`.env` 파일을 생성하고 다음 변수들을 설정하세요:

```env
VITE_AWS_REGION=ap-northeast-2
VITE_AWS_ACCESS_KEY_ID=your_access_key
VITE_AWS_SECRET_ACCESS_KEY=your_secret_key
VITE_API_ENDPOINT=https://api.example.com
```

> ⚠️ **보안 주의**: 민감한 정보는 절대 버전 관리에 커밋하지 마세요. `.env` 파일을 `.gitignore`에 추가하세요.

## 📚 사용 기술

- **프론트엔드**: React, Vite, Tailwind CSS
- **상태 관리**: Redux / Zustand
- **HTTP 클라이언트**: Axios
- **AWS SDK**: AWS SDK for JavaScript
- **테스트**: Vitest, React Testing Library

## 🔧 개발 명령어

```bash
# 개발 서버 실행
npm run dev

# 프로덕션 빌드
npm run build

# 프로덕션 미리보기
npm run preview

# 린트 검사
npm run lint

# 테스트 실행
npm run test

# 테스트 커버리지
npm run test:coverage
```

## 🤝 기여하기

커뮤니티의 피드백과 기여를 환영합니다!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📋 로드맵

- [ ] 고급 AWS 서비스 (SQS, SNS, Step Functions)
- [ ] 실시간 협업 기능
- [ ] 커뮤니티 포럼
- [ ] 인증서 발급 시스템
- [ ] 모바일 앱 출시
- [ ] 다국어 지원

## 🐛 버그 리포트

문제를 발견했나요? [Issues](https://github.com/glassbox71/code-front/issues)에서 버그를 보고해주세요.

## 📞 지원 및 문의

- 📧 Email: support@code-front.io
- 💬 Discord: [커뮤니티 서버](https://discord.gg/example)
- 🌐 웹사이트: https://code-front.io

## 📄 라이센스

이 프로젝트는 MIT 라이센스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 👨‍💻 개발팀

- **유지보수**: glassbox71

---

**마지막 업데이트**: 2026-05-18

기여에 감사합니다! 🙏
