# zzirit static page

`zzirit.kr` 서비스 점검 및 상태 안내를 위한 정적 페이지 저장소입니다.

## 포함 내용

- `index.html`: GitHub Pages에 바로 배포할 수 있는 단일 정적 상태 페이지

## 배포 방식

이 저장소는 `main` 브랜치 루트를 GitHub Pages 소스로 사용하는 것을 기준으로 만들었습니다.

기본 공개 주소 예시:

- `https://doojoo9999.github.io/zzirit-static-page/`

별도 도메인을 붙이고 싶다면:

1. GitHub Pages 설정에서 Custom domain을 지정합니다.
2. DNS에서 원하는 서브도메인 예: `status.zzirit.kr`를 `doojoo9999.github.io`로 연결합니다.

## 운영 팁

- 점검 시작 직전과 종료 직후에 `index.html` 문구만 빠르게 수정하면 됩니다.
- 점검 중에는 메인 서비스가 내려가 있어도 이 페이지는 계속 열려야 합니다.
- 필요하면 이후 `CNAME` 파일을 추가해 커스텀 도메인을 붙일 수 있습니다.
