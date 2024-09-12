# Documentação do Projeto: Aplicação de Gerenciamento de Receitas

## Escopo do Projeto
O projeto visa desenvolver uma aplicação web que permita aos usuários criar, editar, visualizar e excluir receitas culinárias de forma intuitiva e organizada. A aplicação oferecerá funcionalidades para categorização de receitas, inclusão de ingredientes e instruções, além de possibilitar a configuração de preferências alimentares. A segurança será garantida por meio de autenticação JWT, enquanto o armazenamento de dados será feito com MongoDB. A interface será desenvolvida utilizando React, e o backend será construído com Node.js.

## Objetivos SMART

- **Específico:** Criar uma aplicação de gerenciamento de receitas que permita criar, editar, visualizar e excluir receitas, categorizá-las e adicionar preferências alimentares, com segurança por autenticação JWT.
  
- **Mensurável:** O sucesso será medido pela implementação das funcionalidades principais de CRUD de receitas, categorização e autenticação JWT.
  
- **Atingível:** A aplicação será desenvolvida em 3 meses, utilizando Node.js, React, MongoDB e JWT.
  
- **Relevante:** Oferecer uma ferramenta que facilite a organização e gestão de receitas pessoais de forma prática e segura.
  
- **Temporal:** Lançar a versão inicial da aplicação em 90 dias.

## Cronograma

| Fase                     | Duração    | Início      | Término     |
|--------------------------|------------|-------------|-------------|
| Planejamento              | 1 semana   | 01/09/2024  | 07/09/2024  |
| Configuração do Backend   | 3 semanas  | 08/09/2024  | 28/09/2024  |
| Configuração do Frontend  | 3 semanas  | 29/09/2024  | 19/10/2024  |
| Integração do Sistema     | 2 semanas  | 20/10/2024  | 03/11/2024  |
| Testes e QA               | 2 semanas  | 04/11/2024  | 17/11/2024  |
| Lançamento                | 1 semana   | 18/11/2024  | 24/11/2024  |

## Análise de Risco

- **Riscos Técnicos:** A integração da autenticação JWT pode ser vulnerável a falhas de segurança.  
  **Mitigação:** Implementar práticas de segurança recomendadas, como criptografia de senhas, tokens de acesso com validade curta, e proteção contra ataques CSRF.
  
- **Riscos de Prazo:** Possíveis atrasos devido a bugs inesperados durante a integração de funcionalidades.  
  **Mitigação:** Implementar testes contínuos ao longo do desenvolvimento, com foco em testes unitários e de integração.
  
- **Riscos Financeiros:** Custos com servidores e infraestrutura em nuvem para o ambiente de produção.  
  **Mitigação:** Começar com soluções de hospedagem gratuitas ou de baixo custo, como Heroku ou Netlify.

## Recursos

- **Pessoas:** 1 desenvolvedor full-stack, 1 designer UX/UI, 1 QA tester.
- **Tecnologia:** Node.js, MongoDB, React, JWT, Figma (para prototipagem e design).
  
## Diagramas

### Diagrama de Classes
<img width="104" alt="image" src="https://github.com/user-attachments/assets/c91bf8a8-a691-4d18-bbfb-65e11c8a311f">


### Diagrama de Uso
<img width="264" alt="image" src="https://github.com/user-attachments/assets/7f0fe95f-8985-436c-85f3-7297c689d3a2">


### Diagrama de Fluxo
<img width="268" alt="image" src="https://github.com/user-attachments/assets/b7ae0ed3-f5b9-42a5-9cd5-074601877992">

## Prototipagem

### Baixa Fidelidade
![ReceitasBaixaFidelidade](https://github.com/user-attachments/assets/984fb9c0-0eb1-4a68-95bb-ffc8741842ae)

### Média Fidelidade
Link imagem

### Alta Fidelidade
Link Imagem
