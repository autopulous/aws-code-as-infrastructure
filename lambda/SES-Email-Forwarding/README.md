# SES-Email-Forwarding

A lambda function to be called from SES immediately after SES receives an email and stores it in a domain named folder (e.g. example.com) off of the root of an S3 bucket (e.g. email.forwarding.bucket)

Example:

email.forwarding.bucket\example.com
