FROM boynux/squid-exporter:v1.5 as sqex

FROM alpine:3.9

COPY --from=sqex /usr/local/bin/squid-exporter /usr/local/bin/squid-exporter

EXPOSE 9301

ENTRYPOINT ["sh"]
