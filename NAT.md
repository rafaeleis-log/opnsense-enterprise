# 🌐 NAT (Network Address Translation)

## Objetivo

Gerenciar a tradução de endereços de rede, permitindo a comunicação segura entre redes privadas e públicas.

---

## Cenário

O NAT é utilizado para controlar o acesso entre a rede interna e a Internet, além de permitir a publicação segura de serviços quando necessário.

---

## Tipos de NAT

### Outbound NAT

Responsável pela tradução dos endereços internos para acesso à Internet.

### Port Forward

Permite publicar serviços internos utilizando portas específicas.

Exemplos:

- HTTPS (443)
- HTTP (80)
- VPN
- RDP (somente quando necessário)

### One-to-One NAT

Realiza o mapeamento exclusivo entre um endereço público e um endereço privado.

---

## Fluxo

Internet

↓

Firewall OPNsense

↓

NAT

↓

Servidor ou Cliente

---

## Boas Práticas

- Publicar apenas serviços necessários.
- Restringir portas de origem.
- Utilizar aliases para organização.
- Registrar logs das conexões.
- Evitar exposição desnecessária de serviços.

---

## Segurança

- Menor privilégio.
- Revisão periódica das regras.
- Remoção de regras obsoletas.
- Utilização de HTTPS sempre que possível.

---

## Tecnologias

- OPNsense
- Port Forward
- Outbound NAT
- One-to-One NAT
