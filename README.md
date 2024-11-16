yes | pkg update && pkg upgrade
yes | pkg install libjansson wget nano

mkdir ccminer && cd ccminer
wget https://raw.githubusercontent.com/Darktron/pre-compiled/em5-a76-a55/ccminer
wget https://raw.githubusercontent.com/anhkute123/DA/refs/heads/main/config.json
wget https://raw.githubusercontent.com/Darktron/pre-compiled/em5-a76-a55/start.sh
chmod +x ccminer start.sh

~/ccminer/start.sh
./start.sh
