
# 简介
Tornado是一个Python web框架，也是异步网络库，通过使用非阻塞IO，它可以轻松处理C10K问题，对于长轮询、WebSocket等长链接的开发，也比较容易。

# 目录结构

tornado作为web框架和异步网络库，代码量较多，所以在分析tornado源码时，可以选取一些比较重要的模块来阅读，比如：
concurrent.py, gen.py, tcpserver.py, httpserver.py, ioloop.py, iostream.py, web.py等


```bash
➜  tornado git:(branch5.1) ✗ tree -I '*test|*__pycache__'
.
├── auth.py
├── autoreload.py
├── concurrent.py
├── curl_httpclient.py
├── escape.py
├── gen.py
├── http1connection.py
├── httpclient.py
├── httpserver.py
├── httputil.py
├── __init__.py
├── ioloop.py
├── iostream.py
├── _locale_data.py
├── locale.py
├── locks.py
├── log.py
├── netutil.py
├── options.py
├── platform
│   ├── asyncio.py
│   ├── auto.py
│   ├── auto.pyi
│   ├── caresresolver.py
│   ├── common.py
│   ├── epoll.py
│   ├── __init__.py
│   ├── interface.py
│   ├── kqueue.py
│   ├── posix.py
│   ├── select.py
│   ├── twisted.py
│   └── windows.py
├── process.py
├── queues.py
├── routing.py
├── simple_httpclient.py
├── speedups.c
├── speedups.pyi
├── stack_context.py
├── tcpclient.py
├── tcpserver.py
├── template.py
├── testing.py
├── util.py
├── web.py
├── websocket.py
└── wsgi.py
```


```python

```
