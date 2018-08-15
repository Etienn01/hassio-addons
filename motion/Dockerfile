
FROM homeassistant/armhf-homeassistant-base

RUN apk add --update \
    motion \
    jq

# Copy data
COPY run.sh /
COPY motion.conf /etc/

RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
