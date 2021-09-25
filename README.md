# senai-3sem

<h1>
    <h1 align="center">
    <img src="https://computerworld.com.br/wp-content/uploads/2020/10/Gastos-com-infraestrutura-de-data-center-devem-crescer-em-2021.jpg" height="300" width="800">
</h1>

Este repositório contém scripts e documentações (organizados em pastas) referentes aos conceitos abordados no 3° semestre do Curso Técnico de Redes de Computadores - SENAI de informática.

**Alguns desses conceitos são:**

* Cacti;
* Zabbix;
* Grafana;
* Introdução aos conceitos de Segurança da Informação;
* IPTables;
* ASA;
* PFSense;
* Introduction Cybersecurity.

## Projetos de rede já desenvolvidos

<h1>
    <h1 align="center">
    <img src="https://github.com/Lcmc23/senai-3sem/blob/main/Sprint%20B/Aula%2016/CENARIO%20DE%20MONITORAMENTO.png" height="400" width="800">
</h1>
    
## Troubleshooting já realizados
    
“O troubleshooting pode ser compreendido como uma espécie de diagrama de ações, um conjunto de medidas que orienta a resolução de problemas dentro do ambiente de TI. Em tradução, troubleshooting significa solução de problemas e é exatamente sobre isso que este conceito trata.”
    
<h1>
    <h1 align="center">
    <img src="https://i.ibb.co/6bwGtMk/AULA-8-CENARIO-TROUBLESHOOTING-WINDOWS-A.png" height="400" width="800">
</h1>  
    
<h1>
    <h1 align="center">
    <a href="https://ibb.co/ds9sGNX"><img src="https://i.ibb.co/8n3n6yG/Troubleshooting.png" alt="Troubleshooting" border="0"></a>
</h1>  

## Monitoramento e Gerenciamento - protocolo SNMP
    
“SNMP é o protocolo padrão para monitoramento e gerenciamento de redes. A sigla SNMP é um acrônimo para 'Simple Network Management Protocol' (Protocolo Simples de gerenciamento de redes).”
    
**Cacti**
    
<h1>
    <h1 align="center">
    <img src="https://i.ibb.co/hKsK29q/Cacti.png">
</h1>
    
**Zabbix**
    
<h1>
    <h1 align="center">
    <img src="https://i.ibb.co/v1qZNtH/Zabbix.png">
</h1>
    
**Grafana**
    
<h1>
    <h1 align="center">
    <img src="https://i.ibb.co/9tmpZZL/Grafana.png">
</h1> 
    
## Segurança Cibernética - IPtables
    
* Funciona através da comparação de regras para saber se um pacote tem ou não permissão para passar;

* Em firewalls mais restritivos, o pacote é bloqueado e registrado para que o administrador do sistema tenha conhecimento sobre o que está acontecendo em seu ambiente;
    
* Por intermédio de regras, fazemos com que pacotes possam ou não serem recebidos por toda uma rede, somente uma máquina, uma interface ou até mesmo uma porta de comunicação;

* As regras do iptables são compostas de uma Tabela, Opção, Chain, Dados e Ação. Através destes elementos, podemos especificar o que fazer com os pacotes, seguindo a estrutura:

```
iptables [-t tabela] [opção] [chain] [dados] -j [ação]
```
    
<h1>
    <h1 align="center">
    <img src="https://miro.medium.com/max/1000/1*OIoNQkH4RTSm-eY2lUMBcQ.jpeg">
</h1> 
    
## Cisco - ASA

<h1>
    <h1 align="center">
    <img src="https://xtech.com.br/config/imagens_conteudo/blogs/firewall-cisco-asa-configuracao-basica-comandos-basicos%20(1).png" height="400" width="800">
</h1> 
    
Nas redes de computadores, os dispositivos de segurança adaptativos Cisco ASA série 5500, ou simplesmente Cisco ASA, são a linha de dispositivos de segurança de rede da Cisco, lançada em maio de 2005, que sucedeu a três linhas existentes de produtos populares da Cisco.

* Os firewalls Cisco ASA oferecem a visibilidade de rede necessária, proteção superior contra ameaças e malware avançado e maior automação para reduzir custos e complexidade;

* Para habilitar a funcionalidade básica, existem oito comandos básicos (esses comandos são baseados no software versão 8.3 (1) ou superior).

```
interface;
nameif;
security-level;
ip address;
switchport access;
object network;
nat;
route.
```
    
## pfSense
    
<h1>
    <h1 align="center">
    <img src="https://conexti.com.br/wp-content/uploads/2021/01/pfsense_logo.png">
