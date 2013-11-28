---
layout: post
title: "'blog' 프로젝트 생성하기"
description: ""
category: ""
comments : true
tags: []
---
{% include JB/setup %}


`blog` 레일스 프로젝트를 생성하고 프로젝트 디렉토리로 이동합니다.

{% highlight bash linenos %}
$ rails new blog && cd blog
{% endhighlight %}

다음은 제대로 프로젝트가 생성되었는지를 확인하기 위해 로컬 서버를 실행합니다.

{% highlight bash linenos %}
$ rails server        # server를 줄여서 "s"로 사용해도 됩니다.
($ rails s)
{% endhighlight %}

이제 아래와 같은 페이지가 보이면 제대로 blog 프로젝트가 생성된 것입니다.

![rails welcome](http://rails-guides.joefiorini.com/images/rails_welcome.png)