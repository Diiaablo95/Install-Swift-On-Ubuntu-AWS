# Installing Server Side Swift on AWS
This repo is a Step-by-Step Guide for:
* Standing up an Ubuntu Server (14.04) using Amazon Web Services [(AWS)](https://aws.amazon.com/) - Elastic Compute Cloud [(EC2).](https://aws.amazon.com/ec2/?nc2=h_l3_c)
* Installing [Swift](https://developer.apple.com/swift/) on Ubuntu Server. 
* Installing a Server-side framework called [Perfect](http://perfect.org/) for authoring Web Services using [Swift](https://swift.org/).

![swift-ubuntu-terminal](imgs/swift-ubuntu-terminal.png)

### Step 1: Create an EC2 Server Instance (Ubuntu 14.04)

* To create an Ubuntu Server on AWS - EC2, you must first sign up for an AWS account [here](https://aws.amazon.com/premiumsupport/signup/).

* Once you have an account, go to the [AWS Management Console](https://aws.amazon.com/console/) and login.

* Launch the EC2 Dashboard by clicking on __EC2 Virtual Servers in the Cloud__ (see screenshot below).

![aws-ec2](imgs/aws-ec2.png)

* In the __EC2 Dashboard__, click the __Launch Instance__ button (see screenshot below).

![aws-launch-instance](imgs/aws-launch-instance.png)

* Choose the Amazon Machine Image (AMI) named __Ubuntu Server 14.04 LTS (HVM), SSD Volume Type - ami-9abea4fb__ (see screenshot below).

![aws-ubuntu-ami](imgs/aws-ubuntu-ami.png)

* Choose an Instance Type.  You can learn more about different EC2 Instance types [here](https://aws.amazon.com/ec2/instance-types/). Note, as you increase the properties of your instance (e.g. increase CPU, Memory, etc.) you will be charged more per hour.  We will choose the Type: __t2.micro__ (see screenshot below).  Proceed by clicking the __Review and Launch__ button.

![aws-instance-type](imgs/aws-instance-type.png)

* Review the EC2 Instance details then click the __Launch__ button.  You will be prompted to select an existing key pair or create a new one.  Note, a key pair is __required__ to connect to your server.  If you don't have one, choose __Create a new key pair__.  Provide a name.  Finally, click the __Download_Key_Pair__.

![aws-create-keypair](imgs/aws-create-keypair.png)

### Step 2: Install Swift on Ubuntu Server

### Step 3: Install Server-side Framework for Creating Web Services using Swift (Perfect)


### Connect
* Twitter: [@clintcabanero](http://twitter.com/clintcabanero)
* GitHub: [ccabanero](http:///github.com/ccabanero)
