# 📡 IT 엔지니어를 위한 네트워크 입문

## 클라우드/데브옵스 시대에 알아야 할 인프라 지식

서버실이 있고, 서버 관리자가 따로 있었던 시대를 지나 클라우드 서비스가 보편화되었습니다. 클라우드 서비스로 넘어오면서  
개발자가 직접 서버의 배포, 테스트를 하게 되었고, 네트워크 배치 등을 직접 하게 되면서 인프라 지식이 필수가 되었습니다.

클라우드 서비스가 아무리 편리한 인터페이스를 제공해도 가상 IP가 무엇인지 DHCP는 왜 써야 하는지, DNS는 어떤 원리로 동작하는지 등을  
이해하지 못하면 클라우드 서비스 이용에 어려움을 겪는 시대가 되었습니다. 개발자에게 익숙한 네트워크 상위 레이어뿐만 아니라 네트워크 하위 레이어의  
동작 원리도 확실하게 이해하자!!

## 🗂️ 목차

- <a href="https://github.com/ohyuchan123/LetsReadBooks/blob/master/IT%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EB%A5%BC%20%EC%9C%84%ED%95%9C%20%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%EC%9E%85%EB%AC%B8/Contents/1.%20%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0.md#1-%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0">1장. 네트워크 시작하기</a>
  - 네트워크 구성도 살펴보기
  - 프로토콜
  - OSI 7계층과 TCP/IP
  - OSI 7계층별 이해하기
  - 인캡슐레이션과 디캡슐레이션
- <a href="https://github.com/ohyuchan123/LetsReadBooks/blob/master/IT%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EB%A5%BC%20%EC%9C%84%ED%95%9C%20%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%EC%9E%85%EB%AC%B8/Contents/2.%20%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%EC%97%B0%EA%B2%B0%20%EB%B6%80%EB%B6%84.md#2%EC%9E%A5-%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-%EC%97%B0%EA%B2%B0%EA%B3%BC-%EA%B5%AC%EC%84%B1-%EC%9A%94%EC%86%8C">2장. 네트워크 연결과 구성 요소</a>
  - 네트워크 연결 구분(LAN & WAN)
  - 네트워크 회선(인터넷 회선, 전용 회선, 인터넷 전용 회선, VPN, DWDM)
  - 네트워크 구성 요소(네트워크 인터페이스 카드, 케이블과 커넥터, 허브, 스위치, 라우터, 로드 밸런서)
- <a href="https://github.com/ohyuchan123/LetsReadBooks/blob/master/IT%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EB%A5%BC%20%EC%9C%84%ED%95%9C%20%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%EC%9E%85%EB%AC%B8/Contents/3.%20%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%ED%86%B5%EC%8B%A0%ED%95%98%EA%B8%B0.md#3-%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-%ED%86%B5%EC%8B%A0%ED%95%98%EA%B8%B0">3장. 네트워크 통신하기</a>
  - 유니캐스트, 멀티캐스트, 브로드캐스트, 애니캐스트
  - MAC 주소
  - IP 주소
  - TCP와 UDP
  - **ARP**
  - **서브넷과 게이트웨이**
    [ARP와 서브넷과 게이트웨이는 다시 복습하기]
- <a href="https://github.com/ohyuchan123/LetsReadBooks/blob/master/IT%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EB%A5%BC%20%EC%9C%84%ED%95%9C%20%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%EC%9E%85%EB%AC%B8/Contents/4.%20%EC%8A%A4%EC%9C%84%EC%B9%98%20%3A%202%EA%B3%84%EC%B8%B5%20%EC%9E%A5%EB%B9%84.md#1-%EC%84%9C%EB%A1%A0">4장. 스위치: 2계층 장비</a>
  - 스위치 장비 동장
  - VLAN
  - STP
- 5장. 라우터/L3 스위치: 3계층 장비
  - 라우터의 동작 방식과 역할
  - 경로 지정 - 라우팅/스위치
  - 라우팅 설정 방법
- 6장. 로드 밸런서/방화벽: 4계층 장비(세션 장비)
  - 4계층 장비의 특징
  - 로드 밸런서
  - 방화벽
  - 4계층 장비를 통과할 때의 유의점(세션 관리)
- 7장. 통신을 도와주는 네트워크 주요 기술
- 8장. 서버 네트워크 기본
- 9장. 보안
- 10장. 서버의 방화벽 설정/동작
- 11장. 이중화 기술
- 12장. 로드 밸런서
- 13장. 네트워크 디자인
- 14장. 가상화 기술
- 15장. 가상화 서버를 위한 네트워크
