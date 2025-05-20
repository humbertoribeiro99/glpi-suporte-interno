# 📡 GLPI - Central de Suporte Técnico com Docker

Este projeto simula uma central de suporte técnico utilizando o sistema GLPI rodando via Docker.

## 🧰 Tecnologias utilizadas
- GLPI
- MySQL 5.7
- Docker & Docker Compose
- Linux Ubuntu (para testes)

## 🎯 Funcionalidades simuladas
- Abertura e gerenciamento de chamados
- Cadastro de ativos (computadores, impressoras, etc.)
- Criação de perfis e usuários técnicos
- Geração de relatórios e histórico de atendimento

## 🚀 Como rodar localmente
```bash
git clone https://github.com/seuusuario/glpi-suporte-interno
cd glpi-suporte-interno
docker-compose up -d
