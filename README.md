# Desafio Dio - Criando um Star Schema para Cenários de Vendas com Power BI



O objetivo deste projeto é criar um star schema para cenários de vendas usando o Microsoft Power BI. Um star schema é um modelo de banco de dados usado para armazenar dados dimensionais, que são dados que não mudam com o tempo. Os star schemas são usados para melhorar o desempenho das consultas e facilitar a análise de dados. Este projeto guiará os usuários pelas etapas básicas de criação de um star schema no Power BI, incluindo a criação de tabelas de dimensão, tabelas de fatos e relacionamentos entre as tabelas.

## **Requisitos**

- O projeto deve criar um star schema para cenários de vendas usando o Microsoft Power BI.
- O projeto deve criar tabelas de dimensão.
- O projeto deve criar tabelas de fatos.
- O projeto deve criar relacionamentos entre as tabelas.

### **Programas**

- **Programa 1: Star Schema do Power BI**
  - **Código:**
    - Código não aplicável, pois o Power BI é uma ferramenta gráfica de arrastar e soltar.

### **Códigos**

Não há códigos para este projeto, pois o Power BI é uma ferramenta gráfica de arrastar e soltar.



## **Regras de Negócio**

- O projeto deve usar dados reais ou de amostra.

- O star schema deve ser preciso e eficiente.

- O star schema deve ser otimizado para desempenho de consulta.

  

## **Aplicando este projeto**

Este projeto pode ser aplicado a qualquer organização que venda produtos ou serviços. As organizações podem usar o Power BI para criar star schemas para seus dados de vendas, o que pode ajudá-las a obter insights valiosos sobre suas vendas e tomar melhores decisões.



## Instruções de Entrega do Desafio

#### **Descrição do desafio módulo 4 – Criando um Star Schema para Cenários de Vendas com Power BI**

_(Modelo Universidade)_

#### **Objetivo**

Criar o diagrama dimensional – star schema – com base no diagrama relacional disponibilizado.

Foco:

Professor – objeto de análise

Vocês irão montar o esquema em estrela com o foco na análise dos dados dos professores. Sendo assim, a tabela fato deve refletir diversos dados sobre professor, cursos ministrados, departamento ao qual faz parte.... Por aí vocês já têm uma ideia do que deve compor a tabela fato do modelo em questão.

Obs.: Não é necessário refletir dados sobre os alunos!

O que deve ser feito?

Deverá ser criada a tabela Fato que contêm o contexto analisado. Da mesma forma, é necessária a criação das tabelas dimensão que serão compostas pelos detalhes relacionados ao contexto.

Por fim, mas não menos importante, adicione uma tabela dimensão de datas. Para compensar a falta de dados de datas do modelo relacional, suponha que você tem acesso aos dados e crie os campos necessários para modelagem.

Ex: data de oferta das disciplinas, data de oferta dos cursos, entre outros. O formato, ou melhor, a granularidade, não está fixada. Podem ser utilizados diferentes formatos que correspondem a diferentes níveis de granularidade.

______________________________________________________________________________________________________________________________________________

## Passo 01 – Criação do modelo padrão

Criação no Software Workbench o modelo padrão proposto no desafio

![image](https://user-images.githubusercontent.com/116984176/214466941-45889125-7b5c-4a3f-9159-4c147a483ab3.png)



## Passo 02 – Etapas de modelagem

Foi usada a metodologia de abstração das informações do dataset proposto de redimensionamento das tabelas para arquitetar tabelas dimensões com adição da tabela "data" e a tabela fato "professor".

- Tabela-fato: "Professor" pois possui informações numéricas sobre os professores, como número de disciplinas ministradas. As outras tabelas foram convertidas em tabelas-dimensão;

- A tabela "Departamento" foi usada como uma tabela-dimensão, pois contém informações descritivas sobre os professores, como o nome e o campus do departamento;

- A tabela "Disciplina" também foi usada como uma tabela-dimensão, pois contém informações descritivas sobre as disciplinas ministradas pelos professores;

- Foi incluído a tabela-dimensão "Data" com atributos data, dia, semana, mês, trimestre e ano;

- A tabela "Curso" foi usada como uma tabela-dimensão, pois contém informações descritivas sobre os cursos relacionados aos departamentos;

- A tabela "Aluno" e "Matriculado" não é necessário para o Star Schema proposto.

  

## Passo 03 – Resultado Star Schema - Universidade

![image](https://user-images.githubusercontent.com/116984176/214468270-ce3a75e7-f842-466a-ab1d-b5e3e2dd4d17.png)



## **Conclusão**

Criar um star schema para cenários de vendas é uma parte essencial da modelagem de dados para análise de vendas. O Power BI fornece uma variedade de ferramentas e recursos que podem ajudar os usuários a criar star schemas precisos e eficientes. Ao seguir as etapas deste projeto, os usuários podem aprender os fundamentos da criação de star schemas no Power BI e começar a criar seus próprios star schemas personalizados.

## **Aprendizado e Aplicabilidade Prática:**

- O Power BI é uma ferramenta poderosa para criar star schemas para cenários de vendas.

- O Power BI é fácil de usar, mesmo para iniciantes.

- Os star schemas podem melhorar o desempenho das consultas e facilitar a análise de dados.

- O Power BI pode ajudar os usuários a criar star schemas precisos e eficientes.

  
