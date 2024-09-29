# Definition of Ready (DoR) para as User Stories da Sprint 1

## US01: Eu, como gerente de RH, quero visualizar o tempo médio de contratações realizadas para cada processo seletivo em um período determinado, para que avaliar a eficiência dos processos de recrutamento e identificar áreas de melhoria

- **Requisitos Funcionais**

  - API e endpoints prontos para buscar os dados de processos seletivos e contratações.
  - Dados de processo seletivo e contratações disponíveis e consistentes no banco de dados.
  - Critérios claros para o cálculo do tempo médio de contratação.

- **Requisitos Não Funcionais**

  - Interface gráfica para exibir o gráfico de tempos médios.

- **Critérios de Aceitação**

  - O usuário deve poder selecionar o intervalo de tempo a ser analisado.
  - O tempo médio deve ser exibido de forma clara e precisa para cada processo seletivo.

- **Dependências**

  - Banco de dados populado com dados de processos seletivos e contratações.
  - Design do gráfico de visualização de tempos definido.

## US02: Eu, como analista de RH, quero visualizar o tempo médio de contratações realizadas para cada vaga em um período determinado,para que eu possa entender o desempenho das vagas individuais e melhorar a gestão de vagas futuras

- **Requisitos Funcionais**

  - API e endpoints prontos para buscar os dados de contratações por vaga.
  - Critérios para o cálculo do tempo médio por vaga definidos e validados.

- **Requisitos Não Funcionais**

  - Interface de fácil navegação para a seleção da vaga e exibição dos resultados.

- **Critérios de Aceitação**

  - O sistema deve permitir a seleção de vagas específicas e exibir o tempo médio de contratação para cada uma.

- **Dependências**

  - Banco de dados populado com dados de vagas e contratações.
  - Design do gráfico de visualização de tempos definido.

## US03: Eu, como gerente de RH, quero visualizar a quantidade de contratações realizadas por cada processo seletivo em um período específico, para que eu possa monitorar o progresso e a eficiência dos processos seletivos

- **Requisitos Funcionais**

  - Endpoints de API para busca de dados sobre o número de contratações realizadas em cada processo seletivo.
  - Definir intervalos de tempo para a consulta.

- **Requisitos Não Funcionais**

  - Interface gráfica para visualizar o número de contratações por processo.

- **Critérios de Aceitação**

  - O sistema deve exibir a quantidade de contratações realizadas por cada processo seletivo no período selecionado.

- **Dependências**

  - Disponibilidade de dados de contratações no banco de dados.
  - Design do gráfico de visualização de contratações por processo definido.

## US04: Eu, como analista de RH, quero visualizar a quantidade de contratações realizadas por cada participante de RH, em um período específico, para que eu possa avaliar a produtividade e desempenho individual dos recrutadores

- **Requisitos Funcionais**

  - API para busca de dados de participantes do RH e suas respectivas contratações.
  - Dados claros de quem participou de cada contratação.

- **Requisitos Não Funcionais**

  - Interface que permita a seleção do participante do RH e exiba os resultados de forma clara.

- **Critérios de Aceitação**

  - O usuário deve poder ver o número de contratações realizadas por cada participante de RH no período escolhido.

- **Dependências**

  - Dados de participantes de RH, processos seletivos e contratações disponíveis no banco de dados.
  - Design do gráfico de visualização de contratações por participante definido.

## US05: Eu, como gerente de RH, quero um processo de ETL que extraia, transforme e carregue os dados de processos seletivos, vagas, participantes de RH, contratações e tempos envolvidos, para que eu possa consolidar essas informações em um data warehouse e realizar análises mais eficazes para melhorar as decisões de recrutamento

- **Requisitos Funcionais**

  - Pipeline de ETL definido e funcionando para extrair, transformar e carregar dados relacionados a processos seletivos, vagas e contratações.
  - Configuração do Data Warehouse no MySQL.

- **Requisitos Não Funcionais**

  - Tempo de execução do ETL dentro do esperado.

- **Critérios de Aceitação**

  - Dados de processos seletivos, vagas e contratações devem estar disponíveis para consulta no Data Warehouse após a execução do ETL.

- **Dependências**

  - Modelagem de dados validada e disponível.
  - Arquitetura de ETL validada e integrada com o banco de dados.
  - Spark e Spring Boot configurados para o processo ETL.
