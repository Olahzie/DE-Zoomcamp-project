FROM python:3.9.1

RUN pip install wget
RUN pip install pandas sqlalchemy psycopg2


WORKDIR /app
COPY ingestion.py ingestion.py


ENTRYPOINT [ "python", "ingestion.py" ]