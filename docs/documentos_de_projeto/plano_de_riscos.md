# Planejamento de Gerenciamento de Riscos


## Histórico de versão

|        Data        |       Autor       |                  Descrição da revisão                  | Versão |
| :----------------: | :---------------: | :----------------------------------------------------: | :----: |
| 26 de Maio de 2023  | **Davi Matheus**  |                Inclusão da documentação                | 1.0.0  |


## Objetivo do documento

O plano de gerenciamento de riscos tem como objetivo identificar, analisar e planejar ações para lidar com possíveis riscos relacionados ao desenvolvimento do projeto. Com base nessa análise, serão implementadas medidas preventivas, de mitigação, eliminação ou aceitação dos riscos identificados. A responsabilidade pelo gerenciamento dos riscos será atribuída ao Scrum Master ao longo das sprints, garantindo que o processo seja acompanhado de forma contínua e eficiente.

##  Estrutura Analítica dos Riscos (EAR)

A estrutura analítica dos ricos, é uma ferramenta na qual são agrupados os riscos e classifica-os em categorias. Essas categorias são divididas de forma hieráquica destrinchando as possíveis fontes de risco.


## Análise quantitativa


### Probabilidade

|Probabilidade|Intervalo|Peso|
|:----:|:-----:|:------:|
|**Muito Baixa**|0 a 10|1|
|**Baixa**| 11 a 30|2|
|**Média**| 31 a 50|3|
|**Alta**| 51 a 65|4|
|**Muito Alta**| 65 a 100| 5|

### Impacto

|Impacto|Descrição|Peso|
|:----:|:-----:|:------:|
|**Muito Baixo**|Impacto pouco expressivo no desenvolvimento do projeto|1|
|**Baixo**| Pouco impacto no desenvolvimento do projeto|2|
|**Médio**| Possui certo impacto porém é facilmente recuperado|3|
|**Alto**| Há grande impacto no desenvolvimento do projeto|4|
|**Muito Alto**| O impacto inviabiliza o projeto| 5|

###  Prioridade

 Se baseando com os valores do impacto e de probabilidade calcula-se a prioridade dos riscos. O que determina a urgência com que medidas devem ser tomadas para mitigar ou resolver um risco que pode impedir o projeto.

|Probabilidade/Impacto|Muito Baixa|Baixo|Média|Alta|Muito Alta|
|:----:|:-----:|:------:|:------:|:------:|:------:|
|**Muito Baixa**|1|2|	3|	4|	5|
|**Baixa**| 2|4	|6	|8	|10|
|**Média**| 3|6|	9	|12|	15|
|**Alta**| 4| 8	|12	|16|	20|
|**Muito Alta**| 5| 	10|	15	|20	|25|

#### Valor de prioridade

|Prioridade|Intervalo|
|:----:|:-----:|
|Muito Baixo|1 a 5|
|Baixo| 6 a 10|
|Médio| 11  a 15|
|Alto| 16 a 20|
|Muito Alto| 21 a 25 |

## Identificação dos riscos

A forma utilizada para a identifação de riscos do projeto foi a análise de premissas e brainstorming - elaborar uma lista de riscos do projeto, promovendo a identificação de ameaças e oportunidades.

* Os riscos podem ser classificados de acordo com várias categorias:

        Técnico, que são riscos associados à tecnologia, requisitos e qualidade.
        Externo, são riscos relativos ao cliente, mercado ou ambiente.
        Organizacional, são relacioandos à priorização e recursos do projeto.
        Gerência, são relativos à estimativa, planejamento, controle e comunicação.


##  Riscos levantados

###  Riscos técnicos
|Risco| Descrição|	Ação Preventiva|	Ação Reativa	|Probabilidade	|Impacto|	Prioridade|
|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
| R01 | Falta de conhecimento com as tecnologias de desenvolvimento. |  Treinamentos e pareamentos efetivos	. | 4 | 5  | 20 | 
| R02 | Não cumprimento dos padrões de qualidade | Monitoramento dos indíces de qualidade	 |Implementar melhorias que atendam os padrões de qualidade | 8 | 5 | 25 | 
| R03 | Alteração de Tecnologias do projeto |  Clareza no escopo do projeto | Planejamento de sprints de modo que possíveis alterações não afetem o desenvolvimento do projeto. | 2 | 2 | 10 |
| R04 | Defeito no equipamento de algum integrante do grupo | Comunicação clara e transparente entre todos os membros do grupo. | Realocação de integrantes em diferentes funções |  1 | 4 | 10 | 
| R05 | Conflito entre entregas da sprint e de tarefas de outras disciplinas | Planejamento das entregas	| Redefinição do planejamento das tarefas | 2 | 5 | 10 | 

###  Riscos externos
|Risco| Descrição|	Ação Preventiva|	Ação Reativa	|Probabilidade	|Impacto|	Prioridade|
|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
| R06 | Problemas na comunicação com o cliente | Clareza nas funcionalidades que serão entregues ao cliente | Reuniões para definir de forma concisa escopo e features. | 4 | 3 | 20 | 
| R07 | Alguns dos membros contrair uma doença ou ficar indisponível | nenhuma ação preventiva	 | Redefinição do planejamento| 5 | 2 | 10 | 

### Riscos organizacionais
|Risco| Descrição|	Ação Preventiva|	Ação Reativa	|Probabilidade	|Impacto|	Prioridade|
|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
| R08 | Dependência entre as atividades| Planejar de forma paralela | Planejar issues de forma que issues não ocorra o excesso de dependências entre as issues | 3 | 3 | 8 | 

###  Riscos de gerência
|Risco| Descrição|	Ação Preventiva|	Ação Reativa	|Probabilidade	|Impacto|	Prioridade|
|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
| R09 | Alterar escopo | Reuniões para descrever de forma clara os requisitos do projeto. | Dailys para atualizações de todos os integrantes sobre possíveis mudanças e melhor planejamento. | 3 | 3 | 20 |  
| R10 | Falta de comunicação entre os integrantes do grupo |  Estabelecer ferramentas de comunição entre os membros, realizações de dailys e assuntos pontuais por whatsapp/telegram | Sempre deixar principais pontos das sprints em ambientes que os integrantes acessam constantemente. | 3 | 4 | 12 | 
| R11 | Desistência de algum membro da equipe. | Dividir de forma igualitária as issues do projeto.  | Adequar os horários e realocar as tarefas entre os membros sem sobrecarregar nenhum membro. | 3 | 4 | 15 | 
| R12 | Baixa produtividade dos integrantes do grupo |  Motivação da equipe através de dailys | Realizar checkpoints de saúde mental com os integrantes do grupo, ou elaboração de gamificação | 3 | 4 | 10 |
| R13 | Conflitos de horários disponíveis para os integrantes. |  Montar uma grade com os horários disponíveis de cada membro. | Os pontos das sprints deve ser divido visando a carga horária compatível com o que os integrantes terão na semana, sendo maleável a mudanças(desde que o membro notifique o grupo no planejamento da sprint).| 4 | 3 | 10 | 


## Referências

> [1] </b>FREITAS, Renata. Aplique o Plano de Gerenciamento de Riscos no seu negócio.</b> Disponível em: https://www.glicfas.com.br/plano-de-gerenciamento-de-riscos/. Acesso em 25 maio de 2023

