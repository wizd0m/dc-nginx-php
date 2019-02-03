FROM php:7.1-fpm-alpine

RUN set -xe; \
    apk add --no-cache --virtual .fetch-deps \
	    graphviz \
    && apk del .fetch-deps
