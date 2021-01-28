FROM python:3.6

RUN mkdir -p /app
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r requirements.txt

ENV PYTHONPATH "${PYTHONPATH}:/utils/"

EXPOSE 5000

CMD python route.py