FROM nodered/node-red

RUN npm install node-red-contrib-influxdb 

COPY ./data/settings.js /data/settings.js

COPY ./data/flows_cred.json /data/flows_cred.json

COPY ./data/flows.json /data/flows.json


