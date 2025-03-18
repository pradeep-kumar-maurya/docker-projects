FROM python:3

ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=admin

RUN mkdir -p testapp && \
    pip install pymongo

COPY . /testapp

CMD [ "python", "/testapp/mongodb-docker.py" ]
