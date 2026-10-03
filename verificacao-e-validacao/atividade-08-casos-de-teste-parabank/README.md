# Atividade 08 - Casos de Teste e Critérios de Aceitação (ParaBank)

[⬅ Voltar ao início](../../README.md) · [Verificação e Validação](../)

| | |
|---|---|
| **Matéria** | Verificação e Validação |
| **Tipo** | Individual |
| **Data** | 02/10/2026 |
| **Status** | Entregue |
| **Sistema** | [ParaBank](https://parabank.parasoft.com/) |
| **Tags** | `#casos-de-teste` `#criterios-de-aceitacao` `#bugs` `#riscos` |
| **Relacionadas** | [Atividade 07](../atividade-07-release-assessment-saucedemo/) · [Projeto Integrador](../../projeto-integrador/) (as user stories seguem o mesmo formato) |

## O que foi pedido

Explorar o ParaBank sem requisito nenhum, deduzir os requisitos, escrever histórias de usuário, critérios de aceitação e casos de teste, e executar.

## O que eu fiz

- Foquei em Login, Transferência e Pagamento de contas (Bill Pay), que são as partes mais críticas.
- Escrevi 3 histórias de usuário e 4 critérios de aceitação para a transferência.
- Montei 6 casos de teste: 2 positivos, 2 negativos, 1 de valor-limite e 1 exploratório.

## Problemas que encontrei

| Onde | Problema | Gravidade |
|---|---|---|
| Login | Depois do logout, entra mesmo com senha errada | Crítica |
| Transferência | Aceita valor negativo | Crítica |
| Transferência | Aceita valor maior que o saldo | Crítica |
| Bill Pay | Aceita pagar mais do que o saldo | Alta |

## O que aprendi

Formulário que "funciona" não quer dizer que a regra de negócio está certa. Os bugs mais graves estavam justamente nas validações que ninguém escreve no requisito.
