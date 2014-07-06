docker-jnethack-server
======================

Dockerfile for Public JNetHack server

## Howto

    docker run --detach --name=jnh --publish=23:23 matsuu/jnethack-server

## Build

    docker build -t jnethack-server .

## References

- [Public JNetHack Server at nethack.matsuu.net](https://matsuu.net/nethack/)
- [matsuu/docker-jnethack](https://github.com/matsuu/docker-jnethack)
- [NetHack 3.4.3: Home Page](http://www.nethack.org/)
- [JNetHack Home Page](http://www.jnethack.org/)
- [JNetHack Project](http://jnethack.sourceforge.jp/)
- [Compiling - Wikihack](http://nethack.wikia.com/wiki/Compiling)
- [jNetHack UTF-8対応 を CentOS 6.3 にインストール](http://qiita.com/KurokoSin/items/bbbfb4b4f9ee645418f1)
- [paxed/dgamelaunch](https://github.com/paxed/dgamelaunch)
- [HowTo setup dgamelaunch](http://nethackwiki.com/wiki/User:Paxed/HowTo_setup_dgamelaunch)
