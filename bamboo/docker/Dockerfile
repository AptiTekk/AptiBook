FROM docker:18.05.0-ce

# Install dependencies of Bamboo
RUN apt-get install -y git maven

# Copy the docker images of the services built by Bamboo into this image.
COPY ./images /images/

