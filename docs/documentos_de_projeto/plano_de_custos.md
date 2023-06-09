# Custos de projeto

## Histórico de versão

|        Data        |       Autor       |                  Descrição da revisão                  | Versão |
| :----------------: | :---------------: | :----------------------------------------------------: | :----: |
| 2 de Maio de 2023  | **Luis Marques**  |                Inclusão da documentação                | 1.0.0  |
| 11 de Maio de 2023 | **Luis Marques**  |                    Inclusão de EVM                     | 1.1.0  |
| 12 de Maio de 2023 | **Luis Marques**  | Inclusão de descrição de EVM e link de tabela completa | 1.1.1  |
| 13 de Maio de 2023 | **Paulo Batista** |                  Revisão do documento                  | 1.1.1  |
| 22 de Maio de 2023 | **Luis Marques** |           Alteração do link da tabela de EVM           | 1.1.2  |
| 22 de Maio de 2023 | **Marcos Tavares** |           Adiciona Formula e Referências do EVM       | 1.2.0  |

## Objetivo do documento

Esse documento visa descrever os custos estimados para o desenvolvimento do projeto. Para essa estimativa será levado em consideração o tempo de
desenvolvimento definido no cronograma do projeto, e o custo de um aluno de graduação da Universidade de Brasília.

Ao término desse documento será possível conhecer os custos que foram estimados para desenvolver esse projeto, assim como o valor agregado entregue em cada uma das iterações de desenvolvimento.

## Custo por graduando

