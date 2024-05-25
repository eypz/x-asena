FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/eypz/x-asena /root/x-asena
WORKDIR /root/x-asena
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"] 
