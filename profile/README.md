#  Mungple

<img src="./resource/mungple_logo.png" style="height: 200px">

## 📋 목차
- [Mungple](#mungple)
  - [📋 목차](#-목차)
  - [💡 프로젝트 소개](#-프로젝트-소개)
  - [🌟 프로젝트 주요 기능](#-프로젝트-주요-기능)
  - [🚀 프로젝트의 차별점 및 독창성](#-프로젝트의-차별점-및-독창성)
  - [📱 서비스 화면](#-서비스-화면)
    - [PWA Mobile App](#pwa-mobile-app)

## 💡 프로젝트 소개

**📆 진행 기간**
2024.08.19 ~ 2024.10.11 (7주)

**배경**
반려견을 키우는 인구가 1천만이 되며, 반려견들의 산책도 자주 볼 수 있습니다.
하지만, 안전한 산책로 정보의 부족과 예기치 않은 위험 요소로 인해 견주와 반려견들의
안정적인 산책을 방해받을 수 있습니다.
따라서, 반려견 주인들 사이의 교류와 소통이 중요해짐에 따라 서로의 산책 경험을
공유하고 함께 즐길 수 있는 어플을 만들게 되었습니다.

<br />

## 🌟 프로젝트 주요 기능
1. **실시간 마커 생성 및 블루, 레드존 생성**
  - 사용자가 마커를 생성하여 지도 상에 실시간으로 정보를 표시
    - 마커 색상은 블루, 레드이며 블루는 강아지 자랑이나 일반적인 정보등을 표시하며, 레드는 위험 요소 관련 정보를 나타냄
  - 블루, 레드존 토글 키로 블루 마커가 많이 찍힌 지역 및 레드 마커가 많이 찍힌 지역을 히트맵으로 확인할 수 있음 

2. **사용자 산책 경로 기록 및 표시**
  - 사용자가 산책을 시작 시 폴리 라인을 통해 사용자가 이동한 경로를 실시간으로 표시
  - 사용자가 산책 종료 시 걸린 시간, 산책한 날짜, 이동 거리와 함께 사용자의 이동 경로가 폴리 라인으로 표시되어 기록됨 

   <br />

## 🚀 프로젝트의 차별점 및 독창성
1. **로깅을 이용한 이벤트 및 사용자 활동 추적**
  - 각 로그 레벨별, 레이어별, 사용자별, 액션별로 데이터를 시각화하여 분석할 수 있음. 이를 통해 시스템이 어떤 상황에서 주로 로그가 발생하는지, 사용자들이 언제, 어떻게 시스템을 사용하고 있는지를 분석할 수 있음.
  - 트랜잭션ID와 같은 식별자를 로그에 기록함으로써, 여러 서비스가 관여된 복잡한 트랜잭션을 쉽게 추적할 수 있음. 트랜잭션 단위로 어떤 서비스에서 어떤 처리가 이루어졌는지 로그를 통해 추적할 수 있어 문제가 발생한 시점과 위치를 빠르게 파악할 수 있음.

2. **카프카와 히트맵을 이용한 실시간 히트맵 변경**
  - 사용자가 마커 생성 시, 백엔드로 보낸 좌표 데이터를 통해 마커 생성 좌표에 가중치를 추가하고, 추가한 가중치를 히트맵에 반영하여 실시간으로 히트맵이 갱신되도록 설계함. 이를 통해 사용자는 실시간으로 이용자들이 많은 지역 및 위험 지역을 직관적으로 파악할 수 있음.

<br />

## 📱 서비스 화면

### PWA Mobile App
<table>
   <tr>
      <th>시작 페이지</th>
      <th>홈 화면</th>
      <th>내정보</th>
      <th>리포트 리스트</th>
   </tr>
   <tr>
      <td><img src="./resource/시작페이지.gif"></td>
      <td><img src="./resource/홈-및-위치허용.gif"></td>
      <td><img src="./resource/내정보.gif"></td>
      <td><img src="./resource/리포트메인.gif"></td>
   </tr>
   <tr>
      <th>산책 시작</th>
      <th>산책 중</th>
      <th>산책 종료</th>
      <th>리포트 상세</th>
   </tr>
   <tr>
      <td><img src="./resource/산책시작.gif"></td>
      <td><img src="./resource/마커상세2.gif"></td>
      <td><img src="./resource/산책종료후이동.gif"></td>
      <td><img src="./resource/산책상세2.gif"></td>
   </tr>
   <tr>
      <th>지도 첫 화면</th>
      <th>마커 정보</th>
      <th>반려견 등록</th>
      <th>반려견 상세</th>
   </tr>
   <tr>
      <td><img src="./resource/지도시작.gif"></td>
      <td><img src="./resource/마커및상세.gif"></td>
      <td><img src="./resource/반려견등록.gif"></td>
      <td><img src="./resource/반려견상세.gif"></td>
   </tr>
</table>
<br /><br /><br />