Tomando como referência a reportagem Raio-X do custo por aluno nas univerdades federais, publicada pelo jornal O Globo em 2016[[5](https://infograficos.oglobo.globo.com/brasil/raio-x-do-custo-por-aluno-nas-universidades-federais.html)], o custo de um aluno da Universidade de Brasília é de R$ 38.805,00 por ano.

Uma vez que esse valor é referente ao ano de 2016, e desde então houve inflação, foi utilizado o a calculadora de ajuste de inflação do Banco Central do Brasil [[6](https://www3.bcb.gov.br/CALCIDADAO/publico/corrigirPorIndice.do?method=corrigirPorIndice)] para calcular o valor atualizado para o ano de 2023. Para isso foi utilizado o índice de inflação IPCA (IBGE) com a data inicial em 01/2016 e a data final em 01/2023. O resultado foi de R$ 73.168,62.

Desta forma, dividindo o custo anual por 12 para encontrar o custo mensal de um ano da UnB, temos que o custo mensal é de R$ 6097,38. E considerando que em média um aluno de graduação da Universidade de Brasília cursa 7 disciplinas por ano, o custo de um aluno por disciplina é de R$ 871,06. Uma vez que a discplina de EPS possui 60 horas de aula, o custo de um aluno por hora é de R$ 14,52.

Considerando que cada membro do grupo irá trabalhar em média 40 horas por mês no projeto, e que o o projeto tem duração de 4 meses e possui 15 membros, em que o custo por hora para cada membro seja de R$ 14,52, é estimado que o custo total no desenvolvimento do projeto seja aproximadamente R$ 34848,00.

## Custo de internet

Considerando que todos os integrantes do time possuem internet banda larga, de pelo menos 250 MBPS, os valores estimados para Brasília foram de:

| Mensal por aluno | Mensal por grupo | 4 meses    |
| ---------------- | ---------------- | ---------- |
| R$ 100.00        | R$ 1500.00       | R$ 6000.00 |

## Custo de água

| Mensal por aluno | Mensal por grupo | 4 meses    |
| ---------------- | ---------------- | ---------- |
| R$ 50.00         | R$ 750.00        | R$ 3000.00 |

## Custo de Energia

| Mensal por aluno | Mensal por grupo | 4 meses    |
| ---------------- | ---------------- | ---------- |
| R$ 80.00         | R$ 1200.00       | R$ 4800.00 |

## Custo de equipamentos

Para realizar a estimativa de custo de equipamentos, foi considerando que o único equipamento necessário para o desenvolvimento do projeto é um computador com as seguintes especificações:

-   Deve possuir um processador Intel Core i5 da 11ª geração ou superior;
-   Deve possuir 8 GB de memória RAM ou superior;
-   Deve possui SSD de 256 GB ou superior;

Com base nessas especificações, foi feita uma pesquisa de preços de computadores com essas especificações e foi definido que o computador que melhor atende a essas especificações é o: Notebook Lenovo IdeaPad 3i i5 - Notebook-1135G7 8GB 256GB SSD Placa de Vídeo Intel Iris Xe Windows 11 15.6" - 82MD0007BR por R$ 3.079,99.

Deste modo, o custo total de aquisição é o custo de 15 computadores, que é de R$ 46.199,85.

## Custo pré-desenvolvimento

Antes de inicializar o desenvolvimento, diversas reuniões e atividades foram realizadas com a finalidade de definição de escopo e planejamento do projeto. Para isso, foi necessário realizar diversas reuniões e atividades, que foram listadas a seguir:

| Atividade      | Quantidade de alunos | Quantidades de reuniões | Tempo médio (horas) | Quantidade de horas na atividades (por pessoa) | Custo total |
| -------------- | -------------------- | ----------------------- | ------------------- | ---------------------------------------------- | ----------- |
| Lean Inception | 15                   | 10                      | 3                   | 30                                             | R$ 6534,00  |
| Prototipagem   | 3                    | -                       | -                   | 50                                             | R$ 2178,00  |

## EVM

Earned Value Management (EVM), também conhecido como Gerenciamento do Valor Agregado, é uma técnica de gerenciamento de projetos amplamente utilizada para medir o desempenho real de um projeto em relação ao planejamento inicial. O EVM integra informações sobre custo, cronograma e desempenho técnico para fornecer uma visão abrangente do progresso do projeto.

Para o cálculo do EVM, foram utilizadas as seguintes fórmulas:


 ![EVM](../assets/images/formulas_evm.png "FONTE: (SULAIMAN; BARTON; BLACKBURN, 2006)")


O sumário do valor planejado pode ser visto na tabela a seguir:

<iframe width="682" height="350" frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ9aH_sbUtjvi6iSp35Ep8GMWbRttoiq_Cjk99cBJXHsqxGoxNkF2O8U8OQF_DMo26PtAedLWFKLXWe/pubhtml?gid=1015652774&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

Para analisar os dados completos do projeto pode-se analisar nesse [link](https://docs.google.com/spreadsheets/d/1yooiI0do8aH4Cppv79ZBRAlqe535To_shebGenEKe90/edit?usp=sharing)

## Referência

[1] Portas abertas ao cidadão. Dísponivel em: https://www.correiobraziliense.com.br/app/noticia/eu-estudante/ensino_ensinosuperior/2015/03/05/ensino_ensinosuperior_interna,474102/portas-abertas-ao-cidadao.shtml. Acesso em 04/04/2023.

[2] Planos de Internet Residencial. Disponivel em: https://planos.minhaconexao.com.br/internet-banda-larga/internet-residencial. Acesso em 04/04/2023.

[3] Notebook Lenovo. Disponível em: hhttps://www.lenovo.com/br/pt/laptops/ideapad/serie-300/IdeaPad-3-15ITL6/p/82MD0007BR. Acesso em 04/04/2023.

[4]Tabela de tarifas de energia elétrica. Disponível em: https://www.neoenergiabrasilia.com.br/comercial-e-industrial/Documents/01_nbsb_tarifas_energia_eletrica_grupoB_nov_2022_reh3134.pdf. Acesso em 04/04/2023.

[5] RAIO-X DO CUSTO POR ALUNO NAS UNIVERSIDADES FEDERAIS. Disponível em: https://infograficos.oglobo.globo.com/brasil/raio-x-do-custo-por-aluno-nas-universidades-federais.html. Acesso em 04/04/2023.

[6] SULAIMAN, T.; BARTON, B.; BLACKBURN, T. AgileEVM - Earned Value Management in Scrum Projects. AGILE 2006 (AGILE’06). Anais... Em: AGILE 2006 (AGILE’06). Minneapolis, MN, USA: IEEE, 2006. Disponível em: <http://ieeexplore.ieee.org/document/1667558/>. Acesso em: 9 jul. 2023

[7] VisualEasy 2022-1, Documentação, EVM. Dísponivel em: https://fga-eps-mds.github.io/2022-1-Visualeasy-Doc/documentacao/evm/. Acesso em 04/04/2023.
