# Deployment 1
---

### Jenkins Pipeline

1. Was able to Login to Jenkins server and setup the pipeline
2. Ran the build and got an error in the test stage
3. Looked at the logs from the build and it stated the following "you need to install the python3-venv
package"
4. Went into the Jenkinsfile and added the command to install the needed python package to the build stage
5. Reran the build in Jenkins and everything passed.

### Elastic Beanstalk

1. Zip all application files to be used to deploy on Elastic Beanstalk
2. Created the needed IAM roles for the AWS Services so they have the appropriate permissions to be used by Elastic Beanstalk
3. Deployed the URL shortner on Elastic Beanstalk and was able to use the domain created to open the application
