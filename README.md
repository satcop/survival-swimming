
1. 개발 서버 실행 (권장)
터미널에서 프로젝트 루트 경로(/Users/park/sources/temp1/survival-swimming)로 이동 후 아래 명령어를 실행합니다.

npm start


실행 시 Webpack 개발 서버(webpack-dev-server)가 동작하며 기본 브라우저가 자동으로 열립니다.
코드 수정 시 핫 리로딩(Live Reload / Hot Module Replacement)이 적용됩니다.


2. 기타 유용한 명령어
패키지 설치 (의존성 모듈이 없거나 새로 설치할 때):

npm install

프로덕션 빌드 (dist 디렉토리에 번들 파일 생성):

npm run build
