FROM python:3.9

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app
COPY load_zones.py load_zones.py

ENTRYPOINT ["python", "load_zones.py"]