# awesome-asyncio-cn [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 一个精心准备的 Python asyncio 优秀资源列表，囊括了网络框架，库，软件以及资源。

[awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) 是 [timofurrer](https://github.com/timofurrer) 发起维护的 Python asyncio 资源列表。本项目是其中文版，用于收集关于 Asyncio 的优秀资源，供大家探索发现 Python 的异步编程世界。

Python [asyncio](https://docs.python.org/3/library/asyncio.html) 模块是 Python3.4+ 引入的标准库，内置了对异步 IO 的支持。asyncio 的编程模型类似一个消息循环，从 asyncio 模块中直接获取一个 EventLoop 的引用，然后把需要执行的协程放到 EventLoop 中执行，就实现了异步 IO。asyncio 是由 Python 之父 Guido 领导的的项目，该项目被命名为 tulip（郁金香）。asyncio 绝对是 Python3 中最雄心勃勃的库，该库的引入使得我们现在可以很方便的编写异步代码。但 asyncio 对于 Python 社区来说并不是一个新鲜的技术，一些社区有名的第三库如 Twisted、gevent 早已经用到了异步编程模型。


## Web 框架

*构建 Web 应用*

* [aiohttp](https://github.com/KeepSafe/aiohttp) - 基于 asyncio (PEP-3156) 的异步 HTTP 客户端/服务端网络库。
* [sanic](https://github.com/channelcat/sanic) - Python 3.5+ web 框架，主打速度与性能。
* [Quart](https://gitlab.com/pgjones/quart) - 一个 asyncio web 微框架，API 与 Flask 相似。
* [Kyoukai](https://github.com/SunDwarf/Kyoukai) - 使用 asyncio 编写的 Python3.5+ 完全异步 Web 框架。
* [cirrina](https://github.com/neolynx/cirrina) - 基于 aiohttp 的有主见的异步 Web 框架。
* [autobahn](https://github.com/crossbario/autobahn-python) - 提供 WebSocket 和 WAMP 客户端/服务端，可用于 asyncio 和 Twisted。
* [websockets](https://github.com/aaugustin/websockets/) - Python 实现的构建 WebSocket 客户端/服务端，专注于编写正确却简单的代码的异步库。
* [Tornado](http://www.tornadoweb.org/en/stable/) - 高性能 Web 框架以及异步网络库。

## 消息队列

*为应用使用消息队列*

* [aioamqp](https://github.com/Polyconseil/aioamqp) - AMQP 的 asyncio 异步实现。
* [aiozmq](https://github.com/aio-libs/aiozmq) - ZeroMQ 的 Asyncio (pep 3156) 实现。
* [crossbar](https://github.com/crossbario/crossbar) - Crossbar.io 是一个分布式和微服务应用的网络平台。

## 数据库驱动

*提供数据库连接驱动*

* [asyncpg](https://github.com/MagicStack/asyncpg) - 快速的 PostgreSQL 异步数据库驱动。
* [aiopg](https://github.com/aio-libs/aiopg/) -另一个 PostgreSQL 异步数据库驱动。
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - sqlalchemy 核心支持的 Asyncpg。
* [aiomysql](https://github.com/aio-libs/aiomysql) - Mysql 异步数据库驱动。
* [aioodbc](https://github.com/aio-libs/aioodbc) - ODBC 异步数据库驱动。
* [motor](https://github.com/mongodb/motor) - Python MongoDB 异步数据库驱动。
* [aioredis](https://github.com/aio-libs/aioredis) - [aio-libs](https://github.com/aio-libs) 提供的异步 Redis 客户端 (PEP 3156)。
* [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis) - 另一个异步 Redis 客户端 (PEP 3156)。
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) - 基于 aiohttp (asyncio) 构建的 CouchDB 客户端。
* [aioinflux](https://github.com/plugaai/aioinflux) - 基于 aiohttp 构建的 InfluxDB 客户端。
* [aioes](https://github.com/aio-libs/aioes) - Asyncio 兼容的 elasticsearch 驱动。
* [peewee-async](https://github.com/05bit/peewee-async) - 基于 [peewee](https://github.com/coleifer/peewee) 和 aiopg 实现的 ORM。
* [GINO](https://github.com/fantix/gino) - 一个基于 [SQLAlchemy](https://www.sqlalchemy.org/) 核心，有着与 [asyncpg](https://github.com/MagicStack/asyncpg) 相同方言的 Python 轻量级异步 ORM。

## 网络

*网络通讯*

* [AsyncSSH](https://github.com/ronf/asyncssh) - 提供一个实现了 SSHv2 协议的异步客户端/服务端。

## 测试

*测试基于 asyncio 的应用程序*

* [aiomock](https://github.com/nhumrich/aiomock/) - 支持异步 mock 方法。
* [asynctest](https://github.com/Martiusweb/asynctest/) - 一个增强标准 unittest 包的测试库。
* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) - Pytest 的 asyncio 实现。

## 事件循环

*可供选择的 asyncio 事件循环*

* [uvloop](https://github.com/MagicStack/uvloop) - Pyhton 实现的构建于 libuv 之上的超快的 asyncio 事件循环。
* [curio](https://github.com/dabeaz/curio) - 并发协程库。

## 其他

*其他优秀的 asnycio 资源库*

* [aiofiles](https://github.com/Tinche/aiofiles/) - 基于 asyncio，提供文件异步操作。
* [aiodebug](https://github.com/qntln/aiodebug) - 一个小巧的测试库用于监控异步程序。
* [aiorun](https://github.com/cjrh/aiorun) - 提供一个 `run()` 函数，可以处理通用的 asyncio 样板以及优雅的关闭事件驱动。
* [aiozipkin](https://github.com/aio-libs/aiozipkin) - 分布式的基于 asyncio 的 zipkin 追踪仪器。

## 写作

*关于 asyncio 的文档，文章以及博客*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - 异步 I/O，事件循环，协程以及任务。 
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) - 生成器，协程，原生协程以及 async/await。
* [Async Through the looking Glass](https://hackernoon.com/async-through-the-looking-glass-d69a0a88b661) - 关于是否值得使用 asyncio 的讨论，提供了一些具体例子。
* [Asynchronous Python](https://hackernoon.com/asynchronous-python-45df84b82434) - 介绍使用 Python 进行异步编程。
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - 介绍异步编程，使用基本的 URL 爬取作为例子。
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - 使用 Python aiohttp 进行百万并发测试。

## 视频

*关于 asyncio 的主题演讲*

* [Topics of Interest (Python Asyncio)](https://www.youtube.com/watch?v=ZzfHjytDceU) - David Beazley 的主题演讲。
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) - Philip Guo 的主题演讲。
