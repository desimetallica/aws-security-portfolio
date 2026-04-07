# AWS Security Portfolio

A structured, hands-on portfolio demonstrating practical security competencies across AWS environments, including hardening, visibility, Infrastructure as Code (IaC), workload protection, and privilege escalation.

**Author:** Davide Desirello

---

## Overview

This repository serves as a consolidated entry point for a multi-week security study focused on AWS.

The work emphasizes:

* Practical implementation over theory
* Realistic misconfigurations and attack paths
* Defensive strategies aligned with cloud security best practices

Each module explores a specific domain of cloud security, combining offensive techniques (to understand risks) and defensive controls (to mitigate them).

---

## Learning Objectives

* Understand and mitigate common AWS misconfigurations
* Gain visibility into cloud environments through logging and monitoring
* Secure infrastructure provisioning using Terraform
* Protect workloads at runtime
* Identify and prevent IAM privilege escalation paths

---

## Lab Modules

| Week | Topic                | Focus Area                                      | Repository                                               |
| ---- | -------------------- | ----------------------------------------------- | -------------------------------------------------------- |
| 1    | Hardening            | Linux and baseline cloud security               | https://github.com/desimetallica/week1-hardening-lab     |
| 2    | AWS Visibility       | CloudTrail, logging, monitoring                 | https://github.com/desimetallica/week2-aws-visibility    |
| 3    | IaC Security         | Terraform misconfigurations and secure patterns | https://github.com/desimetallica/week3-iac-basics        |
| 4    | Workload Security    | Runtime protection and attack surface reduction | https://github.com/desimetallica/week4-workload-security |
| 5    | Privilege Escalation | IAM abuse techniques and mitigation             | https://github.com/desimetallica/week5-escalation-lab    |

---

## Competencies Demonstrated

### AWS Security

* IAM policy analysis and privilege escalation detection
* Principle of least privilege enforcement
* Identity and access misconfiguration analysis

### Visibility & Detection

* CloudTrail configuration and log analysis
* Detection of suspicious activity patterns
* Logging strategies for incident response

### Infrastructure as Code (IaC)

* Terraform security best practices
* Identification of insecure defaults
* Prevention of configuration drift and exposure

### Workload Security

* Attack surface reduction techniques
* Runtime security considerations
* Secure configuration of compute resources

### Offensive Security Perspective

* Simulation of real-world attack paths
* Exploitation of misconfigured IAM roles
* Understanding attacker methodology in cloud environments

---

## Security Approach

The labs follow a progressive security model:

1. **Hardening** → Establish a secure baseline
2. **Visibility** → Enable detection and monitoring
3. **IaC Security** → Prevent insecure deployments
4. **Workload Protection** → Secure runtime environments
5. **Privilege Escalation** → Understand and mitigate attacker techniques

This reflects a real-world defensive strategy where prevention, detection, and response are layered.

---

## Example Attack Scenarios Covered

* Over-permissive IAM roles leading to privilege escalation
* Lack of logging visibility enabling stealth activity
* Misconfigured Terraform deployments exposing resources
* Weak system hardening increasing attack surface

---

## Why This Matters

In cloud environments, the majority of security incidents are caused by misconfigurations rather than software vulnerabilities.

This portfolio focuses on:

* Identifying those weaknesses
* Understanding how they are exploited
* Applying effective mitigations

---

## Disclaimer

This project is intended for educational purposes only.
All activities were performed in controlled lab environments.

---

## Contact

For professional inquiries or collaboration:

* GitHub: https://github.com/desimetallica
