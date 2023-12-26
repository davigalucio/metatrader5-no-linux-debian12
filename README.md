# Instalação do MetaTrader 5 no linux Debian 12

apt install -y git

git clone https://github.com/davigalucio/metatrader5-no-linux-debian12.git

sh metatrader5-no-linux-debian12/INSTALL.SH

# Você pode integrar com o Guacamole Server e acessar o Metatrader via web

apt install -y git

git clone https://github.com/davigalucio/guacamole-server.git

sh guacamole-server/INSTALL.SH

1. Após instalar o Guacamole Server, configure o host onde foi instalado o Metatrader 5 para acesso via RDP.
