# Intrusion Detection System (IDS)

An **Intrusion Detection System (IDS)** is a security solution—either a device or software application—that monitors network or system activities for malicious actions or policy violations. When suspicious or unauthorized activity is detected, the IDS generates alerts to notify administrators or security teams for further investigation.

## How IDS Works

- IDS tools analyze network traffic or system events to identify known threats (using signature-based detection) or unusual behavior (using anomaly-based detection).
- They are typically deployed in two main forms:
  - **Network-based IDS (NIDS):** Monitors network traffic for suspicious activity.
  - **Host-based IDS (HIDS):** Monitors activities on individual devices or hosts.
- IDS solutions can be passive (monitor and alert) or, in some cases, active (take limited action, though this is more typical of Intrusion Prevention Systems, IPS).

## Key Features

- **Detection:** Identifies potential intrusions, such as unauthorized access, malware, or policy violations.
- **Alerting:** Notifies administrators or integrates with SIEM (Security Information and Event Management) systems for centralized monitoring.
- **Types of Detection:**
  - **Signature-based:** Matches activity against known attack patterns.
  - **Anomaly-based:** Flags deviations from established normal behavior.

## IDS vs. IPS

| Feature                | IDS (Intrusion Detection System) | IPS (Intrusion Prevention System) |
|------------------------|----------------------------------|-----------------------------------|
| Role                   | Detects and alerts               | Detects and blocks                |
| Network Placement      | Out-of-band                      | Inline                            |
| Response               | Passive (alert only)             | Active (can block/mitigate)       |

## Use Cases

- Detecting unauthorized access attempts
- Identifying malware or exploit activity
- Monitoring for policy violations
- Supporting compliance and incident response.

IDS is a foundational component of modern cybersecurity, helping organizations detect and respond to threats before significant damage occurs.
