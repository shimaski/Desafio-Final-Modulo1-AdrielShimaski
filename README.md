# 📡 Projeto de Rede Corporativa – Werneck S/A

Proposta técnica oficial para a estruturação de uma rede moderna, segura e escalável conectando a matriz (São Paulo) às filiais (Rio de Janeiro e Minas Gerais).

---

## 📋 Sumário Executivo

A rede proposta oferece:

- Segmentação por departamentos usando **VLANs**
- Conexões **VPN site-to-site** entre matriz e filiais
- **Firewall corporativo** com regras e logs de segurança
- Rede separada para **visitantes e dispositivos IoT**
- Integração segura com **serviços em nuvem** (Office 365, CRM)
- Planejamento com foco em **expansão e desempenho**

---

## 📁 Documentação

- [📄 Proposta Técnica Completa](docs/proposta-tecnica-completa.md)  
- [🧰 Lista de Equipamentos](docs/equipamentos/lista-equipamentos.md)  
- [🛠️ Plano de Implementação](docs/implementacao/plano-acao.md)  
- [📊 Diagramas e Arquitetura de Rede](docs/diagramas)

---

## 🏗️ Estrutura do Projeto

A rede corporativa será baseada em:

- **Switch Core** centralizando VLANs e servidores na matriz
- **Firewall com NAT e logging**
- **VPN site-to-site** conectando filiais RJ (10.1.0.0/24) e MG (10.1.10.0/24)
- **Servidores locais** (ERP, arquivos, impressão) na matriz
- **Rede de visitantes** completamente isolada
- **Acesso remoto seguro** via conexões criptografadas

---

## ✅ Destaques Técnicos

- Arquitetura segmentada por áreas: TI, Financeiro, Atendimento, etc.
- Acesso à nuvem filtrado por firewall
- Comunicação segura entre unidades
- Preparação para crescimento sem reestruturação
- Equipamentos sugeridos com suporte a VLAN, VPN, múltiplos SSIDs e logging

---

## 👨‍💻 Autor

**Adriel Shimaski **  
Curso: *Cybersec - Vai na Web / Kensei*

---

![Status](https://img.shields.io/badge/status-finalizado-green)
![Versão](https://img.shields.io/badge/versão-1.0-blue)
![Licença](https://img.shields.io/badge/licença-MIT-green)
