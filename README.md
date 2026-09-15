# 2027 경기도 진로전담교사 모의면접 v5 — 완전무료 공개판

- OpenAI API 키/크레딧 불필요
- Netlify Functions 불필요
- Chrome 브라우저 음성인식(Web Speech API) + 녹음 재생
- 90문항 통합 문제은행 및 자료 기반 루브릭 내장
- 핵심요소, 구조, 구체성, 답변시간 자동점검
- 음성인식 실패 시 직접 전사문 입력 가능

## 배포
GitHub 저장소에서 기존 `public/index.html`과 `netlify.toml`을 이 버전 파일로 교체하면 됩니다. 기존 `netlify/functions` 폴더는 삭제해도 됩니다. OpenAI 환경변수도 필요하지 않습니다.

## 주의
무료판 점수는 생성형 AI의 의미 이해 평가가 아니라 내장된 자료 기반 루브릭과 표현 일치, 답변 구조, 시간에 따른 연습용 자동점검입니다. Chrome의 SpeechRecognition은 브라우저/환경에 따라 동작 차이가 있을 수 있습니다.
