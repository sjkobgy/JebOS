# Security Policy

## Supported Versions

This section outlines which versions of **JebOS** are currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 7.8     | :white_check_mark: |
| 7.0     | :x:                |

> **Note:** Only versions **7.8.x** and **7.6.x** are actively supported with security updates. Older versions (below 7.6) are no longer maintained and may contain unpatched vulnerabilities.

## Reporting a Vulnerability

If you have found a vulnerability in **JebOS**, please follow these steps to report it:

1. **Create a private issue** in the GitHub repository for **JebOS** or, if the repository is private, email us directly at [security@jebos.org](mailto:security@jebos.org).

2. In your report, please include the following details:
   - A detailed description of the vulnerability.
   - Steps to reproduce the issue.
   - The version of **JebOS** in which the vulnerability was found.
   - Potential exploit vectors.
   - A sample of code or configuration that illustrates the problem, if possible.

3. **Expected Response Time:**
   - We aim to respond to all security reports within **48 hours**.
   - Once the vulnerability is confirmed, we will issue a fix in the next patch or release.

4. **What to expect if the vulnerability is accepted or declined:**
   - **Accepted Vulnerability**: A patch will be developed and included in the next update. All affected versions of **JebOS** that are currently supported will receive the fix.
   - **Declined Vulnerability**: If the reported issue is determined not to be a security vulnerability or is not reproducible, we will inform you of our findings and close the report.

5. **Security Patch Updates:**
   - **JebOS** will make every effort to address security vulnerabilities in supported versions.
   - Users of unsupported versions should update to the latest supported version to receive security fixes.
   - If a patch is released, it will be made available through GitHub releases or other distribution channels.

> **Important:** Please refrain from publicly disclosing vulnerabilities until a fix has been issued to avoid exploitation.
