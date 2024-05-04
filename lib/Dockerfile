FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Arther23/ARTHER_BOT /root/Arther23
WORKDIR /root/Arther23/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
