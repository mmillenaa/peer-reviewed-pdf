# Security Policy

## Context & Privacy Guarantee
The Peer-Reviewed PDF App is a 100% client-side web application built with HTML, JS, pdf.js, and pdf-lib. **No backend server exists, and no files are ever uploaded or transmitted over the internet.** 

All PDF processing, line numbering, and annotation happen entirely within the user's local browser memory. This guarantees complete confidentiality for sensitive academic manuscripts and peer-review documents.

The realistic security risks are confined to the browser environment, such as vulnerabilities within the third-party JavaScript libraries used for PDF rendering.

## Supported Versions
Only the latest release on the `main` branch receives security updates and bug fixes.

## Reporting a Vulnerability
If you discover a security vulnerability (e.g., an exploit in the PDF parsing libraries), please do not open a public issue. Report it privately using one of the following methods:

1. **GitHub Private Reporting:** Go to the Security tab → Report a vulnerability.
2. **Email:** Send a message directly to millena@usp.br.

Please include the steps to reproduce the issue and the potential impact. You will receive an acknowledgment within ten working days.
