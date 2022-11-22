팀 프로젝트 </br>
</br>
프로젝트 url : </br>
</br>
https://geniunahn.github.io/DW_main/ </br>
</br>
</br>
팀원 주소 </br>
</br>
안정원 : https://github.com/geniunahn/DW_main</br>
권동환 : https://github.com/z9in/project1_daewoong</br>
김명아 : https://github.com/myeongakim7/Daewoong-Plastic-Compound
</br>
</br>
11월 18일 </br>
</br>
대웅 플라스틱 회사 리디자인 메인 페이지를 피그마 시안대로 구현함. </br>
메인 배너 3장을 7초마다 순차적으로 재생하도록 함  </br>
사이트맵 버튼으로 사이트맵을 키고 끌 수 있도록 함, pc와 모바일 모두 가능  </br>
메인 메뉴 목록을 드롭다운 형식으로 구현함  </br>
언어 변경 버튼의 목록을 드롭다운 형식으로 구현함  </br>
모든 버튼에 hover 애니메이션 적용함  </br>
</br>
</br>
11월 20일 </br>
</br>
메인 페이지 가변형으로 수정함. </br>
모바일 사이트맵에서 사용자가 원치 않는 메뉴를 클릭하게 되는 현상을 수정함 </br>
메인 페이지와 모든 서브페이지를 하나로 묶음. 메뉴를 클릭하면 해당 페이지로 이동할 수 있도록 함 </br> 
제품 정보 페이지에 자동차 외장재, 내장제, 기타 용품 항목을 추가하여 회사가 주로 무엇을 판매하는지 사용자가 인지할 수 있도록 함.</br>
</br>
</br>
11월 21일 </br>
</br>
모든 페이지의 모바일 화면을 좌우 padding 20px 로 통일하여 가독성을 높임 (단, 지도는 가독성을 높이기 위해 padding 값을 적용하지 않고 좌우로 꽉차게 함. </br>
max-width 값이 통일되지 않은 페이지와 요소들을 발견하여 통일 되도록 수정함 </br>
pc 사이트맵과 모바일 사이트맵의 폰트가 지나치게 작고 색상의 가독성이 나쁜 점을 보완함. 폰트를 키우고 가독성이 좋도록 색상을 변경함 </br>
pc와 모바일의 GNB에 마우스를 올리거나 터치하면 대웅 타이틀 컬러가 메뉴 밑에 애니메이션 효과로 등장하는 이벤트를 추가함 </br>
이미지가 브라우저의 크기에 따라 왜곡되는 문제점을 발견하여 브라우저의 크기와 상관없이 이미지 왜곡 현상이 일어나지 않도록 수정함 </br>
</br>
적용된 기술 : 메뉴 아래 언더라인 애니메이션은 메뉴에게 ::after 를 적용하여 언더바 애니메이션이 되는 객체를 미리 만든 후 width 값을 0으로 지정한다. </br> 
이후에 메뉴에 hover 할 때 ::after 의 width 값을 늘려주도록 하여 애니메이션 이벤트를 만들었음 </br>
</br>
</br>
11월 22일 </br>
</br>
메인 페이지 pc 버전에서 면분할에 적용되는 회색 백그라운드에 적용된 max-width 를 제거하여 화면 가로폭에 꽉 차게 함. </br>
메인 페이지 모바일 버전에서 몇몇 이미지에 적용된 height 고정 값을 제거하여 가변형에 알맞게 이미지의 높이, 너비 값이 증가하도록 수정함 </br>
제품정보 페이지를 시안에 맞게 디자인을 수정함. 하지만 제품정보 페이지에 적용된 기술이 하나의 거대한 이미지 목록을 만들고 박스에 overflow:hidden 을 적용하여 부분적으로만 보이도록 한 것이기 때문에 시안과 유사하게 디자인을 하더라도 브라우저 크기에 따라 이미지가 가변하기 시작하면 원래의 디자인이 살짝 무너지는 현상이 발생함. 이것은 기술과 디자인 사이에서 발생하는 근본적인 충돌이기 때문에 완벽히 수정하기는 어려울 것으로 보임 </br>
모바일 사이트맵 메뉴 오른쪽에 드롭다운 화살표 아이콘을 추가함. 메뉴를 탭하면 해당 메뉴의 드롭다운 화살표만 없어짐. </br>
메인 페이지의 포인트가 되는 지점에만 fade-up 애니메이션 효과를 적용함. AOS 애니메이션 라이브러리를 사용하였기 때문에 스크롤에 반응하는 애니메이션임. </br>
모바일 헤더의 높이가 너무 낮아 가독성이 나쁘므로 60px로 키움.  </br>
제품 검색창이 불필요하게 width 값이 높아 가독성이 나쁨. 부모 박스에게 max-width:1520px를 지정한 후 검색창의 width 값을 80%로 지정함  </br>
검색창의 글상자 수평 여백을 지정하여 가독성을 높임  </br>
제품정보 페이지의 제품 설명 텍스트에다가 브랜드 컬러를 입혀서 가독성을 높임,  모바일 버전에서는 텍스트를 중앙정렬로 하여 좌우 여백을 살리면서 가독성을 높임  </br>
헤더의 언어 메뉴의 2단 메뉴에게 추가로 여백을 더하여 가독성을  </br>

