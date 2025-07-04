# modulo-V-

mkdir practica1
cd practica1/
sudo touch {1..100}.txt
ls

sudo apt install rsync -y

rsync -a /practica1 kaliclon@192.168.0.110:/home/kaliclon 

en la otra maquina ponemos 

ls 
cd practica1/ 
ls 

y se mostrara como se envio el archivo de manera integra 
