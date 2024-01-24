# Caldera

Commands:
sudo apt-get update && sudo apt-get upgrade -y

sudo apt install python3-pip -y
pip3 install pyopenssl --upgrade

git clone https://github.com/mitre/caldera.git --recursive
cd caldera
pip3 install -r requirements.txt
python3 server.py
