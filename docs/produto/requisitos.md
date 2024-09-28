# Solução dos Requisitos para a plataforma de DataViz 

## Visão Geral

Esta proposta de solução é voltada para a criação de uma plataforma interativa de DataViz, que permitirá ao setor de Recursos Humanos (RH) e gestores realizar análises estratégicas em processos seletivos e recrutamento. O sistema integrará dados oriundos de uma base fornecida em formato Excel e os transformará em relatórios visuais de fácil interpretação, permitindo a personalização e o compartilhamento de métricas.

## 1. Objetivos do Sistema

O sistema será uma plataforma focada na análise de dados de recrutamento e seleção. Ele oferecerá insights valiosos como:
- Métricas de eficiência no recrutamento (ex. tempo médio de contratação, taxa de retenção de novos funcionários).
- Identificação de padrões e tendências para otimizar o processo de seleção.
- Personalização de relatórios conforme as necessidades específicas dos gestores.

A plataforma é voltada para RH e analistas gestores, sem funcionalidades de CRUD sobre os dados operacionais, exceto por permissões, dashboards e usuários.

## 2. Requisitos Funcionais

**1. Dashboard Interativo em Tempo Real:** Fornecimento de uma visão geral das métricas principais como número de candidatos por vaga, status de processos seletivos, desempenho de recrutadores, etc. Isso permitirá que os usuários monitorem a eficácia dos processos.

**2. Personalização de Relatórios:** Usuários poderão personalizar relatórios com filtros por Departamento, Tipo de Vaga e Localização.

**3. Geração Automática de Relatórios:** Relatórios gerados automaticamente sobre indicadores-chave, como tempo de contratação, taxa de preenchimento de vagas e taxa de conversão de entrevistas em contratações. Exportação em PDF e Excel.

**4. Controle de Acesso e Permissões:** Sistema de controle de acesso com diferentes níveis de permissão, garantindo que apenas usuários autorizados acessem dados sensíveis.

**5. Análises Predefinidas e Configuração de Alertas:** Configuração de KPIs e alertas automáticos para notificar os usuários quando certos limites forem ultrapassados.

**6. Compartilhamento de Relatórios:** Facilidade de compartilhamento de dashboards e relatórios entre equipes.

**7. Importação de Dados:** Importação de dados em formato Excel, permitindo a atualização periódica dos dados de recrutamento.

## 3. Requisitos Não Funcionais

**1. Manual de Usuário e Guia de Instalação:** Instruções detalhadas sobre o uso da plataforma e configuração técnica.

**2. Segurança de Dados:** Implementação de protocolos de segurança robustos, conforme LGPD e GDPR.

**3. Modelagem de Banco de Dados Eficiente:** Armazenamento eficiente e recuperação rápida de grandes volumes de dados.

**4. Interface de Usuário (UI):** Interface seguindo o estilo visual da Pro4Tech.

## 4. Proposta Técnica

### ETL e Data Warehouse
O processo de ETL (Extração, Transformação e Carga) será utilizado para integrar os dados recebidos em formato Excel ao sistema:
- **Extração:** Leitura dos arquivos Excel relacionados a processos seletivos.
- **Transformação:** Limpeza e validação dos dados, tratamento de informações inconsistentes.
- **Carga:** Armazenamento dos dados transformados em um Data Warehouse com modelo Estrela.

### Ferramentas e Tecnologias
- **ETL:** Apache Spark
- **Data Warehouse:** MySQL com modelo estrela
- **Backend:** Spring Boot (Java)
- **Frontend:** Vue.js
- **Segurança:** Spring Security
- **Infraestrutura:** Docker para containerização

## 5. Benefícios Esperados
- **Otimização do Processo de Seleção:** Redução do tempo de contratação.
- **Integração de Dados:** Centralização de fontes de dados em um painel visual único.
- **Melhoria na Tomada de Decisão:** Identificação de padrões para otimização das estratégias de recrutamento.