FROM python:2.7

RUN pip install jupyter
RUN pip install pandas

ADD start.sh /app/
RUN chmod +x /app/start.sh

CMD ["bash", "/app/start.sh"]
