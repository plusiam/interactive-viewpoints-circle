# 🎯 인터랙티브 관점의 원 (Interactive Circle of Viewpoints)

하버드대학교 프로젝트 제로(Project Zero)의 보이는 사고(Visible Thinking) 루틴을 기반으로 한 교육용 웹 애플리케이션

[🌐 Live Demo](https://plusiam.github.io/interactive-viewpoints-circle/)

> 🧠 이 도구는 **[생각이 보이는 교실 - 사고가시화 전략 허브](https://plusiam.github.io/edu-thinking-toolkit/)** 프로젝트의 일부입니다. 더 많은 사고가시화 도구를 만나보세요!

## 📖 소개

관점의 원(Circle of Viewpoints)은 학생들이 하나의 주제에 대해 다양한 관점에서 생각해보고 탐구할 수 있도록 돕는 교육 도구입니다. 이 프로젝트는 하버드대학교 프로젝트 제로의 사고 루틴을 인터랙티브한 웹 애플리케이션으로 구현했습니다.

### 주요 특징
- 🎡 **인터랙티브 룰렛**: 관점을 시각적으로 표현하고 무작위 선택 가능
- 📝 **구조화된 탐구**: 각 관점에서 생각, 이유, 궁금한 점을 체계적으로 기록
- 💾 **자동 저장**: 브라우저에 작업 내용 자동 저장
- 📊 **진행률 추적**: 실시간 진행 상황 표시
- 🖼️ **결과 저장**: 탐구 결과를 이미지로 다운로드
- 📱 **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기 지원

## 🚀 사용 방법

### 1. 학습 정보 입력
- 학반, 이름, 탐구할 중심 주제를 입력합니다
- 예: "6학년 1반", "홍길동", "지구 온난화"

### 2. 관점 추가
- 주제와 관련된 다양한 관점을 추가합니다 (최대 12개)
- 예: 과학자, 정치인, 기업가, 학생, 미래세대, 지구 등
- 주제 입력 시 추천 관점이 자동으로 제시됩니다

### 3. 관점 선택
- SPIN 버튼을 눌러 무작위로 선택하거나
- 원하는 관점을 직접 클릭하거나
- "탐구 시작하기" 버튼으로 목록에서 선택

### 4. 탐구하기
각 관점에서 다음 세 가지를 작성합니다:
- **나는 ~라고 생각한다** (관점의 입장)
- **왜냐하면 ~이기 때문이다** (근거나 이유)
- **나는 ~이 궁금하다** (질문이나 궁금증)

### 5. 결과 저장
- "탐구결과 저장" 버튼을 클릭하여 결과를 이미지로 다운로드
- 학생 정보와 모든 탐구 내용이 포함된 정리된 문서 형태로 저장됩니다

## 🛠️ 기술 스택

- **HTML5** - 시맨틱 마크업
- **CSS3** - 커스텀 스타일링 및 애니메이션
- **JavaScript (Vanilla)** - 인터랙티브 기능 구현
- **Tailwind CSS** - 유틸리티 기반 스타일링
- **Pretendard Font** - 한글 웹폰트
- **html2canvas** - 이미지 다운로드 기능

## 📋 주요 기능

### 자동 저장
- 모든 입력 내용은 브라우저의 localStorage에 자동 저장됩니다
- 페이지를 새로고침해도 작업 내용이 유지됩니다

### 진행률 표시
- 학습 정보 입력과 관점별 탐구 진행 상황을 실시간으로 표시
- 시각적 진행률 바로 한눈에 확인 가능

### 관점 추천
- 입력한 주제에 따라 적합한 관점을 자동으로 추천
- 환경, 역사, 과학, 사회, 예술, 기술 등 다양한 분야별 추천 제공

### 반응형 디자인
- 모바일, 태블릿, 데스크톱 모든 화면 크기에 최적화
- 터치 인터페이스 완벽 지원

## 🎓 교육적 활용

이 도구는 다음과 같은 교육 상황에서 활용할 수 있습니다:

- **비판적 사고 훈련**: 하나의 주제를 다각도로 바라보는 연습
- **공감 능력 개발**: 다른 입장에서 생각해보는 경험
- **토론 준비**: 다양한 관점을 미리 탐구하여 풍부한 토론 준비
- **창의적 글쓰기**: 다양한 시각에서 이야기 구성
- **프로젝트 학습**: 주제 탐구의 시작점으로 활용

## 🧠 관련 프로젝트

이 도구는 **[생각이 보이는 교실](https://plusiam.github.io/edu-thinking-toolkit/)** 프로젝트의 일부입니다.

### 함께 사용하면 좋은 도구들:
- 📊 [프레이어 모델](https://plusiam.github.io/frayer-model-worksheet/) - 개념의 깊이 있는 이해
- 🌉 [3-2-1 브릿지](https://plusiam.github.io/321-bridge-worksheet/) - 학습 전후 사고 변화 추적
- 🔍 [See-Think-Wonder](https://plusiam.github.io/see-think-wonder-worksheet/) - 관찰과 탐구력 향상
- 🎭 [Step-Inside](https://plusiam.github.io/step-inside-worksheet/) - 공감 능력 개발
- 🎯 [ORID 성찰 도구](https://plusiam.github.io/orid-reflection-tool/) - 체계적인 성찰

## 📱 브라우저 지원

- Chrome (권장)
- Firefox
- Safari
- Edge
- 모바일 브라우저

## 🤝 기여하기

이 프로젝트는 오픈소스입니다. 개선 사항이나 버그를 발견하시면 이슈를 등록하거나 풀 리퀘스트를 보내주세요.

### 개발 환경 설정
```bash
# 저장소 클론
git clone https://github.com/plusiam/interactive-viewpoints-circle.git

# 디렉토리 이동
cd interactive-viewpoints-circle

# 로컬 서버 실행 (Python 3)
python -m http.server 8000

# 브라우저에서 접속
# http://localhost:8000
```

## 📄 라이선스

MIT License

## 🙏 감사의 말

- 하버드대학교 프로젝트 제로(Project Zero) - 보이는 사고(Visible Thinking) 루틴 제공
- 교육 현장에서 이 도구를 활용해주시는 모든 선생님들께 감사드립니다

## 📞 문의 및 제안

- **개발자**: 룰루랄라 한기쌤
- **Facebook**: [@playrurulala](https://www.facebook.com/playrurulala)
- **GitHub**: [@plusiam](https://github.com/plusiam)
- **프로젝트 홈**: [생각이 보이는 교실](https://plusiam.github.io/edu-thinking-toolkit/)

새로운 기능이나 개선 사항에 대한 제안을 언제든 환영합니다!

---

Made with ❤️ for educators and students