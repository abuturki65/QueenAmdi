FROM blackamda/queenamdi:public

RUN git clone https://github.com/abuturki65/abuturkibot6 /root/abuturkibot6
WORKDIR /root/abuturkibot6/
ENV TZ=Asia/Mecca
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
