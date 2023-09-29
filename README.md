# Atividade_banco_paises
## Q1
```sql
select * from tabela_paises;
```
## Resultado esperado:
![image](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/69d2ff56-67ee-413c-9f4e-0ce3b0ee2ef9)

## Q2
```sql
select cidade from tabela_paises where pais = 'Brazil';
```
## Resultado esperado:

![image](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/ffebf65c-ca2f-4878-9fa7-0e3cb6eeda98)


## Q3 
```sql
select cidade from tabela_paises where regiao = 'Ceará';
```
## Resultado esperado:
![image](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/b290568e-7834-406f-b361-5ed8b0bec503)


## Q4
```sql
select count (distinct regiao) from tabela_paises where pais = 'China';
```
## Resultado esperado:
![Captura de Tela (1)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/ce349fbb-c565-41e8-aa9e-8cb47dc94235)


## Q5
```sql
select count (distinct regiao) from tabela_paises where pais = 'Canada';
```
## Resultado esperado:
![Captura de Tela (2)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/f44d91ec-f090-4949-9db3-84960e8fd97e)


## Q6
```sql
select count (distinct pais) from tabela_paises;
```
## Resultado esperado:
![Captura de Tela (3)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/f0046eb0-6d23-49d0-9c48-10241e1f7242)

## Q7
```sql
select count (distinct cidade) from tabela_paises where pais = 'Brazil';
```
## Resultado esperado:
![Captura de Tela (4)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/d1c2d953-69b2-43b9-84c7-d40bb9c9fefe)

## Q8
```sql
select pais, count (distinct regiao) as quant_regiao from tabela_paises group by pais order by pais;
```
## Resultado esperado:
![Captura de Tela (5)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/5cb794e6-e30c-4420-b3cd-f61d08cf1534)

## Q9
```sql
select count(nome) as quant_João from tabela_paises where nome like 'João%';
```
## Resultado esperado:
![Captura de Tela (6)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/08839c8c-eee9-4063-80ec-8e7aee5bf13e)

## Q10
```sql
select count(nome) as quant_John from tabela_paises where nome like 'John%';
```
## Resultado esperado:
![Captura de Tela (7)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/caf2109c-191d-4326-b37c-15b8fe2ce612)

## Q11
```sql
select distinct pais from tabela_paises order by pais;
```
## Resultado esperado:
![Captura de Tela (8)](https://github.com/KalelOliveira/Atividade_banco_paises/assets/116455659/af5fa8d6-e049-4426-b9e0-a095c29d8d01)

