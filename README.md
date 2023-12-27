# Celestial
Tool is specifically engineered to identify and mitigate a wide range of vulnerabilities, ensuring the integrity and security of your cloud databases.

## Key Features:

- Multi-Cloud Support: Tailored to seamlessly integrate with AWS, Azure, and GCP, Celestial provides a unified security front across different cloud environments.
- Comprehensive Scanning: From common SQL injections to cloud-specific vulnerabilities, our tool exhaustively scans for various security threats, leveraging the latest in cybersecurity research.
- User-Friendly Interface: Powered by HTMX, Celestial boasts an intuitive, responsive user interface. Manage scans, view results, and configure settings with ease.
- Automated Scans: Schedule regular scans to ensure ongoing protection, keeping your databases secure around the clock.

## Understanding Cloud Database Services
- AWS (Amazon RDS): Research RDS's various database engines and common vulnerabilities.
- Azure (SQL Database): Research Azure's security features and known vulnerabilities.
- GCP (Google Cloud SQL): Research Google Cloud SQL's configuration and potential security issues.

## Vulnerability Scanning Criteria
- Common Database Vulnerabilities: SQL injection, privilege escalation, data exposure, etc.
- Cloud-Specific Vulnerabilities: Unique vulnerabilities for each cloud provider.

## To-Do

### Backend (Go with Echo):

- [ ] Design RESTful APIs for managing scans, viewing results, and configuring settings.
- [ ] Implement robust authentication and authorization for API access.
- [ ] Integrate with cloud providers' APIs for database information retrieval.
- [ ] Develop the vulnerability scanning logic for various types of database vulnerabilities.

### Frontend (HTMX):

- [ ] Create a dynamic and responsive user interface for the tool.
  - Use HTMX for real-time content updates without full page reloads.
- [ ] Implement intuitive controls for initiating scans, viewing results, and managing configurations.
