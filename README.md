# 이서현 포트폴리오

Minimal Mistakes와 Jekyll 없이 동작하는 정적 포트폴리오입니다.

## 구성

- `index.html`: 메인 포트폴리오
- `resume/index.html`: 이력서
- `projects/*/index.html`: 프로젝트 상세 페이지
- `assets/css/portfolio.css`: 전체 스타일
- `assets/fonts`: 로컬 웹폰트
- `assets/images/projects`: 프로젝트 이미지
- `.nojekyll`: GitHub Pages에서 Jekyll 처리를 건너뛰는 표시

## 실행

별도의 설치나 빌드가 필요하지 않습니다. 웹 서버의 루트에 모든 파일을 그대로 올리면 됩니다.

로컬에서 확인하려면 이 폴더를 정적 파일 서버로 열고 `/`에 접속하세요. 사이트 내부 링크가 루트 경로(`/assets`, `/projects`, `/resume`)를 사용하므로 HTML 파일을 직접 여는 방식보다 로컬 서버 사용을 권장합니다.

## GitHub Pages 배포

이 저장소의 기본 브랜치를 GitHub Pages 배포 소스로 지정하면 됩니다. `.nojekyll` 파일이 있으므로 테마, Ruby, Gem, Jekyll 설정 없이 정적 파일이 그대로 게시됩니다.
