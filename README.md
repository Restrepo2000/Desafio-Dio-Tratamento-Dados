# Processo de Tratamento de Dados no Power BI

Este README descreve o processo de tratamento de dados realizado no Power BI, incluindo etapas como verificação dos dados, modificação de valores monetários, tratamento de nulos, atribuição de gerentes, adição de colunas e junção de tabelas. Tudo isso feito em um Desafio proposto pela DIO.

## Descrição do Conjunto de Dados

O conjunto de dados utilizado neste processo consiste em informações sobre funcionários de uma empresa, incluindo seus nomes, departamentos, salários, IDs de gerente (quando aplicável) e informações sobre horas trabalhadas em projetos. O Objetivo principal era o tratamento dos dados e logo após foi realizado um relatório básico para testes.

## Passos de Tratamento de Dados

Aqui estão as etapas realizadas no Power BI para tratar os dados:

1. **Verificação dos Cabeçalhos e Tipos de Dados**:
   - Verificou-se os nomes das colunas e tipos de dados para garantir consistência.

2. **Modificação de Valores Monetários**:
   - As colunas com valores monetários foram convertidas para o tipo "double".

3. **Tratamento de Nulos**:
   - Verificou-se a existência de valores nulos e aplicaram-se transformações conforme necessário.

4. **Atribuição de Gerentes**:
   - Identificou-se funcionários sem gerentes com base em colunas relevantes.

5. **Verificação de Departamentos sem Gerentes**:
   - Identificou-se departamentos sem gerentes e, se necessário, atribuíram-se gerentes.

6. **Adição de Coluna de Horas de Projeto**:
   - Adicionou-se uma nova coluna com as horas de projeto associadas a cada funcionário.

7. **Separação de Colunas Complexas**:
   - Separaram-se colunas complexas. Estava o nome completo em apenas uma coluna, porém foi separada em duas sendo "Nome" e "Sobrenome".

8. **Eliminação de Colunas Desnecessárias**:
   - Foram removidas colunas que não serão usadas no relatório final.

13. **Criação de um relatório**:
    - Criado um relatório simples para testar se o tratamento foi feito com sucesso.


## Considerações Finais

Este processo de tratamento de dados no Power BI permitiu a criação de um conjunto de dados limpo e preparado para análises mais detalhadas e relatórios. As etapas podem variar dependendo do conjunto de dados e dos requisitos específicos da análise. Certifique-se de personalizar essas etapas de acordo com suas próprias necessidades.
