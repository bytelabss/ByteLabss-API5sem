# Definition of Ready (DoR) para as User Stories da Sprint 2

## US06: Eu, como analista de RH, quero poder gerar relatórios manualmente, em PDF e em Excel, para que eu possoa estudar periodos específicos dos processos seletivos e tomas novas decisões de forma embasada
- **Requisitos Funcionais**
  - Endpoint ou funcionalidade que permita a geração manual de relatórios em PDF e Excel.
  - Critérios definidos para o que deve constar nos relatórios (ex.: dados de processos seletivos, contratações, etc.).
  - Interface para seleção do período específico dos processos seletivos que será incluído no relatório.
- **Requisitos Não Funcionais**
  - Layout dos relatórios bem definido e padronizado.
- **Critérios de Aceitação**
  - O usuário deve ser capaz de selecionar o período e os dados desejados e gerar relatórios em formato PDF e Excel.
- **Dependências**
  - Banco de dados atualizado e com dados completos.
  - Integração com bibliotecas de geração de PDF e Excel (ex.: Apache POI, iText).

## US07: Eu, como analista de RH, quero poder receber relatórios automáticos sazonais, em PDF e em Excel, para que eu possoa estudar periodos específicos dos processos seletivos e tomas novas decisões de forma embasada
- **Requisitos Funcionais**
  - Pipeline configurado para a geração automática de relatórios sazonais (ex.: trimestral, semestral).
  - Critérios definidos para o conteúdo dos relatórios automáticos.
  - Mecanismo de envio de relatórios automáticos por notificação.
- **Requisitos Não Funcionais**
  - A execução automática de relatórios deve ser agendada com base em intervalos definidos.
  - Garantir que o sistema possa gerar os relatórios sem interferir na performance geral.
- **Critérios de Aceitação**
  - O sistema deve gerar e enviar relatórios automáticos em PDF e Excel para os analistas de RH de forma periódica.
  - Relatórios devem ser completos e sem falhas de formatação.
- **Dependências**
  - Template de relatórios automáticos finalizado.
