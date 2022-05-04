FROM blackamda/queenamdi:public

RUN git clone https://github.com/abuturki65/QueenAmdi /root/QueenAmdi
WORKDIR /root/QueenAmdi/
ENV TZ=Asia/Mecca
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
