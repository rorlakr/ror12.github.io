---
layout: post
title: "'post' 모듈 생성하기"
description: ""
category: ""
tags: []
---
{% include JB/setup %}

이제 Post 모델을 생성해 보겠습니다. 

{% highlight bash linenos %}
$ rails generate model Post title content:text
{% endhighlight %}

`posts` 테이블 생성하기 위해 아래와 같이 마이그레이션(migration) 작업을 합니다. 

{% highlight bash linenos %}
$ rake db:migrate
{% endhighlight %}
