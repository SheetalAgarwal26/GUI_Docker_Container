FROM centos:latest
RUN yum install libcanberra-gtk2 -y
RUN yum install PackageKit-gtk3-module -y
RUN yum install python3 -y
RUN pip3 install jupyter
CMD ["/usr/local/bin/jupyter"]


