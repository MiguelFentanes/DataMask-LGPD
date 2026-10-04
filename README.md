# 🛡️ DataMask-LGPD

Uma solução leve e extensível em **Java / Spring Boot** projetada para automatizar o **mascaramento de dados pessoais (PII)** — como CPF, e-mail e telefone — ajudando sistemas e APIs a estarem em conformidade com a **LGPD (Lei Geral de Proteção de Dados)**.

## 🚀 Funcionalidades
- **Mascaramento de CPF:** Preserva início e fim, ocultando dígitos centrais (`123.***.***-00`).
- **Mascaramento de E-mail:** Oculta partes do nome mantendo a estrutura e domínio (`m***l@email.com`).
- **Mascaramento de Telefone:** Mantém DDD e dígitos finais (`(77) 9****-9814`).
- **Integração com Spring Boot:** Anotações customizadas para DTOs e APIs REST.
