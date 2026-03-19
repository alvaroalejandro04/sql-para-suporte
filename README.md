# SQL para Suporte

Exemplos de consultas SQL usadas no dia a dia de suporte.

## Buscar usuários ativos
SELECT * FROM usuarios WHERE ativo = 1;

## Buscar pedidos de um cliente
SELECT * FROM pedidos WHERE cliente_id = 123;
