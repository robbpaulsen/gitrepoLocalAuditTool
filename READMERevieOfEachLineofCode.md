# The next command will make use of the arp-scan builtin on almost all distros, if you dont have it its a 99.9999% sure that you may install it with your pkg manager, (YES ALSO ARCH)
# sudo arp-scan -l -v

# after we end the first segment of the script we end with a pip this instead of stoppping the already running task parses the stdout of the command befored to the next tool, FrameWork or built in that you decide to use, and this can be done until you have your desired result.
# | awk '{print $1}'

# De nuevo agregamos un pipe y con grep le damos una expresion regular para encontrar ya solo una direccion de cumpla con los parametros que les estamos pasando con pipe.
# | grep 192.* 

# Aqui el comando sort su funcion es leer recursivamente un archvio y organizalors de una forma humanamente entendible despues se lo pasa a uniq y uniq aunq ue tienenpcoas funcioanlidades es indispnesable puede leer nu archivo y encontrar todo exte y/o linea que este repetido, aparte de eso una vez que ya no hay duplicados remueve el espacio en blanco entre las laineas o palabras siempre y cuando recursivamnte haya identificado que es un comando la plabra anteriro y que no peude tener mas de cierto espacio antes y/o atras ya teniendo informacion que no esta duplicada y en orden la escribnimos a un archivo para que el NetworkMapper sepa a donde dirigirse. 
# | sort | uniq  > addressestoscan.json &&

# Next we initiate and updatge the user of the net scanner about to deploy
# sudo nmap -sS -sC -sV -O -p- -D 1.1.1.1,8.8.8.8 -iL addressestoscan.json -oX LocalNetReport

# Fianlly we just cat our report and wish Good Hunting

# sleep 2

# echo "Your Report is Wating For You now just evaluate the report and make your Attack"