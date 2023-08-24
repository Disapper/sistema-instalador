#instalador

adduser deploy
cd /home/deploy/
git clone https://github.com/Disapper/sistema-instalador
cd sistema-instalador/
chmod +x install_primaria 
sudo apt update && sudo apt upgrade

git clone https://github.com/Disapper/sistema-codigo
 
