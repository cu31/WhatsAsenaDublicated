FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cu31/WhatsAsenaDuplicated /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN yarn install --no-audit

CMD ["node", "bot.js"]
