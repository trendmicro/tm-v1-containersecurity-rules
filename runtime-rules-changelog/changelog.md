# Trend Vision One™️ Container Security
# Runtime Security Rules Changelog

## 2025-07-09

### Added
- No new rules added.

### Changed
- **Rule:** (T1222.002)File attributes changed in container
  **Change:** Improved detection condition to better target relevant file attribute modifications.

- **Rule:** (T1059)Redirect STDOUT/STDIN to Network Connection in Container
  **Change:** Improved the performance and excluded known legitimate activity.

- **Rule:** (T1021.004)Lateral Movement using SSH
  **Change:** Improved performance and refined detection logic for more targeted alerts.

- **Rule:** (T1611)Switch Linux namespace
  **Change:** Enhanced detection condition to exclude known legitimate activity.

- **Rule:** (T1059)System procs network activity
  **Change:** Improved conditions to exclude known legitimate activity.

### Removed
- No rules removed.


## 2025-05-28

### Added
- No new rules added.

### Changed
- **Rule:** (T1070.002)Clear Log Activities  
  **Change:** Improved the condition to exclude known legitimate activity detected by the rule.

- **Rule:** Vulnerable liblzma loaded into sshd  
  **Change:** Improved the condition to better detect the library name.
  - Rule name updated to (T1133)Vulnerable liblzma loaded into sshd.
  - Rule description updated.

### Removed
- No rules removed.


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