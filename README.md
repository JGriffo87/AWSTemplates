# Instructions for Deploying Cloud Formation Templates

Step 1: Open Cloudformation Template and copy all text to a notepad

Step 2: Save Notepad as <choosename>.yaml

Step 3: Download the AWS CLI at https://awscli.amazonaws.com/AWSCLIV2.msi and Install

Step 4: Open Powershell as an Admin and navigate to the folder path that the saved yaml file is located.

Step 5: login to your AWS account in Powershell by using <aws configure>. Will need account access ID, Secret Access Key, and Default Region Name

Step 6: Use command example (aws cloudformation create-stack  --stack-name Test --template-body file://<Name of file> --parameters  ParameterKey=<First Parameter>,ParameterValue=<parameter value> ParameterKey=<second parameter>,ParameterValue=<second parameter value>

