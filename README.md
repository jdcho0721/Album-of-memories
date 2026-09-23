# 전북맹아학교: 추억의 앨범
### Jeonbuk School for the Blind — A Relay of Memories

<p align="center">
  <img src="https://img.shields.io/badge/WCAG-2.1%20AA-4CAF50?style=flat-square" alt="WCAG 2.1 AA">
  <img src="https://img.shields.io/badge/PWA-Offline%20Ready-5A67D8?style=flat-square" alt="PWA">
  <img src="https://img.shields.io/badge/Mobile-Touch%20%26%20Swipe-E67E22?style=flat-square" alt="Mobile Touch & Swipe">
  <img src="https://img.shields.io/badge/License-MIT-A07840?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/Humartology-Lab-1A362D?style=flat-square" alt="Humartology Lab">
</p>

<p align="center">
  <b>전북맹아학교 졸업생들의 이야기를 소리와 촉각으로 전하는 디지털 졸업 앨범</b><br>
  <i>A digital graduation album conveying the stories of Jeonbuk School for the Blind's
  graduates through sound and touch</i>
</p>

---

## 프로젝트 소개 / Overview

**전북맹아학교: 추억의 앨범**은 시각장애 특수학교인 전북맹아학교 졸업생들의
학창 시절과 이야기를, 사진 한 장으로 지나치는 평면적 앨범이 아니라
음성과 영상, 촉각적 경험으로 전하는 디지털 졸업 앨범입니다. 각 졸업생과
선생님의 사진을 짚으면 그 사람의 목소리와 이야기가 영상과 함께 재생됩니다.

*A Relay of Memories* conveys the school years and stories of graduates from
Jeonbuk School for the Blind — not as a flat photo album to glance past, but
through voice, video, and tactile interaction. Touching each graduate's or
teacher's photo plays their story through narration and video.

> **"한 장의 사진이 아니라, 한 사람의 목소리로 남는 졸업 앨범."**

---

## 주요 기능 / Features

### 🎓 추억의 릴레이 / The Memory Relay
고등부 3학년 C반 졸업생 7명과 담임 최철 선생님, 모두 8명의 사진이 앨범에 담겨 있습니다.
사진 한 장을 누르면 다섯 단계가 이어서 재생됩니다.

| 단계 | 내용 |
|:---:|---|
| ① 명찰 | 이 사진이 앨범의 몇 번째 줄, 몇 번째 칸에 있는 누구인지 안내 |
| ② 사진 해설 | 안경, 머리 모양, 표정 등 사진 속 모습을 말로 설명 |
| ③ 실제 목소리 | 졸업생·선생님이 직접 녹음한 졸업 인사 |
| ④ 장래 희망 | 그 사람의 꿈과 바람 |
| ⑤ 영상 | 꿈을 담은 짧은 영상 |

### 🗣️ 접근 가능한 음성 안내 / Accessible Narration
- 졸업생 본인의 **녹음된 목소리**를 중심으로, 명찰·사진 해설·장래 희망은 음성합성으로 읽어 줌
- **음성 인식 챗봇**: "임이삭 어디 있어?", "최철 선생님 졸업멘트"처럼 말하면 위치를 알려 주거나 꿈과 영상을 바로 재생
- 은은한 배경 음악(교실 햇살) 위로 모든 안내가 흘러, 화면을 보지 않고도 전체 흐름을 따라갈 수 있음

### 📱 모바일 터치·스와이프 / Mobile Touch & Swipe
- 화면 하단 고정 **◀ 이전 · ① 명찰 ② 사진 ③ 목소리 ④ 꿈 ⑤ 영상 · 다음 ▶** 버튼
- 앨범 위에서 좌우로 밀어 다음·이전 친구로 이동
- 스크린 리더 없이도 모든 음성을 **화면 하단 자막 바**로 동시에 제공

