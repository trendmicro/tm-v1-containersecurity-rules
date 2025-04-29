# Vision One Container Security Rules Changelog

## 2025-04-14

### Added
- No new rules added.

### Changed
- **Rule:** (T1552.005) Contact EC2 Instance Metadata Service From Container  
  **Change:** Improve the condition to exclude known legitimate activity detected by the rule.

- **Rule:** (T1609) Docker or Kubernetes client executed in container  
  **Change:** Improve the condition to exclude known legitimate activity detected by the rule.

- **Rule:** (T1562.004) Iptables Modification  
  **Change:** Improve the condition to exclude known legitimate activity detected by the rule.

- **Rule:** (T1055.008) PTRACE attached to process  
  **Change:** Improve the condition to exclude known legitimate activity detected by the rule.

- **Rule:** (T1083) Read environment variable from /proc files  
  **Change:** Improve the condition to exclude known legitimate activity detected by the rule.

### Removed
- No rules removed.


## 2025-04-07

### Added
- No new rules added.

### Changed
- **Rule:** (T1070.002)Clear Log Activities
  **Change:** Update condition to be more specific.

- **Rule:** (T1564.001)Create Hidden Files or Directories
  **Change:** Improve the condition to exclude known legitimate activity detected by the rule.

- **Rule:** (T1609)Docker or kubernetes client executed in container
  **Change:** Update condition to be more specific.

- **Rule:** (T1105)Launch Ingress Remote File Copy Tools in Container
  **Change:** Update condition to be more specific.

- **Rule:** (T1611)Switch Linux namespace
  **Change:** Improve the condition to exclude known legitimate activity detected by the rule.

### Removed
- No rules removed.