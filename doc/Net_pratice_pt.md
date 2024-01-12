# Sobre o projeto

#### Este projeto é relacionado à administração do sistema e neste artigo documentarei praticamente tudo o que você precisa saber sobre o projeto do início ao fim.

## Os tópicos que discutiremos neste artigo são:

- O que é um IP?

- O que é um IP?

- Quais são os tipos de endereço IP

- Qual é a finalidade dos endereços IP?

- Qual é a diferença entre IPv4 e IPv6?

- O que é TCP/IP?

- Qual é a diferença entre TCP e IP?

- Como funciona exatamente o TCP/IP?

- O que é um interruptor?

- O que é um router?

- Como funciona um router?

- Qual é a diferença entre um Modem e um router?

- O que é um endereço de loopback?

- O que é uma sub-rede?

- Como calcular passo a passo uma máscara de sub-rede a partir do endereço IP?

## O que é um IP?

#### Um endereço IP significa Endereço de Protocolo de Internet, que é um conjunto de regras para comunicação pela Internet, como envio de e-mails, streaming de vídeos ou conexão a um site, etc…, um endereço IP identifica uma rede ou um dispositivo na Internet . E um endereço IP tem duas partes importantes, que são:

- O ID da rede
- O ID do host

## Quais são os tipos de endereço IP?

#### Existem dois tipos importantes de endereço IP, que são:

#### 1. Endereço IP estático: que permanece permanente e não muda, e é usado principalmente para equipamentos importantes, como (empresas, servidores…)
#### 2. Endereço IP dinâmico: que muda ocasionalmente e é utilizado para equipamentos de consumo, como (laptop, smartphone, tablet…)

## Qual é a finalidade dos endereços IP?

#### * A finalidade do endereço IP é lidar com a conexão entre dispositivos que enviam e recebem dados por toda a rede.
#### * O endereço IP identifica exclusivamente cada dispositivo na internet, sem ele não há outra forma de contatá-los.
#### * Os endereços IP permitem que os dispositivos de computação se comuniquem com destinos como sites e serviços de streaming, e permitem que os sites saibam quem está se conectando.

## Qual é a diferença entre o IPv4 e o IPv6?

#### * IPv4: implantado em 1981, funciona com endereço de 32 bits e possui mais de 4,3 bilhões de endereços (o que é uma pequena quantidade de endereços comparado ao IPv6), portanto os endereços IP devem ser reutilizados e mascarados, e usa ponto-decimal numérico Notação (ex: 192.108.42.64), e você deve configurá-la manualmente.
#### * Ipv6: implantado em 1998, funciona com um endereço de 128 bits e tem mais de 340 undecilhões de endereços (que são 340 trilhões, trilhões, trilhões, trilhões [36 zeros]), então cada dispositivo pode ter seu endereço IP exclusivo, e ele usa notação hexadecimal alfanumérica (ex: 2002:0de6:0001:0042:0100:8c2e:0370:7234) e suporta configuração automática.

## O que é TCP/IP?

#### TCP/IP significa Transmission Control Protocol/Internet Protocol, que é um conjunto de regras que orientam e permitem que os computadores se comuniquem em uma rede como a Internet.

## Qual é a diferença entre TCP e IP?

#### * TCP e IP são dois protocolos de rede de computadores separados.
#### * IP é a parte que obtém o endereço para onde os dados são enviados, enquanto TCP é a parte responsável pela entrega dos dados assim que o endereço IP for encontrado.

## Como funciona exatamente o TCP/IP?

#### O trabalho do TCP/IP é dividir as diferentes tarefas de comunicação em camadas, cada camada tem uma função diferente. Os dados passam por quatro camadas individuais antes de serem recebidos na outra extremidade. O TCP/IP então passa por essas camadas ao contrário para remontar os dados e representá-los ao destinatário.

### As quatro camadas do modelo TCP/IP são:

#### * Camada Datalink: também chamada de camada física, é o que trata das partes físicas de envio e recebimento de dados usando Ethernet, ou WiFi, etc…
#### * Camada de Internet: também chamada de camada de rede, e controla a movimentação dos pacotes pela Internet.
#### * Camada de Transporte: é o que fornece uma conexão de dados confiável entre dois dispositivos, divide os dados em pacotes, conhece os pacotes que são recebidos do outro dispositivo e garante que o outro dispositivo conheça os pacotes que recebe.
#### * Camada de Aplicação: é o grupo de aplicações que requer comunicação em rede, que é com o qual o usuário normalmente interage, como e-mails e mensagens, pois a camada inferior trata dos detalhes da comunicação e não há necessidade de preocupação das aplicações. eles mesmos com isso.

## O que é um switch?

#### Um switch é um dispositivo que conecta dispositivos dentro da mesma rede, geralmente uma rede LAN (que é uma rede local), e encaminha pacotes de dados de e para esses dispositivos. Ao contrário de um router, um switch apenas envia os dados para os dispositivos que ele se destina (que pode ser outro switch, um router ou o computador de um usuário).

## O que é um router?

#### Um router é um dispositivo que conecta duas ou mais redes ou sub-redes comutadas por pacotes. Ele desempenha duas funções principais: gerenciar o tráfego entre essas redes, encaminhando pacotes de dados para os endereços IP pretendidos e permitindo que vários dispositivos usem a mesma conexão com a Internet.

## Como funciona um router?

#### O trabalho de um router é direcionar e guiar os pacotes que são enviados para que cheguem ao seu destino (que é o seu endereço IP) da maneira mais eficiente possível e, para enviar os pacotes de maneira eficaz, um router usa uma tabela de roteamento interna (que é uma lista de caminhos para vários destinos de rede), um router lê o cabeçalho de um pacote para determinar para onde ele está indo e, em seguida, consulta a tabela de roteamento para decidir qual caminho é o mais eficiente para que o pacote chegue ao seu destino.

## Qual é a diferença entre um modem e um router?

#### Um router forma redes e gerencia o fluxo de dados dentro e entre essas redes, enquanto um modem conecta essas redes à Internet. Por outro lado, um router apenas conecta os dispositivos entre si para fazer uma LAN entre todos eles, mas sem acesso à internet, por outro lado, um modem pode se conectar a apenas um dispositivo, mas fornece acesso à internet.

#### E para fazer uma LAN que se conecte à internet, você deve combinar um modem e um router, para que o router conecte todos os dispositivos enquanto um modem lhes dê acesso à internet.

## O que é um endereço de loopback?

#### Um endereço de loopback é um endereço integrado ao sistema de domínio IP para permitir que um dispositivo envie e receba seus próprios pacotes de dados. E é um intervalo de endereços IP reservado distinto que começa em 127.0.0.0 e termina em 127.255.255.255, e é usado para vários tipos de análise, geralmente para fins de teste e depuração.

## O que é uma subnet?

#### Uma subnet ou subnetwork é uma rede dentro de uma rede. As subnets tornam as redes mais eficientes.

#### Subnetting  é o processo de roubar bits da parte HOST do endereço IP para dividir a grande rede em outras menores, chamadas sub-redes. Após a Subnetting , terminamos com os campos NETWORK SUBNET HOST, e sempre reservamos um endereço IP para identificar a subnet e outro para identificar o endereço da subnet de broadcast, e através da subnetting, o tráfego de rede pode percorrer uma distância menor sem passar por rotas desnecessárias para chegar ao seu destino.

## Como calcular passo a passo uma máscara de sub-rede a partir do endereço IP?

#### Trabalharemos com o endereço IP 10.20.4.13/29
