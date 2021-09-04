# Use an Existing docker image as a Base
FROM alpine
# Download and install a dependency
RUN apk add --update redis
RUN apk add --update gcc
#Tell the Image what to do when it starts as a container
CMD ["redis-server"]
