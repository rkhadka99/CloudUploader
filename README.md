## CloudUploader
This is a bash CLI tool that allows you to upload files to AWS S3.

## S3 File Uploader

A Bash-based CLI tool for uploading files to an S3 bucket. 

## Prerequisites

- [AWS CLI](https://aws.amazon.com/cli/) installed and configured with the necessary credentials.
- Bash shell environment.

## Usage
To use the tool, run the following command:

./.sh <local-file> <destination-path>
<local-file>: The path to the local file you want to upload.
<destination-path>: The destination path in the S3 bucket.

Examples:
./.sh ./example.txt uploads/

Please note that the script will prompt you to enter your S3 Bucket name.