</h1>
    
<h1>
    <h1 align="center">
    <img src="https://fabiosilvabuzina.files.wordpress.com/2016/04/46185-8.png">
</h1>
    
O pfSense é open source, licenciado sob BSD license, baseado no sistema operacional FreeBSD e adaptado para assumir o papel de um firewall e/ou roteador de redes. O nome deriva do fato que o software utiliza a tecnologia packet-filtering.
    
Na linguagem dos especialistas em Segurança da Informação, a disponibilização dos pacotes para as mais diversas funções credencia o pfSense como um UTM (Unified Threat Management, ou Central Unificada de Gerenciamento de Ameaças, em português), que, em breves palavras, pode ser entendido por um dispositivo com diversas funções, tais como:

* firewall;
* servidor (internet, DHCP, NTP, Proxy…);
* antivírus;
* antispyware;
* antispam;
* filtragem de conteúdo;
* detecção de intrusão, entre outros.
    
## Docker
    
<h1>
    <h1 align="center">
    <img src="https://programadev.com.br/static/5ef27418358e0041cd02966fc3e74e55/docker.png" height="400" width="800">
</h1>
    
**O que é arquitetura de microsserviços?**
    
Os microsserviços são uma arquitetura e uma abordagem para escrever programas de software. Com eles, as aplicações são desmembradas em componentes mínimos e independentes. Diferentemente da abordagem tradicional monolítica em que toda a aplicação é criada como um único bloco, os microsserviços são componentes separados que trabalham juntos para realizar as mesmas tarefas. Cada um dos componentes ou processos é um microsserviço. Essa abordagem de desenvolvimento de software valoriza a granularidade, a leveza e a capacidade de compartilhar processos semelhantes entre várias aplicações. Trata-se de um componente indispensável para a otimização do desenvolvimento de aplicações para um modelo nativo em nuvem.
    
**O que é Docker?**
    
Docker se refere a muitas coisas. Isso inclui: um projeto da comunidade open source; as ferramentas resultantes desse projeto; a empresa Docker Inc., principal apoiadora do projeto; e as ferramentas compatíveis formalmente com a empresa. O fato de que as tecnologias e a empresa têm o mesmo nome pode causar uma certa confusão.

Veja uma simples explicação:

* O software de TI "Docker" é uma tecnologia de containerização para criação e uso de containers Linux®.
* A comunidade open source do Docker trabalha gratuitamente para melhorar essas tecnologias para todos os usuários.
* A empresa Docker Inc. se baseia no trabalho realizado pela comunidade do Docker, tornando-o mais seguro, e compartilha os avanços com a comunidade em geral. Depois, ela oferece aos clientes corporativos o suporte necessário para as tecnologias que foram aprimoradas e fortalecidas.
    
**Como o Docker funciona?**
    
A tecnologia Docker usa o kernel do Linux e recursos do kernel como Cgroups e namespaces para segregar processos. Assim, eles podem ser executados de maneira independente. O objetivo dos containers é criar essa independência: a habilidade de executar diversos processos e aplicações separadamente para utilizar melhor a infraestrutura e, ao mesmo tempo, manter a segurança que você teria em sistemas separados.
    
<h1>
    <h1 align="center">
    <img src="https://www.redhat.com/cms/managed-files/traditional-linux-containers-vs-docker_0.png">
</h1>
    
**Links**
    
* https://docs.docker.com/
* https://docker.com/
* https://docs.docker.com/engine/install/debian/
* https://hub.ocker.com/
    
**Curiosidades**
    
* Docker Engine: principal tecnologia, intermédio entre o S.O e os containers
* Docker Compose: orquestração de múltiplos containers
* Docker Swarm: Clusters de Docker Engine
* Docker Hub: Repositório de Imagens Docker
* Docker Machine: Permite gerenciar o Docker em um host virtual
    
## Cursos realizados neste semestre

Site | Curso
---- | -----
[SENAI - EAD](https://ead.sp.senai.br/) | Competências Socioemocionais (Soft Skills)
[SENAI - EAD](https://ead.sp.senai.br/) | Desvendando a Indústria 4.0
[SENAI - EAD](https://ead.sp.senai.br/) | Desvendando a Blockchain
   
**VMs já utilizadas**
    
* https://drive.google.com/drive/folders/1WeSn9JFeWt2TIryZKvPJqJSg73haicE8

**Plataforma utilizada para o desenvolvimento dos scripts e documentações:**

* VisualStudio - https://visualstudio.microsoft.com/pt-br/
