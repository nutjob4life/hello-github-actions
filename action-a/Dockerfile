FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello, World"
LABEL "com.github.actions.description"="Write arguments to stdout"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="http://github.com/nutjob4life/hello-github-actions.git"
LABEL "homepage"="http://non.exist.ent/"
LABEL "maintainer"="Sean Kelly <kelly@seankelly.biz>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
