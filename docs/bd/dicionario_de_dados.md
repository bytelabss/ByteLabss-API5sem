# Dataviz Bytelabss
**Database model documentation**  
*Created with Vertabelo.com*

---

## 1. Model details
- **Model name**: Dataviz Bytelabss
- **Version**: 2.4  
- **Database engine**: MySQL  
- **Description**: Versão 1 do modelo estrela do data warehouse do projeto de Dataviz do 5º semestre de Banco de Dados  

---

## 2. Tables  

### 2.1. Table `fato_contratacao`  
**Description**: Tabela para armazenar os fatos contratações  

#### 2.1.1. Columns
| Column name               | Type    | Properties | Description                                                                |
|---------------------------|---------|------------|----------------------------------------------------------------------------|
| `id_participante_rh`      | integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_participante_rh`    |
| `id_processo_seletivo`    | integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_processo_seletivo`  |
| `id_vaga`                 | integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_vaga`               |
| `id_tempo`                | integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_tempo`              |
| `quantidade`              | integer |            | Coluna para armazenar a quantidade do fato referente à ocorrência          |
| `tempo_medio`             | int     |            | Coluna para armazenar o tempo médio do fato                                |

### 2.2. Table `fato_avaliacao`  

#### 2.2.1. Columns
| Column name   | Type    | Properties | Description                                                        |
|---------------|---------|------------|--------------------------------------------------------------------|
| `id_vaga`     | integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_vaga`       |
| `id_tempo`    | integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_tempo`      |
| `id_candidato`| integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_candidato`  |
| `id_criterio` | integer | PK         | Coluna de id gerada para a cada linha da dimensão `dim_criterio`   |
| `pontuacao`   | int     |            | Coluna para armazenar a pontuação do candidato no critério         |

### 2.3. Table `dim_criterio`  
**Description**: Tabela para armazenar as dimensões de Critério  

#### 2.3.1. Columns
| Column name      | Type         | Properties | Description                                               |
|------------------|--------------|------------|-----------------------------------------------------------|
| `id_dim_criterio`| integer      | PK         | Coluna de id gerada para a cada linha da dimensão         |
| `tipo_criterio`  | varchar(255) |            |                                                           |

### 2.4. Table `dim_processo_seletivo`  
**Description**: Tabela para armazenar as dimensões de Processo Seletivo  

#### 2.4.1. Columns
| Column name               | Type         | Properties | Description                                                                                   |
|---------------------------|--------------|------------|-----------------------------------------------------------------------------------------------|
| `id_dim_processo_seletivo`| integer      | PK         | Coluna de id gerada para a cada linha da dimensão                                             |
| `id_processo_seletivo`    | integer      |            | Coluna de id referente ao objeto transformado em dimensão                                     |
| `nome_processo_seletivo`  | varchar(255) |            | Coluna referente ao nome ou título do processo seletivo                                       |
| `descricao`               | varchar(255) |            | Coluna referente à descrição geral do processo seletivo                                       |
| `criado_por`              | varchar(255) |            | Coluna referente ao identificador ou nome da pessoa do RH que criou o processo seletivo       |
| `status`                  | varchar(255) |            | Coluna referente ao status atual (e.g., Aberto, Em Andamento, Fechado) do processo seletivo   |

### 2.5. Table `dim_participante_rh`  
**Description**: Tabela para armazenar as dimensões de Participantes do RH  

#### 2.5.1. Columns
| Column name               | Type         | Properties | Description                                                                                   |
|---------------------------|--------------|------------|-----------------------------------------------------------------------------------------------|
| `id_dim_participante_rh`  | integer      | PK         | Coluna de id gerada para a cada linha da dimensão                                             |
| `id_participante_rh`      | integer      |            | Coluna de id referente ao objeto transformado em dimensão                                     |
| `cargo`                   | varchar(255) |            | Coluna referente ao cargo do participante na equipe de RH (e.g., Recrutador, Gerente de RH)   |
| `feedback_dados`          | varchar(255) |            | Coluna referente ao número de feedbacks fornecidos pelo participante                          |

### 2.6. Table `dim_tempo`  
**Description**: Tabela para armazenar as dimensões de Tempo  

#### 2.6.1. Columns
| Column name   | Type    | Properties | Description                                                        |
|---------------|---------|------------|--------------------------------------------------------------------|
| `id_dim_tempo`| integer | PK         | Coluna de id gerada para a cada linha da dimensão                  |
| `dia`         | integer |            | Coluna referente ao dia do mês (1-31)                              |
| `mes`         | integer |            | Coluna referente ao mês do ano (1-12)                              |
| `ano`         | integer |            | Coluna referente ao ano (YYYY)                                     |
| `trimestre`   | integer |            | Coluna referente ao trimestre do ano (1-4)                         |
| `semestre`    | integer |            | Coluna referente ao semestre do ano (1-2)                          |

### 2.7. Table `dim_vaga`  
**Description**: Tabela para armazenar as dimensões de Vagas  

#### 2.7.1. Columns
| Column name        | Type         | Properties | Description                                                                      |
|--------------------|--------------|------------|----------------------------------------------------------------------------------|
| `id_dim_vaga`      | integer      | PK         | Coluna de id gerada para a cada linha da dimensão                                |
| `id_vaga`          | integer      |            | Coluna de id referente ao objeto transformado em dimensão                        |
| `titulo_vaga`      | varchar(255) |            | Coluna referente ao título ou nome da vaga (e.g., Gerente, Atendente, Suporte)   |
| `numero_posicoes`  | integer      |            | Coluna referente ao número de posições abertas para a vaga                       |
| `requisitos_vaga`  | varchar(255) |            | Coluna referente à lista de requisitos ou qualificações necessárias para a vaga  |
| `status`           | varchar(255) |            | Coluna referente ao status atual da vaga (e.g., Aberta, Fechada, Em Análise)     |

### 2.8. Table `dim_candidato`  
**Description**: Tabela para armazenar as dimensões de Candidato  

#### 2.8.1. Columns
| Column name         | Type         | Properties | Description                                                     |
|---------------------|--------------|------------|-----------------------------------------------------------------|
| `id_dim_candidato`  | integer      | PK         | Coluna de id gerada para a cada linha da dimensão                |
| `id_candidato`      | integer      |            | Coluna de id referente ao objeto transformado em dimensão        |
| `nome_candidato`    | varchar(255) |            | Coluna referente ao nome completo do candidato                   |
| `email_candidato`   | varchar(255) |            | Coluna referente ao email de contato do candidato                |
| `status_candidato`  | varchar(255) |            | Coluna referente ao status atual no processo seletivo (e.g., Em Análise, Entrevista, Contratado, Rejeitado) |
| `potuacao_candidato`| integer      |            | Coluna referente à pontuação do candidato baseada em critérios de avaliação |

---

## 3. References

### 3.1. Reference `Fato_Contratacoes_Dim_Tempo`
- **Tables**: `dim_tempo`, `fato_contratacao`  
- **Columns**: `id_dim_tempo` <-> `id_tempo`  

### 3.2. Reference `Fato_Contratacoes_Dim_ProcessoSeletivo`
- **Tables**: `dim_processo_seletivo`, `fato_contratacao`  
- **Columns**: `id_dim_processo_seletivo` <-> `id_processo_seletivo`  

### 3.3. Reference `Fato_Contratacoes_Dim_ParticipantesRH`
- **Tables**: `dim_participante_rh`, `fato_contratacao`  
- **Columns**: `id_dim_participante_rh` <-> `id_participante_rh`  

### 3.4. Reference `Fato_Contratacoes_Dim_Vagas`
- **Tables**: `dim_vaga`, `fato_contratacao`  
- **Columns**: `id_dim_vaga` <-> `id_vaga`  

### 3.5. Reference `Fato_Avaliacoes_Dim_Vagas`
- **Tables**: `dim_vaga`, `fato_avaliacao`  
- **Columns**: `id_dim_vaga` <-> `id_vaga`  

### 3.6. Reference `Fato_Avaliacoes_Dim_Tempo`
- **Tables**: `dim_tempo`, `fato_avaliacao`  
- **Columns**: `id_dim_tempo` <-> `id_tempo`  

### 3.7. Reference `Fato_Avaliacoes_Dim_Criterios`
- **Tables**: `dim_criterio`, `fato_avaliacao`  
- **Columns**: `id_dim_criterio` <-> `id_criterio`  

### 3.8. Reference `Fato_Avaliacoes_DimCandidatos`
- **Tables**: `dim_candidato`, `fato_avaliacao`  
- **Columns**: `id_dim_candidato` <-> `id_candidato`  
