FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cu31/WhatsAsenaDuplicated /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul

CMD ["node", "bot.js"]
