This is a small project I worked on recently to learn about securing CI/CD pipelines.  
I used GitHub Actions as the CI/CD tool and implemented Bandit, SonarCloud, and Aikido for security scanning.  
My future plan is to integrate DAST, SCA tools and image scanning for microservices.  
Current issue is that all vulnerabilities are not in one place as Bandit generates a report, while SonarCloud and Aikido manage vulnerabilities on their dashboards. One solution I found was to use Defect-Dojo, but it doesn't provide a free cloud-based option and manually adding all vulnerabilities to the software defeats the purpose of automation in pipelines.  
  
Future Scope:  
- Integreate Terraform to deploy services on different cloud platforms.  
  
