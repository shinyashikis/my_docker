FROM python:2.7

RUN pip install jupyter
RUN pip install pandas

ADD start.sh /app/
RUN chmod +x /app/start.sh
RUN mkdir /usr/local/notebook

CMD sh /app/start.sh
