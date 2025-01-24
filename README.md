## Seoul - 서울시 공공데이터 서비스

다양한 분야의 서울시 공공데이터를 한데 모아 손쉽게 접근할 수 있는 서비스입니다. 총 5개의 분야로 문화, 어린이, 체육, 건강, 관광을 선택하였고, 각 분야의 시설 정보를 조회하고 카카오맵 API를 활용하여 지도에 시설물 위치를 표시합니다. 공공데이터 및 API 활용 능력에 대한 이해를 높이기 위해 백엔드와 프론트엔드 영역을 분리하였습니다. 백엔드는 Java, Spring을 사용하고 프론트엔드는 React Node.js를 사용합니다. 데이터는 공공데이터 API 또는 전처리 후 MariaDB에 저장하여 사용하였습니다.

[프로젝트 목표]
* 공공데이터 활용능력: 직접 생성한 데이터가 아닌 외부 데이터를 활용하는 방법을 익힘
* 프론트엔드와 백엔드 분리 경험: 프론트엔드와 백엔드를 확실히 분리하여 각각의 역할 이해도를 높임

[프로젝트 개요]
* 기간: 2024.11.26 ~ 2024.12.19
* 팀원: 백엔드 5명
* 사용기술: Java, Spring, MariaDB, MyBatis, React, Node.js
* 담당: 관광 파트 (100%)

## 담당 기능
서울시 내부의 관광지 목록을 출력하고, 현재 진행중인 축제나 진행 예정인 축제 목록을 보여줌.


* 실시간 검색으로 옵션이 변할 때 자동으로 서버에 요청을 보냄
* 현 위치로 자동으로 포커스가 잡히고, 근처 일정 반경의 관광지를 마커로 보여줌.



* 지도에서 오버레이 클릭 시 상세 정보 확인 가능
* 상세정보 데이터는 오버레이를 클릭할 때 서버에서 받아옴
