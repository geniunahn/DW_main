# 대웅 리디자인 팀 프로젝트
- 팀장 : 안정원 (시안 디자인, 메인 페이지, header, footer, sitemap, 페이지 전체적인 등장 애니메이션, 버튼 이벤트 구현, 조원들이 완성한 소스를 받아 시안대로 구현되지 않은 문제점이 있는지 검토하고 수정함.)
- 조원 : 권동환 (연구정보, 제품정보 페이지 구현함, 연구정보의 '특허증 자세히 보기' 와 제품 정보의 버튼 이벤트를 구현함.)
- 조원 : 김명아 (회사소개 디자인을 추가로 수정, 파비콘 디자인, 회사소개, 홍보센터 페이지를 구현함.)

- 안정원 깃허브 url : https://github.com/geniunahn/DW_main
- 권동환 깃허브 url : https://github.com/z9in/project1_daewoong
- 김명아 깃허브 url : https://github.com/myeongakim7/Daewoong-Plastic-Compound

- 대웅 플라스틱 오리지날 사이트 : http://www.dwpolychem.com/home/index.php
- 프로젝트 url : https://geniunahn.github.io/DW_main/

# 제작 상황 및 목표
- 제작 상황 : 자바스크립트와 jQuery를 배운 후 웹 사이트에 이벤트를 부여하는 것까지 배운 상황. 각 조는 선생님이 정해준 회사의 홈페이지의 약점을 분석하고 그것을 보완하기 위한 사이트맵과 디자인을 고안해야 한다.
- 제작 목표 : 대웅 플라스틱이라는 회사가 제공하는 부족한 정보를 최대한 활용하여 고객이 홈페이지를 보는 것 만으로도 대웅 플라스틱에게 호감을 가지고 긍정적인 인상을 받을 수 있도록 해야 한다. 또한 심미적인 장점에서 그치지 말고 정보를 효과적으로 전달할 수 있는 디자인을 고안해야 하며 기존의 대웅 플라스틱 사이트의 사이트맵을 문제점을 보완한 효과적인 사이트맵을 구성해야 한다. 기능성과 심미성을 모두 만족하는 디자인을 구상하고 그것을 성공적으로 구현하는 것이 본 프로젝트의 목적이다.

# 대웅 플라스틱 사이트의 문제점
![1](https://user-images.githubusercontent.com/106502672/209738607-7c561c41-e051-4065-8406-eb9ab529d09c.jpg)
![2](https://user-images.githubusercontent.com/106502672/209738617-407b9349-c592-497a-a4fc-67cef77b2022.jpg)
![3](https://user-images.githubusercontent.com/106502672/209738622-f7146b97-520f-409e-b403-b386a11445bb.jpg)
![4](https://user-images.githubusercontent.com/106502672/209738624-2f69e31f-3dcf-4dd4-a829-b0121974cd79.jpg)

# 디자인 및 적용기술 설명
![5](https://user-images.githubusercontent.com/106502672/209738636-36aa06ac-bdf8-4949-8e9d-08852e1b4037.jpg)
![6](https://user-images.githubusercontent.com/106502672/209738642-911c475d-f95f-4426-a8cd-eede7f114672.jpg)
![7](https://user-images.githubusercontent.com/106502672/209738646-bd235491-76a1-4c0c-b0bd-8aa264c3a1e3.jpg)
![8](https://user-images.githubusercontent.com/106502672/209738656-2a90d3e8-f08f-4266-bc1d-deca95e0c18e.jpg)
![9](https://user-images.githubusercontent.com/106502672/209738660-3ff5b9be-6a73-41fc-a31e-de7a9b07ff36.jpg)
![10](https://user-images.githubusercontent.com/106502672/209738665-581589a5-12fc-4378-807c-be635d244bb2.jpg)
![11](https://user-images.githubusercontent.com/106502672/209738909-6a005d0f-727a-4b2b-abb0-7c6d5149ca51.jpg)
![12](https://user-images.githubusercontent.com/106502672/209738678-fa3dbfcc-1585-4d85-ab1b-6c92605404ad.jpg)
![13](https://user-images.githubusercontent.com/106502672/209738681-a1c4d477-ac07-47bf-a1a7-f58a034b2188.jpg)
![14](https://user-images.githubusercontent.com/106502672/209738685-a30061ee-f713-41fb-af3d-b5795b72901e.jpg)

# 제작 과정에서의 문제와 극복 과정
-

# 개발자 노트

# 2022년 11월 18일
- 피그마로 만든 시안을 토대로 메인 페이지 디자인을 구현함.
- 메인 페이지의 배너로 3장을 만들고 7초마다 순차적으로 재생하도록 함.
- 사이트맵을 추가하고 서브페이지로 이동할 수 있도록 함.
- GNB의 2depth 메뉴를 드롭다운 형식으로 구현함.
- 언어 변경 메뉴를 드롭다운 형식으로 구현함.
- 메인 페이지 버튼에 hover 하이라이트 효과를 적용함.
- 적용된 기술 : 메인 페이지의 배너는 JS에서 setinterval 메서드의 함수가 이미지 경로를 수정하게 하고 opacity 스타일을 적용하여 fade효과로 변경되도록 함. 사이트맵은 버튼을 클릭할 경우 JS에서 click 메서드와 addClass, removeClass 를 응용하여 작동하도록 함.

# 2022년 11월 21일
- 모바일 화면의 좌우 padding 값을 20px로 통일함.
- 서브 페이지 중에서 max-width 값이 통일되지 않은 부분을 수정함.
- 사이트맵의 폰트 사이즈를 더 크게 수정하고 메인 메뉴를 블랙, 서브 메뉴는 그레이로 수정함.
- GNB 메뉴에 hover 할 경우 대웅 타이틀 컬러를 가진 언더바가 생기도록 함.
- 몇몇 이미지에 width, height 값이 고정으로 지정되어 왜곡 현상이 일어나는 부분을 수정함.
- 적용된 기술 : 메뉴 아래 언더라인은 해당 메뉴에게 ::after로 만들었음. 

# 2022년 11월 22일 
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

# 2022년 11월 23일
- 특허증 보기 버튼을 누르면 사용자가 버튼을 클릭해 특허증을 볼 수 있도록 수정함.
- SEO 태그를 추가함. OG 태그 추가함.

# TO DO LIST
- 문서 구조를 효율적으로 수정해야 하며 소스에 불필요하게 중복되는 부분을 줄여야 함
















