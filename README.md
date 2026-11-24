# 🐧 Administração de Sistemas Abertos (ASA)

Repositório dedicado aos estudos, práticas laboratoriais, scripts de automação e documentações da disciplina/área de **Administração de Sistemas Abertos (ASA)**, com foco em ambientes **GNU/Linux**, serviços de rede e infraestrutura de servidores.

---

## 📋 Sobre o Projeto

Este repositório reúne materiais práticos sobre instalação, configuração, manutenção e segurança de serviços essenciais em sistemas operacionais baseados em Unix/Linux. O objetivo é servir como portfólio técnico e guia de consulta rápida para administração de infraestrutura.

## 🛠️ Tecnologias e Ferramentas

* **Sistemas Operacionais:** Debian, Ubuntu Server, Rocky Linux / AlmaLinux
* **Virtualização e Containers:** Docker, Docker Compose, VirtualBox / KVM
* **Automação & Scripting:** Bash / Shell Script
* **Controle de Versão:** Git e GitHub

---

## 📚 Conteúdos e Tópicos Abordados

Abaixo estão os principais módulos e serviços configurados neste repositório:

### 1. Fundamentos e Administração Linux
- Gerenciamento de usuários, grupos e permissões (`chmod`, `chown`, ACLs)
- Gerenciamento de pacotes (`apt`, `dnf`) e processos (`systemd`, `journalctl`)
- Particionamento de discos, sistemas de arquivos e LVM
- Agendamento de tarefas (`cron` e `systemd timers`)

### 2. Redes e Conectividade
- Configuração de interfaces de rede (Netplan, NetworkManager)
- Resolução de nomes com **DNS (BIND9)**
- Atribuição dinâmica de endereços com **DHCP (ISC DHCP / Kea)**
- Roteamento básico, NAT e diagnóstico de rede (`ip`, `ss`, `dig`, `tcpdump`)

### 3. Serviços de Infraestrutura e Aplicação
- **Acesso Remoto:** Servidor SSH (chaves públicas, hardening e tunneling)
- **Servidores Web:** Apache HTTP Server e Nginx (Virtual Hosts, Reverse Proxy)
- **Compartilhamento de Arquivos:** Samba (SMB/CIFS) e NFS
- **E-mail e Mensageria:** Postfix e Dovecot *(opcional/em estudo)*

### 4. Segurança e Monitoramento
- Firewall e filtragem de pacotes (`iptables`, `nftables`, `ufw`)
- Certificados SSL/TLS (OpenSSL / Let's Encrypt)
- Análise de logs e monitoramento de recursos (`htop`, `vmstat`, `iostat`)

---

## 📂 Estrutura do Repositório

```text
├── 📁 01-fundamentos-linux/      # Comandos, permissões e gerenciamento do sistema
├── 📁 02-shell-script/           # Scripts de automação e backup
├── 📁 03-redes-dns-dhcp/         # Arquivos de zona BIND9 e configurações DHCP
├── 📁 04-servidores-web/         # Configurações Apache, Nginx e Proxy Reverso
├── 📁 05-compartilhamento/       # Configurações Samba e NFS
├── 📁 06-docker-containers/      # Dockerfiles e docker-compose.yml dos serviços
└── 📄 README.md
