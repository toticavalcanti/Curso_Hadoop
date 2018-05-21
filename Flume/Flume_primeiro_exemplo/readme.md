#Para ativar o agente, entre na pasta onde tá o exemplo.conf
#No caso da máquina cloudera a pasta /etc/flume-ng/conf
#E digite o comando abaixo:

flume-ng agent -n a1 -c conf -f exemplo.conf

#Agora abra outro terminal e digite o comando abaixo:

telnet localhost 44444

