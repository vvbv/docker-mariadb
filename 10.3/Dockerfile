FROM mariadb:10.3
RUN apt-get update && \
    apt-get install mariadb-plugin-rocksdb -y && \
    rm -rf /var/lib/apt/lists/*