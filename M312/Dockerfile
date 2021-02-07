FROM mongo:3.4.2
RUN   apt update -y \
    && apt upgrade -y --force-yes \
    && mkdir -p /data \
    && chmod -R 777 /data   \
    && mkdir -p /data/db \
    && mkdir -p /home/vagrant/data \
    && chmod -R 777 /home/vagrant/data \
    && mkdir -p /home/vagrant/data/authdb \
    && apt install -y python-dev \
    && apt install -y python-pip \
    && apt install python-setuptools \
    && pip install pymongo --upgrade \
    && pip install docopt --upgrade \
    && pip install faker==3.0.1 \
    && apt install python-psutil \
    && pip install setuptools==45.3.0 \
    && pip install psutil==5.7.2 \
    && pip install mtools==1.5.3 