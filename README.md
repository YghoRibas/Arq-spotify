## O caso Spotify (Introdução)
O maior sistema de streaming de música da atualidade. Aqui discutiremos algumas escolhas e definições feitas pela equipe do Spotify para alcançar o sucesso desse aplicativo tão bem aceito pelo mercado. 
## Arquitetura Utilizada
Por conta do volume de usuários simultâneos e que utilizam o aplicativo diariamente, a estratégia abordada foi utilizar serviços de nuvem. 
#### Microsserviços
Eles utilizam alguns microsserviços e nuvem para conseguirem uma alta confiabilidade e disponibilidade.
A escolha por microsserivços se dá pelo tamanho da equipe de desenvolvimento, dessa forma são criados vários módulos em quais equipes distintas podem focar única e exclusivamente na entrega do componente em foco, tornando seu desenvolvimento muito mais ágil.
#### Elasticidade
Para lidar com a alta demanda de streaming de música, o Spotify emprega estratégias de balanceamento de carga e escalabilidade automática para garantir que seus sistemas possam se adaptar às necessidades dos usuários.
#### Apache Cassandra
Banco de dados NoSQL altamente escalável. Ele foi desenvolvido para lidar com grandes volumes de dados distribuídos em vários servidores, proporcionando alta disponibilidade e tolerância a falhas. Por conta dessas especificidades foi aderido pela equipe do Spotify.
#### Container
Para gerenciar seus contêineres, o Spotify utiliza Docker e Kubernetes(antes a orquestração era feita por um serviço chamado Helios) desde 2014 . Essas tecnologias facilitam o dimensionamento e a orquestração dos microserviços, garantindo que a plataforma seja altamente disponível e resiliente.
#### Kafka
O Kafka é usado como sistema de mensageria com eventos em tempo real na plataforma do Spotify. Ele é usado para transmitir dados entre os microserviços e manter a consistência dos dados em todo o sistema.
## Referências
[Visão de agilidade do spotify](https://www.product-frameworks.com/Spotify-MVP.html)
[Utilização de microsserviços](https://www.infoq.com/br/news/2016/03/microservices-spotify/)
[Apache Cassandra](https://intuji.com/what-is-apache-cassandra-why-spotify-uses-it/)
[Docker e Kubernetes](https://kubernetes.io/case-studies/spotify/)
[Helios](https://github.com/spotify/helios)
[Docker hub Kafka](https://hub.docker.com/r/spotify/kafka)
