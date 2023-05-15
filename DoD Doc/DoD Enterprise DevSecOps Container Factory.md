The DoD Enterprise DevSecOps Container Factory (DEDF) is a container factory that provides a secure, scalable, and standardized environment for building and deploying containerized applications within the Department of Defense. The workflow of DEDF can be described as follows:

| Workflow Step              | Description                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------------------|
| Source Code Management     | Developers check-in code changes into the source code repository                                   |
| Build Automation           | The CI/CD pipeline is triggered to build the container image                                        |
| Image Scanning and Analysis| The container image is scanned for vulnerabilities and security issues                             |
| Container Image Signing    | The container image is signed to ensure authenticity and integrity                                 |
| Artifact Repository        | The container image is stored in a secure artifact repository                                       |
| Testing                    | The container image is tested for functionality and security                                        |
| Deployment                 | The container image is deployed to the production environment                                       |
| Runtime Monitoring         | The containerized application is monitored for performance and security issues                    |


Let's say you want to build a mobile app that helps people learn a new language. You write the code for the app and save it in a repository, where it can be easily accessed and modified. Next, you use the DEDF to build a container image of your app, which is a complete and self-contained version of your app that can run on any device or platform. The container image is scanned for any security issues, signed to ensure authenticity, and stored in a secure artifact repository. Then, the container image is tested for functionality and security to make sure everything is working properly. Once the testing is complete, the container image is deployed to the app store or other production environment where users can download and use your app. Finally, the app is monitored for performance and security issues to make sure it continues to work properly and keep user data safe.

List of tools used in a table:


| Tools | Descprition |
| ---|---|
| Git | Version control system used for source code management |
| Jenkins   | CI/CD pipeline orchestration tool used for building and testing the container image                   |
| Docker    | Containerization platform used for building and running containerized applications                     |
| Clair     | Container image vulnerability scanner used for image scanning and analysis                           |
| Notary    | Tool used for container image signing                                                                  |
| Artifactory | Artifact repository used for storing container images                                                 |
| Selenium  | Testing tool used for functional and security testing                                                 |
| Kubernetes | Container orchestration platform used for deployment and runtime monitoring                          |

[[Containers]]