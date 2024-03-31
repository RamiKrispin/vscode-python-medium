ARG PYTHON_VER="3.10"
FROM python:$PYTHON_VER

ARG PYTHON_ENV=my_env
ENV PYTHON_ENV=$PYTHON_ENV

RUN mkdir requirements

COPY requirements.txt set_python_env.sh /requirements/

RUN bash ./requirements/set_python_env.sh $PYTHON_ENV
