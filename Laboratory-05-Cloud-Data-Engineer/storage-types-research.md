# Storage Types Research

## Introduction

Cloud computing provides different types of storage depending on how data needs to be stored, accessed, and managed. The three primary types of cloud storage are Block Storage, File Storage, and Object Storage.

## Comparison of Cloud Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks that can be accessed individually. | Operating systems, databases, and applications that require high-performance storage. | AWS EBS |
| File Storage | Stores data as files organized into folders and directories. | Shared files and applications that require a traditional file system. | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Images, videos, backups, documents, and other large amounts of unstructured data. | AWS S3 |

## Block Storage

Block Storage divides data into individual blocks that can be accessed separately. It is commonly used for operating systems, databases, and applications that require high-performance storage.

An example of a cloud Block Storage service is Amazon Elastic Block Store (AWS EBS).

## File Storage

File Storage organizes data into files and directories. It provides a traditional file-system structure that allows multiple users or applications to access shared files.

An example of a cloud File Storage service is Amazon Elastic File System (AWS EFS).

## Object Storage

Object Storage stores data as objects. Each object contains the actual data, metadata, and a unique identifier. It is commonly used for large amounts of unstructured data such as images, videos, documents, and backups.

An example of a cloud Object Storage service is Amazon Simple Storage Service (AWS S3).

## Why Object Storage?

Object Storage is the best choice for the client's user-uploaded images because it is designed for large amounts of unstructured data such as images and videos. It also allows files to be stored and accessed independently, making it suitable for a photo-sharing application that may contain millions of images.
