FROM alpine:latest
<<<<<<< HEAD
RUN mkdir /data
WORKDIR /data
CMD ["sh", "-c", "echo 'data written by rajnish' > /data/test.txt && cat /data/test.txt && sleep 30"]
=======

LABEL maintainer="rajnish197"

RUN apk add --no-cache curl vim bash

WORKDIR /app

COPY hello.sh .

Run chmod +x hello.sh

CMD ["./hello.sh"]
>>>>>>> 0bcb9cf3cd7765af765615c0ad268832e6c4b197
