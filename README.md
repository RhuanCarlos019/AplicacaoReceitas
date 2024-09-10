# Aplicação de Bloco de Notas

## Escopo do Projeto
Desenvolver uma aplicação de bloco de notas que permita ao usuário criar, editar e armazenar suas notas de maneira segura, utilizando autenticação JWT. O backend será construído em Node.js, com MongoDB para armazenamento de dados e React para interface do usuário. O foco é oferecer uma solução intuitiva, segura e responsiva para gerenciar notas pessoais.

## Objetivos SMART
- **Específico**: Criar uma aplicação de bloco de notas que salva, edita e deleta notas com autenticação JWT.
- **Mensurável**: O sucesso será medido pela implementação de todas as funcionalidades principais.
- **Atingível**: A aplicação será desenvolvida em 3 meses, utilizando Node.js, React, MongoDB e JWT.
- **Relevante**: Fornecer uma ferramenta segura e prática para gerenciamento de notas pessoais.
- **Temporal**: Lançar a versão inicial em 90 dias.

## Cronograma - Diagrama Gantt

| Fase                     | Duração  | Início      | Término      |
| ------------------------ | -------- | ----------- | ------------ |
| Planejamento              | 1 semana | 01/09/2024  | 07/09/2024   |
| Configuração do Backend   | 3 semanas| 08/09/2024  | 28/09/2024   |
| Configuração do Frontend  | 3 semanas| 29/09/2024  | 19/10/2024   |
| Integração do Sistema     | 2 semanas| 20/10/2024  | 03/11/2024   |
| Testes e QA               | 2 semanas| 04/11/2024  | 17/11/2024   |
| Lançamento                | 1 semana | 18/11/2024  | 24/11/2024   |

## Análise de Risco
- **Riscos Técnicos**: Integração de autenticação JWT pode ser vulnerável a falhas de segurança. **Mitigação**: Implementar boas práticas de segurança.
- **Riscos de Prazo**: Atrasos podem ocorrer devido a bugs imprevistos. **Mitigação**: Adotar testes contínuos para prevenir problemas de última hora.
- **Riscos Financeiros**: Custos adicionais com servidores e infraestrutura. **Mitigação**: Iniciar com serviços de hospedagem gratuitos.

## Recursos
- **Pessoas**: 1 desenvolvedor full-stack, 1 designer UX/UI, 1 QA tester.
- **Tecnologia**: Node.js, MongoDB, React, JWT, Figma (prototipagem).

## Diagramas

### Diagrama de Classes
- **Usuário**: id, nome, email, senha.
- **Nota**: id, título, conteúdo, data de criação, data de modificação, id_usuário.
- **Autenticação JWT**: token, id_usuário.

### Diagrama de Caso de Uso
1. **Usuário**: Cadastro, login, criação de nota, edição de nota, exclusão de nota.
2. **Sistema**: Autenticar usuário, armazenar notas, garantir acesso seguro.

### Diagrama de Fluxo
1. **Fluxo de Cadastro/Login**: Usuário -> Frontend -> Backend -> Banco de Dados -> JWT gerado -> Resposta ao Frontend.
2. **Fluxo de CRUD de Notas**: Usuário autenticado -> Frontend -> Backend -> MongoDB -> Notas salvas/recuperadas.
