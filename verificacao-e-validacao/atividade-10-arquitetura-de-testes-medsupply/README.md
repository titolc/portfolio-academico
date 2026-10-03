# Atividade 10 - Arquitetura de Testes MedSupply

[⬅ Voltar ao início](../../README.md) · [Verificação e Validação](../)

| | |
|---|---|
| **Matéria** | Verificação e Validação de Software |
| **Tipo** | Individual (para casa) |
| **Data** | 02/10/2026 |
| **Status** | Entregue |
| **Tags** | `#arquitetura-de-testes` `#automacao` `#qa` |
| **Relacionadas** | [Atividade 06](../atividade-06-plano-de-testes-mediroute/) (plano de testes) · [Atividade 09](../atividade-09-arquitetura-de-testes-ecommerce/) (arquitetura de testes, em grupo) |

## O que foi pedido

Propor uma arquitetura de testes para a Release 3.0 da MedSupply Connect, uma plataforma fictícia B2B que liga hospitais, fornecedores e transportadoras. O sistema tem 20 módulos e vários serviços separados, e estava dando problema em produção.

## O que eu fiz

- Separei os testes por nível (unidade, integração, API, ponta a ponta).
- Indiquei onde vale automatizar e onde o teste manual ainda faz sentido.
- Dei mais atenção aos pontos críticos: pagamento, estoque, aprovação de pedido e as integrações entre serviços.
- Organizei como os testes entram no fluxo de entrega (pipeline).

## O que aprendi

Num sistema dividido em serviços, a maior parte dos problemas aparece na comunicação entre eles. Por isso o teste de integração pesa mais aqui do que no plano da [atividade 06](../atividade-06-plano-de-testes-mediroute/).
