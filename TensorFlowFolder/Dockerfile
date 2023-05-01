FROM tensorflow/tensorflow:latest-gpu

COPY . /tf
WORKDIR /tf
RUN pip install -r requirements.txt
EXPOSE 8888

ENTRYPOINT ["jupyter","lab","--ip=0.0.0.0","--allow-root","--no-browser"]