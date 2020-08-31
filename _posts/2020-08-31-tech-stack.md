---
title: 기술 스택
author: 박찬수
date: 2020-08-31 11:41:00 +0800
categories: [Formation Labs, Education]
tags: [getting started]
pin: true
---

# 기술 스택 이야기
##### 다양한 기술 스택들의 개념을 다룬다.
<br>
<br>

### Git
---
- 현재 가장 대표적인 버전 컨트롤 툴이자 소스 코드 관리 도구
- 과거 CVS나 SVN 같이 클라이언트-서버 시스템이 아닌 모든 노드의 모든깃 디렉터리는 네트워크 접속이나 중앙 서버와는 독립적으로 동작한다.

#### 장점
1. 매우 빠르다
2. 장소에 구애받지 않고 협업 가능
3. 일시적인 작업에 관리가 쉽다
4. 작업 중 실수가 있어도 바로 영향을 미치지 않는다.

#### 단점  
1. 다소 높은 진입장벽 (최근엔 소스트리, Github For Desktop 등으로 해결)
2. 프로젝트 중 일부만 브랜칭하거나 클로닝하는게 불가능하다.

<br>

### GitLab & GitHub & Bitbucket
---
- 대표적인 Git 저장소들의 차이점

| 내용&nbsp;&nbsp;&nbsp;&nbsp; | GitLab | GitHub | Bitbucket |
| :---: | :---: | :---: | :---: |
| 레포지토리 | Git Only | Git, SVN, TFS | Git, CodePlex, SVN, Sourceforge, Mercurial |
| 프로젝트 | Private 프로젝트 무제한 무료 지원 | 오픈소스 프로젝트에 더 적합 (Private은 유료) | Private 프로젝트 무제한 무료 지원 (단 협업자 5명까지)
| 속도 | 보통 | 빠름 | 느림
| 특징 | - Jenkins와 연동하여 빌드 배포까지 가능<br> - 온라인 개발기능을 지원 | 가장 많은 레포지토리, 가장 많은 사용자 수 보유 | 자사 다른 서비스인 Jira, Hipchat 등 과 연동이 편하다|
