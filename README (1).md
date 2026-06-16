# Meus Primeiros Passos em ADS

Repositório criado para documentar minha evolução técnica durante o 1º semestre do curso de Análise e Desenvolvimento de Sistemas (ADS) — incluindo estudos de lógica, algoritmos e o desenvolvimento do projeto principal da grade curricular.

---

## 🏆 Reconhecimento

> **2º Lugar — Grande Prêmio Dev No/Low Code 2025-1**
> Categoria: *Sprint Master — Foco e Entrega*
> Critério avaliado: Gestão de Projetos · App Sabor Local
> Concedido pela Coordenação do Curso ao grupo **Rango Legal** pelo foco e consistência na entrega das sprints ao longo do semestre.

---

## Projeto em Destaque: Sabor Local

O **Sabor Local** é um ecossistema completo de delivery voltado para o comércio gastronômico regional. O projeto foi estruturado com foco em **Desenvolvimento Backend** — priorizando modelagem de dados relacional robusta, integridade referencial e organização das regras de negócio em camadas.

---

## Stack Tecnológica

| Camada | Tecnologia |
|---|---|
| Backend & Banco de Dados | Xano (PostgreSQL) |
| Frontend | FlutterFlow |

---

## Arquitetura & Regras de Negócio

O sistema foi projetado mapeando a jornada completa do usuário, com fluxos estruturados para:

- **Autenticação segura** — Cadastro e Login com verificação de código via e-mail
- **Gestão de endereços** — Suporte a múltiplos endereços por usuário, com busca automática via CEP (integração ViaCEP)
- **Carrinho dinâmico** — Controle de itens, quantidades e totais em tempo real
- **Checkout estruturado** — Pagamento via PIX com geração de QR Code e Cartão de Crédito

---

## Mapeamento de Telas (FlutterFlow)

**Fluxo 1 — Autenticação & Navegação Principal**
(Tela Inicial → Login → Esqueci Senha → Verificação de Código → Nova Senha → CardápioDinâmico → Detalhe do Produto)

<img alt="Fluxo de autenticação e navegação principal" src="(https://private-user-images.githubusercontent.com/272666239/608833902-9db1e0ef-585b-47f8-a0b8-ad598f9875de.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODE2NDEzNjksIm5iZiI6MTc4MTY0MTA2OSwicGF0aCI6Ii8yNzI2NjYyMzkvNjA4ODMzOTAyLTlkYjFlMGVmLTU4NWItNDdmOC1hMGI4LWFkNTk4Zjk4NzVkZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNjE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDYxNlQyMDE3NDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kOGZiZmUxMTc4ZjNlYWVhNDkzY2ZlNDNkOTIwMjRiYmIwY2JjOTMzMzRkMzM4Y2RlYjRmZGQwMzczZmExYTkzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.cmJBBxr0Mh_PGR3T9KkJk9cxfWv4KIWpb3rvyC9CrzE)" />

**Fluxo 2 — Cadastro, Endereços, Carrinho, Pagamento & Confirmação**
(Criar Conta → Buscar → Meus Pedidos → Finalizar Pedido → Cartão/PIX → Pedido Confirmado → Mapa Motoboy)

<img alt="Fluxo de cadastro, endereços e checkout" src="[URL_IMAGEM_2_AQUI](https://private-user-images.githubusercontent.com/272666239/608833953-5fed9087-8930-4220-8aed-c5df1460c087.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODE2NDEzNjksIm5iZiI6MTc4MTY0MTA2OSwicGF0aCI6Ii8yNzI2NjYyMzkvNjA4ODMzOTUzLTVmZWQ5MDg3LTg5MzAtNDIyMC04YWVkLWM1ZGYxNDYwYzA4Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNjE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDYxNlQyMDE3NDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05NzA3MjAzZDgxNDg3MWVlYjBiMGZhYjBlMjE1Y2E5ZmU0NTJiMGVmNzE1NmQ1YWE3NmNjMTQ5MGYzZGNkNzI2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.BNjzoipwLRjuH0wPf-cubfnARJ0aprl16JmyLEPZ6x8)" />

**Fluxo 3 — Detalhe: Endereços, PIX, Verificação de Cadastro & Cartões Salvos**

<img alt="Fluxo detalhado de endereços, PIX e cartões salvos" src="[URL_IMAGEM_3_AQUI](https://private-user-images.githubusercontent.com/272666239/608833969-6578489a-f5e8-4a4b-8103-da5638c31355.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODE2NDEzNjksIm5iZiI6MTc4MTY0MTA2OSwicGF0aCI6Ii8yNzI2NjYyMzkvNjA4ODMzOTY5LTY1Nzg0ODlhLWY1ZTgtNGE0Yi04MTAzLWRhNTYzOGMzMTM1NS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNjE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDYxNlQyMDE3NDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zMGVhY2UyZDZlZGRmM2RkN2Y4MjI1YjIwY2E3ZTUxZGQ0MmZmZTQ2NWUyYzQyNjI5NzQzMGZlMTIxYzU3MWI2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.yNr0Ah9x0a_Yu0U09BB2Z_OfpnZ1mTCDdDWZrJ1AjFA)" />

---

## Modelagem de Banco de Dados

O banco de dados foi modelado utilizando PostgreSQL via Xano, com **mais de 20 tabelas interligadas**, garantindo integridade referencial, consistência dos dados e performance nas consultas.

Principais entidades: `USUARIO`, `CLIENTE`, `ENDERECO`, `RESTAURANTE`, `PRODUTO`, `PEDIDO`, `ITEM_PEDIDO`, `PAGAMENTO`, entre outras.

### Diagrama Entidade-Relacionamento (DER)

<img width="506" height="667" alt="Captura de tela 2026-06-04 194842" src="https://github.com/user-attachments/assets/3aaec983-34df-4fdf-b102-b7f95250d349" />

---

## Status

Projeto em desenvolvimento contínuo. Aberto a oportunidades de **estágio em Desenvolvimento Backend**.
