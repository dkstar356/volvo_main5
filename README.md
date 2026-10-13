# IPTV_ASIS_VOLVO_샘플 — GitHub Pages 게시용

원본 화면, 포커스 및 조작 흐름을 유지하고 내장 미디어를 외부 파일로 분리한 패키지입니다. 이미지와 영상은 재인코딩하지 않았습니다.

## 게시 방법

1. ZIP 파일을 압축 해제합니다. ZIP 자체를 업로드하지 않습니다.
2. GitHub Desktop으로 저장소를 연 뒤, 압축 해제한 폴더 **안의 모든 파일과 폴더**를 저장소 루트에 복사합니다. `index.html`과 `assets` 폴더를 같은 위치에 둡니다.
3. 변경 사항을 Commit 후 Push 합니다.
4. 저장소의 Settings → Pages에서 Build and deployment의 Source를 Deploy from a branch로 선택합니다. Branch는 업로드한 브랜치(일반적으로 main), Folder는 /(root)로 선택하고 Save 합니다.
5. GitHub가 제공하는 게시 주소로 접속합니다. 프로젝트 저장소 주소 형식은 `https://<계정>.github.io/<저장소>/`입니다.

브라우저로 직접 업로드할 때는 파일을 100개 이하씩 나누어 업로드하고 폴더 구조를 유지하세요. 두 패키지를 각각 별도 저장소에 게시하면 두 개의 URL로 관리할 수 있습니다.

## 확인 방법

- 메인배너 광고 샘플: 홈에서 오른쪽 방향키 4회 → Enter로 볼보 상세화면. 상세화면에서 Enter로 재생, Esc로 재생 종료, 다시 Esc 또는 홈 버튼으로 배너 복귀.
- 영상은 volvo-detail.html에서 assets/video의 MP4 파일을 읽습니다.

전체 폴더를 함께 옮겨야 이미지·영상 경로가 유지됩니다. 게시된 URL은 해당 GitHub Pages 설정에 따라 접근할 수 있습니다.

## 참고 문서

- https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
