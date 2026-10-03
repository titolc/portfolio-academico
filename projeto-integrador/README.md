# Projeto Integrador - DaMatch

[⬅ Voltar ao início](../README.md)

| | |
|---|---|
| **Matéria** | Extensão Full Stack (Projeto Integrador) |
| **Tipo** | Grupo |
| **Semestre** | 2026.2 |
| **Status** | Em desenvolvimento |
| **Repositório do grupo** | [Diogo746/Da-Match](https://github.com/Diogo746/Da-Match) |
| **Meu papel** | Product Owner / Analista |
| **Tags** | `#full-stack` `#angular` `#spring-boot` `#user-stories` |

## Sobre o projeto

O DaMatch é uma plataforma web que conecta startups do Nordeste com mentores e investidores. Cada lado preenche o perfil (setor, estágio, tipo de apoio, faixa de investimento...) e o sistema calcula uma pontuação de compatibilidade. Quando os dois lados demonstram interesse, vira uma conexão e dá pra marcar reunião.

**Tecnologias:** Angular, Spring Boot, SQLite, LLDAP, GitHub Actions, SonarQube e deploy no Render.

## Equipe

| Integrante | Papel |
|---|---|
| Diogo Barbosa | Scrum Master / DevOps |
| Mário Brandão | Back-end |
| Davi Maia | Front-end |
| Christopher Lindoso | Product Owner / Analista |
| Nikolas Messias | Gerente de Projeto |

## Minha parte

Como PO, fico com o backlog, as histórias de usuário e a parte de requisitos. A documentação do projeto está na pasta [`docs/`](https://github.com/Diogo746/Da-Match/tree/main/docs) do repositório do grupo:

- [Requisitos](https://github.com/Diogo746/Da-Match/blob/main/docs/02-software-requirements-specification.md)
- [Casos de uso](https://github.com/Diogo746/Da-Match/blob/main/docs/03-use-cases.md)
- [Histórias de usuário](https://github.com/Diogo746/Da-Match/blob/main/docs/04-user-stories.md)

## Pesquisa com o público

Antes de fechar os requisitos, fizemos um [formulário de pesquisa](https://docs.google.com/forms/d/e/1FAIpQLSdWaY8GitUXkt7KDYUNWOpQwVt2yEz-pO1sdkYKuyOiDRTRew/viewform) com startups, mentores e investidores. A ideia era entender como essas conexões acontecem hoje:

- quantas vezes a pessoa buscou mentoria, parceria ou investimento nos últimos 6 meses;
- onde procurou (indicação, eventos, LinkedIn, WhatsApp, incubadoras...);
- quais critérios pesaram na escolha (setor, estágio, experiência, localização...);
- qual foi a maior dificuldade e no que deu a busca.

Os critérios perguntados no formulário são os mesmos que o sistema usa para calcular o match.

## Ligação com as outras matérias

- O problema e a oportunidade do projeto vieram da atividade [Da tendência à oportunidade](../empreendedorismo-e-planos-de-negocio/da-tendencia-a-oportunidade/), de Empreendedorismo.
- As histórias de usuário e os critérios de aceitação usam o mesmo formato da [Atividade 08](../validacao-e-verificacao/atividade-08-casos-de-teste-parabank/).
- O plano de testes do projeto pode seguir o modelo da [Atividade 06](../validacao-e-verificacao/atividade-06-plano-de-testes-mediroute/).
