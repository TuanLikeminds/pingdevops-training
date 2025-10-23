ARG BASE_IMAGE_REPOSITORY
ARG PRODUCT
ARG BASE_IMAGE_TAG

# Use the specified base image with arguments
FROM ${BASE_IMAGE_REPOSITORY}/${PRODUCT}:${BASE_IMAGE_TAG}

# Copy all files and directories from the local ./pingdirectory/ or ./pingfederate/  directory to /opt/in/ in the container
COPY . /opt/in/