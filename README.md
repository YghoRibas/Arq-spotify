## O caso Spotify (Introdução)
O maior sistema de streaming de música da atualidade
## Arquitetura Utilizada
Por conta do volume de usuários simultâneos e que utilizam o aplicativo diariamente, a estratégia abordada foi utilizar serviços de nuvem. 
#### Microsserviços
Eles utilizam alguns microsserviços e nuvem para conseguirem uma alta confiabilidade e disponibilidade.
A escolha por microsserivços se dá pelo tamanho da equipe de desenvolvimento, dessa forma são criados vários módulos em quais equipes distintas podem focar única e exclusivamente na entrega do componente em foco, tornando seu desenvolvimento muito mais ágil.
#### Apache Cassandra
Banco de dados NoSQL altamente escalável. Ele foi desenvolvido para lidar com grandes volumes de dados distribuídos em vários servidores, proporcionando alta disponibilidade e tolerância a falhas. Por conta dessas especificidades foi aderido pela equipe do Spotify.
## Referências
[Visão de agile do spotify](https://www.product-frameworks.com/Spotify-MVP.html)
