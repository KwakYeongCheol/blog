---
layout: post
comments: true
title:  "jekyll 로 블로그 시작!"
date:   2016-12-27 23:30:24 +0900
categories: kwakstory
---

jekyll 을 사용해서 블로그를 시작해볼 예정이다.

markdown 문법도 익숙해질 겸, 내가 적고자 하는 내용을 메모장에서 두들기면(?) 되니 나름 편할 것 같다.

github page를 이용해서 별도로 서버를 구성하지는 않을 것이며, 
사용하는 맥북이 여러대가 되다보니 블로그를 작성하려 할 때마다 checkout 받은 후 정리하면 될 것 같다.



jekyll 사용
----------

themes, category, tags, 댓글(disqus) 등 이것저것 알아야할 것, 설정해야할 것들도 많긴 하지만, 
내 성격상 하나하나 검색해본 후 적용하려면 아마... 다시 도루묵이 되어 tistory 를 끄적이고 있을 것 같다.
그래서 가장 중요한 도전은 __일단 사용해볼 것__


개발 환경 정하기
------------

오랜만이라 감이 많이 죽었지만, 일단 잡아야할 환경은 개발 환경이다.
로컬 개발 환경에서의 1차적인 개발 후, 'push test', 'push production' 처럼 테스트 서버, 운영 서버로의 배포가 자동화되도록 설정해야 한다.
예전처럼 수동으로 커밋하고, 빌드하고, 배포할 수는 없는 노릇이 아닌가 :D


Spring Boot
-----------

backend 를 하기 위해서 nodejs를 한참 고민해봤으나, 크게 익숙하지도 않은 javascript 에 대한 부담 뿐만 아니라, express 도 어렵다 ;-(
그래도 사용해본 거라고 spring mvc 를 적용하려고 설정을 해봤지만, spring boot 를 보게 되었고, 이번 기회에 한 번 사용해보면 좋겠다 싶어서 
spring boot 로 정했다. 기본적인 사이트를 만드는 거라 크게 기술적인 부분을 개발하는 일은 없겠지만, security, social 등 직접 적용해보지
못했던 부분들도 이번 기회에 적용해보면 재밌을 것 같다.


WHY?
----

사실 개발을 접은 지도 오래되었을 뿐더러, 가장 최근에 다녔던 회사에서 개발에 대한 재미를 몽땅 잃어버린 채 노가다만 하다가 나온터라, 현재 사용하는 
대부분은 사실상 대학생 때 배웠던 것 뿐이다. 현재는 개발자가 아닌 '소매판매업'에 종사하는 장사꾼이 되었지만, 어차피 웹사이트 개발이라는 취미는
알아두면 알아둘 수록 유용한 취미가 아니던가! 그래서 1차적인 목표는 **쇼핑몰 비스무리한 것**. 와이프님의 지원도 있으니 두려울 것 없이! 다시 한 번
개발자로서 공부를 시작해보려고 한다 ^^ 누가 또 아는가, 이러다 다시 개발자 할지도 ㅎㅎ

<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = '//kwakyc.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
