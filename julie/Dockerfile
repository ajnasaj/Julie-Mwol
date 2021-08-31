FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ajnasaj/Julie-Mwol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/ajnasaj/media

CMD ["node", "bot.js"]
