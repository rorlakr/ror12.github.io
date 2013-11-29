---
layout: post
title: "'post' 모듈 생성하기"
description: ""
category: ""
tags: []
---
{% include JB/setup %}

이제 Post 모델을 생성해 보겠습니다. 

{% highlight bash %}
$ rails generate model Post title content:text
{% endhighlight %}

`digging deeper` : 레일스 디폴트 제너레이터에 대한 사용법

`posts` 테이블 생성하기 위해 아래와 같이 마이그레이션(migration) 작업을 합니다. 

{% highlight bash %}
$ rake db:migrate
{% endhighlight %}

`digging deeper` : `migration`이란 무엇인가?

이제 레일스 `console`을 실행하여 방금 생성된 `posts` 테이블을 `Post` 클래스를 이용하여 조작해 보도록 하겠습니다.

{% highlight bash %}
$ rake console
{% endhighlight %}

`digging deeper` : 레일스 `console` 사용법