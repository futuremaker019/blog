---
layout: post
tags: [Isolation Level, Database, blog]
---


### Transaction Isolation Level 이란

- `Isolation Level` 이란 트랜잭션에서 일관성이 없는 데이터를 허용하는 수준을 이야기한다.
- 동시에 여러 트랜잭션이 처리될 때, 특정 트랜잭션이 다른 트랜잭션에서 변경하거나 조회하는 데이터를 볼 수 있도록 허용할지 하지않을지 결정하는 것이다.
- 레벨이 높아질수록 처리에 대한 비용이 증가된다.
  
### 트랜잭션의 격리수준에 따른 문제점

#### 낮은 트랜잭션 격리수준의 문제점



