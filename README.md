# SSHPLUS

apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/ogenio/SSHPLUS/master/Plus && chmod 777 Plus && ./Plus


#Acessa Root

wget https://raw.githubusercontent.com/ogenio/SSHPLUS/master/senharoot.sh && chmod 777 senharoot.sh && ./senharoot.sh

#Formatar vps

bash <(wget -qO- https://raw.githubusercontent.com/ogenio/SSHPLUS/master/Modulos/delscript) 
