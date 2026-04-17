# Ji & Sarah 학자금 대출 상환 시뮬레이터

Student loan repayment simulator PWA.

## GitHub Pages 배포 방법

1. GitHub에서 새 repository 생성: `Ji_Sarah_Financial_Simulator`
2. 이 ZIP의 모든 파일을 repository에 업로드
3. Settings → Pages → Source를 `main` 브랜치, `/ (root)` 선택
4. 몇 분 후 `https://유저명.github.io/Ji_Sarah_Financial_Simulator/` 로 접속 가능

## 앱 설치

- **Android**: Chrome으로 접속 → 하단 "앱 설치" 배너 클릭
- **iPhone**: Safari로 접속 → 공유 버튼 → "홈 화면에 추가"

## 코드 수정 후 업데이트

1. `index.html` 수정
2. `sw.js`의 `CACHE_NAME`을 `loan-sim-v2` → `loan-sim-v3` 등으로 변경
3. GitHub에 push
4. 사용자가 앱을 다시 열면 자동 업데이트

## 파일 구조

```
index.html          ← 시뮬레이터 본체
manifest.json       ← PWA 앱 정보 (이름, 아이콘, 테마)
sw.js               ← 오프라인 캐시 (서비스워커)
icons/              ← 앱 아이콘 (192x192, 512x512)
manual_ko.md        ← 한국어 매뉴얼
manual_en.md        ← 영어 매뉴얼
```
