# 🌸 Blossom 게시판 알림 (Blossom Alarm)

> **사내 인트라넷 게시판(Blossom)의 새로운 공지사항 및 피드를 실시간으로 모니터링하여 바탕화면 푸시 알림으로 즉각 전송해 주는 크롬 익스텐션(Chrome Extension)입니다.**

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/ppoofmgpfajidnjnbfdnbbpfbinohidl.svg?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chromewebstore.google.com/detail/blossom-%EA%B2%8C%EC%8B%9C%ED%8C%90-%EC%95%8C%EB%A6%BC/ppoofmgpfajidnjnbfdnbbpfbinohidl?authuser=0&hl=ko)

---

## 📥 다운로드 및 설치

아래 크롬 웹스토어 공식 링크를 통해 브라우저에 즉시 추가하여 사용하실 수 있습니다.

* **[Chrome Web Store - Blossom 게시판 알림 설치하기](https://chromewebstore.google.com/detail/blossom-%EA%B2%8C%EC%8B%9C%ED%8C%90-%EC%95%8C%EB%A6%BC/ppoofmgpfajidnjnbfdnbbpfbinohidl?authuser=0&hl=ko)**

---

## ✨ 핵심 기능

1. **실시간 알림 (Push Notification)**: 브라우저가 백그라운드에 켜져 있는 동안에도 새로운 게시글이 올라오면 즉각 우측 하단 푸시 알림을 띄워 줍니다.
2. **배지 카운트 (Badge Count)**: 익스텐션 아이콘 위에 읽지 않은 피드의 개수를 직관적으로 표기해 줍니다.
3. **원클릭 이동**: 알림창을 클릭하면 해당 공지사항 상세 페이지로 바로 이동합니다.

---

## 🛠️ 기술 스택 및 구조

* **Frontend**: Vanilla JS, HTML, CSS (Chrome Extension Manifest V3)
* **Background Worker**: Chrome Service Worker API를 활용한 폴링 및 웹훅 연동 엔진
* **APIs**: Chrome Notifications API, Chrome Alarms API
