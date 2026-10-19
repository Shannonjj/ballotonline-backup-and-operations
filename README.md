# Cloud Backup, Operations, and Governance — BallotOnline (CCA 630)

The operations document set from my UMGC CCA 630 capstone work for BallotOnline (coursework case-study company): a deployment runbook, an operations plan, and a governance policy addendum.

## Final Cloud Backups and Archiving Deployment Runbook
Step-by-step deployment guide for the backup architecture:
- **Amazon S3 with Glacier deep archive** inside a VPC for backup and long-term archiving
- **NetApp Cloud Sync** data broker (CCA630DB) replicating SMB file data into S3
- **CloudWatch** monitoring of S3 cost and traffic

## Cloud Operations Plan
- **AWS Service Catalog** operations, with separate administrator and end-user guides: portfolios, products, and provisioning
- IAM group structure for operations, including a **BackupOperators** group

## Final Cloud Adoption Policy Addendum
Governance policy covering:
- Cloud vendor governance and accountability
- **Exit strategy** — how the organization leaves a provider without data loss
- RFP process for future cloud procurements

## Skills demonstrated
- Runbook and operations documentation writing
- Backup/archiving architecture (S3, Glacier, Cloud Sync)
- AWS Service Catalog operations
- Cloud governance: vendor management, exit planning, procurement policy


---
*Shannon Javone Jenkins — MS in Cloud Computing Architecture, University of Maryland Global Campus (UMGC). Graduate coursework and hands-on labs.*
