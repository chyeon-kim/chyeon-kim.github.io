---
layout: post
title:  "Web automation setting_selenium"
date:   2020-10-16 15:04:13 +0800
categories: automation
tags: [automation, selenium, web]
---

## 웹 자동화_selenium 셋팅 방법

### Web automation_selenium setting


웹 자동화를 하기전 먼저 진행되어야 할 셋팅 방법에 대해 소개하겠습니다.

[Jdk 설치 및 환경변수 설정]
* jdk설치
https://www.oracle.com/java/technologies/javase-downloads.html

* '시스템 환경변수 편집' 검색
![image](https://user-images.githubusercontent.com/69964166/96219557-0a8cbe00-0fc2-11eb-8bef-8f2b4b773e0d.png)
환경변수 > 환경변수 페이지로 넘어감

![image](https://user-images.githubusercontent.com/69964166/96220460-ba166000-0fc3-11eb-9d36-c7dfa7090d70.png)

![image](https://user-images.githubusercontent.com/69964166/96220801-68baa080-0fc4-11eb-810b-a67963785080.png)
* 새로 만들기 > 변수이름, 변수값 입력 후 확인버튼 클릭 

** 변수 이름(N) : JAVA_HOME **
** 변수값(V) : jdk 설치된 경로 (ex: C:\Program Files (x86)\Java\jre1.8.0_241) **


![image](https://user-images.githubusercontent.com/69964166/96220952-af0fff80-0fc4-11eb-9814-e8ab892c41e7.png)
* Path > 편집버튼 클릭
* 새로 만들기 > **%JAVA_HOME%\bin** 입력 > 확인


jdk가 정상설치된 경우 cmd 창에서 다음과 같은 결과가 나옵니다.
* cmd 창에서 java -version 입력
![image](https://user-images.githubusercontent.com/69964166/96221411-85a3a380-0fc5-11eb-83ce-e6d0e206beb6.png)


[eclipse 설치]
https://www.eclipse.org/downloads/packages/


[eclipse에 TestNG 설치]



[eclipse에 selenium 파일 추가]


[chrome driver 설치]