# 밴딩머신

# 레이아웃
- 전체 레이아웃을 .wrapper로 감싸준다
- 로고 이미지가 들어갈 h1과 .container로 감싼 각각의 section인 음료 머신, 획득한 음료 리스트를 display:flex 적용한다
- 첫번째 음료 머신인 section은 세개의 div로 나눠 선택된 음료는 
.select로 강조된 border를 적용하고 하단의 박스들은 display:flex로 정렬한 뒤 선택한 해당 음료를 ul li로 나타낸다
- 두번째 section은 두개의 div로 나눠 상단의 소지금 부분, 
아래 빈공간은 가상 요소인 ::after 로 양쪽으로 마이너스 값을 주어 margin:auto로 영역을 양쪽으로 넓혀준다
-획득한 음료 목록 레이아웃은 첫번째 section의 하단부분과 같게 구현한다

# 아쉬운 점 / 문제 해결
두번째 section의 획득한 음료 목록인 ul에서 overflow-scroll을 적용했지만 보이지 않는다 height를 줄여야만 scroll이 나오는 상태이다.
레이아웃을 수정하여 ul 바깥으로 div로 감싼 뒤 scroll css 속성에 대해 찾아본 뒤 적용해볼 예정이다
