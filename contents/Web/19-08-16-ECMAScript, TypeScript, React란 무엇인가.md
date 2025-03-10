---
title: "ECMAScript, TypeScript, React란 무엇인가?"
date: "2019-08-16"
template: "post"
draft: false
path: "/frontend/19-08-16/"
description: "프론트엔드 공부를 시작할 때, 처음에 많이 언급되는 ECMAScript, TypeScript, React에 대해 정리합니다. 위키피디아에서는 ECMAScript를 아래와 같이 설명하고 있습니다. ECMA스크립트는 Ecma 인터내셔널의 ECMA-262 기술 규격에 정의된 표준화된 스크립트 프로그래밍 언어이다."
category: "FrontEnd"
thumbnail: 'javascript'
---

프론트엔드 공부를 시작할 때, 처음에 많이 언급되는 ECMAScript, TypeScript, React에 대해 정리합니다.

### ECMAScript

 위키피디아에서는 ECMAScript를 아래와 같이 설명하고 있습니다.

>  ECMA스크립트는 Ecma 인터내셔널의 ECMA-262 기술 규격에 정의된 표준화된 스크립트 프로그래밍 언어이다. 1996년 3월, 넷스케이프에서 넷스케이프 네비게이터 2.0을 출시하면서 자바스크립트를 지원하기 시작했다. 넷스케이프는 표준화를 위해 자바스크립트 기술 규격을 Ecma 인터내셔널에 제출하였고, 이 규격에 대한 작업은 ECMA-262의 이름으로 1996년 11월부터 시작됐다. ECMA-262의 초판은 ECMA 일반 회의에서 1997년 6월 채택됐다.
>
>  ECMA스크립트는 ECMA-262에 의해 표준화된 언어의 이름이다. 자바스크립트와 J스크립트는 모두 ECMA스크립트와의 호환을 목표로 하면서, ECMA 규격에 포함되지 않는 확장 기능을 제공한다.

- **Ecma 인터내셔널**은 정보와 통신 시스템을 위한 국제적 표준화 기구를 말합니다.
- **ECMA-262**는 Ecma 인터내셔널에서 Script language에 대한 표준을 정의한 명세서를 말합니다.
- **스크립트 프로그래밍 언어**는 소스 코드를 컴파일하지 않고도 실행할 수 있는 프로그래밍 언어를 말합니다.

 즉, Ecma 인터내셔널에서 만든, ECMA-262 표준에 의해 정의된, 스크립트 프로그래밍 언어를 **ECMAScript**라고 합니다. 그리고 우리에게 익숙한 JavaScript는 ECMASciprt 표준을 바탕으로 구현된 범용 스크립트 언어입니다.

### TypeScript

 위키피디아에서는 TypeScript를 아래와 같이 설명하고 있습니다.

>  타입스크립트(TypeScript)는 자바스크립트의 슈퍼셋인 오픈소스 프로그래밍 언어이다. 마이크로소프트에서 개발, 유지하고 있으며 엄격한 문법을 지원한다. 클라이언트 사이드와 서버 사이드를 위한 개발에 사용할 수 있다.
>
>  타입스크립트는 자바스크립트 엔진을 사용하면서 커다란 애플리케이션을 개발할 수 있게 설계된 언어이다. 자바스크립트의 슈퍼셋이기 때문에 자바스크립트로 작성된 프로그램이 타입스크립트 프로그램으로도 동작한다. 타입스크립트에서 자신이 원하는 타입을 정의하고 프로그래밍을 하면 자바스크립트로 컴파일되어 실행할 수 있다. 
>

 간단히 말하면 TypeScript는 JavaScript를 확장한 언어입니다. 그렇기에 자바스크립트의 특성을 따르며 최신 ECMA 표준을 따르고 있습니다. 다만 자바스크립트는 인터프리터 언어인데 반하여, TypeScript는 컴파일 언어로 코드 수준에서 미리 타입을 체크 합니다.

![img](https://miro.medium.com/max/445/1*tOpeQXW36hEFiV8THpYUzA.png)



 그렇기에 **type을 지정**하는 것이 TypeScript의 가장 큰 특징이라고 말할 수 있습니다. 원래는 var만을 사용하는 JavaScript와 달리 TypeScript는 string, number, let 등을 사용함으로써 코드의 안정성을 높입니다. 이로 인해 대규모 애플리케이션 구현에 대한 자바스크립트의 불편함을 TypeScript가 대체할 수 있게 되었습니다. 

### React.js

 React는 **자바스크립트 라이브러리**의 하나로서 사용자 인터페이스를 만들기 위해 사용됩니다. 페이스북과 개별 개발자 및 기업들 공동체에 의해 유지보수되고 있습니다. 현재 프론트엔트 파트에서 가장 보편적으로 사용되고 있는 라이브러리라고 말할 수 있으며, **컴포넌트**를 기반으로 한다는 것이 React의 특징입니다.

 프론트엔드 개발을 할 때 HTML, CSS만 이용해서 웹 페이지를 만들 수 있기는 합니다. 하지만 이런 웹 페이지는 단순한 정적화면에 불과하며, 사용자가 행하는 이벤트에 따라 동적으로 작동하지 못한다는 단점을 가지고있습니다. 이럴 때 필요한 것이 React이고 이를 통해 사용자와 상호작용하는 동적 UI를 보다 쉽게 제작할 수 있게 됩니다. 

 이 외에 프론트엔드 개발을 돕는 **Vue.js, Angular** 같은 라이브러리나 프레임워크에 대해서는 [네이버 D2블로그](https://d2.naver.com/helloworld/3259111)에서 잘 설명해주고 있으니 참고하시면 좋을 것 같습니다. 또한 라이브러리와 프레임워크의 개념에 대한 차이점은 [이 블로그](https://webclub.tistory.com/458)(Kim jaehee님의 WEBCLUB) 에서 잘 설명해주고 있으니 참고하시길 바랍니다. 

저는 간단하게 프레임 워크는 '일을 하는 작업공간', 라이브러리는 '필요한 것을 하나씩 뽑아쓰는 코드 도서관' 정도로 기억해두고 있습니다.
