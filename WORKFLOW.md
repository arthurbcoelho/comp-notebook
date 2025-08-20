# Comparador de Notebook

## Objetivo

Este é um pequeno projeto desenvolvido para treinar o uso do Git na faculdade. O objetivo é praticar os conceitos fundamentais de versionamento de código e colaboração em equipe.

## GitFlow

Utilizaremos o **GitFlow** como estratégia de branching. O GitFlow é um modelo de ramificação que define tipos específicos de branches e como elas interagem entre si:

- **master**: Branch principal com código de produção
- **develop**: Branch de desenvolvimento onde as features são integradas
- **feature/**: Branches para desenvolvimento de novas funcionalidades
- **release/**: Branches para preparação de novas versões
- **hotfix/**: Branches para correções urgentes em produção

![GitFlow](gitflow.png)

## Padrão de Commits

Todos os commits devem seguir o padrão estabelecido:

```
[CON-<N°ISSUE>] - <tipo do commit> <mensagem>
```

### Estrutura do Commit

- **CON-**: Prefixo do projeto
- **N°ISSUE**: Número da issue relacionada ao commit
- **tipo do commit**: Categoria da mudança (veja tipos abaixo)
- **mensagem**: Descrição clara e concisa da alteração

### Tipos de Commit

- **feat**: Nova funcionalidade
- **fix**: Correção de bug
- **docs**: Alterações na documentação
- **style**: Mudanças de formatação (espaços, vírgulas, etc.)
- **refactor**: Refatoração de código
- **test**: Adição ou modificação de testes
- **chore**: Tarefas de manutenção

### Exemplos

```bash
[CON-001] - feat: adiciona sistema de login
[CON-002] - fix: corrige validação de email
[CON-003] - docs: atualiza README com instruções de instalação
[CON-004] - refactor: reorganiza estrutura de pastas
```