FROM imranathumber/node

CMD ["node", "/web-ping/app.js"]

ENV TARGET="humber.ca" \
    METHOD="HEAD" \
    INTERVAL="3000"

WORKDIR /web-ping
COPY app.js .