# aws-s3-lifecycle-backup-optimization
AWS S3 Lifecycle policy implementation for backup cost optimization and long-term retention.

# S3 Lifecycle Implementation

## Step 1 – Access the S3 Bucket

Navigated to the AWS S3 console and selected the backup bucket.

## Step 2 – Create Lifecycle Rule

Opened the Management tab and created a lifecycle rule.

https://github.com/Sabelo-madi/aws-s3-lifecycle-backup-optimization/blob/main/screenshots/Screenshot%20(389).png

## Step 3 – Configure Transition

Configured transition after 60 days to Glacier Deep Archive.

https://github.com/Sabelo-madi/aws-s3-lifecycle-backup-optimization/blob/main/screenshots/Screenshot%20(390).png

https://github.com/Sabelo-madi/aws-s3-lifecycle-backup-optimization/blob/main/screenshots/Screenshot%20(391).png

## Step 4 - Confirm Lifecycle Rule

Status "Enabled" for lifecycle rule

https://github.com/Sabelo-madi/aws-s3-lifecycle-backup-optimization/blob/main/screenshots/Screenshot%20(392).png
