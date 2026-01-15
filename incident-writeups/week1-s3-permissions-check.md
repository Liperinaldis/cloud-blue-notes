# Week 1 — S3 Permissions Check (Public Risk)

## Checks I performed
1) Block Public Access: ON
2) Bucket policy: No bucket policy
3) ACL / Object ownership: Bucket owner enforced; no public permissions

## Result
- Bucket is private because public access is blocked and no policy/ACL grants public read.

## What I learned
- Public access can come from: Block Public Access off, a public bucket policy, or ACLs (if enabled).
