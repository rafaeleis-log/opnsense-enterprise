# 🔐 VPN Site-to-Site

## Objetivo

Interligar matriz e filiais por meio de túneis VPN criptografados, garantindo comunicação segura entre as unidades.

---

## Cenário

A VPN Site-to-Site permite que todas as unidades compartilhem recursos corporativos de forma transparente.

Principais recursos acessados:

- Active Directory
- Microsoft 365
- Servidores de Arquivos
- Sistemas ERP
- Telefonia VoIP
- Monitoramento Zabbix

---

## Topologia

Internet

↓

OPNsense Matriz

↓

VPN IPSec / OpenVPN / WireGuard

↓

Filiais

---

## Benefícios

- Comunicação segura
- Criptografia ponta a ponta
- Administração centralizada
- Redução de custos
- Alta disponibilidade

---

## Boas práticas

- Utilizar AES-256
- Certificados digitais
- Renovação periódica de chaves
- Logs habilitados
- Backup das configurações
- Testes periódicos de conectividade

---

## Monitoramento

Itens monitorados:

- Status do túnel
- Latência
- Perda de pacotes
- Disponibilidade
- Tempo de resposta

---

## Tecnologias

- OPNsense
- OpenVPN
- WireGuard
- IPSec
- Zabbix
