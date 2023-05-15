# Documento de Arquitetura

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|15/05/2023|1.0|Criação do documento| Paulo Batista e Igor |


## Introdução

<p align = "justify"> &emsp;&emsp; A finalidade este documento é apresentar de forma geral os aspectos mais significativos da arquitetura do projeto Measure SoftwareGram. Neste documento são apresentados os seguintes pontos, os serviços e as tecnologias utilizadas em cada parte do projeto, modelo de arquitetura seguido atualmente e as motivações que guiam essas escolhas. </p>

<p align = "justify"> &emsp;&emsp; Através desse documento, é possível obter um melhor entendimento da arquitetura do projeto, permitindo ao leitor a compreensão do funcionamento do sistema e as abordagens utilizadas para o seu desenvolvimento.</p>

### Visão Geral

* Introdução: Apresenta uma visão geral sobre o conteúdo dessa documentação;
* Representação de Arquitetura: Descreve os serviços, tecnologias e os padrões de arquitetura utilizados e informa as razões que motivaram tais escolhas;
* Metas e Restrições de Arquitetura: Fala sobre objetivos que buscam ser alcançados dentro da arquitetura escolhida;
* Referências: Emprega as fontes utilizadas nas pesquisas para relacionar as publicações que foram consultadas e citadas.

## Representação de Arquitetura

### Linguagens

- **Python**: Uma linguagem de programação de alto nível que permite a estabilidade do projeto com alta escalabilidade. Ele pode ser usado para criar interfaces simples em terminais de computadores.

- **JavaScript/TypeScript**: Uma linguagem de programação de alto nível que é interpretada de forma estruturada. JavaScript é uma das três principais tecnologias da World Wide Web, junto com HTML e CSS. Usaremos TypeScript, que estende o JavaScript com digitação estática opcional.

#### Tecnologias

- **React**: Um framework em JavaScript que suporta TypeScript, desenvolvida pelo Facebook. Proporciona o desenvolvimento de sites com mais facilidade e rapidez do que os tradicionais HTML, CSS e JavaScript.

- **Next.js**: Uma estrutura da Web de desenvolvimento front-end React de código aberto criada pela Vercel, que permite geração de sites estáticos para aplicativos da Web baseados em React e recursos como renderização do lado do servidor.

- **Django**: um Framework open source baseado em Python. Altamente escalável e robusto, foi projetado para resolver problemas comuns durante o desenvolvimento web, disponibilizando diversas facilidades como: ORM, autenticação, rotas, e <i>migrations</i> [<a href=./#referencia>1</a>].

- **Jupyter Notebook**: Uma ferramenta open source para criar e editar Notebooks. Sendo uma tecnologia baseada em Python.

- **PyPI**: O Python Package Index [<a href=./#referencia>2</a>] é um repositório para armazenar pacotes de código escritos na linguagem de programação **Python**.

#### Banco de dados

- **PostgreSQL**: Um sistema de gerenciamento de banco de dados relacional de software livre. Tem a capacidade de gerir os dados de forma organizada e eficaz.

#### Serviços

**CLI** Abreviação de "interface de linha de comando". Este é um programa que permite aos usuários criar comandos para funções específicas passando instruções para o computador.

**Frontend Web** Esta é a aplicação interface web que permite aos usuários analisar e acompanhar os produtos pelo navegador. 

**Service** Este é o programa responsável por se comunicar com a aplicação `Frontend Web` e fornecer todos os dados necessários para a aplicação web.


## Diagrama arquitetural

## Diagrama de Pacotes

## Metas e Restrições de Arquitetura

### Metas

<center>

|     Metas      |                                                                           |
| :------------: | :-----------------------------------------------------------------------: |
| Escalabilidade | A aplicação deverá ser escalável                                          |
|   Segurança    | A aplicação deverá tratar de forma segura os dados sensíveis dos usuários |
|     Deploy     | A aplicação deverá possuir deploy automatizado                            |
|     Usabilidade     | A aplicação deverá ter uma boa usabilidade para o usuário                           |

</center>

### Restrições

| Restrições    |                                                                                                                  |
| :-----------: | :--------------------------------------------------------------------------------------------------------------: |
| Conectividade | Para utilização do <b>Frontend</b> é preciso ter conexão com a internet. Para utilizar o <b>CLI</b> isso já não é mais necessário                                       |
|  Plataforma   | A aplicação possuirá suporte WEB e para linha de comando                                                         |
|    Público    | A aplicação será desenvolvida com foco em empresas de tecnologia e desenvolvedores                               |
|   Linguagem   | O inglês foi escolhido por conta das integrações com plataformas que já utilizam essa linguagem                  |
|    Equipe     | A equipe possui 15 integrantes                                                                                   |
|     Prazo     | O prazo é até o final do semestre 2023-2 (25/07/2023) da Universidade de Brasília                                |

## Referências

> [1] ROVEDA, Ugo; <b>O que é Django, para que serve e como usar este framework</b>. Disponível em: < [https://kenzie.com.br/blog/django](https://kenzie.com.br/blog/django) > Acesso em: 28 de Novembro de 2022

> [2] <b>Python Package Index Org</b>. Disponível em: < [https://pypi.org/.](https://pypi.org/.) > Acesso em: 28 de Novembro de 2022

> Arquitetura do Sistema (MeasureSoftGram-2022-2). Disponível em: < [https://fga-eps-mds.github.io/2022-2-MeasureSoftGram-Doc/plano-monitoramento/documento_de_arquitetura](https://fga-eps-mds.github.io/2022-2-MeasureSoftGram-Doc/plano-monitoramento/documento_de_arquitetura/) > Acesso em: 15 de Maio de 2023