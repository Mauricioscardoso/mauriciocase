<p align="center">
  <img src="logo-ifood.png" alt="Logo iFood" height="80"/>
</p>

#  Case Técnico – Data Analytics | iFood

Este repositório contém a análise técnica desenvolvida para o case de Data Analytics do iFood. A proposta é responder às questões do teste A/B com foco em retenção de usuários, por meio de uma abordagem analítica robusta, utilizando Python, pandas, seaborn e outros pacotes para exploração de dados, testes estatísticos e visualizações.

##  Escopo do Projeto

- Análise de distribuição de valores (order_total_amount)
- Filtragem de outliers com base em limites estatísticos
- Verificação de normalidade (Shapiro-Wilk test)
- Aplicação do teste estatístico **Mann–Whitney U**
- Visualização gráfica por KDE e boxplot
- Sugestões de negócio com base na retenção da campanha

##  Tecnologias Utilizadas

- Python
- Google Colab
- Pandas
- Seaborn / Matplotlib
- Scipy (Testes estatísticos)
- GitHub

##  Objetivos do Case

### 1. Análise do Teste A/B
-  **Indicador principal**: retenção de usuários com base na realização de pedidos
-  Aplicação do **teste Mann–Whitney U**, após constatação de distribuição não-normal
-  Avaliação da **significância estatística** entre grupos `target` (com cupom) e `control`
-  Estimativa de impacto financeiro da campanha com base na diferença de ticket médio

### 2. Segmentações Estratégicas
- Definição de segmentos com base em:
  - Frequência de pedidos
  - Ticket médio
  - Cidade e faixa de preço dos restaurantes
- Aplicação da análise por segmento para identificação de **respostas diferenciadas ao cupom**

### 3. Recomendações e Próximos Passos
- Proposta de **novo experimento A/B** com variação de valor e regras de uso dos cupons
- Sugestão de **política de retenção personalizada** para cada segmento
- Estimativa de impacto da personalização nas taxas de recompra
- 
##  Estrutura dos Arquivos

- `Script_Teste_ifood.ipynb`: Notebook principal com todo o fluxo analítico
- `imagens/`: Pasta com gráficos exportados
- `relatorio_final.pdf`: Relatório visual para stakeholders
- `README.md`: Este arquivo

###  Sobre o Autor

**Maurício Silveira Cardoso**  
Pronomes: ele/dele  
 Canoas/RS |  (51) 99466-7420  
✉ mauriciosilveiracardoso@hotmail.com  
 [LinkedIn](https://www.linkedin.com/in/mauricioscardoso)  

Engenheiro de Produção, Analista de Dados e Fundador do Instituto LetraPreta. Tenho mais de 4 anos de experiência em projetos de dados, automações, dashboards e inteligência de negócios. Atualmente sou mestrando em Administração pela Unisinos e MBA em Data Science e Analytics pela USP-ESALQ. Acredito no poder da tecnologia aliada à justiça social.

##  Destaques

- Desenvolvimento de ETLs e automações para mais de 30 rankings no GPTW
- Criação do GPTFlow (sistema de gestão de projetos no SharePoint)
- Liderança do Instituto LetraPreta, com +40 voluntários e +9 mil seguidores
- Produção de e-books sobre equidade e educação antirracista
- Especialista em análises preditivas, BI e visualização de dados

---

<p align="center">
  <img src="mauricio-cardoso.jpg" alt="Maurício Silveira Cardoso" width="200" style="border-radius: 10px"/>
</p>
