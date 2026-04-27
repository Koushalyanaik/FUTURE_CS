**Altoro Mutual: Vulnerability Assessment Report 🛡️**


**Project Overview:**
This project involves a comprehensive Vulnerability Assessment of the digital infrastructure for Altoro Mutual (demo.testfire.net). The audit focuses on identifying security gaps, classifying risks, and providing actionable remediation steps based on the OWASP Top 10 framework.

**Identified Vulnerabilities--**
**Vulnerability**                           **Risk Level**               **Mitigation Strategy**
Missing Security Headers                  Medium                    Implement HSTS, CSP, and X-Frame-Options
Insecure Cookie Flags                     Medium                    Apply HttpOnly and Secure attributes to all session tokens
Server Info Disclosure                    Low                        Suppress server version headers and use generic error pages.

**Methodology**
Passive Analysis: Conducted non-disruptive testing using browser-based inspection tools.
Manual Inspection: Evaluated HTTP response headers and cookie configurations.
Information Gathering: Analyzed server responses and directory structures for potential leakage.

**Tools Used**
Browser DevTools (F12): For header and session analysis.
Canva: For professional report documentation and layout.
