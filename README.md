# 우편함 · EML Viewer

브라우저에서 EML 파일을 열어보는 정적 웹 앱입니다.

## 실행
압축을 풀고 index.html을 브라우저에서 여세요. index.html, app.js, styles.css는 같은 폴더에 두세요.
설치나 빌드, 서버 없이 사용할 수 있습니다. 최신 Chrome 또는 Edge를 권장합니다.
로컬 파일 환경에서는 클립보드 복사가 브라우저 정책에 따라 제한될 수 있습니다.

## 기능
- HTML / 텍스트 본문, 메일 상세 정보
- CID 내장 이미지 표시, 첨부파일 다운로드
- 외부 이미지 선택적 로드 (기본 차단)
- 원문 32KB 페이지 표시, 전체 원문 복사
- 인쇄 / PDF 저장

## GitHub에 올리기
1. 새 저장소를 만드세요.
2. 이 폴더의 index.html, app.js, styles.css, README.md, .gitignore를 저장소 루트에 올리세요.
3. Code > Download ZIP으로 받은 뒤 index.html을 열면 실행됩니다.
4. 웹 주소도 필요하면 Settings > Pages > Deploy from a branch에서 main, /(root)를 선택하세요.

## 개인정보
EML 파일은 브라우저에서 처리하며 서버에 업로드하지 않습니다.
외부 이미지 불러오기를 켜면 이미지 서버에 접속하며 수신 확인 요청이 발생할 수 있습니다.
메일 본문의 스크립트는 실행하지 않습니다.
실제 업무 메일 및 첨부파일은 이 배포 묶음에 포함되어 있지 않습니다.

## 소스 구성
- index.html: 화면 구조
- styles.css: 디자인 및 반응형 레이아웃
- app.js: MIME 파싱, 본문 및 첨부파일 표시

이 ZIP은 2026-10-20 이미지 수정본의 실행 소스 전체입니다.
Sites 전용 배포 설정과 Git 이력은 포함하지 않습니다.
