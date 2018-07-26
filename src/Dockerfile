FROM ubuntu:14.04
WORKDIR /root
RUN apt-get update \
	&& apt-get install -y g++ gcc gcc-multilib g++-multilib make cmake --no-install-recommends \
	&& cp /etc/apt/sources.list /etc/apt/sources.list.bak \
	&& sed -i 's/archive.ubuntu.com/mirrors.ustc.edu.cn/g' /etc/apt/sources.list