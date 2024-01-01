FROM ubuntu

MAINTAINER ORKHAN GASANOV <riins@bk.ru>

RUN apt-get update && apt-get install -y cowsay && ln -s /usr/games/cowsay /usr/bin/cowsay

ENTRYPOINT ["cowsay"]
