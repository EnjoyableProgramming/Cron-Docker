FROM python:3.9.0b4-alpine3.12
COPY my_python /bin/my_python
COPY root /var/spool/cron/crontabs/root
RUN chmod +x /bin/my_python
CMD crond -l 2 -f