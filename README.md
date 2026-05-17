# COUNTERVIEW version 1.0

> Firebase Realtime Database 기반의 양방향 실시간 동기화 웹 타이머 시스템

COUNTERVIEW는 호스트(발표자/진행자)와 뷰어(청중/참가자) 간의 완벽한 실시간 시간 동기화를 제공하는 웹 기반 타이머 애플리케이션입니다. 반응형 레이아웃이 적용되어 모바일 가로/세로 모드 및 데스크톱 환경 어디서나 최적의 화면을 제공합니다.

<br>

## ✨ 주요 기능 (Key Features)

* **실시간 타이머 동기화**: Firebase Realtime Database를 통해 호스트의 타이머 상태(시작, 일시정지, 초기화, 남은 시간)가 뷰어 화면에 0.1초의 오차도 없이 실시간으로 전송됩니다.
* **중간 알림 (Split Timer)**: 목표 시간 외에 특정 남은 시간을 설정하여 중간 알림을 보낼 수 있습니다. 지정된 시간에 도달하면 화면 텍스트 알림과 함께 경고음이 발생합니다.
* **오디오 알림 시스템**: Web Audio API를 활용하여 별도의 오디오 파일 없이 오실레이터(Oscillator) 사운드로 중간 알림(2회 비프음) 및 최종 종료 알림(5회 비프음)을 명확하게 전달합니다.
* **편리한 화면 공유**: 
  * 단 한 번의 클릭으로 뷰어 모드 전용 URL을 복사할 수 있습니다.
  * QR 코드 생성 기능이 내장되어 있어 스마트폰이나 태블릿으로 쉽게 화면을 스캔하여 공유할 수 있습니다.
* **뷰어 전용 모드 (Viewer Mode)**: 뷰어 URL로 접속 시, 컨트롤 버튼과 설정 창이 자동으로 숨겨지며 화면 전체에 대형 타이머 디스플레이만 직관적으로 표시됩니다.
* **완벽한 반응형 및 모바일 최적화**: 모바일 가로 모드(Landscape) 및 노치 디자인(Safe Area CSS)을 고려하여 설계되어 디바이스를 돌려도 UI가 깨지지 않고 유연하게 늘어납니다.

<br>

## 🛠️ 기술 스택 (Tech Stack)

* **Frontend**: HTML5, CSS3 (Flexbox, CSS variables, `clamp()` responsive font), JavaScript (ES6+ Modules)
* **Backend / Database**: Firebase Realtime Database (NoSQL)
* **API / Libraries**: QR Code Generator API, Web Audio API

<br>

## 🚀 시작하기 (Getting Started)

1. **Repository Clone**
   ```bash
   git clone [https://github.com/anhyeokkyun/counterview.git](https://github.com/anhyeokkyun/counterview.git)
2. **실행**
   별도의 로컬 서버 설치 없이 index.html 파일을 브라우저에서 더블 클릭하거나 Live Server를 통해 바로 실행할 수 있습니다.

📝 라이선스 (License)
   이 프로젝트는 MIT 라이선스를 따릅니다.

---

```markdown
# COUNTERVIEW ⏱️
> Web-based Real-time Synchronized Timer App powered by Firebase Realtime Database.

COUNTERVIEW is a web-based timer application that offers seamless, real-time time synchronization between a Host (Presenter/Organizer) and Viewers (Audience/Participants). Featuring a fully responsive layout, it guarantees an optimized display across desktop and mobile devices in both portrait and landscape orientations.

<br>

## ✨ Key Features

* **Real-time Timer Synchronization**: Leverages Firebase Realtime Database to sync the host’s timer status (Start, Pause, Reset, Remaining Time) to all connected viewer screens instantly without latency.
* **Split Timer (Intermediate Alert)**: Allows the host to set an intermediate milestone. When the timer hits the specified split time, a blinking text alert and audio chime trigger on both host and viewer screens.
* **Web Audio System**: Utilizes the native Web Audio API to synthesize clean oscillator sound effects (2 beeps for the split alert, 5 beeps for completion) without relying on heavy external audio files.
* **Effortless Screen Sharing**:
  * **Copy Link**: Instantly copy the dedicated Viewer Mode URL with a single click.
  * **QR Code Generation**: Displays an on-screen QR code for quick scanning via smartphones or tablets.
* **Dedicated Viewer Mode**: When accessed via a viewer URL, all control buttons, input fields, and configuration boxes are hidden, leaving a clean, maximized, distraction-free timer display.
* **Fully Responsive & Mobile-Optimized**: Engineered with CSS `clamp()` and media queries tailored for ultra-low mobile landscape viewports (`max-height: 500px`) and Safe Area Insets to avoid device notches.

<br>

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3 (Flexbox, CSS variables, `clamp()` responsive font), JavaScript (ES6+ Modules)
* **Backend / Database**: Firebase Realtime Database (NoSQL)
* **API / Libraries**: QR Code Generator API, Web Audio API

<br>

## 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/your-username/counterview.git](https://github.com/your-username/counterview.git)
   
2. Run Application
   No heavy installation required. Simply double-click the index.html file or use a local extension like VS Code's "Live Server" to run    the application in your browser.

📝 License
   This project is licensed under the MIT License.
