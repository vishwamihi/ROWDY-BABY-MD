FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/vishwamihi/ROWDY-BABY-MD /root/vishwamihi
WORKDIR /root/vishwamihi/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
