# **GrammarAI Tutor (AI 영어 문법 & 표현 교정 튜터)**

> 

> 사용자가 입력한 영어 문장을 다각도로 분석하여 문법 오류 교정, 상황별 원어민 추천 표현, 핵심 문법 설명, 음성 지원(STT/TTS), 그리고 응용 복습 퀴즈까지 제공합니다.

## **✨ 주요 기능 (Key Features)**

* **🔍 실시간 문법 분석 & 교정**:  
  * 문법 교정 문장 (Grammar Correction) 및 원어민 스타일 표현 (Native Standard) 동시 제공  
  * 교정 사유와 오류 유형(전치사, 시제, 수일치 등) 세부 설명 제공  
* **🎯 상황별(Context) 교정 톤 선택**:  
  * **일상 회화 (Casual)**: 캐주얼하고 친근한 어조  
  * **비즈니스 (Business)**: 정중하고 격식 있는 이메일/업무용 어조  
  * **학술/정식 (Academic)**: 논문 및 에세이용 학술 어조  
* **🎙️ 음성 입력 & 발음 듣기 (STT & TTS)**:  
  * **STT (Speech-to-Text)**: 마이크 버튼을 통해 음성으로 영어 문장 입력  
  * **TTS (Text-to-Speech)**: 교정된 문장 및 원어민 추천 문장 발음 듣기 지원  
* **🧩 응용 빈칸 퀴즈 (Interactive Practice)**:  
  * 교정된 문법과 어휘를 기반으로 자동 생성되는 맞춤형 퀴즈로 즉시 복습  
* **🔖 학습 보관함 & 오답 노트 (History & Bookmarks)**:  
  * 학습한 문장을 보관함에 저장하여 언제든지 다시 확인 및 복습 가능  
  * 로컬 스토리지(localStorage) 기반 자동 저장  
* **🔑 개인 Gemini API Key 설정**:  
  * 상단 헤더의 API Key 입력란을 통해 개인 API Key를 직접 설정 및 보관 가능  
* **🌙 다크 모드 (Dark Mode)**:  
  * 눈이 편안한 라이트/다크 모드 디자인 지원

## **🛠️ 기술 스택 (Tech Stack)**

* **Frontend**: HTML5, Vanilla JavaScript (ES6+)  
* **Styling**: Tailwind CSS (CDN)  
* **Icons**: Lucide Icons  
* **AI Model**: Google Gemini 3 Flash API (gemini-3-flash-preview)  
* **Web APIs**: Web Speech API (SpeechRecognition & SpeechSynthesis), LocalStorage API

## **🚀 시작하기 (Getting Started)**

별도의 백엔드 서버나 빌드 프로세스 없이 **단일 HTML 파일**로 작동합니다.

## **💡 사용 방법 (Usage Guide)**

1. 웹사이트 접속 후 상단 헤더에서 필요시 본인의 **Gemini API Key**를 입력합니다.  
2. 왼쪽 입력창에 교정받고 싶은 영어 문장을 입력하거나 마이크 아이콘(🎙️)을 눌러 음성으로 입력합니다.  
3. 원하는 교정 톤(**일상 회화 / 비즈니스 / 학술**)을 선택합니다.  
4. **'문법 분석 & 교정 받기'** 버튼을 클릭합니다.  
5. AI가 제시하는 수정 문장, 원어민 표현, 핵심 문법 설명, 그리고 아래쪽 퀴즈를 학습합니다.  
6. 우측 상단의 북마크(🔖) 버튼으로 마음에 드는 문장을 학습 보관함에 저장합니다.

