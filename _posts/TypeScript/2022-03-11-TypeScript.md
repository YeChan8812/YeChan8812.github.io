---
layout: single
title: "TypeScript를 사용한 이유"
categories: TypeScript
permalink: /categories/typescript/1
author_profile: true
sidebar:
  nav: "study"
---

### TypeScript를 사용하는 이유

JavaScript에는 몇가지 문제점이 있다. 예를 들자면 아래와 같은 상황이다.

```javascript
"" == 0; // true
1 == "1"; // true
1 + "1"; // '11'
```

JavaScript는 동적 타이핑(Dynamic Typing)을 제공하기에 변수의 타입지정 없이 값이 할당되는 과정에서 값의 타입에 의해 자동으로 타입이 결정된다. 이런 문제를 해결하기 위해 TypeScript를 사용한다. TypeScript는 정적 타임 검사자로서 프로그램을 실행시키기 전에 값의 종류를 기반으로 프로그램의 오류를 찾아낸다.

##### 내가 TypeScript를 사용한 이유

코드스테이츠에서 파이널 프로젝트를 진행할 때 팀 내에서 Typescript를 사용해 보자는 의견이 나왔다. 이런 의견이 나온 이유는 프로젝트 기획 단계에서 클라이언트에서 서버로 데이터를 보낼 때 서로간에 타입이 맞지 않아 오류가 생겼기 때문이다.  
 첫 프로젝트 때 기획 단계에서 어떤 타입으로 데이터를 보낼지 결정했었지만 정신없이 프로젝트를 진행하다보니 타입을 잘못 지정해 오류가 발생했다. 이 문제를 해결하고자 파이널 프로젝트에서는 클라이언트와 서버를 담당하는 사람 모두 데이터의 타입을 TypeScript의 인터페이스로 지정을 해 놓고 각자 코드를 작성했다. 이렇게 처음부터 인터페이스로 타입을 지정해 놓으니 이후 클라이언트와 서버에서 데이터를 주고 받을 때 오류가 생기지 않았다.  
 이런 이점이 있었기에 TypeScript를 사용했고 계속해서 공부하는 중이다.
