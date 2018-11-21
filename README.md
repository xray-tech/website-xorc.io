## xorc.io

This repo contains the [Hugo](https://gohugo.io/) sources of [http://xorc.io](http://xorc.io)


### Installing
[See docs](https://gohugo.io/getting-started/quick-start/)

tl;dr:

```
brew install hugo
```

### Editing

Run a local server with a watchdog to reload the changes then open the local url [http://localhost:8080/](http://localhost:8080/)

```
hugo server -D -p 8080

```

The content to edit is in [data/en](data/en)

### Publishing

Generates the source in ./public

```
hugo
```

`./public` is a git submodule poiting to [xray-tech/xray-tech.github.io](https://github.com/xray-tech/xray-tech.github.io). Any sources pushed there are live

```
cd public
git add .
git push origin master
```






