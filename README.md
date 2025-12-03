<p align="center">
  <img src="capavideo.png" alt="Capa do Projeto" width="700"/>
</p>

# Análise Comportamental de Clientes no E-commerce
✨ Projeto desenvolvido no curso Télos + CESAR + ThoughtWorks

### **Equipe:** Mariah Lisboa e Tatiana Freitas
### Novembro/2025

---

## 📌 Contexto

O avanço acelerado do comércio eletrônico tem transformado significativamente os hábitos de consumo e a forma como os clientes interagem com marcas e plataformas digitais.

Diante de um ambiente altamente competitivo, compreender o comportamento do consumidor no e-commerce (incluindo padrões de navegação, engajamento e perfil) torna-se fundamental para orientar estratégias de marketing, melhorar a jornada e fortalecer a fidelização.

Este projeto analisa a base de clientes de um e-commerce com o objetivo de identificar padrões, perfis e fatores que influenciam a probabilidade de compra.

---

## 🎯 Objetivo

Resumidamente, o projeto busca responder:

> *Quais segmentos de clientes, considerando gênero, faixa etária, região e tipo de vínculo (novo, recorrente, fidelizado), apresentam maior propensão à compra e, como essas características se relacionam com o comportamento de navegação e engajamento na plataforma?*
</details> 

Além disso, foram investigadas hipóteses envolvendo:

- Perfil e comportamento dos diferentes segmentos;
- Fontes de origem e impacto no funil;
- Relação entre tempo de relacionamento e probabilidade de compra;
- Construção de um score de propensão baseado em perfil, comportamento e engajamento.

---

<details>
  <summary><strong>⚙️ Ferramentas e Tecnologias</strong></summary>
  <br>

  - **Limpeza, Transformação e Modelagem**: BigQuery e Power BI;  
  - **Visualização**: Power BI e Google Colab (Pandas, Matplotlib, Numpy); 
  - **Documentação Técnica**: Google Colab e Google Documentos;  
  - **Apresentação**: Figma.  

  > *O projeto foi desenvolvido desde o pré-processamento até a modelagem exploratória, integrando análises estatísticas e visualizações interativas.*
</details>

<details>
  <summary><strong>📂 Processamentos e Análises dos Dados</strong></summary>
  <br>

As ferramentas utilizadas foram Google BigQuery e Power BI.

**Etapas realizadas:**

- Conversão e padronização de colunas numéricas que estavam sendo interpretadas incorretamente pelo Power BI (notação científica);
- Recarregamento da base após padronização;
- Limpeza final no Power BI:
  - Checagem dos tipos de dados;
  - Exclusão/substituição de valores inconsistentes;
  - Padronização de categorias textuais;
  - Conferência de integridade entre variáveis.

</details>

<details>
  <summary><strong>📊 Análises Exploratórias – EDA</strong></summary>
  <br>

Conduzida no Power BI, com granularidade a nível de cliente.

**Metodologias aplicadas:**

- Medidas de tendência central;
- Cruzamento entre variáveis categóricas;
- Tabelas matrizes;
- Gráficos descritivos (barras, rosca, combinado, etc.).

**Resultado:** geração de perguntas de negócio, identificação de padrões de comportamento e direcionamento das etapas seguintes.
</details>

<details>
  <summary><strong>🔄 Cruzamento e Comparações Entre Variáveis</strong></summary>
  <br>

Realizado no BigQuery + Power BI.

**Principais análises:**

- Relação entre tipo de cliente e volume de compras;
- Influência de características demográficas e regionais;
- Diferenças de comportamento entre grupos (engajamento, perfil, navegação);
- Impacto do tempo de relacionamento na recompra e fidelização;
- Correlações entre variáveis de interesse.

Esses cruzamentos serviram de base para identificar padrões-chave e orientar recomendações estratégicas.
</details>

<details>
  <summary><strong>⭐ Construção do Score de Propensão à Compra</strong></summary>
  <br>

**Etapas:**

- Seleção das variáveis mais consistentes com os pilares: perfil, comportamento e engajamento;
- Divisão das variáveis em quartis;
- Transformação das pontuações em valores binários (presença/ausência);
- Cálculo do score total (soma das binárias);
- Classificação dos clientes em:
  - Baixa propensão
  - Média propensão
  - Alta propensão
- Comparação de padrões entre esses grupos (proporções médias);
- Visualização final com gráficos radar.

Esse score permitiu sintetizar comportamentos complexos em uma métrica simples e aplicável.
</details>

<details>
  <summary><strong>📈 Resultados e Conclusões</strong></summary>
  <br>

A análise comportamental permitiu identificar padrões relevantes na jornada dos clientes e compreender como variáveis de perfil, engajamento, tempo de relacionamento e comportamento de navegação influenciam a probabilidade de compra em um ambiente de e-commerce.

O projeto consolidou uma visão ampla e estruturada do comportamento dos clientes, gerando insumos valiosos para decisões orientadas a dados nos pilares de segmentação, retenção, engajamento e experiência do usuário.
</details>

## 🔗 Links Úteis

<br>

- 📄 [Notebook Técnico (Colab)](https://colab.research.google.com/drive/1gW1CKuTYlZmS9uRZkPdJxM-tfJMjPcFl?usp=sharing)
- 🎞️ [Apresentação (Figma)](https://www.figma.com/deck/qLXbdwcVxEzdbLHbhwZ0W5/T%C3%A9los_Projeto_Final_git?node-id=1-1830&t=jO0mqGY3A3QDazNA-1)

---

## 📊 Panorama Descritivo do Perfil dos Clientes

<br> <p align="center"> <img src="panorama_descritivo.gif" alt="Panorama Descritivo" width="700"/> </p>

## 📈 Comportamento de Clientes por Nível de Propensão à Compra

<br> <p align="center"> <img src="panorama_score.gif" alt="Panorama Score" width="700"/> </p>
