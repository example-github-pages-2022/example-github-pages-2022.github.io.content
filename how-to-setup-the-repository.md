## Theme

```console
$ mkdir -p themes
$ git submodule add https://github.com/mazgi/hugo-theme-techlog-simple.git themes/techlog-simple
```

## Local Preview

```console
docker-compose up
```

You are able to open the preview on the URL http://localhost:1313/ .

## Write a Post

```console
$ mkdir -p content/posts/2022/07/first-post
```

If you are a Visual Studio user, you are able to open drafts as follows.

```console
$ code content/posts/2022/07/first-post/index.en.md
$ code content/posts/2022/07/first-post/index.ja.md
```
