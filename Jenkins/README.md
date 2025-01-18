Create a seperate instance on AWS to manage jenkins server.


Ensure Jenkins pre-requisites are availble beforehand (JAVA JRE v17).


Run jenk.sh

Then install Docker on Jenkins Server using: 
```bash
sudo apt-get update

sudo apt-get install -y ca-certificates curl

sudo install -m 0755 -d /etc/apt/keyrings

sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc

sudo chmod a+r /etc/apt/keyrings/docker.asc

echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
$(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \
sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt-get update

sudo apt-get install -y docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin 
```


Then Type "public_ip:8080", Jenkins will open.


![jenkins_successful_setup](https://github.com/user-attachments/assets/943b25f4-b9d0-4cc9-9ca8-79b00a67c4d4)
