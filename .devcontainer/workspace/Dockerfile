FROM amazoncorretto:8

#apt packages
RUN yum install -y \
  git \
  ca-certificates \
  build-essential \
  tar

#add ssh secret-key
COPY .dummy .ssh/* /root/.ssh/
