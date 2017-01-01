---
layout: post
comments: true
title:  "DISQUS 적용하기"
date:   2017-01-01 11:02:00 +0900
categories: kwakstory
---

DISQUS
------

간단하게 댓글 플러그인이라고 생각하면 쉽게 생각할 수 있을 것 같다.

jekyll 로 운영하는 블로그라 가볍게 운영할 수 있지만, 소통을 위한 댓글, 게시판 등의 기능을 구현하는데에는 당연하게도 제약이 따른다. 

하지만 요즘이 어떤 세상이랴,
약간만 불편해도 어떻게든 쉽게 해볼려고 발버둥 치는 세상이 아니던가.. ! ㅎㅎ

* [DISQUS 사이트 바로 가기](https://disqus.com/)



적용 후기
-------

일단 이 글을 작성하면서, disqus 가입 및 적용을 하는 중인데, 생각보다 허무하게(?) ctrl + c 한방에 댓글이... 로드가 되었다.. !!


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
