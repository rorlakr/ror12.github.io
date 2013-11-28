글작성법
====


게시물을 작성할 때는 아래와 같이 rake 명령을 실행합니다.

```
$ rake post title='title_of_post'
```

이제 `_posts` 디렉토리에서 방금 전에 생성한 마크다운 파일을 열고 글을 작성한 후에

```
$ git add .
$ git commit -m "created new post"
$ git push origin master
```

