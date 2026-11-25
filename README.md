<div align="right">
  <a href="#contact">Contato</a>
</div>

## Rodrigo Rosadini

*Analista de Infraestrutura de TI Júnior · SysAdmin Linux & Windows · Cloud & Redes* · Brasília, Brasil

Atuo na sustentação de ambientes de infraestrutura, servidores Linux e Windows Server, redes corporativas e bancos de dados relacionais. Meu foco é manter serviços críticos estáveis, seguros e observáveis — aplicando automação com **Terraform** e **Docker**, monitoramento ativo com **Zabbix** e segmentação de rede com **pfSense** para reduzir falhas operacionais e acelerar o diagnóstico de incidentes.

[Projects](#selected-projects) · [Tools](#tools-i-use) · [Certifications](#certifications) · [Background](#background) · [Now](#now) · [Contact](#contact)

---

## Selected projects

### 01 / Infraestrutura como Código (IaC) na AWS
Provisionamento automatizado de recursos de nuvem para eliminar configurações manuais e garantir ambientes reproduzíveis e versionados.
- *Objetivo:* Estruturar a criação e destruição controlada de instâncias, redes e políticas de acesso via código declarativo.
- *Controls:* Versionamento de estado e templates no Git, padronização de variáveis e isolamento de recursos por ambiente.
- *Stack:* Terraform, AWS (EC2, S3, VPC), Git.
- *Status:* Repositório ativo de laboratório e automação.

[View code](https://github.com/rodrigolrosadini/infra-as-code)

---

### 02 / Laboratório de Monitoramento e Observabilidade com Zabbix
Ambiente virtualizado de monitoramento ativo para coleta de métricas de hardware, disponibilidade de serviços e disparo de alertas preventivos.
- *Objetivo:* Antecipar gargalos de processamento, memória, disco e indisponibilidade de rede antes que afetem a operação.
- *Controls:* Monitoramento via agentes e SNMP, configuração de triggers por severidade, acesso administrativo restrito via SSH e rotação automatizada de logs (`logrotate`).
- *Stack:* Zabbix Server, Linux (Ubuntu/Debian), Docker, SNMP, Bash.
- *Status:* Concluído e documentado em homelab.

[View code](https://github.com/rodrigolrosadini/laboratorio-zabbix-monitoramento-infraestrutura)

---

### 03 / Segmentação de Rede e Firewall de Borda com pfSense
Topologia de rede segmentada para controle de tráfego, isolamento de sub-redes e proteção de serviços internos.
- *Objetivo:* Estruturar regras de firewall, roteamento e serviços essenciais de rede local para ambientes corporativos.
- *Controls:* Listas de controle de acesso (ACLs), políticas de bloqueio por padrão, resolução interna de DNS, gerenciamento de DHCP e reservas de IP estático.
- *Stack:* pfSense, TCP/IP, DNS, DHCP, Firewall/ACLs.
- *Status:* Concluído em ambiente virtualizado.

[View code](https://github.com/rodrigolrosadini/laboratorio-pfsense-segmentacao-rede)

---

### 04 / Pipeline e Arquitetura DevOps na AWS
Fluxo de integração e entrega de aplicações em nuvem utilizando contêineres e automação de deploy.
- *Objetivo:* Padronizar o empacotamento e a publicação de aplicações web em instâncias Linux na AWS.
- *Controls:* Esteira automatizada de build e validação, isolamento de dependências em contêineres e gerenciamento de acesso por chaves.
- *Stack:* AWS (EC2, S3), Docker, GitHub Actions, Linux.
- *Status:* Projeto prático de integração contínua.

[View code](https://github.com/rodrigolrosadini/projeto-devops-aws)

---

## Tools I use

### Sistemas & Virtualização
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white) ![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white) ![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat-square&logo=virtualbox&logoColor=white)

*Linux (Ubuntu, Debian) · Windows Server (Active Directory, DNS, DHCP) · Windows 10/11 · Virtualização (VirtualBox/LVM)*

Administração de usuários e permissões, gerenciamento de serviços (`systemd`), particionamento lógico (LVM), diagnóstico de falhas e suporte técnico N1/N2.

### Cloud, Automação & Containers
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

*AWS (EC2, S3) · Docker & Docker Compose · Terraform · Git · GitHub Actions · Bash · Python*

Arquiteturas em contêineres, automação de rotinas operacionais em shell/Python e provisionamento de infraestrutura.

### Redes, Monitoramento & Bancos de Dados
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white) ![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

*pfSense · Zabbix · TCP/IP (ping, traceroute, DNS, DHCP, SSH) · MySQL · SQL Server · Jira · SoapUI / Postman / Bruno*

Análise de logs em produção, rotinas automatizadas de backup/restore, checagem de integridade de dados via SQL e homologação de APIs/XML.

---

## Certifications

- **Cisco Networking Basics** — Cisco (2023)
- **Scrum Foundation Professional Certificate (SFPC)** — CertiProf (2024)
- **ISO/IEC 27001:2022 INFORMATION SKILLFRONT SECURITY ASSOCIATE™** — SkillFront (2024)

---

## Background

Tenho **2+ anos de experiência** em infraestrutura, suporte técnico e sustentação de sistemas. Atuei como **Analista de Implantação de Sistemas I** na **Serasa Experian / SalaryFits** (monitoramento de servidores Linux em produção, análise de logs, sustentação de dados em MySQL e homologação de APIs/XML com o Portal Emprega Brasil) e como **Analista de Suporte Jr** na **Plan Automação** (atendimento a 200+ clientes corporativos, administração de backups em SQL Server e troubleshooting de redes).

Sou **Pós-graduado em Linguagens de Programação** (Faculdade Gran, 2026) e **Tecnólogo em Análise e Desenvolvimento de Sistemas** (IESB, 2024), com **Inglês Avançado (C1)**.

---

## Now

```text
rodrigo@infra:~/now
├── focus   → Sustentação de Infraestrutura Linux/Windows, Redes e Cloud (AWS)
├── lab     → Orquestração de monitoramento (Zabbix + Grafana + pfSense) via Docker Compose
└── study   → Infraestrutura como Código (Terraform) e arquitetura em nuvem AWS
```

---

## Contact

Aberto a oportunidades como **Analista de Infraestrutura Júnior**, **SysAdmin Júnior** ou **Suporte a Infraestrutura**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigorosadini) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rodrigolrosadini) [![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rodrigorosadini2@gmail.com)

rodrigorosadini2@gmail.com · [linkedin.com/in/rodrigorosadini](https://www.linkedin.com/in/rodrigorosadini)

---

> *Estabilidade em produção vem de observabilidade, automação e documentação clara.*
