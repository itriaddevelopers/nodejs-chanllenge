# Nodejs Challenge

Este desafio tem como objetivo testar os seus conhecimentos de desenvolvedor fullstack e avaliar a sua forma de codificação e habilidades com as tecnologias propostas.

![Parking lot](https://driving-tests.org/wp-content/uploads/2012/02/back-parking.jpg)

Jack e seu pai compraram um terreno e vão inaugurar um estacionamento.

Para ajudar, o irmão de Jacks está desenvolvendo uma aplicação para controle de estacionamento.

Quando o veículo entra no estacionamento, o atendente observa a sua placa e a mesma é registrada, juntamente com o modelo do veículo e a sua cor. A hora de entrada é gerada automaticamente, correspondendo ao momento de registro.

Ao retornar ao estacionamento, o cliente informa a placa do veiculo ao atendente para registro da saída. O tempo de permanência é calculado. Considerando esse tempo de permanência é aplicada a tabela de preços.


## Tabela de preços
Dias | Período | Valor/h
:--------- | :------: | :------:
Segunda - Sexta | 08:00 às 12:00 | R$ 2,00
Segunda - Sexta | 12:01 às 18:00 |  R$ 3,00
Sábado e domingo | 08:00 às 18:00 | R$ 2,50

Os donos precisam de relatórios de faturamento por período. Não aceitar entrada de veiculos fora do horario da tabela de preços.

## O que deve ser entregue:
* No Backend deve ter um endpoint para entrada de veículos, onde ele receba a placa e registre o horário de entrada.
* No Backend deve ter um endpoint para saída de veículos, onde ele receba a placa e devolva o valor a pagar. 
* No Frontend você deve desenvolver uma tela onde o atendente possa dar entrada e saída dos veiculos.
* No Frontend você deve desenvolver uma tela que gere o relatório de faturamento em um determinado período.

## Tecnologias Backend (Obrigatório):
* NodeJS;
* Express ou outros;
* Banco relacional ou não relacional é de livre escolha;

## Tecnologias Frontend (Obrigatório):
* React;
* Angular;
* Vue;
* Svelte;

## Diferenciais:
* Práticas TTD, ATDD ou semelhantes são extremamente bem vindas;
* Docker;
* TypeScript;
* Kubernetes;
* Organização e clareza nas ideias;
* Menos é mais, seja prático e não perca tempo com aspectos desnecessários;

## Instruções: 
* Desejavel que disponibilize o aplicativo na plataforma [Heroku](https://www.heroku.com)
* Obrigatório disponibilizar o link do github para: marco.neves@itriad.org.br
* Obrigatório readme.md conter as instruções para buildar e servir o aplicativo.

Use o contato do Marco (marco.neves@itriad.org.br) para sanar qualquer dúvida.
