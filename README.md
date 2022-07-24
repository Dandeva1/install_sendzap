FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/Dandeva1/install_sendzap.git && sudo chmod -R 777 install_sendzap && cd install_sendzap && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf install_sendzap && git clone https://github.com/Dandeva1/install_sendzap.git && sudo chmod -R 777 ./install_sendzap && cd ./install_sendzap && sudo ./install_instancia
```

