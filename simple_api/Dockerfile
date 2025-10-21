FROM  python:3.11-slim
LABEL Maintainer="Zidane KABI"
COPY  requirements.txt student_age.py / 
RUN apt-get update -y && \
    apt-get install -y gcc build-essential python3-dev libsasl2-dev libldap2-dev libssl-dev && \
    apt-get clean && rm -rf /var/lib/apt/lists/*
RUN   pip3 install -r /requirements.txt
VOLUME [ "/data" ]
EXPOSE 5000
CMD ["python3","/student_age.py" ]

curl -u toto:python -X GET http://192.168.56.5:5000/pozos/api/v1.0/get_student_ages