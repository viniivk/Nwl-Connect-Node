# Ranqueamento de inscrições em evento via link

## Funcionalidade da aplicação

A aplicação é um simulacro de um ranking de inscrições em um evento utilizando links.
Um usuário ao se cadastrar no evento pode utilizar seu id como referência para outros usuários se inscreverem, fazendo com que o referenciado ganhe uma pontuação de acordo com a quantidade de pessoas que utilizaram seu link.

## Tecnologias utilizadas na aplicação
Docker: Com as imagens de bancos de dados utilizados

PostgreSQL: Banco de dados principal, com a tabela de subscriber que é utilizada para armazenar dados de inscritos no evento

Redis : Banco de dados utilizado para armazenar resultados das consultas aos endpoints da aplicação, utilizando as funções disponibilizados por ele

Fastify: Framework para o desenvolvimento da aplicação

Zod: Utilizado na validação e serialização de dados 

Drizzle: Para comunicação entre a aplicação e o banco de dados PostgreSQL

Node.js: Ambiente de execução da aplicação

Typescript: Linguagem utilizada para a escrita do código em si
