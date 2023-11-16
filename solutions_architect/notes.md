# Overviews

## Security

| service       | pre/post | monitoring object           | target                 | trigger   |
| ------------- | -------- | --------------------------- | ---------------------- | --------- |
| SECURITY      |          |                             |                        |           |
| Shield        | pre      | layer3/4 network traffic    |                        | always    |
| WAF           | pre      | layer7 traffic (IPs, URLs)  |                        | always    |
| guard duty    | post     | logs (CloudTrail,VPC,DNS)   | anomaly/threats        | always    |
| macie         | post     | S3                          | PII data               | always    |
| inspector     | pre      | EC2, SG, containers, Lambda | vulnerable libs/ports  | triggered |
| detective     | post     | several AWS services        | None! only visualizer! | triggered |
|               |          |                             |                        |           |
| GOVERNANCE    |          |                             |                        |           |
| Organizations | pre      | permissions via SCP         | CRUD permissions       | always    |
| Config        | pre/post | service CRUD                | custom rules           | always    |
|               |          |                             |                        |           |

## From book AWS for solutions architect

- identity
  - IAM
  - IAM Identity Center (SSO)
  - Organizations
  - Directory services
  - (RAM)
  - (Cognito)
- security (?)
  - guard duty
  - inspector
- infrastructure protection
  - shield
  - WAF
  - firewall manager
- data protection
  - macie
  - KMS
  - secret manager
  - certificate manager (SSL)
  - detective
  - security hub

## Difficult questions

- cloudfront
  - cookies / request headers?
- shield advanced & WAF
  - can I attach those to API gateway / load balancersss
- RDS - Aurora
  - Can I create a RDS replica to Aurora and then promote it to primary DB?
- Custom virtual firewall
  - Can I route traffic to virtual firewall via transit gateway?
- Glacier Deep
  - has 6h retrieval?
- ...
