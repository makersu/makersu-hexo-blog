title: GitHub Pages by Hexo
date: 2015-01-17 11:48:47
tags: hexo
---
## Create by hexo
``` bash
$ npm install hexo -g
$ git clone https://github.com/makersu/makersu-hexo-blog.git
$ hexo init makersu-hexo-blog
$ cd makersu-hexo-blog
$ npm install
$ hexo server
```

## Add Theme
```
$ git clone https://github.com/hexojs/hexo-theme-light.git themes/light
```

## Configuration(_config.yml)
```
...
theme: light
...
deploy:
  type: github
  repo: https://github.com/makersu/makersu.github.io.git
  branch: master
```

## Deploy to GitHub
``` bash
$ hexo deploy
```

## Reference
[GitHub Pages](https://pages.github.com/)
[Hexo](http://hexo.io/)
[Hexo on GitHub](https://github.com/hexojs/hexo)
[Default theme for Hexo](https://github.com/hexojs/hexo-theme-light)