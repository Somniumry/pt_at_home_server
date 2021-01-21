# PT_AT_HOME

사용자 -> 로그인 -> 토큰생성 -> 브라우저 쿠키에 보관
어떤 API 호출 시 토큰 유무 확인 후 
올바른 토큰이 있을 경우 API 실행, 없으면 실행 안함

routes/index.js
로그인

사용자확인
verify



src/lib/token.js  jwt.sign

로그인 -> 유저 있으면 토큰을 발급
