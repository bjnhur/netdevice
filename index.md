---
layout: page
title: Netdevice Home
description: 방문을 환영합니다. 모바일 앱 개발을 포함한 업무 영역과 프로젝트 내역을 살펴보세요
background: "/img/bg-index.jpg"
---

## 업무영역

넷디바이스가 수행가능한 업무영역을 소개해 드립니다. 

<div class="alert alert-success" markdown="1">

**통신 영역** 
- 프로토콜 : TCP, UDP, Mqtt, Modbus TCP USB 등
- 무선 통신 : BLE, Bluetooth 3.0, Wi-Fi 등

**개발 영역**
- 안드로이드 앱 개발
  - 개발 환경 : Eclipse, Android Studio
  - 언어 : Java
- 아이폰 앱 다수 프로젝트 수행
  - 개발 환경 : Xcode
  - 언어 : Objective-C (Swift)
- 라즈베리파이 어플리케이션 Raspberry Pi Program 개발
  - 언어  : C Language, PHP, HTML5, CSS3, JavaScript, Ajax 등
- 윈도우(Qt) UI 및 통신 프로그램 개발
  - 개발 환경 : Qt Creater
  - 언어 : C++
- IoT Mqtt Server 개발
  - Mosquitto Mqtt Broker
- TCP/IP 통신 칩/모듈 공급 및 기술 지원, 통신 컨설팅

</div>


## 임베디드 디바이스용 통신 소프트웨어 개발 수행 프로젝트

기존에 수행했던 프로젝트를 소개해 드립니다. 몇몇 프로젝트는 앱이나 PC 프로그램의 수행 결과물을 엿볼 수 있습니다.

---

- 2019 ~ : TSP용 서버 프로그램 개발
  * Qt 윈도우 프로그램
  * 댜수의 순간정전보상장치로부터 상태, 설정, 히스토리, Sag 정보 수신
  * Wesco 의뢰

- 2018 : SmartProbe용 데이터센터 어플 개발 외 8 Projects
  * 안드로이드, 아이폰 Multi BLE 어플
  * 온도계, 열선/베인 풍속계, 압력계, CO2 측정기 데이터 통합 응용
  * Summit 의뢰

- 2017     : 태양광 모니터링 시스템 개발 외 8 Projects
  * PC, 스마트폰용 모바일웹
  * Raspberry Pi3 Platform (HTML5, CSS3, PHP, JavaScript, Ajax, ModbusTCP C Programming)
  * Willings 의뢰

- 2016    : 온도조절기용 어플 및 서버 시스템 개발 외 5 Projects
  * 안드로이드, 아이폰 Mqtt Client 어플 & Https 어플
  * Mqtt Broker, Webserver를 이용한 서버 (LG Server와 연동)
  * Henersys 의뢰

- 2012 ~ : 안드로이드/아이폰 통신어플 개발 외 50여 Projects
  * 통신어플 : 제조사 장치와 WiFi, BLE, USB 통신
  * 안드로이드폰 : 갤럭시노트2(갤럭시S3) ~, 아이폰 : iPhone4S ~
  * SemiLink의 BLE 어플 개발 협력업체 (2012 ~ 2015)

- 2008 ~ : TCP/IP Ethernet, WiFi 통신부품 판매 및 기술지원
  * ㈜위즈네트의 제품 판매 및 기술지원 협력업체

## 프로젝트 상세 소개

---

<a href="{{"/posts" | relative_url }}">전체 프로젝트 보기는 여기로</a>

<div class="row">
{% for post in site.posts limit:3 %}{% if post.title != null %}
{% if post.background %}
{% assign postimg = post.background | prepend: site.baseurl | replace: '//', '/' %}
{% else %}
{% assign postimg = "/img/bg-post.jpg" | relative_url %}
{% endif %}
  <div class="col-md-4 mb-5">
    <div class="card border-0 shadow h-100">
      <img
        class="card-img-top"
        src="{{postimg}}"
        alt=""
      />
      <div class="card-body">
        <h4 class="card-title">{{ post.title | escape }}</h4>
        <p class="card-text">
          <small>{{ post.date | date: "%Y-%m-%d" }}</small><br>
          {{ post.excerpt | strip_html | escape }}
        </p>
      </div>
      <div class="card-footer">
        <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">더 읽어보기 &raquo;</a>
      </div>
    </div>
  </div>
{% endif %}{% endfor %}
</div>

## 뉴스 - 외부 소식 소개

새로운 소식이나 신규 프로젝트 수주 건이 생기면 여기에 글이 올라올 예정입니다.

