# Datacenter Migration & Backup Platform

## Context

A managed-service platform needed infrastructure migration and continued operation of backup-related services under production constraints. The work involved technical migration planning, service-provider backup tooling, repository servers, monitoring, communication, and operational follow-up.

## Work

- Took project ownership for a datacenter migration track involving infrastructure, backup platform components, customer/reseller communication, and operational coordination.
- Worked with Veeam service-provider tooling, repository servers, mapping/export questions, migration windows, Checkmk/RepoGuard monitoring, and post-cutover cleanup.
- Helped standardize managed repository server onboarding with Ansible and documented operating paths.
- Connected backup platform operations with monitoring and alerting so failures could be detected closer to the infrastructure layer, across Hetzner Dedicated/Cloud infrastructure.

## Technologies

```text
Veeam · VSPC · managed backup repositories · Linux · Ansible
Hetzner Dedicated/Cloud · Checkmk Distributed/MSP · RepoGuard
PowerShell · Bash
```

## Outcome

- Migration path completed with production continuity as the central concern.
- More repeatable repository server provisioning and monitoring.
- Clearer operational ownership across backup, infrastructure, communication, and documentation.

## Good Conversation Topics

- How to plan migration windows for infrastructure that supports many downstream systems.
- Where backup monitoring should happen: job layer, repository layer, host layer, or all of them.
- How to keep technical leadership hands-on without turning every task into single-person ownership.

[Back to case studies](README.md)
