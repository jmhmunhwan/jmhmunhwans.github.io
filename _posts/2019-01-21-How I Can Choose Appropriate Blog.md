---
layout: post
title: 어떤 블로그를 쓸 것인가?
subtitle: 네이버 블로그 / 티스토리 / 구글 블로그스팟/ 깃허브 페이지
gh-repo: jmhmunhwan/jmhmunhwan.github.io
gh-badge: [star, fork, follow]
category : devlog
tags: blog
comments: true
---

![Blog](https://t1.daumcdn.net/cfile/tistory/22498D3353DE517715)

개발에 대해 올릴 블로그를 도대체 뭐로 쓸까 한참 찾아보다 이에 대해 정리하는 것도 좋을 듯 하여 이 포스트를 작성합니다.
**기술** 블로그를 운영하는 **목적**은 개인적으로 크게 3가지로 생각됩니다.
```
  1. 공부한 내용 정리
  2. 공유
  3. 기술적 커리어 노출
```
이건 아마 아래와 같은 느낌이지 않을까 합니다.
```
  1. 공부한 내용 정리 → 다음에 똑같은 문제로 고통받지 않겠다.
  2. 공유 → 수익 창출?
  3. 기술적 커리어 노출 → 이직에 도움(?)
```

>"어떤 블로그를 쓸 것인가?"
```
  1. 친숙함/편리함 : 블로그 작성이 쉬웠으면 좋겠다.
  2. 접근성 : 네이버, 구글에서 검색 노출이 잘 되었으면 좋겠다.
  3. 디자인/편의성 : 이왕 하는 거 좀 멋있는 걸로 하고싶다.
```

|분류| 네이버 블로그 | 티스토리 | 구글 블로그스팟 | 깃허브 페이지 |
|:--- | :--- |:--- | :--- | :--- |
|친숙함/편리함| 익숙/편함 | 익숙/편함 | 있는지 이번에 알게 됨/나쁘지 않음 | 어렵고 복잡/HTML 페이지 만드는 느낌이 좀.. |
|접근성| 네이버에서만? | 둘 다 괜찮 | 글쎄..아직 못 봄 | 기술 페이지 링크로만 봄 |
|디자인/편의성| default | 테마 지원 | 테마 지원 | CSS 및 마크다운 적용 가능 |
|특이사항| 기본 | 초대장은 옛날 이야기 | 구글 애드센스 쓰기에 좋아보임 | 팀 블로그로 사용 가능(블로그도 커밋된다!) |

요즘은 HTML 태그가 뭔지만 알면 블로그에서 다 사용할 수 있습니다. HTML/외부컨텐츠 같은 버튼을 따로 누르거나 작성 중인 문서 내에 직접 HTML 코드를 입력이 가능하거나 각각 방법은 달라서 직접 확인 해야합니다. 기술 블로그를 작성하게 되면 코드 내용이나 커맨드를 보여줘야 하는 일이 많은데, 개인적으로 마크다운을 통해 좀 있어보이게 작성 할 수 있습니다. 

개인적으로는 깃허브 페이지가 제일 기술 블로그로는 핫하지 않나 생각이 듭니다. 깃허브 페이지는 Team Project에서 자주 사용되는 [Slack](https://slack.com/), [Trello](https://trello.com/) 처럼 마크다운을 제공하여 사용자에게 강한 코드 분별력을 제공해줍니다. 그리고 [Github에서 Jekyll 로 검색](https://github.com/topics/jekyll-theme)해보면 이미 기존에 작성된 테마들이 있어서 쉽게 적용이 가능합니다. 

>[daattali/beautiful-jekyll](https://github.com/daattali/beautiful-jekyll) 적용하기
  1. fork 받기
  2. 깃허브 페이지 username.github.io 로 rename
  3. _config.yml 수정
 
>"깃허브 페이지 사용 후기"
```
따로 검색하지 않고 금방 흔히 보던 기술 블로그처럼 만들어 보는 데 성공했습니다. 하지만 실제 써보니 좀 불편한 점이 생기네요.
지금은 |(bar)를 이용해 표 작성한 상태인데, 사이즈가 안 맞아 글자가 한 줄 씩 내려가는 것들이 맘에 안 드네요.
또한, 특수 기호나 다른 기능을 쓰기가 쉽지 않습니다.
이미지 또한 Drag and Drop 식으로 쉽게 사이즈를 조절 할 수 없을 지 알아봐야겠네요.
깃허브 페이지는 직관적으로 쓸 수 있게 지원해주는 건 없습니다.
마크다운 사용법도 하나씩 익혀야하고 이미지, 특수문자, 표 등을 내가 원하는 위치와 크기에 맞게 적용하려면,
웹 UI 개발할 때 느끼던 어려움을 여기서 한번 더 겪게 될 지 모르겠네요.
또한, 제가 내용 수정 후 실제 Post가 바뀌기까지 시간이 오래 걸리는 단점이 있습니다.
장점은 github 프로젝트와 연동이 쉽습니다.
웹 개발에 익숙하고 마크다운을 몇 번 써본 사람이라면 오히려 다른 블로그 플랫폼들보다 더 쉽게 포스팅이 가능할 것 같습니다.
마크다운 적용한 것이 슬랙이나 트렐로 같은 다른 솔루션과도 반 이상은 그대로 적용되는 것 같습니다.(100% 안되니 단점인가..?)
```

### 나만의 결론
~~~
1. 블로그 딱히 꾸밀 생각이 없고, 그냥 편하게 운영하고 싶다. → 네이버 블로그
2. 블로그를 꾸밀 생각도 있고, 대중적인 곳에서 블로그를 운영하겠다. → 티스토리
3. 뭔가 딱히 이쁜 것 같지도 않은데, 그래도 구글이 민다니까 해보겠다. → 구글 블로그스팟
4. 난 좀 어려워도 진짜 개발자 느낌의 기술 블로그를 운영하겠다.(or 팀 블로그를 운영하겠다.) → 깃허브 페이지
~~~


(**수익적인 요소**나 **플랫폼 이사**가 가능한지도 중요하다고 생각해서 추가로 작성 예정..)

이 포스트는 깃허브 페이지(github.io)로 작성하였습니다.
