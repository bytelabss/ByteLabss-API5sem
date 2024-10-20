<span id="topo">

# DataViz - ByteLabss

<p align="center">
        <img src="https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D" alt="Vue.js">
        <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
        <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" alt="Spring">
        <img src="https://img.shields.io/badge/spark-%2523ED8B00.svg?style=for-the-badge&logo=apache%20spark&color=white" alt="Apache Spark">
        <img src="https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white" alt="Jira">
        <img src="https://img.shields.io/badge/mysql-%25230A0FFF.svg?style=for-the-badge&logo=mysql&logoColor=white&color=blue" alt="MySQL">
        <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

<h2 align="right">
        <img src="https://img.shields.io/badge/status-ongoing-blue?style=for-the-badge&logo=appveyor" alt="Status: Ongoing">   
        <img src="https://img.shields.io/badge/sprint-2-blue?style=for-the-badge&logo=appveyor" alt="Second= sprint">
</h2>

<span id="indice">

## Índice 📎

- [Índice 📎](#indice)
- [Sobre 📚](#sobre)
- [Backlog do Produto 📍](#backlog-do-produto)
- [Cronograma de Entrega 🗓](#cronograma-de-entrega)
- [Equipe 👩‍💻👨‍💻](#equipe)

<span id="sobre">

## Sobre 📚

<p align="center">
        <a href="#problema">O Problema 🤔</a> | 
        <a href="#objetivo">Objetivo do Projeto 🎯</a> | 
        <a href="#requisitos">Requisitos Funcionais do Projeto 📝</a> | 
        <a href="#desenvolvimento"> Regras de Desenvolvimento 📏</a>
</p>

<p align="justify">
A projeto de DataViz do ByteLabs é resultado do Aprendizado por Projetos Integrados da Faculdade de Tecnologia do Estado de São Paulo (FATEC) de São José dos Campos. A cada semestre, os alunos são desafiados a desenvolver um projeto de software, com base em um problema real apresentado por uma empresa parceira. O projeto é desenvolvido em sprints, com entregas parciais e um produto final que atenda às necessidades do cliente. O cliente parceiro deste semestre é a empresa <a href="https://pro4tech.com.br/">Pro4Tech</a>.
</p>

<span id="problema">

### O Problema 🤔

<p align="justify">
O problema apresentado pela empresa <a href="https://pro4tech.com.br/">Pro4Tech</a> está relacionado à eficiência e à eficácia no processo de recrutamento e seleção de pessoal. Atualmente, a empresa busca otimizar a maneira como os dados de recrutamento são coletados, visualizados e analisados. A "dor" central do cliente inclui a necessidade de centralizar e visualizar dados dispersos, permitir uma tomada de decisão estratégica, gerar relatórios personalizados e automatizar processos manuais, além de possibilitar a integração de dados de diferentes fontes.
</p>

<span id="objetivo">

### Objetivo do Projeto 🎯

<p align="justify">
O projeto trata de uma plataforma focada na análise de dados de recrutamento e seleção. Tem como objetivo oferecer insights valiosos como:
</p>

- <p align="justify">Métricas de eficiência no recrutamento (ex. tempo médio de contratação, quantidade de contratações por processo seletivo).</p>
- <p align="justify">Identificação de padrões e tendências para otimizar o processo de seleção.</p>
- <p align="justify">Personalização de relatórios conforme as necessidades específicas dos gestores.</p>

<p align="justify">
A plataforma é voltada para gerentes de RH e analistas, sem funcionalidades de CRUD sobre os dados operacionais, exceto por permissões, dashboards e usuários.
</p>

<span id="requisitos">

### Requisitos Funcionais do Projeto 📝

1. [Dashboard Interativo em Tempo Real](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=1.%20Dashboard%20Interativo%20em%20Tempo%20Real%3A)
2. [Personalização de Relatórios](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=2.%20Personaliza%C3%A7%C3%A3o%20de%20Relat%C3%B3rios%3A)
3. [Geração Automática de Relatórios](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=3.%20Gera%C3%A7%C3%A3o%20Autom%C3%A1tica%20de%20Relat%C3%B3rios%3A)
4. [Controle de Acesso e Permissões](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=4.%20Controle%20de%20Acesso%20e%20Permiss%C3%B5es%3A)
5. [Análises Predefinidas e Configuração de Alertas](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=5.%20An%C3%A1lises%20Predefinidas%20e%20Configura%C3%A7%C3%A3o%20de%20Alertas%3A)
6. [Compartilhamento de Relatórios](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=6.%20Compartilhamento%20de%20Relat%C3%B3rios%3A)
7. [Importação de Dados](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=7.%20Importa%C3%A7%C3%A3o%20de%20Dados%3A)

<span id="desenvolvimento">

### Requisitos Não funcionais do Projeto

1. [Manual do Usuário](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=1.%20Manual%20de%20Usu%C3%A1rio%20e%20Guia%20de%20Instala%C3%A7%C3%A3o%3A)
2. [Guia de instalação](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=1.%20Manual%20de%20Usu%C3%A1rio%20e%20Guia%20de%20Instala%C3%A7%C3%A3o%3A)
3. [Modelagem do Banco de Dados](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=Modelagem%20de%20Banco%20de%20Dados%20Eficiente%3A)
4. [Implementação de protocolos de segurança](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Solu%C3%A7%C3%A3o-dos-Requisitos-para-a-plataforma-de-DataViz#2-requisitos-funcionais:~:text=2.-,Seguran%C3%A7a%20de%20Dados%3A,-Implementa%C3%A7%C3%A3o%20de%20protocolos)

### Regras de Desenvolvimento 📏

- [Estratégia de Branches](https://github.com/bytelabss#-estrat%C3%A9gia-de-branches)
- [Estratégia de Commits](https://github.com/bytelabss#%EF%B8%8F-estrat%C3%A9gia-de-commits)

### Regras de DevOps 📏

[Regras de DevOps](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Regras-de-DevOps)

<span id="backlog-do-produto">

## Backlog do Produto 📍

<body>
        <div align="center">
                <table>
                        <thead>
                                <th>Ranking</th>
                                <th>Requisito <b> funcional</b></th>
                                <th>User Story</th>
                                <th>Sprint</th>
                        </thead>
                        <tbody>
                                <tr>
                                        <td>US01</td>
                                        <td>1</td>
                                        <td align="justify">Eu, como gerente de RH, quero visualizar o tempo médio de contratações realizadas para cada processo seletivo em um período determinado, para poder avaliar a eficiência dos processos de recrutamento e identificar áreas de melhoria</td>
                                        <td>1</td>
                                </tr>
                                <tr>
                                        <td>US02</td>
                                        <td>1</td>
                                        <td align="justify">Eu, como analista de RH, quero visualizar o tempo médio de contratações realizadas para cada vaga em um período determinado, para que eu possa entender o desempenho das vagas individuais e melhorar a gestão de vagas futuras</td>
                                        <td>1</td>
                                </tr>
                                <tr>
                                        <td>US03</td>
                                        <td>1</td>
                                        <td align="justify">Eu, como gerente de RH, quero visualizar a quantidade de contratações realizadas por cada processo seletivo em um período específico, para que eu possa monitorar o progresso e a eficiência dos processos seletivos</td>
                                        <td>1</td>
                                </tr>
                                <tr>
                                        <td>US04</td>
                                        <td>1</td>
                                        <td align="justify">Eu, como analista de RH, quero visualizar a quantidade de contratações realizadas por cada participante de RH, em um período específico, para que eu possa avaliar a produtividade e desempenho individual dos recrutadores</td>
                                        <td>1</td>
                                </tr>
                                <tr>
                                        <td>US05</td>
                                        <td>7</td>
                                        <td align="justify">Eu, como gerente de RH, quero um processo de ETL que extraia, transforme e carregue os dados de processos seletivos, vagas, participantes de RH, contratações e tempos envolvidos, para que eu possa consolidar essas informações em um data warehouse e realizar análises mais eficazes para melhorar as decisões de recrutamento</td>
                                        <td>1</td>
                                </tr>
                                <tr>
                                        <td>US06</td>
                                        <td>3</td>
                                        <td align="justify">Eu, como analista de RH, quero poder gerar relatórios manualmente, em PDF e em Excel, para que eu possoa estudar periodos específicos dos processos seletivos e tomas novas decisões de forma embasada</td>
                                        <td>2</td>
                                </tr>
                                <tr>
                                        <td>US07</td>
                                        <td>3</td>
                                        <td align="justify">Eu, como analista de RH, quero poder receber relatórios automáticos sazonais, em PDF e em Excel, para que eu possa estudar períodos específicos dos processos seletivos e tomar novas decisões de forma embasada</td>
                                        <td>2</td>
                                </tr>
                                <tr>
                                        <td>US08</td>
                                        <td>1</td>
                                        <td align="justify">Eu, como analista de RH, quero visualizar a pontuação de cada candidato por critério de avaliação, para cada vaga, para que eu possa avaliar objetivamente o desempenho dos candidatos e tomar decisões mais informadas no processo de contratação</td>
                                        <td>2</td>
                                </tr>
                                <tr>
                                        <td>US09</td>
                                        <td>5</td>
                                        <td align="justify">Eu, como analista de RH, quero receber alarmes na tela sempre que um dashboard padrão sair do ideal, para que eu possa fazer manobras estratégicas quando necessário</td>
                                        <td>3</td>
                                </tr>
                                <tr>
                                        <td>US10</td>
                                        <td>5</td>
                                        <td align="justify">Eu, como gerente de RH, quero receber alarmes na tela sempre que um dashboard padrão sair do ideal, para que eu possa fazer manobras estratégicas quando necessário</td>
                                        <td>3</td>
                                </tr>
                                <tr>
                                        <td>US11</td>
                                        <td>2</td>
                                        <td align="justify">Eu, como gerente de RH, quero poder criar e salvar consultas personalizadas na base de dados, para poder facilitar meu acesso</td>
                                        <td>3</td>
                                </tr>
                                <tr>
                                        <td>US12</td>
                                        <td>6</td>
                                        <td align="justify">Eu, como analista de RH, quero poder compartilhar minhas consultas personalizadas, para poder auxiliar outros usuários em suas atividades</td>
                                        <td>4</td>
                                </tr>
                                <tr>
                                        <td>US13</td>
                                        <td>6</td>
                                        <td align="justify">Eu, como gerente de RH, quero poder compartilhar minhas consultas personalizadas, para poder auxiliar outros em suas atividades</td>
                                        <td>4</td>
                                </tr>
                                <tr>
                                        <td>US14</td>
                                        <td>4</td>
                                        <td align="justify">Eu, como gerente de RH, quero poder cadastrar os novos membros de minha equipe, para que eles possam acessar o sistema</td>
                                        <td>4</td>
                                </tr>
                        </tbody>
                </table>
        </div>
</body>

<span id="cronograma-de-entrega">

## Cronograma de Entrega 🗓

| *Sprints*  | *Cronograma*             | 
| ---------- | ----------               | 
|  [Sprint 1](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Sprint-1)  |  09/09 a 29/09           | 
|  [Sprint 2](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Sprint-2)  |  30/09 a 20/10           | 
|  [Sprint 3](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Sprint-3)  |  21/10 a 10/11           | 
|  [Sprint 4](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Sprint-4)  |  11/11 a 01/12           |    

<span id="equipe">

## Equipe 👩‍💻👨‍💻

<body>
        <div align="center">
                <table>
                        <thead>
                                <th>Larissa Reis - Scrum Master</th>
                                <th>Willian Caboski - Product Owner</th>
                                <th>Alec Rondel - Developer</th>
                                <th>Antônio Zago - Developer</th>
                                <th>Cauana Dias - Developer</th>
                                <th>Jhonny Dutra - Developer</th>
                                <th>Nicolas Cursino - Developer</th>
                        <thead>
                        <tbody>
                                <tr>
                                        <th>
                                                <a href="https://github.com/larissa-fernanda">
                                                        <img src="https://avatars.githubusercontent.com/u/111530654?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/DankoCaboski">
                                                        <img src="https://avatars.githubusercontent.com/u/109988937?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/aleclr">
                                                        <img src="https://avatars.githubusercontent.com/u/43094055?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/Antonio-Zago">
                                                        <img src="https://avatars.githubusercontent.com/u/80283126?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/Cauana">
                                                        <img src="https://avatars.githubusercontent.com/u/77700346?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/dutrajy">
                                                        <img src="https://avatars.githubusercontent.com/u/122806886?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/nicursino">
                                                        <img src="https://avatars.githubusercontent.com/u/67070670?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                </tr>
                                <tr>
                                        <th>
                                                <a href="https://www.linkedin.com/in/larissa-reis-693568250">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="linkedin.com/in/alecrondel">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/antonio-zago-24230b206">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/cauanadias?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/dutrajy?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/nicolas-magarifuchi-406935184">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                </tr>
                        <tbody>
                </table>
        </div>
</body>

→ [Voltar ao topo](#topo)
