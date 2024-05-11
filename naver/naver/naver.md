# homework 📖

테킷 프론트엔드 스쿨 10기 HTML / CSS 과제2

### STACKS

- HTML
- CSS

### 웹표준

- Web developer 검사 완료
- 크롬, 파이어폭스 크로스테스트 완료

### HTML 구조

1. 로고 <br>

- 헤더에 로고 이미지 삽입 및 Naver 홈페이지로 연결될 수 있도록 링크 연결, focus 안되도록 tabindex 조정 <br>

2. 로그인 폼 <br>

- form요소로 데이터 폼 생성 및 fieldset 요소로 연관된 정보 그룹화 <br>
- label, input요소로 입력 서식 생성하고 div태그로 group 지정 <br>
- 각 그룹을 div 태그로 id-pw-wrap 그룹으로 지정 <br>
- 로그인 버튼 생성 <br>

3. 로그인 서브 메뉴 <br>

- ul 요소로 서브 메뉴 리스트화 <br>
- 하위 리스트로 로그인 상태 유지 & 체크박스, IP 보안 & 체크박스 생성 <br>
- IP 보안 텍스트에 관련 웹사이트 링크 연결 <br>

4. 로그인 폼, 로그인 서브메뉴 section 요소로 그룹화 <br>

### CSS 구조

1. 본문 <br>

- reset <br>
- svg형식을 지원하는 않는 웹브라우저는 png형식 로고 적용되도록 구현 <br>

2. 헤더 영역 <br>

- 로고 크기 및 로그인 폼 요소와 구별되도록 margin 설정 <br>

3. 메인 영역 <br>

- 로그인 폼 padding 및 크기 조절, 로그인 서식 flex 속성 및 column 방향으로 배치 gap 10px 설정 <br>
- id pw input 요소 설정 <br>
- 로그인 버튼 설정 <br>
- 모바일 환경에서 IP 보안 미구현 및 로그인 상태 유지 창 오른쪽 배치 <br>
  (체크 박스 커스텀) <br>
- 768px 이상 화면에서 반응하는 mediaquery 구현 <br>
  로그인 창 길이 고정 및 로그인 서브 메뉴에 IP 보안 추가 배치 <br>
  체크박스를 on / off 텍스트로 대체 <br>

### 질문할 것

#### Firefox에서 로고에 tab으로 focus가 되지 않음

- header요소 안에서는 로고가 focus되지 않았고 body안에서는 div 크기 만큼 focus 되는 것이 아니라 a 크기 만큼 focus가 되었음.
