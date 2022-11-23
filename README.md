# 팀 프로젝트

GitHub Pages : https://geniunahn.github.io/DW_main/

팀원 GitHub url
- 안정원 : https://github.com/geniunahn/DW_main
- 권동환 : https://github.com/z9in/project1_daewoong
- 김명아 : https://github.com/myeongakim7/Daewoong-Plastic-Compound

업데이트 기록

2022년 11월 18일
- 피그마로 만든 시안을 토대로 메인 페이지 디자인을 구현함.
- 메인 페이지의 배너로 3장을 만들고 7초마다 순차적으로 재생하도록 함.
- 사이트맵을 추가하고 서브페이지로 이동할 수 있도록 함.
- GNB의 2depth 메뉴를 드롭다운 형식으로 구현함.
- 언어 변경 메뉴를 드롭다운 형식으로 구현함.
- 메인 페이지 버튼에 hover 하이라이트 효과를 적용함.
- 적용된 기술 : 메인 페이지의 배너는 JS에서 setinterval 메서드의 함수가 이미지 경로를 수정하게 하고 opacity 스타일을 적용하여 fade효과로 변경되도록 함. 사이트맵은 버튼을 클릭할 경우 JS에서 click 메서드와 addClass, removeClass 를 응용하여 작동하도록 함.

2022년 11월 21일
- 모바일 화면의 좌우 padding 값을 20px로 통일함.
- 서브 페이지 중에서 max-width 값이 통일되지 않은 부분을 수정함.
- 사이트맵의 폰트 사이즈를 더 크게 수정하고 메인 메뉴를 블랙, 서브 메뉴는 그레이로 수정함.
- GNB 메뉴에 hover 할 경우 대웅 타이틀 컬러를 가진 언더바가 생기도록 함.
- 몇몇 이미지에 width, height 값이 고정으로 지정되어 왜곡 현상이 일어나는 부분을 수정함.
- 적용된 기술 : 메뉴 아래 언더라인은 해당 메뉴에게 ::after로 만들었음. 

2022년 11월 22일 
- 메인 페이지 pc 화면에서 면분할을 하는 회색이 max-width로 인해 화면 전체를 덮지 못하는 현상을 수정함.
- 제품정보 페이지에 적용된 기술과 시안 디자인이 충돌하는 현상이 발생하여 최대한 수정함. 제품정보 페이지의 제품 목록은 세로로 제품 목록을 길게 나열한 박스를 만들고 실제 브라우저에 보이는 화면에게 overflow:hidden 을 적용하여 부분만 보이게 하는 것임. 문제는 제품 목록을 나열한 객체로 인해 시안 디자인대로 만드는 것과 브라우저의 크기에 따라 가변이 일어날 경우 부자연스러운 모습이 나타난다는 것임. 최대한 시안에 맞게 수정하였음.
- 모바일 화면의 사이트맵 메뉴 우측에 드롭다운 화살표 아이콘을 추가함
- 메인 페이지의 텍스트에 fade-up 효과를 적용함.
- 제품 검색창이 불필요하게 길기 때문에 가로 폭을 줄임.
- 검색창에 텍스트가 들어갈 때 들여쓰는 여백을 추가함.
- 파비콘 아이콘을 제작하여 적용함.
- 오시는 길 버튼이나 GNB를 클릭하면 바로 오시는 길 화면으로 갈 수 있도록 링크함.
- 홍보센터의 타이틀 텍스트의 폰트 사이즈와 연구정보 타이틀 텍스트의 구조를 다른 서브 페이지와 동일하도록 수정함.
- 적용된 기술 : 메인 페이지의 텍스트가 fade-up 되는 효과는 AOS 에서 제공하는 라이브러리를 사용하여 구현함.

2022년 11월 23일
- 특허증 보기 버튼을 누르면 사용자가 버튼을 클릭해 특허증을 볼 수 있도록 수정함.
- SEO 태그를 추가함. OG 태그 추가함.
