FROM hardbyte/python3
MAINTAINER quanglys@gmail.com 
WORKDIR "/"
RUN git clone https://github.com/quanglys/Mon
VOLUME ["/Mon/config", "/Mon/data"]
WORKDIR "/Mon"
CMD [ "python3", "Monitor.py" ]