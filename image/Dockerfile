FROM alpine:latest

RUN apk add --update dhcp && \
    touch /var/lib/dhcp/dhcpd.leases

VOLUME /etc/dhcp/
EXPOSE 67/udp

CMD ["dhcpd"]
