ambiente-docker
===============

Ambiente de Desenvolvimento DOCKER PHP

- $: `docker-compose build`
- $: `docker-compose up -d`
- $: `netsh interface ipv4 add address "Ethernet do Docker" 10.254.254.254 255.255.255.0 #Windows Admin`
- $: `sudo ifconfig en0 alias 10.254.254.254 255.255.255.0 #Linux e MAC`


No PhpStorm:
- `Settings > Languages & Framework > PHP > Debug > DBGp Proxy`
- `IDE key: PHPSTORM`
- `Host: 10.254.254.254`
- `Port: 9000`

- `Vai até RunDebug Configurations`
- `Adicione o PHP Web Application`
- `Adicione um novo server`
- `Adicione localhost ao server`
- `Use path mappings`
- `Faça o mapeamento do projeto com o servidor, ex: a Pasta D:/web/www/wordpress está em /var/www/wordpress no servidor `
- `Adicione o contexto da aplicação e Pronto`
