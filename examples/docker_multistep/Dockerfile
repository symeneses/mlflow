FROM openjdk:slim
COPY --from=python:3.6 / /

RUN pip install mlflow>=1.0 \
    && pip install pyspark \
    && pip install requests \
    && pip install click \
    && pip install tensorflow==1.15.2 \
    && pip install keras==2.2.4
