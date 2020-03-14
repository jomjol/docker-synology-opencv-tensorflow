FROM python:3.6

WORKDIR /

COPY ./wheels ./wheels
RUN pip install --no-cache-dir ./wheels/tensorflow-2.1.0-cp36-cp36m-linux_x86_64.whl
RUN pip install --no-cache-dir numpy Pillow opencv-python
RUN rm -r ./wheels