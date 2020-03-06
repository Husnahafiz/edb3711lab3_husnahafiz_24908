FROM       python:3
LABEL      maintainer="husna_24908"

RUN        pip install beautifulsoup4
RUN        pip install requests
RUN        pip install wikipedia

WORKDIR    /app
COPY       wikicrawler.py /app/
RUN        chmod a+x wikicrawler.py

ENTRYPOINT ["./wikicrawler.py"]
