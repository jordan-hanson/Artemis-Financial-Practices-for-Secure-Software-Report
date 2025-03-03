# Artemis Financial Practices for Secure Software Report

## Summary

This project involved completing a secure software review and enhancement process for Artemis Financial, a financial services provider looking to improve the security of their internal web application. The assessment identified critical vulnerabilities, and through a series of refactoring steps, I addressed those issues by introducing a secure communications channel, updating the code to mitigate security risks, and verifying that no new vulnerabilities were introduced during the changes.

## Key Improvements and Results

- Implemented HTTPS to ensure secure communication between clients and the server.
- Updated dependencies to mitigate known critical vulnerabilities, such as issues with outdated libraries.
- Performed a detailed static analysis using dependency-check tools to ensure the codebase complied with security best practices.
- Conducted functional testing to confirm the application still operated as intended after refactoring.
- Removed the inclusion of a vulnerable component, `snakeyaml`, to eliminate its associated risks.

## Reflection

Working through this project provided a valuable opportunity to practice secure coding and gain familiarity with tools like OWASP Dependency-Check and modern Spring Boot security practices. The process reinforced the importance of identifying, mitigating, and verifying security measures in software projects. By focusing on these best practices, I gained confidence in creating more secure code while maintaining functionality and performance. This project, stored in this GitHub repository, serves as a practical example of my ability to secure a web application and ensures that I have a strong understanding of secure software development principles.

## Additional Information

For more details on the process and steps taken, please refer to the full report document included in this repository.
