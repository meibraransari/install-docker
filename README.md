# Install Docker
```
sudo apt-get install -y docker
sudo service docker start
```

# Configure Docker user group permissions
```
sudo groupadd docker
sudo gpasswd -a ${USER} docker
sudo service docker restart
```
# Set Docker to auto-launch on startup
```
sudo systemctl enable docker
```
