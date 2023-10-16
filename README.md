
# Segundo desafio de projeto utilizando o power BI do bootcamp santander.
## Conexão com Banco de Dados "azure_company" com acesso e transformação das Tabelas

Após inserção dos dados na base, conectei o PowerBI com o banco de dados "azure_company" e transformei as tabelas:

- "departament"
- "dependent"
- "dept_locations"
- "project"
- "employee"
- "works_on"

Relatório de alteração de cada tabela:
### Todas as tabelas
1. Exclui a coluna de identificação do ID.
#### Tabela "departament"
2. colunas renomeadas.

#### Tabela "dependent"
Sem alterações necessárias

#### Tabela "dept_locations"
2. colunas renomeadas.

#### Tabela "project"
2. colunas renomeadas.
3. Sufixo adicionado na lozalização.

#### Tabela "employee"
2. Coluna de endereço dividida em 4 diferentes colunas, realizando alterações necessárias para corrigir quinta coluna desnecessária.
3. Junção de 3 colunas de nome em uma para unificar o nome completo do funcionário.

#### Tabela "works_on"
2. colunas renomeadas.


### Mesclando tabelas
As seguintes tabelas foram mescladas:
1. "works_on" e "Project":
    Agrupado pelo nome do projeto, contando as horas empregadas em cada um dos projetos e sua respectiva localização.
   
2. "employee" e "dependent":
    Agrupado por nome completo do  funcionário, contando os dependentes por cada um dos empregados.

3. "employee" e "departament":
    Agrupado por nome completo do  funcionário, contando os projetos por cada um dos empregados.

4. "employee" e "departament":
    Agrupado por nome do projeto, contando a quantidade de empregados em cada um dos projetos.
