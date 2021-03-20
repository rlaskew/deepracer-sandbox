# deepracer-sandbox
Repo for AWS VM Training for Deep Racer

Start Here
https://aws-deepracer-community.github.io/deepracer-for-cloud/installation.html

parameters.json is intentionally in .gitignore

Sample Commands
* aws cloudformation validate-template --template-body file://training_host.yml
* aws cloudformation validate-template --template-body file://training_host.yml > parameters.json
* aws cloudformation create-stack --template-body file://training_host.yml --parameters file://parameters.json --stack-name deepracer-sandbox-1 
* aws cloudformation delete-stack --stack-name deepracer-sandbox-1