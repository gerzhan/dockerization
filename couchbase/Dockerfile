# Use official docker image
FROM couchbase

# Copy file with configuration commands
COPY configure.sh /opt/couchbase

# make script executable
RUN chmod +x /opt/couchbase/configure.sh

# Run script inn docker container after start
CMD ["/opt/couchbase/configure.sh"]
