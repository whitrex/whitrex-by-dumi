FROM fusuf/whatsasena:latest

RUN git clone https://github.com/whitrex/whitrex-by-dumi /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