### ♿ 접근성 / Accessibility
- **WCAG 2.1 AA** 준수 지향
- **TalkBack / VoiceOver** 지원 (WAI-ARIA 역할·라벨, 키보드 조작)
- 스크린 리더가 없어도 터치·마우스·스와이프·음성만으로 같은 경험이 가능한 다감각 설계

---

## 관람 방법 / How to Use

처음 화면의 **[터치하여 앨범 감상 시작하기]** 를 누르면 소리가 켜지고 감상이 시작됩니다.

| 하고 싶은 것 | 방법 |
|---|---|
| 친구의 이야기 듣기 | 사진을 한 번 누르기 → ①~⑤ 단계가 이어서 재생 |
| 다음·이전 친구 | 하단 **◀ 이전 / 다음 ▶** 버튼, 또는 앨범 위에서 **좌우로 밀기** |
| 원하는 단계로 건너뛰기 | 하단 **①~⑤** 버튼 (예: ⑤를 누르면 영상부터) |
| 장래 희망 바로 듣기 | **④ 꿈** 버튼, 사진 **길게 누르기**, 더블 클릭, 또는 스페이스바 |
| 음성으로 찾기 | 마이크 버튼(**눌러서 말하기**, 키보드는 `V`)을 누르고 이름이나 "○○ 장래희망"이라고 말하기 |
| 영상 닫기 | 오른쪽 위 **✕ 닫기**, **아래로 밀기**, 영상 바깥 누르기, 또는 `Esc` |
| 자막 | 화면 아래 자막 바에서 길면 밀어 읽기 · **▾ 접기**(한 줄) · **■ 멈춤**(재생 멈춤) |
| 이용 안내 | 왼쪽 위 **[이용 안내]** — 마우스를 올리면 잠시 뒤 자동으로 열림, 좌우로 밀거나 ✕로 닫기 |
| 키보드 | 방향키로 사진 이동, `Enter` 처음부터 재생, `Space` 장래 희망, `V` 음성 인식, `Esc` 영상 닫기 |

**지금 어디에 있는지 한눈에**
- 하단 버튼 위에 "송영조 학생 (3/8) · ③ 실제 목소리"처럼 누구의 몇 번째 단계인지 표시
- 지금 단계 버튼은 노랗게 채워지고, 지나온 단계는 노란 테두리로 남음
- 재생 중인 사진은 주황 테두리로 떠오르고, 한 번 들은 친구에게는 초록 ✓ 표시

---

## 스크린 리더 없이 쓰는 접근성 설계 / Accessibility without a Screen Reader

**보이는 자막 / Live Captions**
- 명찰, 사진 해설, 장래 희망, 챗봇 답변 등 모든 음성을 화면 하단 자막 바에 동시에 표시
- 녹음된 목소리가 나올 때는 "🔊 ○○ 학생이 목소리로 직접 전하는 이야기를 듣고 있습니다" 표시
- 자막이 떠 있으면 안내 창과 영상이 자막 위 공간까지만 차지해 가려지지 않음

