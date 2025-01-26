# pythonjk

sudo apt install docker.io -y
sudo service docker start
sudo systemctl enablr docker.service

Grant sudo privileges to the Jenkins user without requiring a password: sudo visudo
add this second last line(to give sudo permission): jenkins ALL=(ALL) NOPASSWD:ALL

sudo systemctl restart jenkins

Add Jenkins to the docker group:  sudo usermod -aG docker jenkins

mkdir pythonpp
cd pythonpp/
python3 --version
sudo apt install pip3 -y
sudo apt update
sudo apt install python3-pip -y
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.12-venv
python3 -m venv venv 
source venv/bin/activate
pip install Flask
nano app.py
nano Dockerfile  
nano requirements.txt 

