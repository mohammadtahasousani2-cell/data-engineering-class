\# Activity 5: CI/CD Flow



1\. A developer pushes code to the GitHub repository.

2\. GitHub Actions runs the project's tests.

3\. If any test fails, the pipeline stops. It must not build or deploy.

4\. If all tests pass, the pipeline builds a Docker image.

5\. After a successful build, the pipeline deploys the application.



\## Flow



Developer push → GitHub repository → Run tests



\- Tests fail → Stop the pipeline

\- Tests pass → Build Docker image → Deploy



