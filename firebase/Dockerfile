FROM node:16

RUN RUN npm i -g firebase-tools@10.9.2

ADD firebase.bash /usr/bin
RUN chmod +x /usr/bin/firebase.bash

ENTRYPOINT [ "/usr/bin/firebase.bash" ]
