# MinIO Deployment

This document contains the technical documentation for deploying an S3-compatible object storage server using MinIO and Docker.

## EXACT DOCKER COMMAND USED
The MinIO storage server was deployed using the following Docker command:

docker run -d --name minio-server -p 9000:9000 -p 9001:9001 -e MINIO_ROOT_USER=cloudadmin -e MINIO_ROOT_PASSWORD=CloudNova2026! quay.io/minio/minio server /data --console-address ":9001"

The -d flag runs the container in detached mode. The --name minio-server gives the container the name minio-server. The -p flags map the MinIO ports from the container to the host machine.

## WEB CONSOLE PORT
The MinIO Web Console was accessed using port 9001.

Port 9001 is used for the MinIO Web Console, while port 9000 is used for the MinIO API.

## BUCKET CREATED
The bucket created in the MinIO Web Console was:

client-photos

A sample file was uploaded to the client-photos bucket to verify that the object storage was working properly.

## ENVIRONMENT VARIABLES 
The -e flags were used to set environment variables inside the MinIO container.

The following environment variable:

-e MINIO_ROOT_USER=cloudadmin

sets cloudadmin as the MinIO root username.

The following environment variable:

-e MINIO_ROOT_PASSWORD=CloudNova2026!

sets the password for the MinIO root account.

These environment variables configure the administrator login credentials when the MinIO container is started.
