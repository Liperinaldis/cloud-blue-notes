# Week 1 — S3 Private Access Test

## What I did
- Created an S3 bucket (Block Public Access ON)
- Uploaded a .txt file
- Opened the Object URL in an incognito window

## Expected result
- The object should not be publicly accessible

## Actual result
- Incognito result: AccessDenied ✅

## What this proves
- The bucket/object permissions are not allowing public read access

## If it had been public, I would fix it by
- Enabling Block Public Access
- Removing any public bucket policy / ACL
- Granting access only to required IAM users/roles (least privilege)
