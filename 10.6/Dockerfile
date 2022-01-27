FROM mariadb:10.6
RUN apt-get update && \
    apt-get install mariadb-plugin-rocksdb -y && \
    rm -rf /var/lib/apt/lists/*