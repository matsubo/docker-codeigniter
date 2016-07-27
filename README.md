Development server usage.
===

Spec
---

- Web Application Framework
  - CodeIgniter 2.2.6
- Server
  - CentOS 6.6
  - PHP 5.1.6
  - Postgres 9.4.6


Preparation
---

- Install [docker-compose](https://docs.docker.com/compose/) on localhost.


Start
---


```
% docker-compose up -d
or
% docker-compose up
```


- web application
  - Go to [http://localhost:8000](http://localhost:8000)
- utility application
  - phpinfo
  - phpPgAdmin
  - Go to [http://localhost:8001](http://localhost:8001)
- postgres connection information
  - user: `postgres`
  - password: `<empty>`



Stop
---

```
% docker-compose stop
or
Ctrl-C
```


