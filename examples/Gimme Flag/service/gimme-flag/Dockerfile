FROM debian:stable

RUN apt update && \
    apt install -y socat

EXPOSE 10003

CMD ["socat", "TCP-LISTEN:10003,reuseaddr,fork", "EXEC:echo 'YBN24{hE1lO_froM_N3tC4T}'"]