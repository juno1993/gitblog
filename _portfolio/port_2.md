---
layout: post
title: 배송 대행 보험 청구 서비스
feature-img: "assets/img/portfolio/port_2.png"
img: "assets/img/portfolio/port_2.png"
date: 2021-01-31
tags: [Portfolio]
---

**프로젝트명**

[일디랩 보험 청구 사이트](https://ilnoir.us/claim)

**프로젝트 설명**


해외 직구 배송대행 서비스 관련 불만이 있을 경우 물건의 파손, 오배송, 도난, 분실, 반송시 보험금을 청구할 수 있습니다. 

**주요 업무** 

보험 주문 기능

보험 청구 기능

청구 내용 보험사에게 메일 보내기 기능

주문, 청구 내역 엑셀 다운로드 기능

**주요 사용 기술**

Frontend: Vue js

Backend: Node

Server: Aws Ec2

Database: Mongo DB, redis

**리뷰**

이메일 모듈로 nodemailer를 사용했는데 첨부 파일의 개수 또는 용량이 많아서 메일이 안가는 문제가 있었습니다. <br>
이메일 보내기 테스크가 끝나기 전에 Rest Api가 리턴값을 먼저 반환 하기 때문에 이 같은 오류가 생겼을 것으로 판단해 
[celery-node](https://www.npmjs.com/package/celery-node) 모듈을 사용해 비동기 처리로 문제를 해결했습니다.  
