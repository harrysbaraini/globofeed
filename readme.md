# GloboFeed

Esta aplicação é um pequeno teste em Laravel, com a finalidade de ler ([este feed de notícias do G1](http://g1.globo.com/dynamo/economia/rss2.xml)).

### Instalação

Este projeto pode ser executado como qualquer outro projeto Laravel, utilizando o servidor que desejar.

Porém, o indicado é utilizar o Homestead, usufruindo de uma máquina virtual própria, por questões de separação de ambientes de desenvolvimento.
Com Virtual Box e Vagrant instalados, execute os seguintes comandos:

- Faça um clone deste repositório (git clone https://github.com/harrysbaraini/globofeed.git)
- Na sua linha de comando, execute o comando ```composer install```.
- Ainda na linha de comando, execute ```vagrant up```. Este processo pode levar um tempo.
- Acesse no navegador o IP **192.168.50.99**. Caso ocorra algum conflito de IP, mude-o no arquivo **Homestead.yaml** e então ```vagrant provision```.

Qualquer dificuldade, abra um *issue*.