**누르기 쉽게 / Large Touch Targets (Fitts's Law)**
- 모든 버튼 최소 48px, 하단 버튼 56px, 닫기 버튼 52px
- 휴대폰에서 앨범 틀의 여백을 줄여 사진을 크게 표시
- 누른 자리에 원형 피드백, 더블탭 확대 지연 없이 즉시 반응 (두 손가락 확대는 그대로 가능)

**정확한 위치 안내 / Accurate Position**
- "두 번째 줄, 첫 번째 칸"처럼 알려 주는 위치를 **화면에 실제로 보이는 열 수**로 계산 — 휴대폰(2열), 가로 화면·PC(4열) 어디서나 안내와 화면이 일치

**화면 배치 / Responsive Layout**
- 세로: 2열 앨범, 하단 조작 줄 / 가로(휴대폰): 4열 앨범, 2줄 자막
- 아이폰 노치·홈 표시줄 영역(safe area) 대응

---

## 폴더 구성 / Files

```
memory-album/
├── index.html                              # 화면·스타일·동작 전체
├── README.md
├── Sunlight_on_the_Classroom_Floor.mp3     # 배경 음악
│
│  ── 사진 ──
├── 최철-선생님c.png   김희연-고3c.jpeg   송영조-고3c.png   이정민-고3c.png
├── 임이삭-고3c.jpeg   임찬서-고3c.jpeg   장준원-고3c.jpeg   조헌-고3c.png
│
│  ── 실제 목소리 ──
├── 담임_최철_졸업멘트.m4a   김희연졸업2.m4a   송영조졸업.mp3   "이정민 졸업.m4a"
├── 임이삭졸업.m4a   임찬서졸업2.m4a   장준원졸업2.m4a   조헌졸업1.m4a
│
│  ── 꿈 영상 ──
├── 선생님의_마지막_숙제.mp4          # 최철 선생님
├── 김희연-분홍빛_안경.mp4
├── 송영조-카키색_새벽길.mp4
├── 이정민-함께_뛰는_미래.mp4
├── 임이삭-함께_뛰는_순간.mp4
├── 임찬서-너의_맘이_머무는_곳.mp4
├── 장준원-안전한_내일로.mp4
└── 조헌-비타민_같은_너.mp4
```

> `이정민 졸업.m4a` 는 파일 이름에 띄어쓰기가 있습니다. 대부분의 서버에서 문제없지만, 재생이 안 되면 띄어쓰기를 없애고 `index.html` 의 파일 이름도 같이 바꿔 주세요.
> 목소리 파일이 없거나 재생되지 않으면 ③ 단계를 건너뛰고 ④ 장래 희망으로 넘어갑니다.

## 실행 방법 / Getting Started

https://github.com/jdcho0721/Album-of-memories
```



## 내용 수정 / Customization

| 바꿀 것 | 위치 (`index.html`) |
|---|---|
| 장래 희망 문구·영상 파일·음성 높낮이 | `friendData` |
| 사진 해설 문구 | 각 사진의 `aria-label` (`.character-img`) |
| 사진 파일·얼굴 위치 | CSS `#img-이름 { background-image … }` |
| 실제 목소리 파일 | `<div id="audio-container">` 안의 `<audio>` |
| 사진 순서 | `<div id="album-container">` 안의 카드 순서 (위치 안내·이전/다음 순서도 함께 바뀜) |
| 모바일 버튼·자막·스와이프 | `<style id="mobile-a11y">`, `<script id="mobile-a11y-js">` |

---

## 작품 배경 / Background

전북맹아학교는 시각장애 학생을 위한 특수학교입니다. 이 프로젝트는 그
학교를 졸업한 학생들과 이들을 지도한 선생님의 이야기를, 시각에 의존하지
않고도 온전히 전달할 수 있는 형태로 기록하고자 만들어졌습니다. 사진과
문자로만 남는 보통의 졸업 앨범과 달리, 목소리와 촉각으로 함께 걸어온
시간을 다시 나눕니다.

**추억의 3D 앨범 촉각 모델**은 이 디지털 앨범과 짝을 이루는 실물 촉각 앨범입니다.
졸업생의 캐리커처를 3D 입체 초상으로 정밀하게 구현했으며, 디지털 앨범은 이 촉각 모델의
도슨트 역할을 하도록 설계되었습니다. 촉각 앨범의 태그를 짚으면 디지털 앨범으로 이어져
학생 본인의 목소리와 사운드가 재생됩니다.

- 작품 설명: [tactile-album-site.vercel.app](https://tactile-album-site.vercel.app/)
- 이 앨범은 전북맹아학교 선생님과 학생들의 동의와 협력 아래 제작되었습니다.

---

## 기술 스택 / Tech Stack

| 분류 | 기술 |
|------|------|
| 프론트엔드 | Vanilla HTML / CSS / JavaScript |
| 오디오 | HTML5 Audio (녹음 목소리·배경 음악), Web Speech API (음성합성·자막) |
| 음성 인식 | Web Speech API (SpeechRecognition) + 이름 유사도 매칭 |
| 영상 | HTML5 Video |
| 입력 | Touch Events (스와이프·길게 누르기), Pointer/Keyboard |
| PWA | Service Worker, Web App Manifest |
| 접근성 | WAI-ARIA, WCAG 2.1 AA |

---

## 업데이트 기록 / Changelog

### 2026.09 — 모바일·접근성 개선
- 하단 고정 **◀ 이전 · ①~⑤ 단계 · 다음 ▶** 버튼과 현재 위치 표시 추가
- 스와이프 동작 변경: 좌우 = 다음·이전 친구, 영상은 아래로 밀기 또는 **✕ 닫기** 버튼으로 닫기
- 모든 음성을 보여 주는 **하단 자막 바** 추가 (접기·멈춤·스크롤)
- 재생 중인 사진 강조, 들은 친구 ✓ 표시, 누른 자리 피드백 추가
- 휴대폰에서 줄·칸 위치 안내가 실제 화면과 어긋나던 문제 수정 (2열인데 3열 기준으로 안내하던 버그)
- 음성 인식 미지원 브라우저의 경고창을 자막·음성 안내로 교체
- 이용 안내 창 닫기 버튼 확대, 마우스를 올리면 안내 창이 자동으로 열리도록 변경
- 휴대폰에서 마이크 안내 문구를 "V키 클릭" → "눌러서 말하기"로 변경

---

## Mobile Tactile Museum 전시 / Exhibition

이 작품은 **Mobile Tactile Museum (이동 촉각 뮤지엄)** 전시의 **Work 04 — 전북맹아학교를 위한 촉각 음성 졸업 앨범**입니다.

| # | 작품 | 링크 |
|---|------|------|
| 01 | 오우가와 세연정: 공간의 교향곡 | [Seyeonjung-Garden](https://github.com/jdcho0721/Seyeon) |
| 02 | 반가사유상: 사유의 목소리 | [Pensive-Bodhisattva](https://github.com/jdcho0721/Pensive-Bodhisattva) |
| 03 | 감각의 고고학 2076: 잃어버린 향의 연대기 | [Incense-Burner](https://github.com/jdcho0721/Incense-Burner) |
| 04 | **전북맹아학교를 위한 촉각 음성 졸업 앨범** | 현재 저장소 |
| 05 | 에밀레: 천년의 울림 | [Emille-Bell](https://github.com/jdcho0721/Emille-Bell) |

---

## 제작 / Credits

| 역할 | 이름 | 소속 |
|---|---|---|
| Exhibition Creator & Multisensory Interaction Director | **조준동 (Cho Jundong)** | 성균관대학교 정보통신대학 명예교수 · Humartology Lab 설립자 |

✉ jdcho@skku.edu · 🌐 [blog.naver.com/humartology](https://blog.naver.com/humartology)

### 추억의 3D 앨범 촉각 모델 / 3D Tactile Album

| 역할 | 이름 |
|---|---|
| 심화융합캡스톤디자인 팀 (지도교수 조준동) | 문홍진 · 남재호 · 장예림 · 최송희 |
| 지원 | 성균관대학교 RISE 사업단 · 전북맹아학교 |

### 도와주신 분 / Contributors

| 역할 | 이름 | 소속 |
|---|---|---|
| Virtual Archaeology & Tactile Production Director | **김호용** | (주)위프코 대표 |
| Accessibility Consultant & Barrier-Free Supervisor | **육근해** | 장애인문화복지연구소 대표 |

## 라이선스 / License

[MIT License](./LICENSE) — © 2026 조준동 · Humartology Lab
jdcho@skku.edu

<p align="center"><i>Mobile Tactile Museum — 이동 촉각 뮤지엄 · 2026</i></p>
