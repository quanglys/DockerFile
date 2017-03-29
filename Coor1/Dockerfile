FROM hardbyte/python3
MAINTAINER quanglys@gmail.com 
WORKDIR "/"
RUN git clone https://github.com/quanglys/Coor1
VOLUME ["/Coor1/config", "/Coor1/data"]
WORKDIR "/Coor1"
EXPOSE 9407 7021
CMD [ "python3", "Coordinator.py" ]