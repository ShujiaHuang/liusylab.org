## [The website of liusyLab]

<liusylab.org> 

```bash
git clone --recursive git@github.com:XXXXX

# 更新子模块
git submodule update --remote
#git submodule update --init --recursive

```

## Build

hugo new site liusylab.org
hugo new about.md
hugo new post/hello_world.md


## 启动 hugo 本地运行，测试

```bash
#hugo server --minify --buildDrafts -w
hugo server --theme=hyde --minify --buildDrafts -w
```



## Abuout website

```
├─archetypes 
├─content         # 放markdown文章
├─data            # 放数据
├─layouts         # 放网站模板文件
├─static          # 放图片、css、js等静态资源
├─themes          # 放下载的主题
└─config.toml     # 网站的配置文件，也支持YAML格式的config.yaml或JSON格式的config.json
```




## 参考
- [CAI4CAI 实验室例子](https://cai4cai.ml/)
- [hugo搭建个人博客1-基础建站](https://shuzang.github.io/2019/hugo-blog-build-personal-blog/)











## 测试配置 meme 主题的例子

- https://github.com/reuixiy/hugo-theme-meme/blob/master/README.zh-cn.md

```bash
$ hugo new "posts/hello-world.md"
$ hugo new "about/_index.md"
```

## 配置实验室网站的例子

- https://www.youtube.com/watch?v=X4KzvWMKYaY













## 参考

> https://www.gohugo.org/
> hugo 的工作原理 https://hugo.aiaide.com/post/hugo%E7%9A%84%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86/
> 主题： https://github.com/wowchemy/starter-hugo-research-group




