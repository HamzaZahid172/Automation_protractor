# Automation_protractor
Automation of Site "momonto" checking the button and checklist,etc 

## Step 1 : Download and install node.js
 https://nodejs.org/en/download/
 node -v
 npm -v

## Step 2 : Install Protractor
npm install -g protractor
 protractor --version

Optional: If you face issue with permission then run below command:
 sudo chown -R USER: /usr/local/lib/node_modules

## Step 3 : Run command
 webdriver-manager update

## Step 4 : Find conf.js file at /usr/local/lib/node_modules/protractor/example

On cmd goto the location of this file

and run command
protractor conf.js
