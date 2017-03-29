FROM hardbyte/python3
MAINTAINER quanglys@gmail.com 
WORKDIR "/"
RUN git clone https://github.com/quanglys/Coor2
VOLUME ["/Coor2/config", "/Coor2/data"]
WORKDIR "/Coor2"
EXPOSE 9407 7021
CMD [ "python3", "Coordinator2.py" ]