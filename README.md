# User-defined Port Scanner
This project aims to develop a tool that scans a target system for open ports based on a user-provided list.

**Functionalities**

User Input: The user will be able to specify a list of ports (e.g., comma-separated values) to scan.

Port Scanning: The tool will implement logic to probe each port on the target system.

Open Port Identification: The tool will identify and report any open ports from the provided list.

**Benefits**

Targeted Scanning: This tool provides a more focused approach compared to scanning all ports, saving time and resources.

Customization: Users can tailor the scan to their specific needs by defining the ports of interest.

Security Assessment: This tool can be used for basic security assessments to identify potential vulnerabilities arising from open ports.

**Implementation Considerations**

Operating System Compatibility: The tool should be designed to work across different operating systems (Windows, Linux, macOS).

Scanning Technique: The tool can leverage system libraries or command-line utilities (e.g., netstat on Linux) for port scanning functionality.

Error Handling: The tool should handle potential errors gracefully, such as invalid port numbers or unreachable target systems.

Output Formatting: The tool should present the scan results in a clear and user-friendly format, highlighting open ports.

**Potential Applications**

System Administrators: IT professionals can utilize this tool for routine security checks and troubleshooting network connectivity issues.

Network Security Professionals: This tool can be used as a part of a broader security assessment to identify open ports that might pose security risks.

Penetration Testers: During penetration testing engagements, this tool can be employed to identify potential attack vectors through open ports.
