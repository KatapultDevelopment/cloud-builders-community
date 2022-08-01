FROM node:16 AS app-env

RUN npm install -g firebase-tools@10.9.2

ADD firebase.bash /usr/bin
RUN chmod +x /usr/bin/firebase.bash

ENTRYPOINT [ "/usr/bin/firebase.bash" ]
