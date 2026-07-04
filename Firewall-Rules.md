# 🛡 Firewall Rules

## Objetivo

Controlar o tráfego entre redes seguindo o princípio do menor privilégio.

---

## Estratégia

Todo tráfego é bloqueado por padrão.

Somente portas e serviços autorizados são liberados.

---

## Organização das regras

- WAN
- LAN
- VPN
- VLAN
- Floating Rules
- NAT

---

## Recomendações

- Utilizar aliases
- Nomear todas as regras
- Registrar logs
- Revisar regras periodicamente
- Evitar regras "Any Any"

---

## Segurança

- IDS/IPS
- GeoIP Blocking
- DNS Seguro
- Anti Lockout
- Anti Spoofing

---

## Fluxo

Internet

↓

WAN

↓

Firewall

↓

LAN / VLAN

↓

Servidores

↓

Clientes

---

## Auditoria

Realizar revisões periódicas das regras e remover acessos desnecessários.
