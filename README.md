# Project 03

## CSS

### HTML에서 태그의 구조를 파악하자!

```visual basic
  <header>
    <a href="/">
      <img class="logo" src="images/logo.png" alt="logo">
    </a>
    <!-- 네비게이션 바 -->
    <nav>
      <ul class="nav-items">
        <li><a href="#">Main</a></li>
        <li><a href="#">Box office</a></li>
        <li><a href="#">영화 상영작</a></li>
        <li><a href="#">About</a></li>
      </ul>
    </nav>
  </header>
```

헤더태그부분에 nav태그를 만들어주고 img 를 넣어준다.



```visual basic
  </section>
  <div id="content">
    <aside>
      <h2>장르 목록</h2>
      <ul class="aside-items">
        <li>액션</li>
      </ul>
    </aside>
    <section id="section-movie">
      <h2>실시간 영화 순위</h2>
      <div class="section-movie-items">
        <div class="movie-item">
          <img class="movie-item-poster" src="images/174903.jpg" alt="엑시트">
          <h3 class="movie-item-title">엑시트</h3>
        </div>
      </div>
    </section>
```

div태그로 큰 블록을 만들고 그 안에  aside태그로 장르목록  section태그로 main 정보인 실시간 영화 순위를 만든 구조이다.

### CSS의 다양한 명령어로 HTML을 내 입맛에 맞게 꾸며보자!

`position: fixed;` : html 문서에서 원하는 위치에 고정시킴 / 보통 헤더에 사용한다.

`position: absolute;` : 항상 자기가 속한 자리에 자리에 있도록 만든다.

+ top: 0 / bottom: 0  등과 같이 쓴다.

`z-index: 1000;` : 다른 영역보다 항상 앞에 보이게하려면 큰 수를 넣고 뒤에 두고싶으면 작은 수를 넣는다.

`float: right;` : block을 왼쪽/오른쪽 등 으로 보낸다.

`display: inline-block`: 한줄에 다 넣고 싶을 때 사용한다.

`margin: 0 5px;`: margin을 상하 0 좌우 5px 만큼 준다.

`padding:0;` : padding 상하좌우에 margin을 준다.

`list-style: None;`: li 태그의 bullet point를 없애준다.

`color: green;`: 원하는 태그에 들어가는 text color를 바꿔준다.

`.nav-items > li > a:hover` : class 속성이 nav-items 안에 li 안에 a:hover는 마우스 오버시 모습이다.

`text-decoration: None;` : text를 꾸며주는 역활을 하는데 default는 밑줄을 그어준다.

`background-image: url("images/background.jpg");` : 블록의 배경 이미지 설정한다.

`text-align: center;` : text 블록 가운데 정렬시킨다.

`line-height: 300px;`: text를 수직 가운데 정렬 시킨다. (높이가 300px이면 300px값을 준다.)

`font-size: 3.5rem;`: font의 크기를 바꿔준다. rem은 다른 font크기에 3.5배 키운다.

