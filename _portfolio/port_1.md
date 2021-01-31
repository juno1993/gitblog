---
layout: post
title: 웹/앱 솔루션
feature-img: "assets/img/portfolio/port_1.png"
img: "assets/img/portfolio/port_1.png"
date: 31 January 2021
tags: [Portfolio]
---

**프로젝트 설명**

개발자 없이 창업을 도와주는 웹/앱 솔루션 서비스 입니다. 공식 홈페이지에서 구매 후 서비스 화면과 관리 정보를 구성하여 홈페이지를 제작할 수 있습니다.

**주요 업무** 

백오피스(프론트, 백엔드)
커머스, 예약, 숙박 서비스(백엔드)

**주요 사용 기술**

Frontend: vue js

Backend: python django

Server: aws ecs fargate

Database: rds postgresql 9.6.5


**기타 사용 기술**

결제 시스템 > KG 이니시스 빌링 모듈 (php)

고객 홈페이지 서버 구성 > route53 + elb(alb) + ecs fargate

이미지 대체 텍스트 저장 > Lambda + Api Gateway + DynamoDB

이메일 보내기 > ses + sns + lambda + dynamodb

DynamoDB에 이메일 목록이 있을 경우 반송된 이메일로 간주하고 보내지 아니함.

