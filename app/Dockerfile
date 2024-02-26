FROM python:3.12.2-slim-bookworm

COPY . /app
WORKDIR /app

RUN pip3 install -r requirements.txt
ENTRYPOINT [ "python3" ]
CMD ["app.py"]