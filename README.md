# docker_squid3
docker run --name squid3 --rm -itd \
    -v $(pwd)/squid.conf:/etc/squid/squid.conf:ro \
    -p 3128:3128 \
    jam7/squid3
