FROM alpine:3.4

RUN apk update && \
    apk add curl && \
    apk add vim && \
    apk add git

ENTRYPOINT ["git"] 
CMD ["--help"] 
