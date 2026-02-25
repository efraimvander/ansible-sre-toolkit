# Ansible SRE Toolkit

## 📌 Visão Geral
Este repositório reúne um conjunto de automações de infraestrutura desenvolvidas com Ansible, com foco em práticas de Site Reliability Engineering (SRE).

O objectivo é simular cenários reais de produção, incluindo provisionamento de servidores, hardening de segurança, deploy de serviços e monitoramwnto básico.

## 🎯 Objectivos
- Automatizar tarefas repetitivas de administração de sistemas
- Aplicar boas práticas de organização e reutilização com Ansible (roles, inventories, playbooks)
- Garantir consistência e idempotência na configuração de sistemas
- Simular ambientes reais (dev, staging, produção)

## ⚙️ Funcionalidades
- Setup base de servidores (utilizadores, pacotes)
- Configuração de serviços (ex: Nginx)
- Hardening de segurança
- Deploy de aplicações simples
- Monitoramento de recursos

## 🧱 Estrutura do Projecto
- `inventories/` – definição de ambientes e variáveis
- `roles/` – componentes reutilizáveis
- `playbooks/` – orquestração das automações

## 🚀 Execução
```bash
ansible-playbook playbooks/site.yml