# Simple DJ Landing Page

이 폴더는 Simple DJ 프로젝트의 홍보용 웹사이트를 담고 있습니다. 
메인 프로젝트와 별도로 관리되기 위해 `.gitignore`에 추가되어 있습니다.

## 1. 내용 수정 방법

`index.html` 파일을 열어서 직접 수정하면 됩니다.

### 주요 수정 섹션:
- **제목/헤더**: `<header>` 태그 안의 내용을 수정하세요.
- **ASCII 아트**: `pixel-art-turntable` 클래스 안의 텍스트를 수정하여 그림을 바꿀 수 있습니다.
- **프로젝트 소개**: `> ABOUT_THE_PROJECT` 섹션 아래의 `<p>` 태그를 수정하세요.
- **기능 목록**: `retro-list` 클래스 안의 `<li>` 항목들을 수정하세요.
- **버튼 링크**: `action-card` 안의 `<a>` 태그의 `href` 속성을 실제 앱 주소나 깃허브 주소로 변경하세요.

## 2. 깃허브 페이지 배포 방법 (별도 저장소)

이 `landing-page` 폴더를 독립적인 깃허브 저장소로 만들어야 합니다.

1. 터미널을 열고 이 폴더로 이동합니다:
   ```bash
   cd landing-page
   ```

2. 깃 저장소를 초기화합니다:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

3. 깃허브에서 **새로운 Repository**를 만듭니다 (예: `simple-dj-landing`).

4. 만든 저장소를 원격으로 연결하고 푸시합니다:
   ```bash
   git remote add origin <새로운_레포지토리_주소>
   git branch -M main
   git push -u origin main
   ```

5. 깃허브 리포지토리 설정(Settings) -> Pages 메뉴로 가서 `main` 브랜치를 Source로 선택하고 저장합니다.

6. 잠시 후 `https://<사용자이름>.github.io/<리포지토리이름>/` 주소에서 사이트를 확인할 수 있습니다.
