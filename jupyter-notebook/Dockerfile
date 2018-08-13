FROM python:2.7

RUN pip install jupyter
RUN pip install pandas

ADD start.sh /app/
CMD ["bash", "/app/start.sh"]
