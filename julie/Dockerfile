FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Jasilmp/ABU-BOT /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Jasilmp/Nandhuttynew

CMD ["node", "bot.js"]
