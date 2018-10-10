# cicd-pipeline-train-schedule-pipelines

This is a simple train schedule app written using nodejs. It is intended to be used as a basic example application to use with the build of a CI / CD pipeline

## CI /CD steps implement thus far

Gradle automated build using Gradle Wrapper
Deployment of Jenkins server into Azure and CI via manually triggered Jenkins build
Build automation via Jenkinsfile and webhooks to this Git Repo's Master Branch
Expanded Jenkinsfile with addtional stages.  The project now builds, tests and deploys to a 'staging' server before optional deployment to a 'production' server.

##To Do
Dockerise application and deploy container via Jenkins rather than to a pre-configured web server.
