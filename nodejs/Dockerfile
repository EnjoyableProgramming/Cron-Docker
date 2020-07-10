FROM node:12.18.2-alpine3.9
COPY my_node.js /bin/my_node.js
COPY root /var/spool/cron/crontabs/root
RUN chmod +x /bin/my_node.js
CMD crond -l 2 -f