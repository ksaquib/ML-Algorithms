FROM python:3.8

WORKDIR /app

COPY . /app

RUN pip install numpy scikit-learn matplotlib

EXPOSE 80

CMD ["python3", "train.py"]