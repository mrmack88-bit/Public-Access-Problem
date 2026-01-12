## Problem Statement
A public e-commerce site (CloudMart) experienced downtime when images stored in
S3 became inaccessible due to misconfigured bucket permissions.
## Investigation Process
- Reproduced the Access Denied issue.
- Reviewed S3 public access settings.
- Compared IAM roles and bucket policies.
## Solution
Implemented a least-privilege S3 bucket policy allowing controlled public object
access.
## Validation
- Tested object URLs in a browser, verified public access.
- Confirmed no unauthorized uploads possible.
## Result
✅ Product images restored.
✅ Permissions secured.
✅ Cost: $0 (AWS Free Tier).
## Skills Highlighted
AWS S3 • IAM • Cloud Security • Troubleshooting • Documentation
