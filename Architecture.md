# 🏗️ Arquitetura

## Objetivo

Descrever a arquitetura da infraestrutura baseada em OPNsense.

---

## Visão Geral

O ambiente é composto por:

- Internet
- Firewall OPNsense
- Core Switch
- Active Directory
- Microsoft 365
- UniFi
- Zabbix
- VPN Site-to-Site

---

## Topologia

![Arquitetura](Topology.png)

---

## Fluxo de Rede

Internet

↓

Firewall OPNsense

↓

Core Switch

↓

VLANs

↓

Servidores

↓

Clientes

---

## VLANs

| VLAN | Descrição |
|------|-----------|
|10|Usuários|
|20|Servidores|
|30|VoIP|
|40|CFTV|
|50|Convidados|
|60|IoT|

---

## Segurança

- IDS/IPS
- GeoIP
- DNS Seguro
- VPN IPSec
- Backup Automático
