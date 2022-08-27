# uda-aws-devops-project03
Add starter source code from Udacity to complete the project03 of AWS DevOps course.

01. Presentation.pdf
 - Revenue and cost
 - Transfer the benefits of CICD from technical language to business language (that create revenue, protect revenue, control costs, or reduce costs)
 - 5 slides.

1. [URL01] - Public Url to GitHub repository (not private)
- [caonguyen207/uda-aws-devops-project03]https://github.com/caonguyen207/uda-aws-devops-project03
2. [URL02] - Public URL for your S3 Bucket (aka, your green candidate front-end)
- 
3. [URL03] - Public URL for your CloudFront distribution (aka, your blue production front-end)
- 
4. [URL04] - Public URLs to deployed application back-end in EC2
- 
5. [URL05] - Public URL to your Prometheus Server
- 

TODO: Fix after screenshot03
npm audit fix
OR
change the version in backend/package.json
"class-validator": "0.12.2"
"standard-version": "^7.0.0"

TODO: Create IAM user with ReadOnlyPermission
https://sst.dev/chapters/create-an-iam-user.html

TODO: Add a PostgreSQL database in RDS that has public accessibility
https://aws.amazon.com/getting-started/tutorials/create-connect-postgresql-db/
Make public

Endpoint (Hostname): database-1.ch4a9dhlinpw.us-east-1.rds.amazonaws.com 
Instance identifier: database-1 //This is not the database name
Database name: postgres (default)
Username: postgres
Password: mypassword
Port: 5432

TODO: Manual create S3 bucket first.

TODO:
aws cloudformation deploy \
         --template-file cloudfront.yml \
         --stack-name InitialStack\
         --parameter-overrides WorkflowID=udapeople-kk1j287dhjppmz437