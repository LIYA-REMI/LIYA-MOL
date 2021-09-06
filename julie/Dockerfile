FROM fusuf/whatsasena:latest

RUN git clone https://github.com/LIYA-REMI/LIYA-MOL /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/farhan-dqz/media

CMD ["node", "bot.js"]
