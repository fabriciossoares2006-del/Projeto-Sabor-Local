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
(Tela Inicial → Login → Esqueci Senha → Verificação de Código → Nova Senha → Cardápio → Detalhe do Produto)

![Fluxo de autenticação e navegação principal](https://github.com/user-attachments/assets/9db1e0ef-585b-47f8-a0b8-ad598f9875de)

**Fluxo 2 — Cadastro, Endereços, Carrinho, Pagamento & Confirmação**
(Criar Conta → Buscar → Meus Pedidos → Finalizar Pedido → Cartão/PIX → Pedido Confirmado → Mapa Motoboy)

![Fluxo de cadastro, endereços e checkout](https://github.com/user-attachments/assets/5fed9087-8930-4220-8aed-c5df1460c087)

**Fluxo 3 — Detalhe: Endereços, PIX, Verificação de Cadastro & Cartões Salvos**

![Fluxo detalhado de endereços, PIX e cartões salvos](https://github.com/user-attachments/assets/6578489a-f5e8-4a4b-8103-da5638c31355)

---

## Modelagem de Banco de Dados

O banco de dados foi modelado utilizando PostgreSQL via Xano, com **mais de 20 tabelas interligadas**, garantindo integridade referencial, consistência dos dados e performance nas consultas.

Principais entidades: `USUARIO`, `CLIENTE`, `ENDERECO`, `RESTAURANTE`, `PRODUTO`, `PEDIDO`, `ITEM_PEDIDO`, `PAGAMENTO`, entre outras.

### Diagrama Entidade-Relacionamento (DER)

![Diagrama Entidade-Relacionamento](https://github.com/user-attachments/assets/3aaec983-34df-4fdf-b102-b7f95250d349)

---

## Status

Projeto em desenvolvimento contínuo. Aberto a oportunidades de **estágio em Desenvolvimento Backend**.
