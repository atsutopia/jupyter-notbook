FROM python:3

RUN apt-get update && \
    apt-get install -y vim less &&\
    pip install --upgrade pip &&\
    pip install --upgrade setuptools &&\
    pip install jupyter &&\
    pip install jupytext &&\
    pip install pandas &&\
    pip install matplotlib &&\
    pip install numpy &&\
    pip install seaborn &&\
    pip install ipython-sql &&\
    pip install pymysql &&\
    pip install scikit-learn

EXPOSE 8888

WORKDIR /app
CMD jupyter notebook
