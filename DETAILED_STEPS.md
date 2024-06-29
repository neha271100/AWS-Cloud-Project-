# Detailed Steps for AWS Disaster Recovery Setup

**##Tasks to be performed:**
1. Provision of an EC2 server in the primary region
2. Provision of an S3 bucket in the primary region
3. Configure S3 cross-region replication
4. Take AMI from the primary region and copy to the DR region
5. Provision an EC2 server using the copied AMI
6. Verify the application working in the DR region
7. Verify the S3 files replicated to the DR region
