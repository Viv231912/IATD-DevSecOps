# IATD-DevSecOps
Vulnerable application for DevSecOps Microcredential

The repository was cloned from [https://github.com/erev0s/VAmPI](https://github.com/erev0s/VAmPI)

# Key Takeaways

This DevSecOps project focused on building a secure CI/CD pipeline while integrating various security practices and tools to ensure application and infrastructure security. The primary objective was to implement shift-left security and zero trust principles to identify and resolve vulnerabilities early in the development lifecycle.

## Technologies and Tools Used:
### CI/CD Pipeline:      
    - Automated the development pipeline to build, test, and deploy code securely.
### Threat Dragon: 
    - Utilized for threat modeling and analyzing security risks in the architecture.
### SonarQube: 
    - Integrated for static code analysis to identify code quality issues and vulnerabilities.
### AZ CLI: 
    - Deployed container apps, set up app environments, and managed SQL server and SonarQube containers.
### Docker: 
    - Used to containerize applications and manage container images.
### ZAP (DAST): 
    -  Integrated dynamic application security testing (DAST) to find runtime vulnerabilities.
### SBOM (Software Bill of Materials): 
    - Generated SBOMs to track open-source components and their vulnerabilities.
### Linux Command Line: 
    - Extensively used for setting up and managing containers and infrastructure.
### Python: 
    - The primary language used for automating various aspects of the pipeline and security tools.
## Key Security Concepts:
### Shift-Left Security: 
    - Incorporated security checks early in the development process, enabling faster detection and remediation of vulnerabilities.
### Zero Trust: 
    - Implemented zero trust principles to limit access and enhance system security by validating every interaction.
