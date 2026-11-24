# 냥냥구조대 홈페이지

## 미리보기
압축을 풀고 index.html을 브라우저로 열면 됩니다. 모든 페이지는 외부 라이브러리 없이 작동합니다.

## 출시 전에 반드시 수정
- privacy.html, terms.html, support.html의 대괄호로 표시된 부분을 실제 정보로 채우세요. 초안 경고와 개발 중 문구는 실제 내용 검토 및 출시 단계에 맞춰 제거/변경하세요.
- 홈페이지 고양이 SVG는 실제 게임 이미지가 아닌 임시 장식입니다. 게임 내용, 개발사 이름 및 이미지가 확정되면 반영하세요.
- app-ads.txt 파일에는 AdMob의 실제 맞춤 코드를 그대로 넣으세요. 임의 게시자 ID를 쓰지 마세요.
- 개인정보처리방침과 데이터 보안 설문은 SDK, 권한, 서버, 결제, 어린이 대상 여부와 일치해야 합니다.
- 집 주소 등 사적인 정보는 임의로 추가하지 않았습니다. 법정 표시 의무에 해당하는 경우 필요한 정보는 별도로 확인하세요.

## GitHub Pages 배포(공식 소개·지원용 정적 사이트)
1. GitHub에서 본인 계정의 `사용자이름.github.io` 저장소를 생성합니다(이미 있다면 덮어쓰지 말고 기존 사이트 구조 확인).
2. README 외 홈페이지 파일들을 저장소 최상위에 업로드합니다.
3. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save.
4. `https://사용자이름.github.io/` 및 `/privacy.html`, `/terms.html`, `/support.html`, `/app-ads.txt`가 열리는지 확인합니다.
5. 최종 개인정보처리방침 URL을 Play Console 및 게임 내에 등록합니다. 개발자 웹사이트 URL은 사이트 주소로 등록합니다.
6. AdMob 앱을 출시 후 스토어 목록과 연결하고 app-ads.txt 인증 상태를 확인합니다.

주의: 일반 프로젝트 Pages URL의 하위 경로에 app-ads.txt를 두면 루트 경로 검사에 실패할 수 있습니다. GitHub Pages 이용 제한상 직접 결제·상거래 사이트로 사용하지 마세요. 다른 사이트가 있거나 필요하면 Firebase Hosting 등 루트 경로를 제공하는 호스팅을 선택할 수 있습니다.

공식 안내
- https://support.google.com/admob/answer/9363762
- https://support.google.com/googleplay/android-developer/answer/10144311
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits