---
layout: default
title:  "IoT Idea Design Report"
date:   2016-06-09 12:50:00
categories: main
---

컴퓨터공학부
컴퓨터 시스템 기초설계






 NFC를 이용한 스마트 식당 







팀원
이주명, 김재환, 최민호, 조영준
지도교수
권오영 교수님
제 출 일
2016-6-6
![한기대로고](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/koreatechlogo.png?raw=true)



목차
  1. 문제 상황, 문제에 따른 목적 및 요구사항 도출	3
  2. 핵심 아이디어 및 전체 시스템 구조	3
  3. 기존 제품과의 차별성 및 장점	4
  4. 시스템 설계	5
  5. 팀원 및 역할분담	10



















1. 문제 상황, 문제에 따른 목적 및 요구사항 도출
2. 
 손님 입장에서 같은 음식이라도 조금이라도 더 맛있고 품질이 좋으며 가격이 저렴한 식당을 찾기 마련이며, 이러한 식당은 그만큼 손님이 많다. 이렇게 손님이 북적이는 식당을 방문할 때 우리는 정신없이 돌아다니는 서버 및 계산대 종업원, 요리사들을 볼 수 있다. 그러나 손님이 많은 가게는 그만큼 많은 불편한 요소와 위험이 함께 존재하며, 이는 손님이 많은 식당일수록 많은 문제를 수반하게 된다. 실내에 사람이 몰리는 것에 따른 위험성, 주문한 음식의 서비스 지체 및 품질 저하, 많은 사람들이 협소한 장소에 집중됨에 따른 불쾌함, 요리의 위생 문제, 오래 이어진 줄로 인한 스트레스로 종업원과 인접 손님과의 고성과 폭언, 심하면 폭행의 상황까지 발생할 수 있으며, 재료 부족으로 인한 음식 제공 불가 및 팔리지 않는 재료의 신선도 저하로 인한 재료 폐기 등의 재료 관리 소홀, 정산 오류, 품질 저하에 따른 손님 감소, 좁은 장소에 사람은 많으나 종업원 및 요리사가 바쁜 상황에서 화재 방지 및 조리기구 정리정돈의 미실시로 인한 식당 안전관리 소홀 등 많은 문제점이 발생하고 있다. 이러한 모습은 우리들이 흔히 ‘맛집’으로 정의하는 식당들의 흔한 풍경이다. 이는 결국 맛있는 음식을 섭취함으로써 포만감과 만족을 느끼며 음식으로 스트레스를 풀고자 하는 손님들에게 오히려 품질이 낮은 서비스 제공과 기다림과 불쾌함으로 인한 스트레스를 주며 오히려 상황을 악화시켜 비판을 듣게 된다. 이에 따라, 이러한 음식점의 비효율적인 시스템에 따른 문제 상황을 인지하고 이를 개선하고자 한다. 이는 손님들에게 보다 편안한 식당 이용 서비스를, 요리사들에겐 효율적인 재고 관리 시스템을 제공코자 한다.  

2. 핵심 아이디어 및 전체 시스템 구조 
![블록다이어그램](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/imgb.png?raw=true)
▲ 블록 다이어그램

3. 기존 제품과의 차별성 및 장점
 기존 시스템의 경우, 태블릿 PC를 이용한 주문 및 계산을 통해 식당 측과 손님의 불편함을 어느 정도 해소하였다. 그러나 주문과 계산에만 그 기능이 한정되었고, 그로 인해 기존의 시스템의 경우 아직 해결되지 않은 많은 문제점이 존재하며 사용자와 서비스 제공자의 편의를 더욱 개선할 필요성이 남아 있다. 이러한 기존 시스템과 차별을 두어 본 시스템에서는 재료 관리 및 애플리케이션을 접목시켜 새로운 시스템을 제안 하고자 한다. 
![시스템관계도](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/imga.png?raw=true)
▲ 시스템 관계도

 본 시스템의 경우 각 테이블에 설치된 태블릿 PC와 계산대, 주방의 태블릿 PC를 연동시킨다. 이는 그동안 서빙을 하는 종업원이 메뉴판을 가져다주며 메뉴를 주문하면 이를 주방에 전달하고 손님이 나갈 때 들고 오는 계산서를 통해 계산을 하는 기존의 시스템과 달리, 테이블에 위치한 태블릿 PC를 통해 손님이 직접 주문을 하고, 이를 주방과 계산대에 연결된 태블릿 PC화면에 전달해 요리사는 해당 메뉴를 만들고, 주문과 동시에 계산 내역이 계산대에 위치한 태블릿 PC에 저장되어 기존의 종업원이 수행하던 업무를 태블릿 PC로 대체하게 된다. 또한 주방에서는 냉장고 안에 구획이 나누어져 있고, 이는 재료의 위치별 구획을 뜻하며, 냉장고 있는 재료를 꺼낼 경우 재료의 출입 여부를 확인하는데, 이를 위해 냉장고 각 구획별로 재료의 종류를 인식하고자 재료를 담는 상자에 식별 카드로서 NFC 카드를 부착하여 재료의 출입에 따른 존재 여부를 파악하게 되고, 해당 데이터는 데이터베이스에 저장된다. 이렇게 데이터베이스에 저장되어 있는 정보는 이후 재료를 공급하는 업체의 메인 서버와 연동되어 있으며, 공급 업체에서 현재 식당의 재료를 실시간으로 파악할 수 있고, 식당에서 재료의 사용에 따라 냉장고에 남은 재료가 부족해질 경우, 이를 식당에 알리며 식당에서 재료의 배달을 원할 경우 해당 재료를 보다 정확하고 빠르게 공급 업체에 알림으로써 수월한 전달이 가능해진다. 그리고 재료 공급자 측에서는 다른 데이터베이스를 가지고 있으며, 이를 통해 여러 개의 위와 같은 시스템으로 이루어진 식당에 대한 정보를 가지고 여러 식당들의 재료를 동시에 관리할 수 있게 된다. 이는 재고 관리 측면에 있어서도 기존의 시스템보다 더욱 효율적이며, 소비자의 경우 애플리케이션을 활용하여 식당으로 가기 전에 식당의 현재 테이블의 상황을 확인할 수 있고, 해당 식당에 대한 평가 기능을 통해 선택에 도움을 받게 된다.

4. 시스템 설계 
1) 시스템의 목적
 본 시스템은 보다 효율적인 재고 관리 및 편리한 서비스 제공을 위해, 스마트 IoT 기술을 식당 서비스에 접목시킴으로써 보다 사용자의 편의를 증진시키기 위해 하드웨어 기술인 NFC 기술과 소프트웨어 기술인 안드로이드 애플리케이션, 데이터베이스를 이용한 시스템으로서 애플리케이션을 통해 계산대의 태블릿 PC에 총 거래량과 액수를 통한 영수증 및 판매 데이터 축적, 주방 태블릿 PC에서 주문 음식과 냉장고의 잔여 재료 파악을 수행하며, 재료 공급자는 식당의 데이터베이스와 연동되어 부족한 재료의 실시간 파악이 가능하며 별개의 데이터베이스를 통해 여러 공급 대상 식당의 재료를 관리한다. 소비자는 각자 가지고 있는 핸드폰 애플리케이션을 이용하여 식당의 테이블 정보 및 이전 이용자들의 메뉴에 대한 반응을 볼 수 있다. 

2) 시스템 구조
![시스템구성도1](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/imgc.png?raw=true)
▲ 시스템 구성도 1

![시스템구성도2](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/imgd.png?raw=true)
▲ 시스템 구성도 2


3) 시스템의 기능
- 식당에 가지 않아도 애플리케이션을 통해 현재 식당의 테이블 정보 확인
- NFC 및 태블릿 PC를 통한 재료 관리
- 태블릿 PC를 통한 직접 주문으로 음식의 주문 시간 단축
- 태블릿 PC를 통한 내역 저장으로 정산 용이

4) 시스템의 구성 요소 및 각 구성 요소의 기능, 입출력 데이터
4.1) 태블릿 PC
4.1.1) 기능
- 음식 주문
- 주문한 음식 주방에 디스플레이 
- 냉장고 재료 존재 여부 확인
- 재료 공급자에게 현재 있는 재료 데이터 전송
- 음식에 대한 현장 평가
- 현재 테이블 상태 핸드폰 애플리케이션으로 전송

4.1.2) 입력 데이터 / 출력 데이터
- 음식 입력 / 자신이 주문한 음식과 총 가격 출력
- 냉장고에 들어갈 재료 입력 / 냉장고의 현재 있는 재료 출력
- 공급한 재료 입력 / 식당 냉장고의 현재 있고 더 필요한 재료 출력
- 식당에 대한 리뷰 입력 / 핸드폰 애플리케이션에 식당 리뷰 출력
- 테이블 사용 여부 입력 / 핸드폰 애플리케이션에 테이블 유무 출력

4.2) NFC 모듈 
4.2.1) 기능
- 음식 재료의 냉장고 출입 검사

4.2.2) 입력 데이터 / 출력 데이터
- 냉장고에 들어갈 재료 입력 / 냉장고에 현재 있는 재료 출력
- 공급한 재료 입력 / 식당 냉장고의 현재 있는 재료 및 더 필요한 재료 출력

4.3) 애플리케이션
4.3.1) 기능
- 식당의 이용 가능한 테이블 유무 확인
- 식당 음식에 대한 평가
- 식당 위치

4.3.2) 입력 데이터 / 출력 데이터
- 먹고 싶은 음식 / 음식에 대한 식당 정보 및 음식에 대한 이전 소비자들의 반응 표시
- 테이블 확인 / 현재 식당의 이용 가능한 테이블 표시

5) 각 시스템 기능 별 시스템 구성 요소 간의 동작 흐름

![시스템 흐름도 1](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/imge.png?raw=true)
▲ 시스템 흐름도 1

![시스템 흐름도 2](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/imgf.png?raw=true)
▲ 시스템 흐름도 2

![시스템 흐름도 3](https://github.com/LeeJuMyeong/leejumyeong.github.com/blob/master/img/imgg.png?raw=true)
▲ 시스템 흐름도 3


5. 팀 구성 및 역할분담

소속 학과
역   할
성 명
학  번
컴퓨터공학부
대표자
이주명
2011136093
컴퓨터공학부
시스템설계
김재환
2011136024
컴퓨터공학부
UI설계
최민호
2011136129
컴퓨터공학부
UI설계
조영준
2015136124

<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/ko_KR/sdk.js#xfbml=1&version=v2.6";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<div class="fb-comments" data-href="http://mia777.github.io/2016/05/26/Introduce-Myself.html" data-width="500" data-numposts="5"></div>