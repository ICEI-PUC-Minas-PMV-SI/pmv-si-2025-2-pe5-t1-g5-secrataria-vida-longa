# Ata da Terceira Etapa do Projeto

## Introdução e Contexto Geral
Esta ata refere-se à **terceira etapa** do desenvolvimento do projeto *Infraestrutura de Rede para a Secretaria de Saúde Vida Longa e suas filiais*. O objetivo principal desta fase foi a implementação de dois servidores — um na AWS e outro na VirtualBox — destinados à hospedagem de servidores Zabbix, responsáveis pelo monitoramento dos serviços configurados na etapa anterior.

- **Zabbix na AWS**: Gerenciamento dos serviços de DHCP, Impressão e FTP  
- **Zabbix na VirtualBox**: Gerenciamento do serviço de Active Directory (AD)

## Objetivo da Ata
O propósito desta ata é **registrar e controlar a participação de cada integrante do grupo**, assegurando que as contribuições individuais sejam devidamente documentadas e avaliadas. O acompanhamento inclui presenças, intervenções no desenvolvimento, sugestões apresentadas e tarefas executadas, com o intuito de promover uma distribuição equilibrada de responsabilidades e identificar possíveis lacunas ou sobrecargas.  

Essa abordagem contribui para o gerenciamento eficiente do tempo e dos recursos humanos, além de fortalecer o espírito de equipe, incentivando a motivação e o engajamento contínuo de todos os membros.

- **Foco no Controle de Participação**: Avaliar o nível de envolvimento de cada integrante, considerando frequência de intervenções, qualidade das contribuições e cumprimento de prazos.  
- **Benefícios Esperados**: Evitar desequilíbrios no trabalho em grupo, estimular feedback construtivo e fornecer subsídios para relatórios finais ou avaliações acadêmicas.  

## Participantes e Controle de Presença
Os membros do grupo dividiram-se para executar as tarefas específicas desta etapa, demonstrando comprometimento coletivo com o projeto. A seguir, o registro detalhado das responsabilidades atribuídas:

- **Anna Carolina Saldanha de Lima**: Configuração do Zabbix Agent no serviço de DHCP, permitindo a comunicação com o servidor Zabbix e o monitoramento adequado.  
- **Cristiano Henrique Amorim**: Orientação e apoio aos demais integrantes na configuração dos agentes, garantindo o monitoramento dos serviços.
- **João Alberto Raymundo Borges**: Configuração do Zabbix Agent no serviço de FTP, possibilitando a comunicação com o servidor Zabbix e o monitoramento correspondente.  
- **Lucas Soares dos Reis**: Criação e Configuração de GPO no servidor vidalonga.local 
- **Natália Kiefer Ferreira**: Configuração e hospedagem do servidor Zabbix na AWS; configuração do Zabbix Agent no serviço de Impressão; orientação e apoio aos demais integrantes na configuração dos agentes, garantindo o monitoramento dos serviços.  
- **Rafael Vinícius da Silva**: Configuração e hospedagem do servidor Zabbix na VirtualBox; configuração do Zabbix Agent no serviço de DNS; configuração do Active Directory hospedado na VirtualBox e monitorado pelo servidor Zabbix.  

## Cronograma de Atividades
A tabela abaixo apresenta, de forma organizada, os dias dedicados por cada integrante e as atividades realizadas, facilitando o acompanhamento do progresso e a identificação dos marcos alcançados nesta etapa.

| Integrante                  | Dias Dedicados | Atividades Principais          | Descrição da Atividade                                                                 |
|:----------------------------:|:---------------:|:-------------------------------:|:----------------------------------------------------------------------------------------:|
| Anna Carolina Saldanha de Lima | 4     | Configuração do Zabbix Agent no servidor DHCP | Configuração do agente para comunicação com o servidor Zabbix e monitoramento do serviço DHCP |
| Cristiano Henrique Amorim   |      |  |    |
| João Alberto Raymundo Borges| 5     | Configuração do Zabbix Agent no serviço de FTP | Configuração do agente para comunicação com o servidor Zabbix e monitoramento do serviço FTP |
| Lucas Soares dos Reis       | 4     | Criação e Configuração de GPO no servidor vidalonga.local | Mapeamento das unidades de redes com a GPO |
| Natália Kiefer Ferreira     | 7     | Configuração e hospedagem do servidor Zabbix na AWS; configuração do Zabbix Agent no serviço de Impressão; orientação aos integrantes | Configuração completa do servidor Zabbix na AWS, integração do agente de Impressão e apoio aos demais participantes |
| Rafael Vinícius da Silva    | 7     | Configuração e hospedagem do servidor Zabbix na VirtualBox; configuração do Zabbix Agent no serviço de DNS; configuração do AD | Implementação do servidor Zabbix na VirtualBox, integração do agente de DNS e configuração do Active Directory |
