# CS561-Assignment2

API mocking
URL: http://3.92.62.115:7878/data/2.5/weather


please do the following steps:


1-chmod 600 cloud-labs-nv-delyar.pem
2-ssh -i "cloud-labs-nv-delyar.pem" ec2-user@ec2-3-92-62-115.compute-1.amazonaws.com
3- yum install git -y
4-sudo yum install git -y
5-curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
6-nvm install node
7-node -e "console.log('Running Node.js ' + process.version)"
8-npm install -g apimocker
9-git clone https://github.com/delyar/CS561-Assignment2.git
10-cd CS561-Assignment2
11-git checkout master
12-pwd
13-vi config.json
14- apimocker -c config.json
15-
