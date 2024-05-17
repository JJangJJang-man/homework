# homework 📖

테킷 프론트엔드 스쿨 10기 HTML / CSS 과제3

### STACKS

- HTML
- CSS

### 웹표준

- Web developer 검사 완료
- 크롬, 파이어폭스 크로스테스트 완료

### HTML 구조

1. 본문 (main) 영역 생성 <br>

2. 카드 컴포넌트 <br>

- 최상위 컨테이너로 div요소 생성, "card-box" 및 "제품명"으로 class 지정<br>

3. 문단 및 버튼 그룹핑<br>

- 각 문단끼리, 버튼끼리 div요소로 그룹핑 후 class 지정<br>
- 문단 컨테이너와 버튼 컨테이너를 부제목과 함께 aticle요소로 그룹핑 <br>

3. 이미지 넣기 <br>

- figure요소로 이미지 영역 생성 <br>
- css 백그라운드 속성으로 넣기에 콘텐츠는 없지만 aria-label 속성으로 이미지 설명 추가 <br>

4. 컴포넌트 사용하여 제품 추가 및 내용 수정 <br>

### CSS 구조

1. 카드 컴포넌트 설정 <br>

- 카드 박스(article + image)의 크기 및 색상 조정 <br>

2. 카드(article) <br>

- 각 텍스트, 텍스트 색상, 컨테이너 크기 수정 <br>
- 그룹핑 컨테이너는 flex-box로 설정 후 column 방향 배치 <br>
- 아이템 링크 버튼은 row 방향 배치 <br>
- 버튼은 마우스 호버 시 밝은 색으로 변경되도록 지정하였고 검은색 버튼도 밝아져 임의로 색상 추가 <br>

3. 이미지(image) <br>

- 이미지 크기 설정 및 absolute 속성으로 위치 고정 <br>
- index 순서 조정하여 최하단에 위치 <br>

4. text-black 속성 <br>

- 흰 배경화면 사용하는 아이템에 text 검은색으로 조정되도록 class 추가 <br>

5. mediaquery <br>

- 각 아이템 별 이미지 연결 / 1024px이상 화면에서 간격 및 이미지 조정되도록 mediaquery 추가 <br>

6. 레이아웃 설정 <br>

- 카드 레이아웃 grid로 설정 작은 화면에서 column = 1, 1024px 화면에서 2행으로 되도록 mediaquery 추가 및 배치 조정 <br>

### 느낀점

과제하면서 grid로 이리저리 화면 구성 해봤는데 눈에 보이는 결과물이 있어서 그런지 재밌었습니다.
