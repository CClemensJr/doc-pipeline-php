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
- Click 'Next' without changing any other options
- Choose 'GitHub'
- Connect to GitHub
- Click 'Repository' dropdown and click the 'deployment-pipeline-app'
- Click 'Branch' drop down and click 'master'
- Leave the 'Change Detection Options' on 'Github webhooks' then press next
- Click 'Skip Build Stage' then 'Skip'
- Click 'Deploy Provider' drop down and click 'Elastic beanstalk'
- Open AWS in a new tab
- Go to the Elastic Beanstalk Service
- Click on 'Create New Application'
- Give the application a name
- Click 'Create'
- Click 'Create Environment'
- Ensure 'Web Server Environment' is selected and click Select.
- Under the 'Choose platform' dropdown select PHP
- Without changing any other settings click 'Create Environment"
- After the environment is finished building, return to the tab with the CodePipeline
- Select the name of the Application you created
- Select the name of the Environment you created
- Click Next
- Review the Setup process and then click 'Create Pipeline'

## Screenshot that it works
[Screenshot](https://github.com/Antberry/doc-pipeline-app/blob/master/screenshots/Screen%20Shot%202019-07-16%20at%2010.14.12%20AM.png)
[Screenshot2](https://github.com/Antberry/doc-pipeline-app/blob/master/screenshots/Screen%20Shot%202019-07-16%20at%2010.25.47%20AM.png)

## Troubleshooting Tips

Make sure you uploading the right JS file to the pipeline from GitHub because I uploaded this document file
instead of the deployment-pipeline-app.
