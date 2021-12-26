FROM debian:buster-slim
WORKDIR /root
RUN apt-get update \
	&& apt-get install -y git g++ gcc \
	gcc-multilib g++-multilib \
	make cmake --no-install-recommends
