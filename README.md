# Desafio Transformação e Limpeza de dados para Power BI | Treinamento DIO 📜📜📜

## Foi realizada essas tranformações:
- ### O campo Salary da tabela Employee foi transformada em decimal fixo;
- ### A coluna Address de Employ foi dividida em quatro colunas: número, rua, cidade e estado;
- ### Mesclei as tabelas Employee e Departament para uma nova consulta e eliminei as colunas Dno e Dnumber;
- ### Realizei a junção dos colaboradores e seus respectivos gerentes por meio da consulta sql: select e.Fname as Funcionario, m.Fname as Gerente from employee e inner join employee m on e.Super_ssn = m.Ssn;
- ### Mesclei as colunas de nome e sobrenome da tabela Employee;
- ### Mesclei os nomes de departamento e localização;

## 📑Mesclar e atribuir
Mesclar é a combinação de duas ou mais tabelas por meio de uma coluna correspondente. Seu resultado é semelhante ao resultado de um JOIN realizado no mysql, pois as colunas de uma tabela se adaptam às colunas da outra tabela.

No entanto, atribuir é apenas a junção das linhas de uma tabela com as linhas de outra tabela, empilhando os dados. Neste caso só é possível unir tabelas com estruturas iguais. 

Por isso, apenas o mesclar foi utilizado no desafio.



