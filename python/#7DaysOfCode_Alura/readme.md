# #7DaysOfCode da Alura

✅ No _#7DaysOfCode_ da Alura, o objetivo foi explorar os dados de empréstimos dos acervos do sistema de bibliotecas, disponibilizados [aqui](https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas), por meio da linguagem Python.

🏆 Ao percorrer essa jornada de desafios diários, pude praticar e aprimorar habilidades, trabalhei conceitos de importação de diferentes formatos, manipulação e limpeza de dados, exploração e visualização com bibliotecas como Pandas e Matplotlib. Também fica evidente a necessidade de entender o negócio, que é fundamental para que não se tenha análises sem explicações ou mesmo sem o foco necessário para a resolução dos problemas, podendo assim fornecer insights valiosos, ajudar a tomar decisões informadas para o planejamento estratégico e a melhorar os serviços oferecidos.

### 📍Desafio 1: Importação de dados
Por meio do JupyterLab, a primeira etapa foi unificar em um dataframe todos os dados pertinentes para a análise, que envolviam os empréstimos realizados e as informações dos exemplares do acervo. Aqui vemos a importância da organização em toda a etapa de coleta dos dados, além da verificação e limpeza da sua base de dados, para evitar conteúdos nulos, duplicados e fora do formato adequado para as futuras manipulações.


### 📍Desafio 2: Limpeza de dados
Nesta segunda etapa, tive como objetivo trazer mais contexto que possam trazer informações úteis que agreguem valor e resolvam problemas. A partir da CDU - Classificação Decimal Universal foi possível identificar a que classe geral pertencem os exemplares que foram emprestados nas bibliotecas contidas no banco de dados.

### 📍Desafio 3: Análise exploratória de dados e DateTime
Para entender se a quantidade de empréstimos está diminuindo, aumentando ou permanecendo igual ao decorrer dos últimos anos, foram criados gráficos a partir da contagem de exemplares emprestados por cada ano, mês e horário. Manipulando data e hora para analisar os dados com o Pandas e visualizando as informações por meio do Matplotlib foi possível identificar momentos de maior ocorrência de empréstimos para assim gerar melhores ações de marketing da biblioteca e realocar atividades e colaboradores nas unidades. 

### 📍Desafio 4: Análise exploratória de dados e Variáveis categóricas
Para entender comportamentos dos registros de empréstimos, nessa etapa partimos para análises exploratórias a partir das variáveis categóricas, como Coleções de Exemplares, Unidades de Bibliotecas, Classes gerais dos exemplares e vínculos dos usuários, como estudantes, docentes, etc. Esses tipos de análises são importantes para entender comportamentos e desenvolver novos planos visando melhoria de desempenho nos indicadores, no caso, das próprias bibliotecas, e não apenas fortalecer o que está sendo utilizado, mas também promover o que não está.

### 📍Desafio 5: Mais análise exploratória de dados e Boxplot
O objetivo desta etapa foi realizar uma análise detalhada dos dados de empréstimos de livros na biblioteca, focando nos alunos de graduação e pós-graduação. A análise visou identificar padrões e tendências ao longo dos anos, ajudando a entender como o comportamento dos empréstimos evoluiu entre 2010 e 2020. Utilizar boxplots na análise dos dados de empréstimos foi uma maneira eficiente e informativa de entender a distribuição dos dados, identificar outliers e comparar os diferentes grupos.

### 📍Desafio 6: JSON, Excel e Pivot_table
A fim de avaliar o desempenho de indicadores de uso de materiais do acervo das bibliotecas em determinados cursos, nesta etapa foi proposto o cálculo e análise da quantidade de empréstimos realizados entre 2015 e 2020 entre alunos da graduação. Aqui, usamos mão das tabelas dinâmicas, que ao final da exploração dos dados resumiu e organizou os dados de forma rápida e eficiente, facilitando a visualização das informações.

### 📍Desafio 7:
Na última etapa foi elaborada uma tabela onde pode-se ver a diferença percentual de empréstimos entre os anos especificados para cada curso entre os registros de alunos da pós-graduação. No cenário em observação, foi possível a comparação entre diferentes cursos, independentemente do tamanho absoluto dos números e a utilização da Análise de Porcentagem de Variação  facilitando a comunicação dos resultados para públicos não técnicos, como gestores ou stakeholders.  


