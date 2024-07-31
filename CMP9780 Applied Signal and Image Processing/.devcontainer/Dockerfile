FROM python:3.12

RUN apt-get update && apt-get install ffmpeg libsm6 libxext6  -y

RUN pip install --upgrade pip
RUN pip install mediapipe
RUN pip install opencv-python
RUN pip install ipykernel
CMD ["clear"]