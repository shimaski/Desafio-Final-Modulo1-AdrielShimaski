  
## PROPOSTA TÉCNICA – PROJETO DE REDE CORPORATIVA  

**Cliente:** Werneck S/A  
**Autor:** Adriel Shimaski
**Curso:** Cybersec - Vai na web/kensei  
**Data:** 28/07/2025  
**Versão:** 1.0  


# Proposta de Rede Corporativa – Werneck S/A

## Sumário Executivo

A Werneck S/A está em processo de crescimento e precisa de uma rede moderna e segura para conectar sua sede em São Paulo e as filiais no Rio de Janeiro e em Minas Gerais.

A proposta visa criar uma estrutura de rede organizada, com divisões claras entre os setores da empresa, controle de acessos e proteção das informações, considerando a possibilidade de expansão futura.

Será implantada uma rede segmentada por áreas (usando **VLANs**) e interligada por conexões seguras (**VPNs site-to-site**). Um **firewall** será utilizado para controle de tráfego e proteção contra ameaças. Também será criada uma rede separada para visitantes.

Essa solução proporciona **proteção, desempenho e flexibilidade**, oferecendo uma base tecnológica sólida para o crescimento da empresa.

---

## Objetivo

Criar uma rede moderna e bem organizada para a empresa Werneck S/A, conectando a matriz em São Paulo com as filiais no Rio de Janeiro e Minas Gerais.

---

## Segurança

A estrutura deve garantir:

- Segurança e desempenho;
- Controle de acessos por setor;
- Crescimento futuro sem comprometer estabilidade;
- Proteção dos dados corporativos.

---

## Escopo

Este projeto propõe a criação de uma rede de computadores para a matriz e filiais, garantindo **funcionamento seguro, organizado e eficiente**.

### Recursos Principais:

- **Segmentação por VLANs**: separação por departamentos.
- **VPN site-to-site**: conexão segura entre unidades.
- **Acesso remoto seguro**: para colaboradores externos.
- **Firewall**: controle de acessos e segurança.
- **Integração com nuvem**: Office 365, CRM, etc.

---

## Metodologia

### 1. Identificação de Requisitos

- Análise do briefing
- Levantamento de necessidades, número de funcionários e departamentos
- Definição dos requisitos técnicos

### 2. Elaboração do Plano

- Desenho da arquitetura (VLANs, VPNs, políticas de segurança)
- Ações priorizadas com base no modelo **80/20**

### 3. Criação do Diagrama

- Diagrama lógico da rede
- Justificativas técnicas com foco em segurança, desempenho e manutenção

---

## Estrutura das Unidades

### Matriz – São Paulo

- Centro principal com servidores, switch core, firewall e VLANs
- Acesso a Office 365, CRM e outros sistemas em nuvem

### Filial RJ

- 30 funcionários  
- IPs: `10.1.0.2` a `10.1.0.31/24`  
- Conectada via **VPN site-to-site**

### Filial MG

- 10 funcionários com acesso remoto  
- IPs: `10.1.10.2` a `10.1.10.11/24`  
- Acesso remoto seguro

---

## Justificativas Técnicas

- **Segmentação por VLANs**: separação por departamento → mais segurança e controle
- **VPN entre unidades**: conexão segura pela internet, como se estivessem na mesma rede
- **Isolamento de visitantes/IoT**: redes separadas para evitar riscos
- **Firewall com logs**: controle, bloqueios e rastreamento de acessos
- **Integração com sistemas em nuvem**: produtividade, mobilidade e colaboração

---

## Benefícios da Integração com a Nuvem

- E-mails e agendas corporativas
- Armazenamento colaborativo de documentos
- Videoconferências e comunicação remota
- Redução de servidores locais
- Atualizações e backups facilitados

---

## Diagnóstico / Proposta Técnica

- **VLANs** para cada setor: Administrativo, Financeiro, TI, Atendimento
- Rede para visitantes isolada
- VPN site-to-site entre as unidades
- Firewall com regras e logs
- Acesso remoto seguro para MG
- Servidores locais com acesso restrito

---

## Boas Práticas

1. **Separar visitantes da rede interna**
2. **Criar políticas claras de acesso remoto**
3. **Usar firewall com logging**
4. **Acesso segmentado por VLANs**
5. **VPN site-to-site entre matriz e filiais**


