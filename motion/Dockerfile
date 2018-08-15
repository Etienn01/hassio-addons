
FROM hassioaddons/base

RUN apk add --no-cache motion jq

# Copy data
COPY run.sh /
COPY motion.conf /etc/

RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
