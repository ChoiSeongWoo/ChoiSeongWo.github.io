---
title: "190106.TEST-코드하이라이터"
date: 2019-01-06 01:11:00 -0400
categories: 블로그
---


코드 하이라이터 임베딩 방법 확인
---

블로그에 소스코드를 올리는 방법에 대해 잠깐 알아보았다.
몇가지 방법이 있는 것 같은데, 그 중 가장 쉬운 방법은 gist(https://gist.github.com/)를 사용하는 것.
(광주과학기술원 말하는 거 아님.)

사용법은 매우 간단하다.<br>

1. 깃허브 아이디가 없을 시, 가입한 후 로그인.
2. 제목으로 <파일이름.확장자>를 적는다. (예, helloworld.py)
3. 소스코드를 붙여 넣는다.
4. `Create public gist` 클릭
5. Embed 스크립트 복사
6. 해당 포스트에 붙여넣기




Embed할 스크립트는 다음의 형식을 띄고있다.<br>
```<script src="https://gist.github.com/YOURID/*********.js"></script>```

**결과**
<script src="https://gist.github.com/ChoiSeongWoo/6b00e535009963b6d24d84ac79825979.js"></script>


추가
---
Github Pages에 Rouge라는 Highlighter가 있다는 것을 알게 되었고, 
내가 지금 사용하고 있는 Jekyll 테마에 이미 적용되어 있다는 것을 확인했다..
위의 방법은 필요가 없다는 것.

Gist에 들어가서 Embeding 코드를 가져올 필요 없이 그냥 간단하게 다음의 방법을 사용하면 된다.
` ~~~python
import numpy
print("hello world")~~~ `

**결과**
~~~python
import numpy
print("hello world")~~~
