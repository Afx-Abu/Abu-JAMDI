FROM quay.io/afx-abu/abu-md
RUN git clone https://github.com/Afx-Abu/Abu-JAMDI /root/Abu
WORKDIR /root/Abu/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
