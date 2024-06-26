# 한성대학교 수강신청 도우미
#### 이 프로젝트는 대학생들이 효율적으로 수강신청을 하고, 시간표를 관리할 수 있도록 돕는 안드로이드 애플리케이션이다.
#### 주요 기능으로는 회원가입 및 로그인, 강의 목록 조회, 수강신청, 개인 시간표 조회 등이 있다.
**한성대학교 컴퓨터공학부 2071053 장욱**

## 1. 프로젝트 수행 목적

### 1.1 프로젝트 정의

이 프로젝트의 주된 목적은 대학생들이 보다 쉽게 수강신청을 하고, 자신의 시간표를 효율적으로 관리할 수 있도록 지원하는 애플리케이션을 개발하는 것이다.

이를 통해 수강신청의 복잡성을 줄이고, 사용자 경험을 향상시키는 것을 목표로 한다.

수강신청 앱은 학생들이 모바일 디바이스를 통해 강의를 조회하고, 원하는 강의를 선택하여 수강신청을 할 수 있도록 도와주는 안드로이드 애플리케이션이다.

또한, 신청한 강의를 기반으로 개인화된 시간표를 제공하여 학생들의 학습 계획을 보다 체계적으로 관리할 수 있게 한다.

### 1.2 프로젝트 배경

대부분의 대학은 수강신청 시스템을 웹 기반으로 운영하고 있다. 그러나 많은 학생들은 수강신청 기간 동안 시스템의 복잡성과 사용의 불편함을 경험한다. 

특히, 이동 중이거나 컴퓨터에 접근할 수 없는 상황에서는 수강신청이 어려울 수 있다. 이러한 문제를 해결하기 위해 모바일 환경에서 쉽게 접근할 수 있는 수강신청 앱을 개발하게 되었다.

### 1.3 프로젝트 목표

학생들이 모바일 디바이스를 통해 언제 어디서나 수강신청을 할 수 있도록 지원

사용자가 신청한 강의를 한눈에 볼 수 있는 직관적인 시간표 제공

사용자의 편의성을 높이고, 수강신청의 효율성을 극대화

## 2. 프로젝트 개요

### 2.1 프로젝트 설명

한성대학교 수강신청 도우미 앱은 회원가입 및 로그인, 강의 목록 조회, 수강신청, 시간표 조회 등의 기능을 제공한다. 

사용자 친화적인 UI/UX 디자인을 통해 학생들이 쉽게 사용할 수 있도록 하며, 안정적인 서버와 데이터베이스 연결을 통해 실시간으로 데이터를 처리한다.

회원가입 및 로그인: 사용자가 자신의 정보를 입력하여 회원가입을 하고, 이를 통해 로그인을 할 수 있다.

강의 목록 조회: 현재 개설된 모든 강의를 조회할 수 있으며, 강의명, 교수명, 학년, 학점, 분반, 시간 등의 정보를 확인할 수 있다.

수강신청: 사용자가 원하는 강의를 선택하여 수강신청을 할 수 있고, 수강신청한 강의는 개인 시간표에 반영된다.

개인 시간표 조회: 사용자가 신청한 강의를 시간표 형식으로 확인할 수 있습니다. 요일별로 구분되어 있으며, 각 강의의 시간과 강의명, 교수명이 포함된다.

분석: 내가 등록한 강의와 학점을 볼 수 있으며 등록한 강의를 삭제할 수도 있다. 등록한 강의의 경쟁률을 확인할 수 있다.

### 2.2 프로젝트 구조

안드로이드 개발 도구: Android Studio(안드로이드 애플리케이션 개발을 위한 통합 개발 환경(IDE))

프로그래밍 언어: Java(안드로이드 애플리케이션 개발에 사용된 프로그래밍 언어)

백엔드: PHP (PHP를 사용하여 서버 스크립트 작성, 서버 사이드 스크립팅 언어로, 데이터베이스와의 상호작용을 처리)

데이터베이스: MySQL(관계형 데이터베이스 관리 시스템(RDBMS))을 사용하여 데이터 저장 및 관리

서버 호스팅: Cafe24

네트워크 통신: Volley 라이브러리를 사용하여 서버와의 통신 구현

### 2.3 결과물

초기화면(Splashscreen)

<img width="346" alt="스크린샷 2024-06-16 오후 3 30 08" src="https://github.com/uk0k/mini-project/assets/157580000/15fabfc0-fb72-46fd-b6e9-bc3737b5661d">

회원가입 및 로그인을 진행할 수 있는 화면

<img width="341" alt="스크린샷 2024-06-16 오후 3 30 18" src="https://github.com/uk0k/mini-project/assets/157580000/6cfa019f-de0e-49c6-8471-5d4b887af873">

회원가입화면(아이디 중복체크 기능 및 성별, 전공 선택)

<img width="342" alt="스크린샷 2024-06-16 오후 3 31 09" src="https://github.com/uk0k/mini-project/assets/157580000/c571745e-bea5-456c-8952-f1dd22181dfe">

<img width="339" alt="스크린샷 2024-06-16 오후 3 31 35" src="https://github.com/uk0k/mini-project/assets/157580000/fe05ddd1-3d0e-477d-9ee4-cda85b0d71f5">

메인화면 (회원가입 후 로그인 진행한 화면)

<img width="339" alt="스크린샷 2024-06-16 오후 3 31 55" src="https://github.com/uk0k/mini-project/assets/157580000/5589d738-5201-4a01-ba2a-b976111c09d2">

강의목록화면 (수강신청하고싶은 과목 선택)

<img width="339" alt="스크린샷 2024-06-16 오후 3 32 11" src="https://github.com/uk0k/mini-project/assets/157580000/b8bd775b-4685-4151-9af7-bfb6d741da7c">

만약 이전에 신청한 과목과 시간이 중복될 경우

<img width="343" alt="스크린샷 2024-06-16 오후 3 33 13" src="https://github.com/uk0k/mini-project/assets/157580000/1eb2bb96-b775-436e-8f10-f9416e375292">

성공적으로 수강신청에 성공했을 때

<img width="340" alt="스크린샷 2024-06-16 오후 3 33 29" src="https://github.com/uk0k/mini-project/assets/157580000/c96d0ec1-71f8-4b2e-a655-a58ef90077c8">

나의 시간표 확인

<img width="342" alt="스크린샷 2024-06-16 오후 3 33 41" src="https://github.com/uk0k/mini-project/assets/157580000/e4a6c76a-a5e5-467e-bc59-9ea83fb65f3a">

분석화면 (내가 등록한 강의, 학점, 경쟁률 확인 및 삭제)

<img width="343" alt="스크린샷 2024-06-16 오후 3 33 53" src="https://github.com/uk0k/mini-project/assets/157580000/73358132-78a8-4d1b-b6dc-0cf84832e8a2">

내가 등록한 강의를 성공적으로 삭제했을 경우

<img width="337" alt="스크린샷 2024-06-16 오후 3 34 13" src="https://github.com/uk0k/mini-project/assets/157580000/91b0ac0c-e2b1-4c3d-a8e9-0e3cd605397a">


### 2.4 기대효과

편의성 향상: 모바일 디바이스를 통해 언제 어디서나 수강신청이 가능해져 학생들의 편의성이 크게 향상된다.

시간 절약: 복잡한 수강신청 과정을 간편하게 만들어 시간 절약을 도모한다.

학습 계획 관리: 개인화된 시간표 제공으로 학생들이 자신의 학습 계획을 보다 효율적으로 관리할 수 있다.


### 2.5 발표영상
https://youtu.be/Tu9Y3mhkW84
