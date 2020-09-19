FROM pytorch/pytorch

WORKDIR /workspace

RUN apt-get update
RUN apt-get install -y vim

COPY . /workspace

RUN pip install -r requirements.txt

#CMD ["python", "TrainRunner.py"]
