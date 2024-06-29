FROM python:3.10-alpine

RUN mkdir /app
WORKDIR /app
ADD . /app/
RUN pip3 install -r app/requirements.txt

EXPOSE 5000
CMD ["python", "app/app.py"]