# Node Hello World

Simple node.js app

Great for testing simple deployments on Cloud


## Step 1: Install Jenkins

```bash
sudo apt update
sudo apt install openjdk-11-jre
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins

```



## Step 2: Install NodeJS and NPM using nvm


```bash
sudo su -
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
Activate nvm by typing the following.

```bash
. ~/.nvm/nvm.sh
```

Use nvm to install the latest version of Node.js by typing.

```bash
nvm install node
```

Test that node and npm are installed and running.

```bash
node -v
npm -v
```

## Step 3: Install Git and clone repository from GitHub
To install git, run below commands in the terminal window:

```bash
sudo apt-get update -y
sudo apt-get install git -y
git — version
```


Run below command to clone the code repository from Github:

```bash
git clone https://github.com/amgadelhosieny/CICD-pipeline-for-nodejs.git
```

Get inside the directory and Install Packages and then start

```bash
cd nodejs-on-ec2
npm install
npm start
```

