# comicspider

这里主要包括两大部分：

 - [漫画爬虫，将数据储存到mysql](README.md)
 
 启动命令
 ```python
scrapy crawl manhua163 #或者直接 python start.py
```


代码结构如下：
```markdown
comicspider
├── comicscrapy
│   ├── comicscrapy
│   │   ├── __init__.py
│   │   ├── items.py
│   │   ├── middlewares.py
│   │   ├── pipelines.py
│   │   ├── settings.py
│   │   └── spiders
│   │       ├── __init__.py
│   │       ├── manhua163.py
│   ├── scrapy.cfg
│   ├── scrapy.log
│   └── start.py
├── comicspider
│   ├── __init__.py
│   ├── settings.py
│   ├── spiderfactory.py
│   ├── spiders.py
└── test


```
 