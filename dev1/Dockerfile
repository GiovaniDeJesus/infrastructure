FROM python

COPY ./app/requirements.txt /app/requirements.txt

WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 5000

COPY ./app /app

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]
