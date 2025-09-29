# Project Background

Este dashboard foi desenvolvido para os sócios de uma clínica odontológica em Lajeado, Brasil. O objetivo é resolver um desafio comum: a dificuldade em consolidar e analisar a vasta quantidade de dados de desempenho da clínica. Utilizando um conjunto de dados real de consultas, procedimentos, receita e aquisição de pacientes, este projeto oferece uma interface fácil de usar para explorar tendências operacionais e financeiras, otimizando a tomada de decisões estratégicas e impulsionando o crescimento da clínica.

## Habilidades Demonstradas

  - **Transformação de Dados (ETL) com Power Query:**: Limpeza, modelagem e preparação de dados brutos da clínica para análise, incluindo o tratamento de valores nulos/em branco e a alteração de tipos de dados.
  - **Medidas DAX**: Criação de medidas explícitas para insights e KPIs cruciais, como a Taxa de Conversão (%) de consultas iniciais para pacientes tratados, e a utilização de medidas implícitas para agregações básicas (somas, contagens) presentes nos visuais.
  - **Gráficos Principais:**:  Uso de Gráficos de Linha para rastrear tendências ao longo do tempo (Receita, Novos Pacientes). Utilização de Gráficos de Colunas e Barras para comparar volumes (Procedimentos por Ano, Canais de Aquisição, Contribuição por Especialidade).
  - **Indicadores e Tabelas KPI:** Emprego de Cards para exibir métricas-chave e resumos importantes (Receita Total, Pacientes Atendidos, Taxa de Conversão, Procedimentos Executados).
  - **Design do Painel:** Desenvolvimento de um layout intuitivo e visualmente atraente, focado em clareza e facilidade de leitura para os gestores da clínica. Organização visual dos elementos para apresentar informações-chave de forma hierárquica e coerente.
  - **Relatórios Interativos:** Segmentações de Dados (Slicers) para filtrar dinamicamente os dados por período (ex: ano em gráficos de tendência) e outras dimensões. Capacidade de interagir com os visuais para obter informações detalhadas.
  - **Botões e Marcadores:** Para alternar entre páginas.

## Fonte de Dados

TOs dados utilizados neste projeto são provenientes do banco de dados MySQL da Clínica LAJEADO. As tabelas mais relevantes para a análise foram importadas diretamente, além de quatro SQL Views personalizadas criadas no banco de dados para facilitar a recuperação de informações consolidadas e otimizar o processo de análise.

- ### Tabelas Importadas:

  - **clinicalajeado_initial_consultations:** Registros de consultas iniciais.
  - **clinicalajeado_patient_visits:** Detalhes das visitas de pacientes à clínica.
  - **clinicalajeado_orthodontic_payments:** Pagamentos relacionados a procedimentos ortodonticos.
  - **clinicalajeado_orthodontic_installations:**  Informações sobre a instalação de aparelhos ortodônticos.
  - **clinicalajeado_orthodontic_appointments:** Detalhes de consultas ortodônticas.
  - **clinicalajeado_patients:** Dados de registro de pacientes.
  - **clinicalajeado_payments:** Registros de pagamentos gerais.
  - **clinicalajeado_direct_payments:** Pagamentos diretos.
  - **clinicalajeado_executed_procedures:**  Informações sobre procedimentos executados.

- ### SQL Views:

  - **acquisitionchannel:** Para analisar os canais de aquisição de pacientes.
  - **clinicalajeado_totalsales:** Apresenta o volume total de vendas/serviços.
  - **clinicalajeado_totalpatients:** Contém a contagem consolidada de pacientes.
  - **clinicalajeado_revenue_by_specialty:**  Fornece a receita agregada por cada especialidade odontológica.
 
O modelo de dados foi desenvolvido para otimizar o desempenho e a clareza da análise. A estrutura completa do modelo de dados, incluindo as relações entre as tabelas e views importadas do MySQL, pode ser visualizada no diagrama abaixo:

<img width="1065" height="675" alt="ERD01" src="https://github.com/user-attachments/assets/f010f597-7fb0-44f5-b35d-128fd6b8f0cb" />

## Dashboard Overview

### Página 1: Receita e Serviços

Esta página serve como o painel de controle executivo para a Clínica Odontológica LAJEADO. Ela exibe os KPIs mais importantes, como Receita Total, Número de Pacientes Atendidos, Volume de Procedimentos Gerais e Procedimentos Ortodônticos. Além disso, oferece uma visão detalhada das Tendências de Receita de procedimentos gerais e ortodônticos, e da Contribuição de Receita por Especialidade, fornecendo uma compreensão imediata do desempenho geral da clínica e de suas áreas financeiramente mais significativas.

![Page1](https://github.com/user-attachments/assets/8635954b-4bba-4268-8e76-a56b46fac8ea)

### Página 2: Insights sobre Pacientes

Esta página oferece uma visão detalhada da dinâmica e das estratégias de aquisição de pacientes da clínica. Ela destaca métricas-chave como Novos Pacientes ao Longo do Tempo (tanto gerais quanto ortodônticos), Consultas Iniciais e a crucial Taxa de Conversão. Além disso, oferece insights sobre o Total de Pacientes Ortodônticos e Pacientes Ortodônticos Ativos, juntamente com um detalhamento dos Canais de Aquisição e dos Procedimentos Gerais Mais Realizados, permitindo uma compreensão mais profunda do crescimento de pacientes e da demanda por serviços.

![page2](https://github.com/user-attachments/assets/f60b8649-89cf-489c-9b64-78a5b7cbb051)

## Conclusão

Este painel demonstra como o Power BI pode transformar dados brutos da Clínica LAJEADO em uma poderosa ferramenta de análise e gestão do desempenho da clínica. Ele permite que gestores e equipes segmentem, filtrem e explorem dados para tomar decisões informadas sobre operações, estratégias de aquisição de pacientes e otimização de procedimentos, contribuindo diretamente para o sucesso e crescimento do negócio.


  
