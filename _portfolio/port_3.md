---
layout: post
title: 마트 예약 배달 서비스
feature-img: "assets/img/portfolio/port_3.png"
img: "assets/img/portfolio/port_3.png"
date: 31 January 2021
tags: [Portfolio]
---

**프로젝트명**

[가람식자재마트](https://garamfood.net)

**프로젝트 설명**

우리집 근처 마트 예약 배달 서비스입니다. 구매가 완료되면 지점별 담당 배달자가 배달 가능 

**주요 업무** 

백오피스(프론트, 백엔드)

배송 예약 서비스(백엔드)

**주요 사용 기술**

Frontend: Vue js

Backend: Python Django

Server: Aws Ecs Fargate

Database: Rds Postgresql 9.6.5

**주요 모델링**

![model1](https://user-images.githubusercontent.com/46810003/106386637-446ebc80-6419-11eb-8fa1-bf92d7fdbd6a.png)

![model2](https://user-images.githubusercontent.com/46810003/106386665-69fbc600-6419-11eb-88e5-8a9e20840be9.png)


**리뷰**

상품 parent-child relation 처리를 하여 판매하는 상품을 일괄 처리하였습니다. 
A 지점의 상품의 부모와 B 지점의 상품의 부모가 동일하지만 서로 id값이 다릅니다.
child 자체가 지점이고 parent는 이를 관리하기 위한 부모이자 인터페이스라고 생각하시면 됩니다. 
이로 인해서 지점별로 재고 및 담당자를 관리할 수 있는 있도록 하였습니다.

<!--이번 프로젝트를 하며 일전에 잘 다루지 않았던 통계 관련해서 쿼리를 짤 일이 많아서 어려움이 있었습니다.
단일 상품과 옵션 상품별로 통계를 내야하는 상황이었습니다.-->   