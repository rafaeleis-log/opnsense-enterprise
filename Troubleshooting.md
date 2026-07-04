# 🔧 Troubleshooting

## Objetivo

Documentar procedimentos para diagnóstico e resolução de problemas comuns em ambientes baseados em OPNsense.

---

# Internet indisponível

Verificar:

- Status da WAN
- Gateway
- DNS
- NAT
- Firewall Rules

---

# VPN não conecta

Verificar:

- Interface WAN
- Certificados
- Chaves
- Logs do OpenVPN/IPSec
- Rotas

---

# Lentidão na rede

Verificar:

- Uso de CPU
- Memória
- Interfaces
- Latência
- Perda de pacotes

---

# Falha de DNS

Verificar:

- Unbound DNS
- Forwarders
- Resolução externa
- Firewall Rules

---

# VLAN sem comunicação

Verificar:

- Configuração da VLAN
- Interface
- DHCP
- Gateway
- Regras de Firewall

---

# IDS bloqueando tráfego legítimo

Verificar:

- Alertas do Suricata
- Assinaturas
- Whitelist
- Logs

---

# Checklist Inicial

- Interface WAN Online
- Gateway Online
- DNS funcionando
- VPN ativa
- DHCP operacional
- Firewall sem bloqueios indevidos

---

# Ferramentas de Diagnóstico

- Ping
- Traceroute
- Packet Capture
- Firewall Log
- System Log
- Live View

---

# Recomendações

- Registrar todas as alterações.
- Criar backup antes de mudanças.
- Validar configurações em ambiente de testes.
- Monitorar continuamente os serviços críticos.
