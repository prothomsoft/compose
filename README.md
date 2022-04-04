HOW TO INSTALL DOCKER
sudo yum update
sudo yum search docker
sudo yum info docker
sudo yum install docker
sudo systemctl enable docker.service
sudo systemctl start docker.service
sudo systemctl status docker.service

HOW TO INSTALL DOCKER COMPOSE
sudo su
sudo curl -L https://github.com/docker/compose/releases/download/1.21.0/docker-compose-`uname -s`-`uname -m` | sudo tee /usr/local/bin/docker-compose > /dev/null
sudo chmod +x /usr/local/bin/docker-compose
ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
docker-compose --version

port:81
Log in with the username “admin@example.com” and the password “changeme”.