# Estudos de MySQL

Repositório de estudos de banco de dados relacionais e SQL, organizado a partir do material de um curso livre.

## Sobre

Este repositório reúne anotações e exemplos de SQL estudados durante o curso. O conteúdo foi separado por aulas para facilitar a consulta e a revisão.

**Importante:** o arquivo original foi preservado em `material-original/curso-completo-original.txt`. Os arquivos em `aulas-organizadas/` são recortes do material original por aula e podem conter explicações em texto junto com SQL; portanto, nem todos são scripts executáveis diretamente no MySQL sem separar os trechos de código.

## Conteúdos abordados

- Modelagem de dados e tipos de dados
- Criação de bancos e tabelas
- INSERT, SELECT, WHERE, LIKE, UPDATE e DELETE
- Valores nulos e funções como IFNULL/COALESCE
- COUNT, GROUP BY, SUM, AVG, MIN e MAX
- Relacionamentos, cardinalidade, chaves primárias e estrangeiras
- JOIN, views e subconsultas
- Procedures e funções
- ALTER TABLE e constraints
- Triggers, auditoria e backup
- Autorrelacionamento e cursores
- Introdução à normalização (1FN, 2FN e 3FN)

## Estrutura

```text
estudos-mysql/
├── README.md
├── material-original/
│   └── curso-completo-original.txt
├── aulas-organizadas/
│   └── arquivos separados por aula
└── scripts-sql/
    └── reservado para versões SQL revisadas e executáveis
```

## Como usar

1. Comece pelo material original se precisar conferir o contexto completo.
2. Use `aulas-organizadas/` para revisar por aula.
3. Antes de executar um trecho, confirme se o banco e as tabelas necessários já existem.
4. Teste os comandos em um banco de estudo, nunca em uma base com dados importantes.
5. Ao corrigir ou adaptar um exemplo, documente a alteração para diferenciar o código do curso da sua versão revisada.

## Ferramentas

- MySQL
- MySQL Command Line Client ou outro cliente SQL compatível
- Git e GitHub

## Objetivo

Documentar meu processo de aprendizagem em SQL, praticar consultas e modelagem de dados e desenvolver uma base para projetos futuros com bancos de dados e análise de dados.

## Créditos e autoria

O material de origem foi usado como referência de estudo de um curso. As anotações e os exemplos devem ser atribuídos aos respectivos autores quando identificados. As adaptações próprias devem ser identificadas como revisões ou exercícios pessoais.
