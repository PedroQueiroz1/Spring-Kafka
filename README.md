# <h1 align="center"> Estudo de Spring + Kafka </h1>
![GitHub repo size](https://img.shields.io/github/repo-size/PedroQueiroz1/Spring-Kafka?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/PedroQueiroz1/Spring-Kafka?style=plastic)

<p align="center">
   <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge" #vitrinedev/>
</p>

### Tópicos 

- [Descrição do projeto](#descrição-do-projeto)
- [Ferramentas utilizadas](#ferramentas-utilizadas)
- [Como utilizar](#como-utilizar)
- [Acesso ao projeto](#acesso-ao-projeto)

## Descrição do projeto 

<p align="justify">
   Dois projetos em 1!<br>
   O primeiro projeto foi criado para ter mais conhecimento de como o Kafka funciona e sobre sua implementação.
   O segundo tem como objetivo de ser uma simulação de como operar um sistema realista(grande quantidade de mensagens) com kafka, utilizando o wikimedia.
</p>
 
## Ferramentas utilizadas
[![My Skills](https://skillicons.dev/icons?i=java,spring,kafka,maven)](https://skillicons.dev)

## Como utilizar
Segui exatamente como a [documentação](https://kafka.apache.org/quickstart) do Kafka indica. <br>
⚠️Precisa do Java 8+.⚠️ <br>
#### Primeiro passo: <br>
Precisamos baixar [aqui](https://dlcdn.apache.org/kafka/3.5.0/kafka_2.13-3.5.0.tgz) o kafka. <br>
Após terminar o download, extraia o arquivo em qualquer pasta.

#### Segundo passo:
<br> <br>
<strong><p align="center"><img width="30" src="https://emojis.slackmojis.com/emojis/images/1643514315/2870/windows.png?1643514315" alt="windows" /> Caso utilize Windows siga os passos abaixo.</p></strong>

Abra o CMD do Windows. No cmd, acesse o caminho da pasta em que o arquivo foi baixado e extraído anteriormente. <br>Exemplo: 'cd C:\Users\pedro\Downloads\kafka' <br>

<strong>Iniciar o serviço do Zookeeper: </strong><br>
bin\windows\zookeeper-server-start.bat config\zookeeper.properties<br>

Agora abra outro CMD e acesse novamente o caminho da pasta em que o arquivo foi baixado e extraído anteriormente.<br>

<strong>Iniciar o Kafka Broker Service:</strong><br>
bin\windows\kafka-server-start.bat config\server.properties<br>

Caso queira monitorar o consumo de mensagens do kafka topic execute o comando abaixo ainda na mesma pasta anterior. <br>
bin\windows\kafka-console-consumer.bat --topic nome-do-topic-aqui --from-beginning --bootstrap-server localhost:9092 <br>

<br><br>
<strong><p align="center"><img width="30" src="https://emojis.slackmojis.com/emojis/images/1643514543/5413/linux.png?1643514543" alt="linux" /> Caso utilize Linux siga os passos abaixo. </p></strong>

Abra o terminal do Linux. No terminal, acesse o caminho da pasta em que o arquivo foi baixado e extraído anteriormente. <br>Exemplo: 'cd C:/Users/pedro/Downloads/kafka'<br>

<strong>Iniciar o serviço do Zookeeper: </strong><br>
bin/zookeeper-server-start.sh config/zookeeper.properties<br>

Agora abra outro terminal e acesse novamente o caminho da pasta em que o arquivo foi baixado e extraído anteriormente.<br>

<strong>Iniciar o Kafka Broker Service:</strong><br>
bin/kafka-server-start.bat config/server.properties<br>

<br><br>
## Acesso ao projeto

Você pode [acessar o código fonte do projeto](https://github.com/PedroQueiroz1/Spring-Kafka).
