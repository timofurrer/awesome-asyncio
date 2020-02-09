# Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A carefully curated list of awesome Python asyncio frameworks, libraries, software and resources.

The Python [asyncio](https://docs.python.org/3/library/asyncio.html) module introduced to the standard library with Python 3.4 provides infrastructure for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, running network clients and servers, and other related primitives.

Asyncio is not really a brand-new technology however it appears to be very trending since a few years - especially in the Python community and with the release of Python 3.4 in March 2014.
Thus, it's pretty hard to keep yourself up-to-date with the most awesome packages out there.
Find some of those *awesome* packages here and if you are missing one we count on you to [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) with your suggestion.

## Contents

* [Web Frameworks](#web-frameworks)
* [Message Queues](#message-queues)
* [Database Drivers](#database-drivers)
* [Networking](#networking)
* [GraphQL](#graphql)
* [Testing](#testing)
* [Alternative Loops](#alternative-loops)
* [Misc](#misc)
* [Writings](#writings)
* [Talks](#talks)
* [Alternatives to asyncio](#alternatives-to-asyncio)


***

## Web Frameworks

*Libraries to build web applications.*

* [aiohttp](https://github.com/KeepSafe/aiohttp) - Http client/server for asyncio (PEP-3156).
* [sanic](https://github.com/channelcat/sanic) - Python 3.5+ web server that's written to go fast.
* [Quart](https://gitlab.com/pgjones/quart) - An asyncio web microframework with the same API as Flask.
* [Vibora](https://github.com/vibora-io/vibora) - Performant web framework inspired by Flask.
* [cirrina](https://github.com/neolynx/cirrina) - Opinionated asynchronous web framework based on aiohttp.
* [autobahn](https://github.com/crossbario/autobahn-python) - WebSocket and WAMP supporting asyncio and Twisted, for clients and servers.
* [websockets](https://github.com/aaugustin/websockets/) - A library for building WebSocket servers and clients in Python with a focus on correctness and simplicity.
* [Tornado](http://www.tornadoweb.org/en/stable/) - Performant web framework and asynchronous networking library.
* [Japronto!](https://github.com/squeaky-pl/japronto) - Experimental http toolkit built on top of uvloop and picohttpparser.
* [Starlette](https://github.com/encode/starlette) - A lightweight ASGI framework/toolkit for building high performance services.
* [uvicorn](https://github.com/encode/uvicorn) - The lightning-fast ASGI server.
* [FastAPI](https://github.com/tiangolo/fastapi) - A very high performance Python 3.6+ API framework based on type hints. Powered by Starlette and Pydantic.

## Message Queues

*Libraries to implement applications using message queues.*

* [aioamqp](https://github.com/Polyconseil/aioamqp) - AMQP implementation using asyncio.
* [pyzmq](https://github.com/zeromq/pyzmq) - Python bindings for ZeroMQ.
* [aiozmq](https://github.com/aio-libs/aiozmq) - Alternative Asyncio integration with ZeroMQ.
* [crossbar](https://github.com/crossbario/crossbar) - Crossbar.io is a networking platform for distributed and microservice applications.
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) - Client for the NATS messaging system.
* [aiokafka](https://github.com/aio-libs/aiokafka) - Client for Apache Kafka.

## Database Drivers

*Libraries to connect to databases.*

* [asyncpg](https://github.com/MagicStack/asyncpg) - Fast PostgreSQL Database Client Library for Python/asyncio.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - Asyncpg with sqlalchemy core support.
* [aiopg](https://github.com/aio-libs/aiopg/) - Library for accessing a PostgreSQL database.
* [aiomysql](https://github.com/aio-libs/aiomysql) - Library for accessing a MySQL database
* [aioodbc](https://github.com/aio-libs/aioodbc) - Library for accessing a ODBC databases.
* [motor](https://github.com/mongodb/motor) - The async Python driver for MongoDB.
* [aioredis](https://github.com/aio-libs/aioredis) - [aio-libs](https://github.com/aio-libs) Redis client (PEP 3156).
* [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis) - Redis client for Python asyncio (PEP 3156).
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) - CouchDB client built on top of aiohttp (asyncio).
* [aioinflux](https://github.com/plugaai/aioinflux) - InfluxDB client built on top of aiohttp.
* [aioes](https://github.com/aio-libs/aioes) - Asyncio compatible driver for elasticsearch.
* [peewee-async](https://github.com/05bit/peewee-async) - ORM implementation based on [peewee](https://github.com/coleifer/peewee) and aiopg.
* [GINO](https://github.com/fantix/gino) - is a lightweight asynchronous Python ORM based on [SQLAlchemy](https://www.sqlalchemy.org/) core, with [asyncpg](https://github.com/MagicStack/asyncpg) dialect.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) - native multi-backend ORM with Django-like API and easy relations management.
* [Databases](https://github.com/encode/databases) - Async database access for SQLAlchemy core, with support for PostgreSQL, MySQL, and SQLite.

## Networking

*Libraries to communicate in your network.*

* [AsyncSSH](https://github.com/ronf/asyncssh) - Provides an asynchronous client and server implementation of the SSHv2 protocol.
* [aiodns](https://github.com/saghul/aiodns) - Simple DNS resolver for asyncio
* [httpx](https://github.com/encode/httpx) - asynchronous HTTP client for Python 3 with [requests](https://github.com/psf/requests) compatible API.

## GraphQL

*Libraries to build GraphQL servers.*

* [Ariadne](https://ariadnegraphql.org) - Schema-first Python library for implementing GraphQL servers.
* [Tartiflette](https://tartiflette.io/) - Schema-first Python 3.6+ GraphQL engine built on top of `libgraphqlparser`.

## Testing

*Libraries to test asyncio based applications.*

* [aiomock](https://github.com/nhumrich/aiomock/) - A python mock library that supports async methods.
* [asynctest](https://github.com/Martiusweb/asynctest/) - Enhance the standard unittest package with features for testing. asyncio libraries
* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) - Pytest support for asyncio.
* [aresponses](https://github.com/CircleUp/aresponses) - Asyncio http mocking. Similar to the [responses](https://github.com/getsentry/responses) library used for [requests](https://github.com/requests/requests)
* [aioresponses](https://github.com/pnuckowski/aioresponses) - Helper for mock/fake web requests in Python aiohttp package.

## Alternative Loops

*Alternative asyncio loop implementations.*

* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast implementation of asyncio event loop on top of libuv.

## Misc

*Other awesome asyncio libraries.*

* [aiofiles](https://github.com/Tinche/aiofiles/) - File support for asyncio.
* [aiodebug](https://github.com/qntln/aiodebug) - A tiny library for monitoring and testing asyncio programs.
* [aiorun](https://github.com/cjrh/aiorun) - A `run()` function that handles all the usual boilerplate for startup and graceful shutdown.
* [aioserial](https://github.com/changyuheng/aioserial) - A drop-in replacement of [pySerial](https://github.com/pyserial/pyserial).
* [aiozipkin](https://github.com/aio-libs/aiozipkin) - Distributed tracing instrumentation for asyncio with zipkin
* [asgiref](https://github.com/django/asgiref) - Backend utils for ASGI to WSGI integration, includes sync_to_async and async_to_sync function wrappers.
* [ruia](https://github.com/howie6879/ruia) - An async web scraping micro-framework based on asyncio.
## Writings

*Documentation, blog posts, and other awesome writing about asyncio.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - Asynchronous I/O, event loop, coroutines and tasks.
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) - Generators, Coroutines, Native Coroutines and async/await.
* [Async Through the looking Glass](https://hackernoon.com/async-through-the-looking-glass-d69a0a88b661) - Nice writing about it's worth using asyncio or not for specific use-cases.
* [Asynchronous Python](https://hackernoon.com/asynchronous-python-45df84b82434) - Introduction into asynchronous programming with Python.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - A gentle introduction to asynchronous programming from basic examples working up to URL fetching.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - Making 1 million requests with python-aiohttp.
* [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io/en/latest/) - A spiritual successor to WSGI, intended to provide a standard interface between async-capable Python web servers, frameworks, and applications.
* [First Principles Introduction to Asyncio](https://hackernoon.com/a-simple-introduction-to-pythons-asyncio-595d9c9ecf8c) - A no-buzzword first principles introduction to the internal workings of asyncio.
* [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - This tutorial looks at how to develop and test an asynchronous API with FastAPI using Test-Driven Development (TDD).

## Talks

*Recordings of awesome talks about asyncio.*

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) - PyCon Brasil 2015 keynote (David Beazley).
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) | [blog post](http://pgbovine.net/python-async-io-walkthrough.htm) - 8-part code walkthrough (Philip Guo).
* [Async/await in Python 3.5 and why it is awesome](https://www.youtube.com/watch?v=m28fiN9y_r8&t=132s) - EuroPython 2016 (Yury Selivanov).
* [Fear and Awaiting in Async: A Savage Journey to the Heart of the Coroutine Dream](https://www.youtube.com/watch?v=E-1Y4kSsAFc) | [screencast](https://www.youtube.com/watch?v=Bm96RqNGbGo) - PyOhio 2016 keynote (David Beazley).
* [Asynchronous Python for the Complete Beginner](https://www.youtube.com/watch?v=iG6fr81xHKA) | [slides](https://speakerdeck.com/pycon2017/miguel-grinberg-asynchronous-python-for-the-complete-beginner) - PyCon 2017 (Miguel Grinberg).

## Alternatives to asyncio

*Alternative approaches to async programming in Python, some of which attempt to support some compatibility with `asyncio`, others are not compatible at all.*

* [curio](https://github.com/dabeaz/curio) - The coroutine concurrency library.
  * [Curio-Asyncio Bridge](https://github.com/dabeaz/curio/issues/190) - basic curio -> asyncio coroutine bridge
* [trio](https://github.com/python-trio/trio) - Pythonic async I/O for humans and snake people.
  * [trio-asyncio](https://github.com/python-trio/trio-asyncio) - re-implementation of the asyncio mainloop on top of Trio
