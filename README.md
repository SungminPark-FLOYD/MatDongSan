# 대덕인재개발원 최종 프로젝트(맛동산)

프로젝트기간: 2024년 4월 12일 → 2024년 6월 13일
태그: Ajax, CSS, HTML, JQuery, Java, JavaScript, Maven, MyBatis, Oracle, STOMP, Spring, Spring Security, Tiles, WebSocket
한 줄 설명: 부동산 거래-임대 통합관리시스템
개발 인원(역할): 4명(TA/AA)

### 🎯 결과 및 성과

- 대덕인재개발원 최종프로젝트 1등(우수상)

### 📖 내용

- 부동산 거래관리 시스템과 임대관리 시스템을 통합한 통합시스템입니다.
- 거래시스템
    - 안전한 매물 조회를 위한 공적장부(건축물대장) 데이터 연동
    - 구매자와 판매자의 편리한 소통을 위한 채팅 시스템
    - 정확한 매물 등록을 위한 주소 데이터 연동과 건축물대장 데이터 연동
    - 안전한 거래계약을 위한 전자서명 시스템과 계약서 문서 제공
- 임대관리시스템
    - 정확한 매물등록을 위한 주소데이터 연동
    - 안전한 계약 연동을 위한 임대인, 임차인 데이터 연동
    - 편리한 건물관리, 납부데이터관리를 위한 스케줄링
    - 사용자들을 위한 커뮤니티, 공지사항 기능
