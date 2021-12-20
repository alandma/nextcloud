FROM postgres:10-alpine

RUN apk add --update --no-cache tzdata \
&& rm -fr /var/cache/apk/*

ENV TZ America/Sao_Paulo

EXPOSE 5432

ENTRYPOINT ["docker-entrypoint.sh"]

CMD [ "postgres" ]
