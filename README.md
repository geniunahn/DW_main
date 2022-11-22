팀 프로젝트 </br>
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

