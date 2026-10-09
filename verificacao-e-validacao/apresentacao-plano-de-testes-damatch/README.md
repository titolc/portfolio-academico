# Apresentação: Validação do DaMatch

[⬅ Voltar ao início](../../README.md) · [Verificação e Validação](../)

| | |
|---|---|
| **Matéria** | Verificação e Validação de Software |
| **Tipo** | Grupo (grupo do PI, apresentação) |
| **Equipe** | Christopher Lindoso, José Mário Brandão, Davi Maia, Diogo Barbosa, Nikolas Messias |
| **Data** | 06/10/2026 |
| **Status** | Entregue |
| **Arquivo** | [damatch-validacao-apresentacao.pptx](damatch-validacao-apresentacao.pptx) (16 slides) |
| **Tags** | `#plano-de-testes` `#qa` `#damatch` `#rastreabilidade` |
| **Relacionadas** | [Atividade 04](../atividade-04-plano-de-testes-cadastro-startup/) (primeiro plano de testes do DaMatch) · [Atividade 06](../atividade-06-plano-de-testes-mediroute/) · [Projeto Integrador](../../projeto-integrador/) |

## Resumo

Apresentação do plano inicial de testes e qualidade do DaMatch, com base no documento de testes do projeto (versão 1.0, de 05/10/2026).

O que mostramos:
- **A diferença entre verificação e validação no projeto:** verificar se segue as regras e validar se atende quem vai usar.
- **A base do plano:** 36 requisitos funcionais, 24 não funcionais, 30 regras de negócio, 65 casos de teste e 12 riscos.
- **Os testes mais importantes:**
  - a conta do matching (ex.: 75 de 85 pontos aplicáveis dá 88,2);
  - a conexão só ser criada quando os dois lados têm interesse, mesmo com 20 pedidos ao mesmo tempo;
  - a API recusar o acesso aos dados de outra pessoa.
- **O teste com usuários:** 5 fundadores de startup tentando achar apoio e demonstrar interesse. A meta é que 4 de 5 consigam em até 5 minutos.
- **A situação atual e os próximos passos:** nenhum caso foi executado ainda, porque a jornada completa ainda não está pronta.

Comparado com a [atividade 04](../atividade-04-plano-de-testes-cadastro-startup/), que testava só o cadastro, aqui o plano cobre a jornada inteira do DaMatch.
