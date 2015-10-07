---
layout: page
title: 구성 초등학교 소프트웨어 교육
subtitle: 튜링 테스트
minutes: 10
---

> ### 학습 목표 {.objectives}
>
> *  튜링 테스트를 이해한다.

### 1. 애슐리 매디슨 해킹 사례

[애슐리 매디슨(Ashley Madison)](https://www.ashleymadison.com/)은 기혼자를 대상으로 한 온라인 데이트사이트로 최근에 해킹이 되면서 최근 사회적인 많은 이슈가 생산했다. 

- 나이트 클럽과 유사하게 사업모형은 남성은 유로, 여성은 무료 정책이지만, 여성 고객 확보에 어려움을 겪은 것으로 추정됨.
- 약 7만개 정도로 추정되는 [대화로봇(채팅봇, chatterbot)](https://en.wikipedia.org/wiki/Chatterbot)을 만들어 무료 남성고객을 유료로 전환시키거나, 대화로봇과는 결코 불륜이 일어나지 않기 때문에 지속적인 매출이 발생하는 효과를 창출함.

**대화로봇 소프트웨어**

- [엘리자(ELIZA, 1966)](https://en.wikipedia.org/wiki/ELIZA)
- [A.L.I.C.E.(Artificial Linguistic Internet Computer Entity)](https://en.wikipedia.org/wiki/Artificial_Linguistic_Internet_Computer_Entity)
- [Jabberwacky](https://en.wikipedia.org/wiki/Jabberwacky)

[정보통신기술진흥센터, 불륜 사이트가 보여준 기술력, 남성의 대화상대는 로봇](http://www.kosen21.org/work/03_information/0302_gtbReports/board_kosencollect_detailview.jsp?bid=0000000762076&id_major=0000000000762076)  
[Ashley Madison Code Shows More Women, and More Bots](http://gizmodo.com/ashley-madison-code-shows-more-women-and-more-bots-1727613924)  


### 2. 리캡챠(ReCAPTCHA)

[CAPTCHA](https://ko.wikipedia.org/wiki/CAPTCHA) 시스템은 흔히 웹사이트 회원가입을 할 때 자동가입방지 목적으로 많이 봐와서 익숙할 것이다. 사람이 기계를 사람인지 판별하는 튜링테스트와는 반대로 기계가 사람인지 판별하는 때문에 역튜링테스트(Reverse Turing Test)라고 부른다. 방식은 텍스트와 이미지를 일그러뜨려 변형한 후 인식을 요청하는 방식으로 사람은 쉽게 알 수 있지만, 컴퓨터는 인식률이 떨어져 사람인지 컴퓨터 프로그램인지를 판별할 수 있다.

리캡챠(reCAPTCHA, revision of Completely Automated Public Turing test to tell Computers and Humans Apart)는 카네기 멜론 대학교의 [Luis von Ahn](https://en.wikipedia.org/wiki/Luis_von_Ahn)가 주도되어 개발한 CAPTCHA 시스템이다. [CAPTCHA](https://ko.wikipedia.org/wiki/CAPTCHA)의 인터페이스와 비슷하게, [reCAPTCHA](https://ko.wikipedia.org/wiki/ReCAPTCHA)는 사용자에게 화면에 왜곡된 단어 이미지를 보여준 뒤, 보이는 대로 단어를 입력하라고 한다. 화면에 나타나는 두 개의 단어는 접근이 제한된 구역에 봇이 접근을 시도하는 것으로부터 보호할 뿐만 아니라 실제 책의 내용을 디지털화하는 데 도움을 준다. 

[Luis von Ahn](https://en.wikipedia.org/wiki/Luis_von_Ahn)은 과테말라 출신으로 2009년 reCAPTCHA를 구글에 매각하고 [Duolingo](https://www.duolingo.com/)를 창업하기도 했다. 컴퓨터가 텍스트를 해독하데 한계가 다른 영역 발전에 큰 저해요인이 될 것으로 판단해서 인간 컴퓨터(Human Computer)를 크라우드 소싱(Crowd Sourcing) 방식으로 이용하기로 해서 reCAPTCHA를 개발했다. reCAPTCHA는 기계가 사람인지를 판별할 수 있을 뿐만 아니라, 다음 세대를 위한 전세계 책을 디지털화하는데 도움도 주고 있다. 

**"계산(Compute)"**은 계산하고 추산한다는 의미로, 단순히 보면 **"컴퓨터(Computer)"**는 정보를 계산하고 추산하는 기계다. 수천년에 걸처 인간이 계산기, 즉 컴퓨터로 역할을 해왔고, 인류 역사에서 근래에 들어 컴퓨터를 사용해서 계산하고 추산하는 기계를 만들어서 인간을 대신 혹은 인간을 위해서 활용하기 시작했다.

컴퓨터가 인간을 위해서 일을 하기도 하지만, 인간이 컴퓨터를 위해서 일을 대신하기도 한다. 회사 생활을 하게 되면 전사자원관리(ERP, Enterprise Resource Planning) 시스템을 위해 사람이 일을 하고 작업결과를 컴퓨터에 넣어 주는 것으로도 볼 수 있다. 

> ### 인간 기반 연산 (Human-based computation) {.callout}
>
> 인간 기반 연산(Human-based computation)이란, 연산(computation) 단계의 일부분을 사람에게 외주를 주어 특정 기능을 수행하게 하면서 연산을 수행해 나가는 기법이다. 
> 인간과 컴퓨터 사이의 능력차를 활용, 즉 인간과 컴퓨터 간의 비용차를 잘 활용하여 목적을 달성하는 것이다.
> 전통적으로 인간은 컴퓨터를 동원해 문제를 해결했다: 인간이 정형화된 문제를 컴퓨터에게 제시하면, 컴퓨터가 답안을 제시했다. "인간 기반 연산" 분야에 있어서는, 이 역할이 뒤바뀐다: 컴퓨터가 사람 혹은 다수 인간 집단에게 풀 문제를 제시한다. 이를 통상 **크라우드 소싱(Crowd Sourcing)**이라고 부른다. 그 후 컴퓨터가 인간들이 외주 작업한 결과를 취합하여 컴퓨터 작업 결과와 합쳐 가장 높은 품질이지만 가장 최소의 비용으로 효율적인 산출물을 만들어 낸다. [위키: 인간 기반 연산](https://ko.wikipedia.org/wiki/인간_기반_연산)

인간이 컴퓨터와 비교하여 비교우위가 있는 작업이 있다. 얼굴 인식, 번역, 상상력 등의 분야에서는 컴퓨터가 따라올 수 있는 경쟁우위가 있다. 반면에, 컴퓨터는 정확성, 단순 반복, 성실성, 경제성 등의 분야에서 상대 우위가 있다. 따라서, 인간과 컴퓨터를 조합해서 과거에 복잡하고 고비용으로 포기한 작업을 효율적이고 빠르게 높은 정확성을 갖고 추진할 수 있는 길이 열렸다. 예를 들어, 인간이 작업을 분석하여 컴퓨터가 잘 소화할 수 있게 만들어 컴퓨터에 맡겨서 전체 프로젝트를 완성하는 것이다.

#### 2.1. 사례

- [리캡차(reCAPTCHA)](https://ko.wikipedia.org/wiki/CAPTCHA): 물리적 텍스트를 디지털화
- [듀오링고(Duolingo)](https://www.duolingo.com/): 월드와이드웹(WWW)을 다른 언어로 번역 [Duolingo -- the next chapter in human computation | Luis von Ahn | TEDxCMU 2011](https://www.youtube.com/watch?v=cQl6jUjFjp4)
- [미케니컬 터크(Mechanical Turk)](https://www.mturk.com/): 아마존에서 운영하는 인간 기반 연산을 현실에서 구현할 수 있게 하는 서비스.
- [킥스타터(KickStarter)](https://www.kickstarter.com/): 많은 스타트업이 활용하는 플랫폼으로 스타트업이나 개인이 제품이나 서비스를 제작해서 웹사이트에 올리면 사용자가 평가하고 일정 자금이 모아지면 스타트업이나 프로젝트를 제시한 개인은 개발을 시작하고 결과물을 사용자에게 전달하는 사이트. [킥스타터(KickStarter)](https://www.kickstarter.com/)외에도 [인디고고(Indiegogo)](https://www.indiegogo.com/)가 외국인이 많이 사용하는 유사 크라우드 플랫폼이다.
- [Fold.it](http://fold.it/): 과학을 위한 퍼즐을 풀 수 있는 웹서비스.

[ReCAPTCHA - Humans are computers, too!](https://canvas.instructure.com/courses/884561/pages/recaptcha-humans-are-computers-too)


