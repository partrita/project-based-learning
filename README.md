# 프로젝트 기반 학습 (Project Based Learning)

[![Gitter](https://badges.gitter.im/practical-tutorials/community.svg)](https://gitter.im/practical-tutorials/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

예비 소프트웨어 개발자가 처음부터 애플리케이션을 구축하는 방법을 배우는 프로그래밍 튜토리얼 목록입니다. 이러한 튜토리얼은 다양한 기본 프로그래밍 언어로 나뉩니다. 튜토리얼에는 여러 기술과 언어가 포함될 수 있습니다.

시작하려면 이 저장소를 포크하십시오. 기여 가이드라인은 [기여 가이드라인](CONTRIBUTING.md)을 참조하십시오.

## 목차:

- [C#](#c)
- [C/C++](#cc)
- [Clojure](#clojure)
- [Dart](#dart)
- [Elixir](#elixir)
- [Erlang](#erlang)
- [F#](#f)
- [Go](#go)
- [Haskell](#haskell)
- [HTML/CSS](#html-and-css)
- [Java](#java)
- [JavaScript](#javascript)
- [Kotlin](#kotlin)
- [Lua](#lua)
- [OCaml](#ocaml)
- [PHP](#php)
- [Python](#python)
- [R](#r)
- [Ruby](#ruby)
- [Rust](#rust)
- [Scala](#scala)
- [Swift](#swift)
- [추가 자료](#additional-resources)

## C/C++:

- [인터프리터 만들기](http://www.craftinginterpreters.com/) (14장부터 C로 작성됨)
- [메모리 할당자 101 - 간단한 메모리 할당자 작성](https://arjunsreedharan.org/post/148675821737/memory-allocators-101-write-a-simple-memory)
- [C로 셸 작성](https://brennan.io/2015/01/16/write-a-shell-in-c/)
- [FUSE 파일시스템 작성](https://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/)
- [나만의 텍스트 편집기 만들기](http://viewsourcecode.org/snaptoken/kilo/)
- [나만의 Lisp 만들기](http://www.buildyourownlisp.com/)
- [C로 NES 게임 프로그래밍하는 방법](https://nesdoug.com/)
- [처음부터 OS 작성](https://github.com/tuhdo/os01)
- [처음부터 OS 만드는 방법](https://github.com/cfenollosa/os-tutorial)
- [CHIP-8 에뮬레이터 만들기](https://austinmorlan.com/posts/chip8_emulator/)
- [C++와 SDL로 시작하는 게임 프로그래밍](http://lazyfoo.net/tutorials/SDL/)
- [키-값 저장소 구현](http://codecapsule.com/2012/11/07/ikvs-implementing-a-key-value-store-table-of-contents/)
- 작은 3D 그래픽 프로젝트
  - [Tiny Renderer 또는 OpenGL 작동 방식: 500줄 코드로 소프트웨어 렌더링](https://github.com/ssloy/tinyrenderer/wiki)
  - [256줄의 순수 C++로 이해하는 레이트레이싱](https://github.com/ssloy/tinyraytracer/wiki)
  - [180줄의 순수 C++로 KABOOM!](https://github.com/ssloy/tinykaboom/wiki)
  - [486줄의 C++: 주말에 만드는 구식 FPS](https://github.com/ssloy/tinyraycaster/wiki)
- C++로 최소한의 x86-64 JIT 컴파일러 작성
  - [1부](https://solarianprogrammer.com/2018/01/10/writing-minimal-x86-64-jit-compiler-cpp/)
  - [2부](https://solarianprogrammer.com/2018/01/12/writing-minimal-x86-64-jit-compiler-cpp-part-2/)
- [C++용 라이브 코드 리로더 라이브러리 만들기](http://howistart.org/posts/cpp/1/index.html)
- [C로 해시 테이블 작성](https://github.com/jamesroutley/write-a-hash-table)
- [간단한 데이터베이스 만들기](https://cstack.github.io/db_tutorial/)
- [커널 작성하기](http://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)
- [C로 부트로더 작성](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)
- [500줄 코드로 리눅스 컨테이너 만들기](https://blog.lizzie.io/linux-containers-in-500-loc.html)
- [나만의 가상 머신 작성](https://justinmeiners.github.io/lc3-vm/)
- [KVM 배우기 - 나만의 리눅스 커널 구현](https://david942j.blogspot.com/2018/10/note-learning-kvm-implement-your-own.html)
- [C/C++로 나만의 Redis 만들기](https://build-your-own.org/redis/)
- C 컴파일러 작성
  - [1부: 정수, 렉싱 및 코드 생성](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
  - [2부: 단항 연산자](https://norasandler.com/2017/12/05/Write-a-Compiler-2.html)
  - [3부: 이항 연산자](https://norasandler.com/2017/12/15/Write-a-Compiler-3.html)
  - [4부: 더 많은 이항 연산자](https://norasandler.com/2017/12/28/Write-a-Compiler-4.html)
  - [5부: 지역 변수](https://norasandler.com/2018/01/08/Write-a-Compiler-5.html)
  - [6부: 조건문](https://norasandler.com/2018/02/25/Write-a-Compiler-6.html)
  - [7부: 복합문](https://norasandler.com/2018/03/14/Write-a-Compiler-7.html)
  - [8부: 반복문](https://norasandler.com/2018/04/10/Write-a-Compiler-8.html)
  - [9부: 함수](https://norasandler.com/2018/06/27/Write-a-Compiler-9.html)
  - [10부: 전역 변수](https://norasandler.com/2019/02/18/Write-a-Compiler-10.html)
- [LLVM으로 언어 구현](https://llvm.org/docs/tutorial/#kaleidoscope-implementing-a-language-with-llvm)
- [메타 크러시 사가: C++17 컴파일 타임 게임](https://jguegant.github.io//jguegant.github.io/blogs/tech/meta-crush-saga.html)
- [고성능 행렬 곱셈](https://gist.github.com/nadavrot/5b35d44e8ba3dd718e595e40184d03f0)
- 처음부터 스페이스 인베이더 만들기
  - [1부](http://nicktasios.nl/posts/space-invaders-from-scratch-part-1.html)
  - [2부](http://nicktasios.nl/posts/space-invaders-from-scratch-part-2.html)
  - [3부](http://nicktasios.nl/posts/space-invaders-from-scratch-part-3.html)
  - [4부](http://nicktasios.nl/posts/space-invaders-from-scratch-part-4.html)
  - [5부](http://nicktasios.nl/posts/space-invaders-from-scratch-part-5.html)
- [C++ 플랫폼 독립적인 테트리스 튜토리얼](http://javilop.com/gamedev/tetris-tutorial-in-c-platform-independent-focused-in-game-logic-for-beginners/)
- 리눅스 디버거 작성
  - [1부: 설정](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)
  - [2부: 중단점](https://blog.tartanllama.xyz/writing-a-linux-debugger-breakpoints/)
  - [3부: 레지스터 및 메모리](https://blog.tartanllama.xyz/writing-a-linux-debugger-registers/)
  - [4부: 엘프와 드워프](https://blog.tartanllama.xyz/writing-a-linux-debugger-elf-dwarf/)
  - [5부: 소스 및 신호](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-signal/)
  - [6부: 소스 수준 스텝 실행](https://blog.tartanllama.xyz/writing-a-linux-debugger-dwarf-step/)
  - [7부: 소스 수준 중단점](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-break/)
  - [8부: 스택 풀기](https://blog.tartanllama.xyz/writing-a-linux-debugger-unwinding/)
  - [9부: 변수 처리](https://blog.tartanllama.xyz/writing-a-linux-debugger-variables/)
  - [10부: 고급 주제](https://blog.tartanllama.xyz/writing-a-linux-debugger-advanced-topics/)
- 컴파일러 작성하기
  - [1부: 소개, 언어 선택 및 계획](https://briancallahan.net/blog/20210814.html)
  - [2부: 렉서](https://briancallahan.net/blog/20210815.html)
  - [3부: 파서](https://briancallahan.net/blog/20210816.html)
  - [4부: 테스트](https://briancallahan.net/blog/20210817.html)
  - [5부: 코드 생성기](https://briancallahan.net/blog/20210818.html)
  - [6부: 입력 및 출력](https://briancallahan.net/blog/20210819.html)
  - [7부: 배열](https://briancallahan.net/blog/20210822.html)
  - [8부: 문자열, 전방 참조 및 결론](https://briancallahan.net/blog/20210826.html)

### 네트워크 프로그래밍

- TCP/IP 스택 코딩하기

  - [1부: 이더넷 & ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)
  - [2부: IPv4 & ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)
  - [3부: TCP 기본 & 핸드셰이크](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
  - [4부: TCP 데이터 흐름 & 소켓 API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
  - [5부: TCP 재전송](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)

- 동시성 서버 프로그래밍

  - [1부 - 소개](https://eli.thegreenplace.net/2017/concurrent-servers-part-1-introduction/)
  - [2부 - 스레드](https://eli.thegreenplace.net/2017/concurrent-servers-part-2-threads/)
  - [3부 - 이벤트 기반](https://eli.thegreenplace.net/2017/concurrent-servers-part-3-event-driven/)
  - [4부 - libuv](https://eli.thegreenplace.net/2017/concurrent-servers-part-4-libuv/)
  - [5부 - Redis 사례 연구](https://eli.thegreenplace.net/2017/concurrent-servers-part-5-redis-case-study/)
  - [6부 - 콜백, 프로미스 및 async/await](https://eli.thegreenplace.net/2018/concurrent-servers-part-6-callbacks-promises-and-asyncawait/)

- 처음부터 MQTT 브로커 만들기
  - [1부 - 프로토콜](https://codepr.github.io/posts/sol-mqtt-broker)
  - [2부 - 네트워킹](https://codepr.github.io/posts/sol-mqtt-broker-p2)
  - [3부 - 서버](https://codepr.github.io/posts/sol-mqtt-broker-p3)
  - [4부 - 자료 구조](https://codepr.github.io/posts/sol-mqtt-broker-p4)
  - [5부 - 토픽 추상화](https://codepr.github.io/posts/sol-mqtt-broker-p5)
  - [6부 - 핸들러](https://codepr.github.io/posts/sol-mqtt-broker-p6)
  - [보너스 - 멀티스레딩](https://codepr.github.io/posts/sol-mqtt-broker-bonus)

### OpenGL:

- C++와 OpenGL로 2D 벽돌깨기 게임 클론 만들기
  - [벽돌깨기](https://learnopengl.com/In-Practice/2D-Game/Breakout)
  - [설정](https://learnopengl.com/In-Practice/2D-Game/Setting-up)
  - [스프라이트 렌더링](https://learnopengl.com/In-Practice/2D-Game/Rendering-Sprites)
  - [레벨](https://learnopengl.com/In-Practice/2D-Game/Levels)
  - 충돌
    - [공](https://learnopengl.com/In-Practice/2D-Game/Collisions/Ball)
    - [충돌 감지](https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-detection)
    - [충돌 해결](https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution)
  - [파티클](https://learnopengl.com/In-Practice/2D-Game/Particles)
  - [후처리](https://learnopengl.com/In-Practice/2D-Game/Postprocessing)
  - [파워업](https://learnopengl.com/In-Practice/2D-Game/Powerups)
  - [오디오](https://learnopengl.com/In-Practice/2D-Game/Audio)
  - [텍스트 렌더링](https://learnopengl.com/In-Practice/2D-Game/Render-text)
  - [마지막 생각](https://learnopengl.com/In-Practice/2D-Game/Final-thoughts)
- [핸드메이드 히어로](https://handmadehero.org)
- [C++/OpenGL로 마인크래프트 만드는 방법](https://www.youtube.com/playlist?list=PLMZ_9w2XRxiZq1vfw1lrpCMRDufe2MKV_) (비디오)

## C#:

- [간단한 RPG 게임 만들면서 C# 배우기](http://scottlilly.com/learn-c-by-building-a-simple-rpg-index/)
- [C#으로 로그라이크 게임 만들기](https://roguesharp.wordpress.com/)
- [C#과 Xamarin으로 빈 앱 만들기 (진행 중)](https://www.intertech.com/Blog/xamarin-tutorial-part-1-create-a-blank-app/)
- [Xamarin과 Visual Studio로 iOS 사진 라이브러리 앱 만들기](https://www.raywenderlich.com/134049/building-ios-apps-with-xamarin-and-visual-studio)
- [CoreWiki 빌드](https://www.youtube.com/playlist?list=PLVMqA0_8O85yC78I4Xj7z48ES48IQBa7p) 이것은 ASP.NET Core와 Razor Pages를 사용하여 C#으로 완전히 작성된 위키 스타일 콘텐츠 관리 시스템입니다. 소스 코드는 [여기](https://github.com/csharpfritz/CoreWiki)에서 찾을 수 있습니다.

## Clojure:

- [Clojure로 트위터 봇 만들기](http://howistart.org/posts/clojure/1/index.html)
- [맞춤법 검사기 만들기](https://bernhardwenzel.com/articles/clojure-spellchecker/)
- [Clojure & Atlassian Connect로 JIRA 통합 구축](https://hackernoon.com/building-a-jira-integration-with-clojure-atlassian-connect-506ebd112807)
- [Clojure로 프로토타이핑](https://github.com/aliaksandr-s/prototyping-with-clojure)
- [ClojureScript로 테트리스 만들기](https://shaunlebron.github.io/t3tr0s-slides)

## Dart:

### Flutter:

- [관리자 패널이 있는 아마존 클론](https://youtu.be/O3nmP-lZAdg)
- [음식 배달 앱](https://youtu.be/7dAt-JMSCVQ)
- [구글 문서 클론](https://youtu.be/0_GJ1w_iG44)
- [인스타그램 클론](https://youtu.be/mEPm9w5QlJM)
- [멀티플레이어 틱택토 게임](https://youtu.be/Aut-wfXacXg)
- [틱톡 클론](https://youtu.be/4E4V9F3cbp4)
- [티켓 예매 앱](https://youtu.be/71AsYo2q_0Y)
- [여행 앱](https://youtu.be/x4DydJKVvQk)
- [트위치 클론](https://youtu.be/U9YKZrDX0CQ)
- [왓츠앱 클론](https://youtu.be/yqwfP2vXWJQ)
- [워들 클론](https://youtu.be/_W0RN_Cqhpg)
- [줌 클론](https://youtu.be/sMA1dKbv33Y)
- [넷플릭스 클론](https://youtu.be/J8IFNKzs3TI)

## Elixir

- [Elixir와 Phoenix로 간단한 채팅 앱 만들기](https://sheharyar.me/blog/simple-chat-phoenix-elixir/)
- [Elixir, Phoenix, Mnesia로 매우 빠른 링크 단축기 만드는 방법](https://medium.com/free-code-camp/how-to-write-a-super-fast-link-shortener-with-elixir-phoenix-and-mnesia-70ffa1564b3c)

## Erlang

- [ChatBus : Erlang/OTP로 첫 멀티유저 채팅방 앱 만들기](https://medium.com/@kansi/chatbus-build-your-first-multi-user-chat-room-app-with-erlang-otp-b55f72064901)
- [Erlang, Rebar, Cowboy, Bullet으로 채팅 앱 만들기](http://marianoguerra.org/posts/making-a-chat-app-with-erlang-rebar-cowboy-and-bullet.html)

## F#:

- [100줄의 F#으로 나만의 Excel 작성](http://tomasp.net/blog/2018/write-your-own-excel)

## Java:

- [인터프리터 만들기](http://www.craftinginterpreters.com/) (4-13장은 Java로 작성됨)
- [Java로 간단한 HTTP 서버 만들기](http://javarevisited.blogspot.com/2015/06/how-to-create-http-server-in-java-serversocket-example.html)
- [안드로이드 손전등 앱 만들기](https://www.youtube.com/watch?v=dhWL4DC7Krs) (비디오)
- [사용자 인증 기능이 있는 Spring Boot 앱 만들기](https://spring.io/guides/gs/securing-web/)

## JavaScript:

- [30일 동안 30개의 튜토리얼로 30가지 만들기](https://javascript30.com)
- [순수 JS로 앱 만들기](https://medium.com/codingthesmartway-com-blog/pure-javascript-building-a-real-world-application-from-scratch-5213591cfcd6)
- [Jupyter Notebook 확장 프로그램 만들기](https://link.medium.com/wWUO7TN8SS)
- [JavaScript로 틱택토 게임 만들기](https://medium.com/javascript-in-plain-english/build-tic-tac-toe-game-using-javascript-3afba3c8fdcc)
- [바닐라 JavaScript로 간단한 날씨 앱 만들기](https://webdesign.tutsplus.com/tutorials/build-a-simple-weather-app-with-vanilla-javascript--cms-33893)
- [JavaScript로 할 일 목록 앱 만들기](https://github.com/dwyl/javascript-todo-list-tutorial)

## HTML and CSS:

- [로딩 화면 만들기](https://medium.freecodecamp.org/how-to-build-a-delightful-loading-screen-in-5-minutes-847991da509f)
- [JS로 HTML 계산기 만들기](https://medium.freecodecamp.org/how-to-build-an-html-calculator-app-from-scratch-using-javascript-4454b8714b98)
- [JavaScript, HTML & CSS만으로 스네이크 게임 만들기](https://www.freecodecamp.org/news/think-like-a-programmer-how-to-build-snake-using-only-javascript-html-and-css-7b1479c3339e/)

### 모바일 애플리케이션:

- [React Native 할 일 애플리케이션 만들기](https://egghead.io/courses/build-a-react-native-todo-application)
- [Redux Thunk로 React Native 애플리케이션 만들기](https://medium.com/@alialhaddad/how-to-use-redux-thunk-in-react-and-react-native-4743a1321bd0)

### 웹 애플리케이션:

#### React:

- [서버리스 React.js 앱 만들기](http://serverless-stack.com/)
- [트렐로 클론 만들기](http://codeloveandboards.com/blog/2016/01/04/trello-tribute-with-phoenix-and-react-pt-1/)
- [React, Node, MongoDB, SocketIO로 캐릭터 투표 앱 만들기](http://sahatyalkabov.com/create-a-character-voting-app-using-react-nodejs-mongodb-and-socketio)
- [React 튜토리얼: Yelp 클론하기](https://www.fullstackreact.com/articles/react-tutorial-cloning-yelp/)
- [Mocha, React, Redux, Immutable을 사용한 테스트 우선 개발로 풀 스택 영화 투표 앱 만들기](https://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)
- [React와 Node로 트위터 스트림 만들기](https://scotch.io/tutorials/build-a-real-time-twitter-stream-with-node-and-react-js)
- [React.js와 Node.js로 간단한 미디엄 클론 만들기](https://medium.com/@kris101/clone-medium-on-node-js-and-react-js-731cdfbb6878)
- [JS에 MailChimp 통합하기](https://medium.freecodecamp.org/how-to-integrate-mailchimp-in-a-javascript-web-app-2a889fb43f6f)
- [React + Parcel로 크롬 확장 프로그램 만들기](https://medium.freecodecamp.org/building-chrome-extensions-in-react-parcel-79d0240dd58f)
- [React Native로 할일 앱 만들기](https://blog.hasura.io/tutorial-fullstack-react-native-with-graphql-and-authentication-18183d13373a)
- [채팅 애플리케이션 만들기](https://medium.freecodecamp.org/how-to-build-a-chat-application-using-react-redux-redux-saga-and-web-sockets-47423e4bc21a)
- [React Native로 뉴스 앱 만들기](https://medium.freecodecamp.org/create-a-news-app-using-react-native-ced249263627)
- [React용 Webpack 배우기](https://medium.freecodecamp.org/learn-webpack-for-react-a36d4cac5060)
- [Puppeteer와 Jest로 React 앱 테스트하기](https://blog.bitsrc.io/testing-your-react-app-with-puppeteer-and-jest-c72b3dfcde59)
- [나만의 React 보일러플레이트 만들기](https://medium.freecodecamp.org/how-to-build-your-own-react-boilerplate-2f8cbbeb9b3f)
- [React로 인생 게임 코딩하기](https://medium.freecodecamp.org/create-gameoflife-with-react-in-one-hour-8e686a410174)
- [기본 React+Redux 입문 튜토리얼](https://hackernoon.com/a-basic-react-redux-introductory-tutorial-adcc681eeb5e)
- [약속 스케줄러 만들기](https://hackernoon.com/build-an-appointment-scheduler-using-react-twilio-and-cosmic-js-95377f6d1040)
- [감정 분석 기능이 있는 채팅 앱 만들기](https://codeburst.io/build-a-chat-app-with-sentiment-analysis-using-next-js-c43ebf3ea643)
- [풀 스택 웹 애플리케이션 설정 만들기](https://hackernoon.com/full-stack-web-application-using-react-node-js-express-and-webpack-97dbd5b9d708)
- [React와 Firebase로 Todoist 클론 만들기](https://www.youtube.com/watch?v=hT3j87FMR6M)
- 무작위 명언 생성기 만들기
  - [1부](https://www.youtube.com/watch?v=3QngsWA9IEE)
  - [2부](https://www.youtube.com/watch?v=XnoTmO06OYo)
  - [3부](https://www.youtube.com/watch?v=us51Jne67_I)
  - [4부](https://www.youtube.com/watch?v=iZx7hqHb5MU)
  - [5부](https://www.youtube.com/watch?v=lpba9vBqXl0)
  - [6부](https://www.youtube.com/watch?v=Jvp8j6zrFHE)
  - [7부](https://www.youtube.com/watch?v=M_hFfrN8_PQ)
- [React 폰 이커머스 프로젝트(비디오)](https://www.youtube.com/watch?v=-edmQKcOW8s)

#### Angular:

- [Angular 1.x로 인스타그램 클론 만들기](https://hackhands.com/building-instagram-clone-angularjs-satellizer-nodejs-mongodb/)
- Angular 2+로 오프라인 지원 해커 뉴스 클라이언트 만들기
  - [1부](https://houssein.me/angular2-hacker-news)
  - [2부](https://houssein.me/progressive-angular-applications)
- [Django와 AngularJS (Angular 1.x)로 구글+ 클론 만들기](https://thinkster.io/django-angularjs-tutorial)
- Angular 8로 아름다운 실제 앱 만들기 :

  - [1부](https://medium.com/@hamedbaatour/build-a-real-world-beautiful-web-app-with-angular-6-a-to-z-ultimate-guide-2018-part-i-e121dd1d55e)
  - [2부](https://medium.com/@hamedbaatour/build-a-real-world-beautiful-web-app-with-angular-8-the-ultimate-guide-2019-part-ii-fe70852b2d6d)

- [BootStrap 4와 Angular 6로 반응형 레이아웃 만들기](https://medium.com/@tomastrajan/how-to-build-responsive-layouts-with-bootstrap-4-and-angular-6-cfbb108d797b)
- Angular 5로 할일 앱 만들기
  - [Angular 소개](http://www.discoversdk.com/blog/intro-to-angular-and-the-evolution-of-the-web)
  - [1부](http://www.discoversdk.com/blog/angular-5-to-do-list-app-part-1)

#### Node:

- [NodeJS로 실시간 마크다운 편집기 만들기](https://scotch.io/tutorials/building-a-real-time-markdown-viewer)
- [Node, Postgres, Knex로 테스트 주도 개발](http://mherman.org/blog/2016/04/28/test-driven-development-with-node/)
- Node.js로 트위터 봇 작성하기
  - [1부](https://codeburst.io/build-a-simple-twitter-bot-with-node-js-in-just-38-lines-of-code-ed92db9eb078)
  - [2부](https://codeburst.io/build-a-simple-twitter-bot-with-node-js-part-2-do-more-2ef1e039715d)
- [30분 만에 간단한 검색 봇 만들기](https://medium.freecodecamp.org/how-to-build-a-simple-search-bot-in-30-minutes-eb56fcedcdb1)
- [직업 스크래핑 웹 앱 만들기](https://medium.freecodecamp.org/how-i-built-a-job-scraping-web-app-using-node-js-and-indreed-7fbba124bbdc)
- [GitHub 앱 만들기](https://blog.scottlogic.com/2017/05/22/gifbot-github-integration.html)
- JavaScript, Node.JS, MongoDB, 웹 소켓을 사용하여 나만의 Uber-for-X 앱 만드는 방법
  - [1부](https://www.ashwinhariharan.tech/blog/how-to-build-your-own-uber-for-x-app/)
  - [2부](https://www.ashwinhariharan.tech/blog/how-to-build-your-own-uber-for-x-app-part-2/)

#### Vue

- [Vue 2 + Firebase: 15분 만에 Firebase 인증 시스템으로 Vue 앱 만드는 방법](https://medium.com/@anas.mammeri/vue-2-firebase-how-to-build-a-vue-app-with-firebase-authentication-system-in-15-minutes-fdce6f289c3c)
- [Vue.js 애플리케이션 튜토리얼 – Vue로 간단한 예산 관리 앱 만들기](https://matthiashager.com/complete-vuejs-application-tutorial/)
- [Vue, GraphQL, Apollo로 블로그 만들기](https://scotch.io/tutorials/build-a-blog-with-vue-graphql-and-apollo-client)
- MEVN (MongoDB, Express, Vue, Node) 스택을 사용하여 풀 스택 웹 애플리케이션 만들기
  - [1부](https://medium.com/@anaida07/mevn-stack-application-part-1-3a27b61dcae0)
  - [2부](https://medium.com/@anaida07/mevn-stack-application-part-2-2-9ebcf8a22753)
- [Vue.js 할 일 목록 튜토리얼 (비디오)](https://www.youtube.com/watch?v=78tNYZUS-ps)
- [Vue 2 + Pub/Sub: 게임용 P2P 멀티유저 플랫폼 만들기](https://www.ably.io/tutorials/peer-to-peer-vue)

#### 기타 (Hapi, Express...):

- 프로그레시브 웹 애플리케이션 (PWA) 만들기
  - [1부](https://bitsofco.de/bitsofcode-pwa-part-1-offline-first-with-service-worker/)
  - [2부](https://bitsofco.de/bitsofcode-pwa-part-2-instant-loading-with-indexeddb/)
  - [3부](https://bitsofco.de/bitsofcode-pwa-part-3-push-notifications/)
- [JS로 네이티브 데스크톱 앱 만들기](https://medium.freecodecamp.org/build-native-desktop-apps-with-javascript-a49ede90d8e9)
- NodeJs, GraphQL, Hapi로 강력한 API 만들기
  - [1부](https://medium.com/@wesharehoodies/how-to-setup-a-powerful-api-with-nodejs-graphql-mongodb-hapi-and-swagger-e251ac189649)

#### D3.js

- [예제를 통해 D3 배우기](https://www.sitepoint.com/d3-js-data-visualizations/)
- [선 그래프 만드는 방법 배우기](https://medium.freecodecamp.org/learn-to-create-a-line-chart-using-d3-js-4f43f1ee716b)

### 게임 개발:

- [Phaser로 2D 벽돌깨기 게임 만들기](https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_breakout_game_Phaser)
- Phaser로 HTML5와 JavaScript로 플래피 버드 만들기
  - [1부](http://www.lessmilk.com/tutorial/flappy-bird-phaser-1)
  - [2부](http://www.lessmilk.com/tutorial/flappy-bird-phaser-2)

### 데스크톱 애플리케이션:

- [React와 Electron으로 데스크톱 채팅 앱 만들기](https://medium.freecodecamp.org/build-a-desktop-chat-app-with-react-electron-and-chatkit-744d168e6f2f)

### 기타:

- [20줄 미만의 코드로 웹 프레임워크 만드는 방법](https://www.pubnub.com/blog/build-yourself-a-web-framework-in-less-than-20-lines-of-code/)
- [나만의 Redux 만들기](https://zapier.com/engineering/how-to-build-redux/)
- [나만의 가상 DOM 작성 방법](https://medium.com/@deathmood/how-to-write-your-own-virtual-dom-ee74acc13060)
- [AWS에서 웹소켓으로 실시간 서버리스 GraphQL API 만들기](https://andrewgriffithsonline.com/blog/serverless-websockets-on-aws/)

## Kotlin:

- [Keddit - 안드로이드 애플리케이션 개발하면서 Kotlin 배우기](https://medium.com/@juanchosaravia/learn-kotlin-while-developing-an-android-app-introduction-567e21ff9664)

## Lua:

### LÖVE:

- BYTEPATH: Lua와 LÖVE로 완전한 게임 만들기
  - [0부: 소개](https://github.com/SSYGEN/blog/issues/30)
  - [1부: 게임 루프](https://github.com/SSYGEN/blog/issues/15)
  - [2부: 라이브러리](https://github.com/SSYGEN/blog/issues/16)
  - [3부: 방과 구역](https://github.com/SSYGEN/blog/issues/17)
  - [4부: 연습 문제](https://github.com/SSYGEN/blog/issues/18)
  - [5부: 게임 기본](https://github.com/SSYGEN/blog/issues/19)
  - [6부: 플레이어 기본](https://github.com/SSYGEN/blog/issues/20)
  - [7부: 플레이어 스탯과 공격](https://github.com/SSYGEN/blog/issues/21)
  - [8부: 적](https://github.com/SSYGEN/blog/issues/22)
  - [9부: 디렉터와 게임플레이 루프](https://github.com/SSYGEN/blog/issues/23)
  - [10부: 코딩 관행](https://github.com/SSYGEN/blog/issues/24)
  - [11부: 패시브](https://github.com/SSYGEN/blog/issues/25)
  - [12부: 더 많은 패시브](https://github.com/SSYGEN/blog/issues/26)
  - [13부: 스킬 트리](https://github.com/SSYGEN/blog/issues/27)
  - [14부: 콘솔](https://github.com/SSYGEN/blog/issues/28)
  - [15부: 최종](https://github.com/SSYGEN/blog/issues/29)

## Python:

### 웹 스크래핑:

- [Python으로 트위터 데이터 마이닝](https://marcobonzanini.com/2015/03/02/mining-twitter-data-with-python-part-1/)
- [Scrapy와 MongoDB로 웹사이트 스크래핑](https://realpython.com/blog/python/web-scraping-with-scrapy-and-mongodb/)
- [Python과 Selenium WebDriver로 스크래핑하는 방법](http://www.byperth.com/2018/04/25/guide-web-scraping-101-what-you-need-to-know-and-how-to-scrape-with-python-selenium-webdriver/)
- [BeautifulSoup를 사용하여 어떤 영화를 볼까](https://medium.com/@nishantsahoo.in/which-movie-should-i-watch-5c83a3c0f5b1)

### 웹 애플리케이션:

- [Flask로 마이크로블로그 만들기](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
- [Django로 블로그 웹 앱 만들기](https://tutorial.djangogirls.org/ko/)
- [나만의 모험 프레젠테이션 선택](https://www.twilio.com/blog/2015/03/choose-your-own-adventures-presentations-wizard-mode-part-1-of-3.html)
- [Flask와 RethinkDB로 할 일 목록 만들기](https://realpython.com/blog/python/rethink-flask-a-simple-todo-list-powered-by-flask-and-rethinkdb/)
- [Django와 테스트 주도 개발로 할 일 목록 만들기](http://www.obeythetestinggoat.com/)
- [Python으로 RESTful 마이크로서비스 만들기](http://www.skybert.net/python/developing-a-restful-micro-service-in-python/)
- [Docker, Flask, React로 마이크로서비스 만들기](https://testdriven.io/)
- [Flask로 간단한 웹 앱 만들기](https://pythonspot.com/flask-web-app-with-python/)
- [20분 안에 Django API 만들기](https://codeburst.io/create-a-django-api-in-under-20-minutes-2a082a60f6f3)
- Django, Postgres, JavaScript로 커뮤니티 기반 배달 애플리케이션 만들기
  - [1부](https://www.ashwinhariharan.tech/blog/thinking-of-building-a-contact-tracing-application-heres-what-you-can-do-instead/)
  - [2부](https://www.ashwinhariharan.tech/blog/thinking-of-building-a-contact-tracing-application-heres-what-you-can-do-instead-part-2/)
- Vue, django-notifs, RabbitMQ, uWSGI로 실시간 채팅 애플리케이션 만들기
  - [1부](https://danidee10.github.io/2018/01/01/realtime-django-1.html)
  - [2부](https://danidee10.github.io/2018/01/03/realtime-django-2.html)
  - [3부](https://danidee10.github.io/2018/01/07/realtime-django-3.html)
  - [4부](https://danidee10.github.io/2018/01/10/realtime-django-4.html)
  - [5부](https://danidee10.github.io/2018/01/13/realtime-django-5.html)
  - [6부](https://danidee10.github.io/2018/03/12/realtime-django-6.html)

### 봇:

- [레딧 봇 만들기](http://pythonforengineers.com/build-a-reddit-bot-part-1/)
- [레딧 봇 만드는 방법 - YouTube](https://www.youtube.com/watch?v=krTUf7BpTc0) (비디오)
- [페이스북 메신저 봇 만들기](https://blog.hartleybrody.com/fb-messenger-bot/)
- [레딧 + 페이스북 메신저 봇 만들기](https://pythontips.com/2017/04/13/making-a-reddit-facebook-messenger-bot/)
- Python으로 텔레그램 봇 만드는 방법
  - [1부](https://khashtamov.com/en/how-to-create-a-telegram-bot-using-python/)
  - [2부](https://khashtamov.com/en/how-to-deploy-telegram-bot-django/)
- [Python으로 트위터 봇 만들기](https://medium.freecodecamp.org/creating-a-twitter-bot-in-python-with-tweepy-ac524157a607)

### 데이터 과학:

- 여러 프로젝트를 수행하며 데이터 과학을 위한 Python 배우기 (비디오):
  - [1부: 소개](https://www.youtube.com/watch?v=T5pRlIbr6gg)
  - [2부: 트위터 감정 분석](https://www.youtube.com/watch?v=o_OZdbCzHUA)
  - [3부: 추천 시스템](https://www.youtube.com/watch?v=9gBC9R-msAk&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU&index=3)
  - [4부: 주가 예측](https://www.youtube.com/watch?v=SSu00IRRraY&index=4&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU)
  - [5부: TensorFlow로 딥 드림](https://www.youtube.com/watch?v=MrBzgvUNr4w&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU&index=5)
  - [6부: 유전 알고리즘](https://www.youtube.com/watch?v=dSofAXnnFrY&index=6&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU)

### 머신 러닝:

- [Python으로 처음부터 선형 회귀 작성](https://www.youtube.com/watch?v=uwwWVAgJBcM) (비디오)
- [Python으로 단계별 머신 러닝](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)
- [와인 품질 예측](https://medium.freecodecamp.org/using-machine-learning-to-predict-the-quality-of-wines-9e2e13d7480d)
- [과일 분류 문제 해결](https://towardsdatascience.com/solving-a-simple-classification-problem-with-python-fruits-lovers-edition-d20ab6b071d2)
- [Python으로 비지도 학습 배우기](https://scikit-learn.org/stable/unsupervised_learning.html)
- [Python으로 처음부터 나만의 신경망 만들기](https://towardsdatascience.com/how-to-build-your-own-neural-network-from-scratch-in-python-68998a08e4f6)
- [sklearn 없이 Python으로 선형 회귀](https://medium.com/we-are-orb/linear-regression-in-python-without-scikit-learn-50aef4b8d122)
- [sklearn 없이 다변량 선형 회귀](https://medium.com/we-are-orb/multivariate-linear-regression-in-python-without-scikit-learn-7091b1d45905)
- [KNN을 사용한 음악 추천기](https://towardsdatascience.com/how-to-build-a-simple-song-recommender-296fcbc8c85)
- 유사한 Quora 질문 찾기-
  - [BOW, TFIDF, Xgboost 사용](https://towardsdatascience.com/finding-similar-quora-questions-with-bow-tfidf-and-random-forest-c54ad88d1370)
  - [Word2Vec, Xgboost 사용](https://towardsdatascience.com/finding-similar-quora-questions-with-word2vec-and-xgboost-1a19ad272c0d)
- [Python과 머신 러닝으로 가짜 뉴스 탐지](https://data-flair.training/blogs/advanced-python-project-detecting-fake-news/)

### OpenCV:

- [문서 스캐너 만들기](https://www.pyimagesearch.com/2014/09/01/build-kick-ass-mobile-document-scanner-just-5-minutes/)
- [OpenCV와 딥 러닝으로 얼굴 탐지기 만들기](https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/)
- [YOLOv3를 사용하여 가장 빠른 사용자 정의 객체 감지 시스템 구축(비디오 재생 목록)](https://www.youtube.com/playlist?list=PLKHYJbyeQ1a0oGzgRXy-QwAN1tSV4XZxg)
- [OpenCV, Python, 딥 러닝으로 얼굴 인식 시스템 만들기](https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/)
- [이미지에서 두드러진 특징 감지](https://www.pyimagesearch.com/2018/07/16/opencv-saliency-detection/)
- [바코드 스캐너 만들기](https://www.pyimagesearch.com/2018/05/21/an-opencv-barcode-and-qr-code-scanner-with-zbar/)
- [Python으로 얼굴 클러스터링 배우기](https://www.pyimagesearch.com/2018/07/09/face-clustering-with-python/)
- [Camshift로 객체 추적](https://www.pyimagesearch.com/wp-content/uploads/2014/11/opencv_crash_course_camshift.pdf)
- [OpenCV와 딥 러닝으로 시맨틱 세그멘테이션](https://www.pyimagesearch.com/2018/09/03/semantic-segmentation-with-opencv-and-deep-learning/)
- [이미지 및 비디오에서 텍스트 감지](https://www.pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector/)
- [OpenCV로 사람 수 세기](https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/)
- [OpenCV로 여러 객체 추적](https://www.pyimagesearch.com/2018/08/06/tracking-multiple-objects-with-opencv/)
- [OpenCV로 뉴럴 스타일 트랜스퍼](https://www.pyimagesearch.com/2018/08/27/neural-style-transfer-with-opencv/)
- [OpenCV OCR 및 텍스트 인식](https://www.pyimagesearch.com/2018/09/17/opencv-ocr-and-text-recognition-with-tesseract/)
- [텍스트 기울기 보정 튜토리얼](https://www.pyimagesearch.com/2017/02/20/text-skew-correction-opencv-python/)
- [얼굴 랜드마크 감지 튜토리얼](https://www.pyimagesearch.com/2017/04/03/facial-landmarks-dlib-opencv-python/)
- [Mask-R-CNN을 사용한 객체 감지](https://www.learnopencv.com/deep-learning-based-object-detection-and-instance-segmentation-using-mask-r-cnn-in-opencv-python-c/)
- [자동 표적 감지 튜토리얼](https://www.pyimagesearch.com/2015/05/04/target-acquired-finding-targets-in-drone-and-quadcopter-video-streams-using-python-and-opencv/)
- [OpenCV를 사용한 EigenFaces](https://www.learnopencv.com/eigenface-using-opencv-c-python/)
- [더 빠른(5점) 얼굴 랜드마크 감지 튜토리얼](https://www.pyimagesearch.com/2018/04/02/faster-facial-landmark-detector-with-dlib/)
- [손 키포인트 감지](https://www.learnopencv.com/hand-keypoint-detection-using-deep-learning-and-opencv/)
- Dlib 상관 관계 객체 추적 -
  - [단일 객체 추적기](https://www.pyimagesearch.com/2018/10/22/object-tracking-with-dlib/)
  - [다중 객체 추적기](https://www.pyimagesearch.com/2018/10/29/multi-object-tracking-with-dlib/)
- [OpenCV와 Python으로 이미지 스티칭](https://www.pyimagesearch.com/2018/12/17/image-stitching-with-opencv-and-python/)
- [OpenCV로 인스턴스 세그멘테이션](https://www.pyimagesearch.com/2018/11/26/instance-segmentation-with-opencv/)
- [얼굴 마스크 감지기](https://www.pyimagesearch.com/2020/05/04/covid-19-face-mask-detector-with-opencv-keras-tensorflow-and-deep-learning/)

### 딥 러닝:

- [컨볼루션 신경망을 사용하여 얼굴 키포인트 감지](http://danielnouri.org/notes/2014/12/17/using-convolutional-neural-nets-to-detect-facial-keypoints-tutorial/)
- [Python과 OpenCV를 사용하여 평균 얼굴 생성](https://www.learnopencv.com/average-face-opencv-c-python-tutorial/)
- [CNN을 사용하여 보안 문자 시스템 해독](https://medium.com/@ageitgey/how-to-break-a-captcha-system-in-15-minutes-with-machine-learning-dbebb035a710)
- [사전 훈련된 Inception 모델을 사용하여 이미지 예측 제공](https://medium.com/google-cloud/keras-inception-v3-on-google-compute-engine-a54918b0058)
- [첫 CNN 만들기](https://hackernoon.com/deep-learning-cnns-in-tensorflow-with-gpus-cba6efe0acc2)
- [얼굴 인식 파이프라인 구축](https://hackernoon.com/building-a-facial-recognition-pipeline-with-deep-learning-in-tensorflow-66e7645015b8)
- [이미지 캡션 생성기 만들기](https://medium.freecodecamp.org/building-an-image-caption-generator-with-deep-learning-in-tensorflow-a142722e9b1f)
- [나만의 얼굴 인식 시스템 만들기](https://medium.freecodecamp.org/making-your-own-face-recognition-system-29a8e728107c)
- [20분 만에 언어 감지 AI 훈련](https://towardsdatascience.com/how-i-trained-a-language-detection-ai-in-20-minutes-with-a-97-accuracy-fdeca0fb7724)
- [신경망을 이용한 객체 감지](https://towardsdatascience.com/object-detection-with-neural-networks-a4e2c46b4491)
- 트위터 감정 분석 배우기 -
  - [1부 - 데이터 정제](https://towardsdatascience.com/another-twitter-sentiment-analysis-bb5b01ebad90)
  - [2부 - EDA, 데이터 시각화](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-2-333514854913)
  - [3부 - Zipf의 법칙, 데이터 시각화](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-3-zipfs-law-data-visualisation-fc9eadda71e7)
  - [4부 - 특징 추출(카운트 벡터화기)](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-4-count-vectorizer-b3f4944e51b5)
  - [5부 - 특징 추출(Tfidf 벡터화기)](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-5-50b4e87d9bdd)
  - [6부 - Doc2Vec](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-6-doc2vec-603f11832504)
  - [7부 - 구문 모델링 + Doc2Vec](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-7-phrase-modeling-doc2vec-592a8a996867)
  - [8부 - 차원 축소](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-8-dimensionality-reduction-chi2-pca-c6d06fb3fcf3)
  - [9부 - Tfdif 벡터를 사용한 신경망](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-9-neural-networks-with-tfidf-vectors-using-d0b4af6be6d7)
  - [10부 - word2vec/doc2vec을 사용한 신경망](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-10-neural-network-with-a6441269aa3c)
  - [11부 - Word2Vec을 사용한 CNN](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-11-cnn-word2vec-41f5e28eda74)
- [사용자 정의 이미지 분류를 위한 전이 학습 사용](https://becominghuman.ai/transfer-learning-retraining-inception-v3-for-custom-image-classification-2820f653c557)
- [11줄의 Python으로 간단한 신경망 코딩 배우기](https://iamtrask.github.io/2015/07/12/basic-python-network/)
- [경사 하강법 접근 방식을 사용하여 신경망 구축](https://iamtrask.github.io/2015/07/27/python-network-part2/)
- [색상 생성을 위한 Keras 모델 훈련](https://heartbeat.fritz.ai/how-to-train-a-keras-model-to-generate-colors-3bc79e54971b)
- [사용자 정의 데이터셋에서 Keras 시작하기](https://www.pyimagesearch.com/2018/09/10/keras-tutorial-how-to-get-started-with-keras-deep-learning-and-python/)
- [Faces94 데이터셋에서 EigenFaces 및 FisherFaces 사용](https://nicholastsmith.wordpress.com/2016/02/18/eigenfaces-versus-fisherfaces-on-the-faces94-database-with-scikit-learn/)
- [Kaggle MNIST 숫자 인식기 튜토리얼](https://medium.com/@lvarruda/how-to-get-top-2-position-on-kaggles-mnist-digit-recognizer-48185d80a2d4)
- [tf.keras를 사용한 Fashion MNIST 튜토리얼](https://medium.com/tensorflow/hello-deep-learning-fashion-mnist-with-keras-50fcff8cd74a)
- [Keras를 사용하여 뿌리 건강을 자동으로 분류하는 CNN](https://www.pyimagesearch.com/2018/10/15/deep-learning-hydroponics-and-medical-marijuana/)
- [Keras 대 Tensorflow](https://www.pyimagesearch.com/2018/10/08/keras-vs-tensorflow-which-one-is-better-and-which-one-should-i-learn/)
- [말라리아 검출을 위한 딥 러닝 및 의료 영상 분석](https://www.pyimagesearch.com/2018/12/03/deep-learning-and-medical-image-analysis-with-keras/)
- [Keras를 사용한 이미지 분류를 위한 전이 학습](https://towardsdatascience.com/transfer-learning-for-image-classification-using-keras-c47ccf09c8c8)
- [Python에서 CNN을 사용하여 미소 분류기 코딩](https://github.com/kylemcdonald/SmileCNN)
- [scikit-learn을 사용한 자연어 처리](https://towardsdatascience.com/natural-language-processing-count-vectorization-with-scikit-learn-e7804269bb5e)
- [테일러 스위프트 가사 생성기 코딩](https://towardsdatascience.com/ai-generates-taylor-swifts-song-lyrics-6fd92a03ef7e)
- [PyTorch Lightning을 사용한 마스크 감지](https://towardsdatascience.com/how-i-built-a-face-mask-detector-for-covid-19-using-pytorch-lightning-67eb3752fd61)

### 기타:

- [간단한 인터프리터 만들기](https://ruslanspivak.com/lsbasi-part1/)
- [Python으로 간단한 블록체인 만들기](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)
- [Python으로 NoSQL 데이터베이스 작성](https://jeffknupp.com/blog/2014/09/01/what-is-a-nosql-database-learn-by-writing-one-in-python/)
- [OpenCV/Python/iOS로 주유 펌프 스캐너 만들기](https://hackernoon.com/building-a-gas-pump-scanner-with-opencv-python-ios-116fe6c9ae8b)
- [Python과 Kafka로 분산 스트리밍 시스템 만들기](https://codequs.com/p/S14jQ5UyG/build-a-distributed-streaming-system-with-apache-kafka-and-python)
- [기본 Python으로 처음부터 x86-64 JIT 컴파일러 작성](https://csl.name/post/python-jit/)
- 저수준 (리눅스) 디버거 만들기
  - [1부](https://blog.asrpo.com/making_a_low_level_debugger)
  - [2부: C](https://blog.asrpo.com/making_a_low_level_debugger_part_2)
- 검색 엔진 구현
  - [1부](http://www.ardendertat.com/2011/05/30/how-to-implement-a-search-engine-part-1-create-index/)
  - [2부](http://www.ardendertat.com/2011/05/31/how-to-implement-a-search-engine-part-2-query-index/)
  - [3부](http://www.ardendertat.com/2011/07/17/how-to-implement-a-search-engine-part-3-ranking-tf-idf/)
- [인생 게임 만들기](https://robertheaton.com/2018/07/20/project-2-game-of-life/)
- [터미널 ASCII 아트 만들기](https://robertheaton.com/2018/06/12/programming-projects-for-advanced-beginners-ascii-art/)
- [틱택토 AI 작성](https://robertheaton.com/2018/10/09/programming-projects-for-advanced-beginners-3-a/)
- [포토모자이크 아트 만들기](https://robertheaton.com/2018/11/03/programming-project-4-photomosaics/)
- [터미널에서 "스네이크" 게임 만들기](https://robertheaton.com/2018/12/02/programming-project-5-snake/)
- [나만의 Git 작성](https://wyag.thb.lt/)
- [Python으로 작성된 Python 바이트코드 실행기의 Python 구현](https://www.aosabook.org/en/500L/a-python-interpreter-written-in-python.html)
- [Python을 사용하여 음성 비서 만들기](https://www.geeksforgeeks.org/voice-assistant-using-python/)

## Go:

- [Golang, Angular 2, WebSocket으로 실시간 채팅 앱 만들기](https://www.thepolyglotdeveloper.com/2016/12/create-real-time-chat-app-golang-angular-2-websockets/)
- [Gin을 사용하여 Go 웹 애플리케이션 및 마이크로서비스 구축](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin)
- [Go에서 Godog를 사용하여 행동 주도 개발하는 방법](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go)
- Go로 블록체인 만들기
  - [1부: 기본 프로토타입](https://jeiwan.net/posts/building-blockchain-in-go-part-1/)
  - [2부: 작업 증명](https://jeiwan.net/posts/building-blockchain-in-go-part-2/)
  - [3부: 지속성 및 CLI](https://jeiwan.net/posts/building-blockchain-in-go-part-3/)
  - [4부: 트랜잭션 1](https://jeiwan.net/posts/building-blockchain-in-go-part-4/)
  - [5부: 주소](https://jeiwan.net/posts/building-blockchain-in-go-part-5/)
  - [6부: 트랜잭션 2](https://jeiwan.net/posts/building-blockchain-in-go-part-6/)
  - [7부: 네트워크](https://jeiwan.net/posts/building-blockchain-in-go-part-7/)
- [Go로 처음부터 컨테이너 만들기 - Liz Rice (Microscaling Systems)(비디오)](https://www.youtube.com/watch?v=8fi7uSYlOdc)
- [GoLang으로 웹 애플리케이션 만들기](https://astaxie.gitbooks.io/build-web-application-with-golang/content/ko/)
- Go와 ReactJS로 채팅 애플리케이션 만들기
  - [1부: 초기 설정](https://tutorialedge.net/projects/chat-system-in-go-and-react/part-1-initial-setup/)
  - [2부: 간단한 통신](https://tutorialedge.net/projects/chat-system-in-go-and-react/part-2-simple-communication/)
  - [3부: 프론트엔드 디자인](https://tutorialedge.net/projects/chat-system-in-go-and-react/part-3-designing-our-frontend/)
  - [4부: 여러 클라이언트 처리](https://tutorialedge.net/projects/chat-system-in-go-and-react/part-4-handling-multiple-clients/)
  - [5부: 프론트엔드 개선](https://tutorialedge.net/projects/chat-system-in-go-and-react/part-5-improved-frontend/)
  - [6부: 백엔드 Dockerize](https://tutorialedge.net/projects/chat-system-in-go-and-react/part-6-dockerizing-your-backend/)
- [Go WebAssembly 튜토리얼 - 계산기 튜토리얼 만들기](https://tutorialedge.net/golang/go-webassembly-tutorial/)
- Go의 REST 서버
  - [1부 - 표준 라이브러리](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-1-standard-library/)
  - [2부 - 라우터 패키지 사용](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-2-using-a-router-package/)
  - [3부 - 웹 프레임워크 사용](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-3-using-a-web-framework/)
  - [4부 - OpenAPI 및 Swagger 사용](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-4-using-openapi-and-swagger/)
  - [5부 - 미들웨어](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-5-middleware/)
  - [6부 - 인증](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-6-authentication/)
  - [7부 - GraphQL](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-7-graphql/)
- Go로 URL 단축기 만들기 - Gin & Redis 사용
  - [1부 - 프로젝트 설정](https://www.eddywm.com/lets-build-a-url-shortener-in-go/)
  - [2부 - 스토리지 레이어](https://www.eddywm.com/lets-build-a-url-shortener-in-go-with-redis-part-2-storage-layer/)
  - [3부 - 짧은 링크 생성기](https://www.eddywm.com/lets-build-a-url-shortener-in-go-part-3-short-link-generation/)
  - [4부 - 전달](https://www.eddywm.com/lets-build-a-url-shortener-in-go-part-iv-forwarding/)
- [Go로 TCP 채팅 만들기(비디오)](https://www.youtube.com/watch?v=Sphme0BqJiY)
- [Go로 처음부터 BitTorrent 클라이언트 만들기](https://blog.jse.li/posts/torrent/)
- [Go, PostgreSQL, Docker를 사용한 REST API 마스터클래스(비디오 재생 목록) `진행 중`](https://www.youtube.com/watch?v=rx6CPDK_5mU&list=PLy_6D98if3ULEtXtNSY_2qN21VCKgoQAE)

## PHP:

- [Laravel로 블로그 만드는 방법](https://www.youtube.com/playlist?list=PLwAKR305CRO-Q90J---jXVzbOd4CDRbVx) (비디오)
- [나만의 블로그 만들기 (순수 PHP)](http://ilovephp.jondh.me.uk/en/tutorial/make-your-own-blog)
- [SilverStripe로 부동산 웹사이트 예제 만들기](https://www.silverstripe.org/learn/lessons/)
- [Laravel 5.4와 VueJS로 실시간 채팅 앱 만들기](https://www.youtube.com/playlist?list=PLXsbBbd36_uVjOFH_P25__XAyGsohXWlv) (비디오)
- [소셜 네트워크 만들기: Laravel 5 - Youtube](https://www.youtube.com/playlist?list=PLfdtiltiRHWGGxaR6uFtwZnnbcXqyq8JD) (비디오)
- Laravel로 모든 기능을 갖춘 멀티 테넌트 앱 만들기
  - [0부: 소개](https://medium.com/@ashokgelal/writing-a-full-featured-multi-tenant-laravel-app-from-scratch-a0e1a7350d9d)
  - [1부: 설정](https://medium.com/@ashokgelal/a-full-featured-multi-tenant-app-with-laravel-part-1-4049a3cc229d)
  - [2부: 역할 및 권한](https://medium.com/@ashokgelal/a-full-featured-multi-tenant-app-with-laravel-part-2-roles-and-permissions-d9a5bfe5d525)
  - [3부: 초대](https://medium.com/@ashokgelal/a-full-featured-multi-tenant-app-with-laravel-part-3-invitation-c982dca55eb9)
  - [4부: 인증](https://medium.com/@ashokgelal/a-full-featured-multi-tenant-app-with-laravel-part-4-tenancy-aware-authentication-e0ee37270bc8)
  - [5부: 테스트](https://medium.com/@ashokgelal/a-full-featured-multi-tenant-app-with-laravel-part-2-unit-tests-96d6dfbf0617)
  - [6부: 사용자 프로필](https://medium.com/@ashokgelal/a-full-featured-multi-tenant-app-with-laravel-part-5-user-profile-5c3d0c655f3a)
  - [7부: 배포](https://medium.com/@ashokgelal/a-full-featured-multi-tenant-app-with-laravel-part-7-deployment-40bb3c895627)
- [처음부터 Laravel CRUD 애플리케이션 만들기](https://www.codewall.co.uk/laravel-crud-demo-with-resource-controller-tutorial/)

## OCaml:

- [OCaml에서 LLVM으로 언어 구현](https://llvm.org/docs/tutorial/#kaleidoscope-implementing-a-language-with-llvm-in-objective-caml)
- [OCaml로 게임보이 에뮬레이터 작성](https://linoscope.github.io/writing-a-game-boy-emulator-in-ocaml/)

## Ruby:

- [Ruby로 네트워크 스택 만들기](https://medium.com/geckoboard-under-the-hood/how-to-build-a-network-stack-in-ruby-f73aeb1b661b)
- 나만의 Redis 만들기
  - [0부: 소개](https://rohitpaulk.com/articles/redis-0)
  - [1부: 기본 TCP 서버](https://rohitpaulk.com/articles/redis-1)
  - [2부: PING <-> PONG](https://rohitpaulk.com/articles/redis-2)
  - [3부: 동시 클라이언트](https://rohitpaulk.com/articles/redis-3)
  - [4부: ECHO](https://rohitpaulk.com/articles/redis-4)
- [Ruby로 Git 재구축](https://thoughtbot.com/blog/rebuilding-git-in-ruby)

### Ruby on Rails:

- [루비 온 레일즈 튜토리얼](https://www.railstutorial.org/book)
- [Ruby on Rails로 처음부터 인스타그램 만들기](https://www.dropbox.com/s/9vq430e9s3q7pu8/Let%27s%20Build%20Instagram%20with%20Ruby%20on%20Rails%20-%20Free%20Edition.pdf?dl=0)
- [Rails를 사용하여 소셜 네트워크 만들기](https://medium.com/rails-ember-beyond/how-to-build-a-social-network-using-rails-eb31da569233)
- [Ruby on Rails 애플리케이션 만드는 방법](https://www.digitalocean.com/community/tutorials/how-to-build-a-ruby-on-rails-application)

## Haskell:

- [Haskell 작성 - 최신 함수형 컴파일러 만들기](http://dev.stephendiehl.com/fun/)
- [48시간 안에 Scheme 작성하기](https://ko.wikibooks.org/wiki/48%EC%8B%9C%EA%B0%84_%EC%95%88%EC%97%90_Scheme_%EC%9E%91%EC%84%B1%ED%95%98%EA%B8%B0)
- [Scheme 작성하기, 버전 2](https://github.com/write-you-a-scheme-v2/scheme)
- [나만의 IRC 봇 만들기](https://wiki.haskell.org/Roll_your_own_IRC_bot)
- [Movie Monad 만들기](https://lettier.github.io/posts/2016-08-15-making-movie-monad.html)
- [Haskell로 웹사이트 만들기 **(오래됨)**](http://adit.io/posts/2013-04-15-making-a-website-with-haskell.html)

## R:

- [Shiny로 웹 앱 만들기](http://shiny.rstudio.com/tutorial/)
- [암호화폐 봇 만들기](https://towardsdatascience.com/build-a-cryptocurrency-trading-bot-with-r-1445c429e1b1)
- [R에서 연관 규칙 마이닝 배우기](https://towardsdatascience.com/association-rule-mining-in-r-ddf2d044ae50)

## Rust:

- Rust로 간단한 웹 앱 만들기
  - [1부](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-1/)
  - [2a부](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-2a/)
  - [2b부](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-2b/)
- [순수 Rust로 OS 작성](https://os.phil-opp.com/)
- [Rust로 브라우저 엔진 만들기](https://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html)
- [Rust로 마이크로서비스 작성](http://www.goldsborough.me/rust/web/tutorial/2018/01/20/17-01-11-writing_a_microservice_in_rust/)
- [너무 많은 연결 리스트로 Rust 배우기](http://cglab.ca/~abeinges/blah/too-many-lists/book/README.html)
- Rust 상세: 처음부터 확장 가능한 채팅 서비스 작성
  - [1부: WebSocket 구현. 소개.](https://nbaksalyar.github.io/2015/07/10/writing-chat-in-rust.html)
  - [2부: 메시지 송수신](https://nbaksalyar.github.io/2015/11/09/rust-in-detail-2.html)
- [데스크톱 및 웹용 Rust 로그라이크 작성](https://aimlesslygoingforward.com/blog/2019/02/09/writing-a-rust-roguelike-for-the-desktop-and-the-web/)
- [Rust를 사용한 단일 페이지 애플리케이션](http://www.sheshbabu.com/posts/rust-wasm-yew-single-page-application/)
- [Rust로 NES 에뮬레이터 작성](https://bugzmanov.github.io/nes_ebook/)
- 신경망과 유전 알고리즘을 사용하여 진화 시뮬레이션 만들고 애플리케이션을 WebAssembly로 컴파일
  - [1부](https://pwy.io/en/posts/learning-to-fly-pt1/)
  - [2부](https://pwy.io/en/posts/learning-to-fly-pt2/)
  - [3부](https://pwy.io/en/posts/learning-to-fly-pt3/)
  - [4부](https://pwy.io/en/posts/learning-to-fly-pt4/)

## Scala:

- [간단한 액터 기반 블록체인](https://www.freecodecamp.org/news/how-to-build-a-simple-actor-based-blockchain-aac1e996c177/)
- [마법 없음: 정규 표현식](https://rcoh.svbtle.com/no-magic-regular-expressions)

## Swift:

- [Swift로 해킹하기 - 39개 프로젝트를 수행하며 Swift 배우기](https://www.hackingwithswift.com/read)
- [처음부터 만드는 레트로 1인칭 슈팅 게임](https://github.com/nicklockwood/RetroRampage)

## 추가 자료

- [React Redux 링크](https://github.com/markerikson/react-redux-links)
- [Udemy.com](https://www.udemy.com/)
- [풀 스택 파이썬](https://www.fullstackpython.com/)
- [노드 스쿨](https://nodeschool.io/)
- [ScotchIO](https://scotch.io/)
- [Exercism](http://www.exercism.io/)
- [Egghead.io](http://www.egghead.io/)
- [마이클 허먼 블로그](http://mherman.org/)
- [Thinkster.io](http://thinkster.io)
- [Enlight](https://enlight.nyc/)
- [핵 클럽 워크숍](https://hackclub.com/workshops/)
- [CodeCrafters](https://codecrafters.io/)
