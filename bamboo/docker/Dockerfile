FROM docker:18.05.0-ce

# Install dependencies of Bamboo
RUN apk update && apk upgrade && \
    apk add --no-cache git maven

# Copy the docker images of the services built by Bamboo into this image.
COPY ./images /images/

