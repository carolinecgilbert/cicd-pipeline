# cicd-pipeline

CI/CD Pipeline for basic Node.js "hello world" application using GitHub Actions, Docker, and AWS EC2 instance.


Process:
1. Create Node.js "hello world" app repo
2. Setup Dockerhub repo with same repo name
3. Use GitHub Actions Docker Image workflow to build Docker repo of Github repo (CI pipeline)
4. Setup EC2 instance on AWS to allow for public traffic
5. Setup GitHub Actions runner on EC2 instance (install dotnet 6 on EC2 instance)
6. Create GitHub Actions CD workflow on self-hosted runner to deploy Deocker repo on EC2 instance
7. Setup Nginx server to host Docker IP address

Source:
[CI/CD Pipeline Tutorial](https://youtu.be/rRes9LM-Jh8?si=ChIH1JkdtpdaYJjd)