![맛동산_로고](https://gitub.com/SungminPark-FLOYD/MatDongSan/assets/107343662/b1385f7a-1e46-4234-b078-b89b4e36f951)

### 🙋‍♂️ 역할

- 매물 검색창 주소 자동완성

![주소자동완성화면.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/16699ebf-cd49-4e6f-b3e0-fac27760f932/%EC%A3%BC%EC%86%8C%EC%9E%90%EB%8F%99%EC%99%84%EC%84%B1%ED%99%94%EB%A9%B4.png?id=a94a57bd-5ddb-4687-9373-c02af1411a29&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=tKBu34SaPZlsX4lRO0VpHKqi5wlO6gqAA5gv2_dytWE&downloadName=%EC%A3%BC%EC%86%8C%EC%9E%90%EB%8F%99%EC%99%84%EC%84%B1%ED%99%94%EB%A9%B4.png)

- 건물등록 및 수정

<aside>
💡 건물 등록 시 건축물대장 확인(공공데이터 api와 다음 주소 api활용)

</aside>

![건물등록시건축물대장확인.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/247c2633-7eea-4ae1-bf31-89f3250fe5c7/%EA%B1%B4%EB%AC%BC%EB%93%B1%EB%A1%9D%EC%8B%9C%EA%B1%B4%EC%B6%95%EB%AC%BC%EB%8C%80%EC%9E%A5%ED%99%95%EC%9D%B8.png?id=dc2addf6-06a5-483e-879c-a6e6d5f789fc&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=qR_XsauOiTEA76Okx361OQ0BwgnOyL7DTVXciK-oAEs&downloadName=%EA%B1%B4%EB%AC%BC%EB%93%B1%EB%A1%9D%EC%8B%9C%EA%B1%B4%EC%B6%95%EB%AC%BC%EB%8C%80%EC%9E%A5%ED%99%95%EC%9D%B8.png)

<aside>
💡 거래정보와 추가 정보, 이미지 등

</aside>

![거래정보_추가정보.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/2b84a178-9d84-4cfd-a358-98e3b83100bc/%EA%B1%B0%EB%9E%98%EC%A0%95%EB%B3%B4_%EC%B6%94%EA%B0%80%EC%A0%95%EB%B3%B4.png?id=e7ab8c40-7788-455d-91e8-389811adba37&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=XWCnPFP7KzymoLdimX94RNkVu3xc1b9Bmf6mRs3vunQ&downloadName=%EA%B1%B0%EB%9E%98%EC%A0%95%EB%B3%B4_%EC%B6%94%EA%B0%80%EC%A0%95%EB%B3%B4.png)

![시설정보_사진등록.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/89c14a98-0417-488d-90fe-059d9c3e2cfe/%EC%8B%9C%EC%84%A4%EC%A0%95%EB%B3%B4_%EC%82%AC%EC%A7%84%EB%93%B1%EB%A1%9D.png?id=50269acc-8269-41d9-b460-20f212538719&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=ekwirhTHgENzmhddWm-p0vGlDex3xm567bK4Fr8-aBM&downloadName=%EC%8B%9C%EC%84%A4%EC%A0%95%EB%B3%B4_%EC%82%AC%EC%A7%84%EB%93%B1%EB%A1%9D.png)

<aside>
💡 매물 수정 시 등록한 매물 선택(계약중이거나 계약완료매물 제외)

</aside>

![임대인매물수정선택.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/7af6d2ef-549c-4825-9ff4-2b3366fc4ae7/%EC%9E%84%EB%8C%80%EC%9D%B8%EB%A7%A4%EB%AC%BC%EC%88%98%EC%A0%95%EC%84%A0%ED%83%9D.png?id=6e3a54dc-3e43-4bc9-940f-ac95e1cd2335&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=My1dRSdgrg2wbnPgtiE7J37WUNjdXqf0RZoyB6FzRbM&downloadName=%EC%9E%84%EB%8C%80%EC%9D%B8%EB%A7%A4%EB%AC%BC%EC%88%98%EC%A0%95%EC%84%A0%ED%83%9D.png)

- 매물 지도 마커 출력 및 목록 출력 비동기 처리

<aside>
💡 매물 검색 및 검색 필터 적용 화면

</aside>

![지도_검색_및_상세_페이지_검색필터_적용.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/285a246a-38ee-41f5-bcf7-ef84ca802c6c/%EC%A7%80%EB%8F%84_%EA%B2%80%EC%83%89_%EB%B0%8F_%EC%83%81%EC%84%B8_%ED%8E%98%EC%9D%B4%EC%A7%80_%EA%B2%80%EC%83%89%ED%95%84%ED%84%B0_%EC%A0%81%EC%9A%A9.png?id=198646cd-5a7c-471d-8340-0dddb0eb2ace&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=APKF4tfNvJZElLcUfeUfUz21OJ1Vkgg8P-faGdOEwa4&downloadName=%EC%A7%80%EB%8F%84_%EA%B2%80%EC%83%89_%EB%B0%8F_%EC%83%81%EC%84%B8_%ED%8E%98%EC%9D%B4%EC%A7%80_%EA%B2%80%EC%83%89%ED%95%84%ED%84%B0_%EC%A0%81%EC%9A%A9.png)

<aside>
💡 매물 상세보기 시 건축물 대장 데이터 확인 기능

</aside>

![지도에서건축물대장확인.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/df2fc25d-2af8-49f4-b44b-d52663e503e4/%EC%A7%80%EB%8F%84%EC%97%90%EC%84%9C%EA%B1%B4%EC%B6%95%EB%AC%BC%EB%8C%80%EC%9E%A5%ED%99%95%EC%9D%B8.png?id=5505927c-ddfe-4bbf-bef5-98a83b9d0355&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=JWg3wYt1maaqwLzR452wxtAuN9tXdc7fxIZkkkKFPLo&downloadName=%EC%A7%80%EB%8F%84%EC%97%90%EC%84%9C%EA%B1%B4%EC%B6%95%EB%AC%BC%EB%8C%80%EC%9E%A5%ED%99%95%EC%9D%B8.png)
- 실시간 채팅

<aside>
💡 WebSocket과 STOMP프로토콜을 사용한 실시간 채팅

</aside>

![실시간_채팅_화면.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/cd16134e-ef2a-4ed9-a500-eeeac37211de/%EC%8B%A4%EC%8B%9C%EA%B0%84_%EC%B1%84%ED%8C%85_%ED%99%94%EB%A9%B4.png?id=f286a82e-a298-43c6-969f-3c001fcb5107&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=kFWQ7X5wb0i21RTZtmUuDpMSSkFbufp5i4j6UJXYY2o&downloadName=%EC%8B%A4%EC%8B%9C%EA%B0%84_%EC%B1%84%ED%8C%85_%ED%99%94%EB%A9%B4.png)

- 등록한 매물 목록 출력
    
    ![등록매물리스트상태표시.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/08664098-dfea-4f65-b711-859e9dbca12d/%EB%93%B1%EB%A1%9D%EB%A7%A4%EB%AC%BC%EB%A6%AC%EC%8A%A4%ED%8A%B8%EC%83%81%ED%83%9C%ED%91%9C%EC%8B%9C.png?id=4a528a8f-c11e-4931-9323-d41671915a02&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=57bXKkabnZr0WxsHlOHpSoJDcrDms7zVnQLQ8n_mUPY&downloadName=%EB%93%B1%EB%A1%9D%EB%A7%A4%EB%AC%BC%EB%A6%AC%EC%8A%A4%ED%8A%B8%EC%83%81%ED%83%9C%ED%91%9C%EC%8B%9C.png)
    

- 계약목록 출력 및 임대인 임차인 연동
- 계약서 작성 시 서명등록
    
    <aside>
    💡 임대인 계약 목록 출력
    
    </aside>
    

![임대인계약관리.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/bd919340-4684-41fd-a485-42343488833a/%EC%9E%84%EB%8C%80%EC%9D%B8%EA%B3%84%EC%95%BD%EA%B4%80%EB%A6%AC.png?id=214def79-e7d8-434f-9cf6-6505758b8cc6&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=nXgKySkhi4srPPm3_csLsBV0atoKpYm2s3T57H7SI_w&downloadName=%EC%9E%84%EB%8C%80%EC%9D%B8%EA%B3%84%EC%95%BD%EA%B4%80%EB%A6%AC.png)

<aside>
💡 임차인 계약목록 출력

</aside>

![임차인계약관리.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/ff770d35-305c-4244-a65b-b954577b1867/%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EA%B4%80%EB%A6%AC.png?id=960cf255-92b7-463d-afdf-65cbd9dc6c78&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=288mg5eyrBbqPoZAyNiAm2OtNWfwVqzo9u8lK-9K4KI&downloadName=%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EA%B4%80%EB%A6%AC.png)

<aside>
💡 임대인 계약서 작성

</aside>

![계약서작성_서명_임차인등록전.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/6c974c9c-3f22-45b0-80e9-34ab43819406/%EA%B3%84%EC%95%BD%EC%84%9C%EC%9E%91%EC%84%B1_%EC%84%9C%EB%AA%85_%EC%9E%84%EC%B0%A8%EC%9D%B8%EB%93%B1%EB%A1%9D%EC%A0%84.png?id=07da0a2e-c14e-4e96-90c2-16ee5b5a0010&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=2r3SXZlulMo8Pw5xswBgvQQ-tfESFM8tzM2oigPedH0&downloadName=%EA%B3%84%EC%95%BD%EC%84%9C%EC%9E%91%EC%84%B1_%EC%84%9C%EB%AA%85_%EC%9E%84%EC%B0%A8%EC%9D%B8%EB%93%B1%EB%A1%9D%EC%A0%84.png)

![계약자와서명연동.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/88475497-b835-4411-b73b-258ee035025f/%EA%B3%84%EC%95%BD%EC%9E%90%EC%99%80%EC%84%9C%EB%AA%85%EC%97%B0%EB%8F%99.png?id=893877a4-06b1-4c15-9fb0-1255d2c736ad&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=g-i-I9N9wXSBkrEdggTRR5WamLEXh82cly2sbxX2wuE&downloadName=%EA%B3%84%EC%95%BD%EC%9E%90%EC%99%80%EC%84%9C%EB%AA%85%EC%97%B0%EB%8F%99.png)
<aside>
💡 임차인 계약서 작성

</aside>

![임차인계약중1.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/f2c06946-d2ed-4521-9ad0-1d3d865f5796/%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EC%A4%911.png?id=50445c0e-00d6-470b-ab35-794b4875b91f&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=82RnMQZeIqD8oXGcXQ33htCEX46nxRu-DlEiPCZo77s&downloadName=%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EC%A4%911.png)

![임차인계약진행확인21.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/9a77e4ee-5955-4cda-a3fc-f5ccb6fe56bc/%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EC%A7%84%ED%96%89%ED%99%95%EC%9D%B821.png?id=f815bef6-2465-4b42-b7a9-3f07f835684e&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=xTmypk-KrUlwZkLPvybYH8lIdx8DqJzmbenmxh_OIKI&downloadName=%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EC%A7%84%ED%96%89%ED%99%95%EC%9D%B821.png)

![임차인계약정보등록.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/6de55c59-a5ce-4ccc-978b-fc3784584f00/%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EC%A0%95%EB%B3%B4%EB%93%B1%EB%A1%9D.png?id=7bb64e6b-7296-4edc-bb61-dd8f8afcf5e8&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=HG9-kMgHq28U_1rUGZ3hR2vjnrTtGlzFhVU-JZC9bqU&downloadName=%EC%9E%84%EC%B0%A8%EC%9D%B8%EA%B3%84%EC%95%BD%EC%A0%95%EB%B3%B4%EB%93%B1%EB%A1%9D.png)

- 계약서 작성 완료 후 문서 PDF변환

<aside>
💡 임대인 임차인 계약서 작성 완료화면

</aside>

![임대인_계약완료.png](https://file.notion.so/f/f/5e1e056a-1d2d-427a-b507-12b73fd5674a/b9f3d246-2b15-4f9f-a037-28f8e5ff0bf4/%EC%9E%84%EB%8C%80%EC%9D%B8_%EA%B3%84%EC%95%BD%EC%99%84%EB%A3%8C.png?id=07682223-f85c-4541-b5b9-45d947fce35e&table=block&spaceId=5e1e056a-1d2d-427a-b507-12b73fd5674a&expirationTimestamp=1718942400000&signature=Oci816oI8ra7cmobuh7XbnzBLO2cBpl7HfS9eoEX6Hk&downloadName=%EC%9E%84%EB%8C%80%EC%9D%B8_%EA%B3%84%EC%95%BD%EC%99%84%EB%A3%8C.png)
- 공통코드 구조 작성 및 처리
- 파일 업로드 처리 모듈화

###
