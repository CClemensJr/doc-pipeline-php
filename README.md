# Doc Pipeline PHP

## Implement a CI/CD pipeline with the following steps:
- Fork the repository
- Clone Repository to your computer from terminal
- In terminal type 'code .'
- Go to AWS
- Go to AWS Service 'CodePipeline'
- Click 'Create Pipeline'
- Enter Pipeline name
- Click 'New Service role'
- Click 'Next'
- Choose 'GitHub'
- Connect to GitHub
- Click 'Repository' dropdown and click the 'deployment-pipeline-app'
- Click 'Branch' drop down and click 'master'
- Skip Build stage
- Click 'Deploy Provider' drop down and click 'Elastic beanstalk'
- Go create a Elastic Beanstalk AWS for this app
- Once in Elastic beanstalk give it a name
- Choose platform which is 'node.js'
- Click next
- Select Application Name
- Select pipeline name
- Click Next
- Review the Setup process and then click 'Create Pipeline'

## Screenshot that it works
[Screenshot](https://github.com/Antberry/doc-pipeline-app/blob/master/screenshots/Screen%20Shot%202019-07-16%20at%2010.14.12%20AM.png)
[Screenshot2](https://github.com/Antberry/doc-pipeline-app/blob/master/screenshots/Screen%20Shot%202019-07-16%20at%2010.25.47%20AM.png)

## Troubleshooting Tips

Make sure you uploading the right JS file to the pipeline from GitHub because I uploaded this document file
instead of the deployment-pipeline-app.
