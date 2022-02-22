# UdaGramDeployingIAC
My company is creating an Instagram clone called Udagram.  Developers want to deploy a new application to the AWS infrastructure.  I have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software.  This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results. 

### Dependencies
##### 1. AWS account
I require to have an AWS account to be able to build cloud infrastructure.
![image](screenshots/img1.png)

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. 
![image](screenshots/img2.png)

##### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com](www.lucidchart.com) is required to be able to draw the web app architecture diagrams for AWS.
![image](screenshots/img3.png)

# Ensure that the AWS CLI is configured before runniing the command below
![image](screenshots/img4.png)

# Create the network infrastructure
![image](screenshots/img5.png)

# Check the region in the create.sh file
./create.sh UdaGramApp network.yml network-parameters.json
![image](screenshots/img6-1.png)

![image](screenshots/img7.png)

# Create servers
![image](screenshots/img8.png)

# Change the AMI ID and key-pair name in the servers.yml
![image](screenshots/img9.png)

# Check the region in the update.sh file
./update.sh mySecStack servers.yml server-parameters.json
`![image](screenshots/img10.png)
json

``

