API Security Risk Analysis: ReqRes SaaS Platform 🚀

Project Overview
This project involves a comprehensive API Security Risk Analysis of the ReqRes (reqres.in) demo environment. As modern applications rely heavily on APIs for mobile and web integration, this audit focuses on identifying vulnerabilities in authentication, information disclosure, and rate limiting based on the OWASP API Security Top 10 framework.

Identified Security Risks
**Risk Category**                  **Severity**           **Description**                      
Verbose Auth Errors                 Medium                 API leaks internal logic and header requirements (x-api-key) in error responses.
Excessive Data Exposure              Low                   Response headers disclose server infrastructure (e.g., Cloudflare/Express) facilitating fingerprinting.
Lack of Rate Limiting                High                  Absence of request throttling allows for potential Denial of Service (DoS) attacks.

**Methodology**
Reconnaissance: Analyzed API documentation and public endpoints.
Manual Testing: Performed targeted GET/POST requests to observe authentication behavior.
Traffic Inspection: Used Browser DevTools to analyze HTTP response headers and JSON metadata.
Stress Testing: Conducted manual rapid-fire requests to evaluate rate-limiting resilience.

**Tools Used**
Postman: For automated and manual API endpoint testing.
Browser DevTools (F12): For inspecting Network traffic and security headers.
WORD: For professional report documentation and risk visualization.
