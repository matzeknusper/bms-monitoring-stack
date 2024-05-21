FROM arm32v6/python:3.8-slim

COPY ./setup.py /app/
COPY ./bms_exporter /app/bms_exporter/

WORKDIR /app
RUN pip install .

EXPOSE 8000
ENTRYPOINT ["bms-exporter"]

