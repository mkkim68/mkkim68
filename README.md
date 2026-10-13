<img width="288" height="289" alt="철컥 복사본" src="https://github.com/user-attachments/assets/81c91b2f-52e7-4751-bcf8-de1e5e514c0c" />


# Welcome to 김민경's Github

### 모델 평가부터 에이전트 설계·개발·운영까지<br>AI의 결과를 믿을 수 있게 만드는 AI Engineer 김민경입니다.

### 👩‍💻 How I Work

- 📏 **측정으로 문제를 정의합니다.** 감으로 고치지 않고 기준선부터 세웁니다. STT 평가 하네스를 먼저 만들어 도메인 용어 인식률을 **32% → 86%** 로 올렸습니다.
- 🔍 **원인을 끝까지 추적합니다.** 변수를 하나씩 바꿔 실측해 화자분리 모델이 CPU에 머물던 원인을 찾고, 처리시간을 **163.4s → 11.5s** 로 줄였습니다.
- 🛡️ **AI가 만든 결과도 같은 기준을 통과하게 합니다.** 요약의 고유명사를 원문과 기계적으로 대조하고, 에이전트의 쓰기 동작은 위험도별로 등급을 나눠 **고위험 동작은 사람 승인 후 실행**되게 설계합니다.
- 📝 **판단의 근거를 남깁니다.** 선택한 방법과 기각한 대안을 ADR로 기록해, AI 코딩 에이전트와 협업하면서도 왜 그렇게 만들었는지 설명할 수 있게 합니다.

### 🚀 Projects

| 프로젝트 | 한 줄 소개 | 내가 한 일 |
| --- | --- | --- |
| [**AUTUNE**](https://github.com/AI-X-16-1/AUTUNE) | 회의 녹음 하나로 전사·마스킹·액션아이템·맥락 연결까지 해주는 회의 인텔리전스 플랫폼 (5인 팀) | LangGraph 에이전트 레이어의 메인 에이전트·Research 서브에이전트, 음성 파이프라인(STT·화자분리·PII 마스킹) 모듈 오너 |
| [**조간 논문**](https://github.com/mkkim68/jogan) | 다단계 신뢰도 필터와 원문 대조 요약으로 믿고 읽을 논문을 골라주는 연구 비서 (1인) | 임베딩 검색 + LLM 관련성 판정, 요약 환각을 걸러내는 기계적 원문 대조 검증 |
| [**BOOKIT**](https://github.com/AI-X-16-1/BOOKIT) | AI 꼬리질문으로 아이가 책을 정말 읽었는지 검증하는 독서 서비스 (5인 팀, 원티드 AI Championship 2026 출품) | Supabase DB·RLS 권한 설계, RLS 회귀 테스트 93건 CI 편입, 통합·배포 |

<details>
<summary>이전 프로젝트 (프론트엔드)</summary>

- [**FlowDeck**](https://github.com/mkkim68/Flowdeck-FE) · 실시간 협업 Web IDE. REST와 WebSocket 데이터를 React Query 캐시 하나로 통합 (구름 우수 프로젝트)
- [**Interactive Portfolio**](https://github.com/mkkim68/portfolio) · 실기기 프로파일링으로 메인 스레드 점유 2430ms → 42ms
- [**JamJam**](https://github.com/mkkim68/jamjam) · WebSocket 중복 연결 원인을 찾아 단일 인스턴스로 재설계 (SSAFY 공통 우수상)

</details>

### ✍️ Writing

- [Dream-RSI 논문 리뷰](https://velog.io/@mkkim7375/Dream-RSI-%EB%A6%AC%EB%B7%B0): 화제가 된 "에이전트 호출 162배 절감"이 서로 다른 모델 간 비교임을 짚고, 같은 조건 비교(약 1.7배)로 방법론의 효과를 다시 정리
- [AI가 구성한 Alembic 설정에서 발생한 이슈 두 가지를 재현해봤다](https://velog.io/@mkkim7375/AI%EA%B0%80-%EA%B5%AC%EC%84%B1%ED%95%9C-Alembic-%EC%84%A4%EC%A0%95%EC%97%90%EC%84%9C-%EB%B0%9C%EC%83%9D%ED%95%9C-%EC%9D%B4%EC%8A%88-%EB%91%90-%EA%B0%80%EC%A7%80%EB%A5%BC-%EC%9E%AC%ED%98%84%ED%95%B4%EB%B4%A4%EB%8B%A4)
- [Web IDE 프로젝트에서 React Query와 WebSocket(STOMP) 통합하기](https://velog.io/@mkkim7375/React-Query-%EC%86%8C%EC%BC%93)

<div align="">
<h3>✉ Contact</h3>
<!-- <a href="https://www.instagram.com/hamdragon_mk?igsh=YXB1OTYxcDhxdmR0&utm_source=qr" target="_blank"><img src="https://img.shields.io/badge/hamdragon_mk-E4405F?style=flat-square&logo=instagram&logoColor=FFFFFF"/></a> -->
<a href="https://www.google.com/gmail/about/" target="_blank"><img src="https://img.shields.io/badge/kimminkyoung0608@gmail.com-EAEAEA?style=flat-square&logo=gmail&logoColor=EA4335"/></a>
<a href="https://velog.io/@mkkim7375/posts" target="_blank"><img src="https://img.shields.io/badge/Velog@mkkim7375-ffffff?style=flat-square&logo=velog&logoColor=20C997"/></a>
</div>


<div align="">
  <h3>💻 Tech Stacks</h3>
  <h4>AI · Agent</h4>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-white?style=for-the-badge&logo=pytorch&logoColor=EE4C2C" />
</br>
  <img src="https://img.shields.io/badge/faster--whisper-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/pyannote-white?style=for-the-badge" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<h4>Backend · Data</h4>
  <img src="https://img.shields.io/badge/Python-white?style=for-the-badge&logo=python&logoColor=3776AB" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-white?style=for-the-badge&logo=redis&logoColor=FF4438" />
</br>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-white?style=for-the-badge&logo=supabase&logoColor=3FCF8E" />
  <img src="https://img.shields.io/badge/node.js-white?style=for-the-badge&logo=node.js&logoColor=5FA04E" />
<h4>Frontend</h4>
  <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React Query-092739?style=for-the-badge&logo=reactquery&logoColor=FF4154">
  <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
<h4>DevOps & Tools</h4>
  <img src="https://img.shields.io/badge/Docker-white?style=for-the-badge&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-black?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=black" />
</br>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" />
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
  <img src="https://img.shields.io/badge/notion-white?style=for-the-badge&logo=notion&logoColor=black">
</br>
</div>
<hr />
<div align="" display="flex">
  
  <!-- ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mkkim68&theme=holi) -->
  <!-- ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=mkkim68&show_icons=true&theme=holi) -->
  [![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=kimmk7375)](https://solved.ac/kimmk7375/)
  </div>
