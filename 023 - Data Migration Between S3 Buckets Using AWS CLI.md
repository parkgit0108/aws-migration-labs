# Data Migration Between S3 Buckets Using AWS CLI

---

<aside>

**Purpose:** Migrate data between **S3 buckets** using **AWS CLI** (`aws s3 sync`) and verify the migration.

</aside>

---

### Procedure

1. Check existing S3 buckets:
    1. Run `aws s3 ls`.
2. Create the destination S3 bucket (use the provided name):
    1. Run:
        
        `aws s3api create-bucket --bucket amzn-s3-demo-bucket --region us-east-1`
        
    2. Replace `amzn-s3-demo-bucket` with the provided bucket name.
3. Confirm the new bucket exists:
    1. Run `aws s3 ls` again.
4. Migrate data from source to destination:
    1. Run:
        
        `aws s3 sync s3://source-bucket s3://destination-bucket`
        
    2. Example:
        
        `aws s3 sync s3://datacenter-s3-21233 s3://datacenter-sync-3529`
        
5. Verify the migration completed:
    1. List objects and compare totals (object count and total size) for each bucket:
        
        `aws s3 ls s3://datacenter-s3-21233 --recursive --summarize`
        
        `aws s3 ls s3://datacenter-sync-3529 --recursive --summarize`
        
    2. Or compare total object counts:
        
        `aws s3 ls s3://datacenter-sync-3529 --recursive | wc -l`
        
        `aws s3 ls s3://datacenter-s3-21233 --recursive | wc -l`
        

### Quick check

- **Location:** Terminal with AWS CLI configured
- **Expected result:** Source and destination bucket object counts match, and the summarised totals are consistent