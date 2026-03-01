Client Summary
Artemis Financial is a consulting company that develops financial plans for its clients. The company wanted to modernize its public web application while improving its software security. The main issue to address was protecting sensitive finalical data.

What I Did Well
I successfully identified potential vulnerabilities using OWASP Dependecy-Check and analyzed which findings were risks versus false positives. I implemented TLS encryption over HTTPS and configured the application to use port 8443 with a self-signed certificate. I also used SHA-256 checksum verification.

Challenges
Configuring OWASP Dependency-Check and implementing the suppression.xml file to manage false positives was the most challenging part. However, this experience was valuable because it helped me see real work DevSecOps practices.

Increasing Layers of Security
Security layers were increased by
  Enabling HTTPS using TLS
  Generating a certificate
  SHA-256 hashing
  Running static vulnerability scans

Ensuring Functionality and Security
After refactoring the application, I tested the server to make sure endpoints functioned correctly. I then re-ran OWASP Dependency-Check to make sure of no new vulnerabilities.

Tools and Resources Used
  Spring Boot
  Maven
  OWASP Dependency-Check
  TLS configuration
  SHA-256 hashing
  Secure coding practices

Portfolio Value
This demonstrates my ability to perform vulnerability assessments, apply encryption and hashing techniques, and refactor code.
