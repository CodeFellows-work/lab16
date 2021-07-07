# Lab 16 

## Sunny Lee 

Elastic Beanstalk AWS link GUI: Lab16-env.eba-cindwigm.us-west-2.elasticbeanstalk.com

Elastic Beanstalk CLI deployment: cliHello.eba-qjn2uh9p.us-west-2.elasticbeanstalk.com

For the GUI start by creating a new application and changing the settings to admin priveldges, use of Node.js, and application name. Then retrieve the access key and secret key to enter after inputting aws configure to connect your cli to aws services. After deployment of your code, you can use the link. 

For the CLI we can start with `eb create` after you have configured through aws. Then after answering a couple questions you can move onto deploying. I had to remember to ACP before doing so because the git branch head was still present and would fail the create. You can deploy once the application has been properly loaded. 