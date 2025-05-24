# 📊 Análise de Dados - Campanha "Vida em Equilíbrio com NutriZen"

Projeto de análise de dados realizado pela equipe **3D Analytics** com foco na avaliação de desempenho da campanha de marketing digital **"Vida em Equilíbrio com NutriZen"**, um suplemento natural voltado para bem-estar digestivo, foco e leveza no dia a dia.

## 🧠 Objetivo

Analisar os dados coletados em diferentes plataformas sociais (Instagram e TikTok) para:

- Medir o ROI (Retorno sobre o Investimento) de influenciadores digitais contratados.
- Avaliar o desempenho das publicações em termos de engajamento, conversão e alcance.
- Identificar os formatos, canais e perfis mais efetivos para a marca NutriZen.
- Propor melhorias baseadas em dados reais para campanhas futuras.

---

## 👥 Público-Alvo da Campanha

- Faixa etária: 25 a 35 anos
- Gênero predominante: Feminino
- Interesses: Saúde, bem-estar, leveza, rotina saudável

---

## 📱 Influenciadores e Canais

### Instagram
- 👩‍🍼 **@vivabemcomluna**
- 🌱 **@rotinabio**

### TikTok
- 🤸 **@thalleszen**
- 👯 **@duaszen**
- 💪 **@coachmaromba**

---

## 🛠️ Processo de ETL (Extração, Transformação e Carga)

Os dados foram coletados manualmente e por relatórios disponibilizados pelos influenciadores. Entretanto, alguns campos estavam incompletos, exigindo um processo de tratamento e preenchimento:

### 🧩 Colunas preenchidas/calculadas:
- **Alcance - Impressões**: Estimada com base na média entre o alcance total e a taxa de engajamento, utilizando benchmarks setoriais.
- **Engajamento - Não Seguidores (%)**: Calculada subtraindo a taxa de engajamento dos seguidores da taxa total de engajamento.
- **Cliques no Link**: Inferidos com base na média de cliques por tipo de conteúdo (story, reel, carrossel) e ajustados pela taxa de engajamento e impressões do influenciador.

### 📊 Colunas disponíveis na planilha original:
`Influenciador | Rede Social | Tipo | Publicação | Data de Publicação | Total Alcance | Alcance - Seguidores (%) | Alcance - Não Seguidores (%) | Alcance - Impressões | Total - Engajamento (%) | Engajamento - Seguidores (%) | Engajamento - Não Seguidores (%) | Total Interações | Curtidas | Salvamentos | Respostas | Compartilhamentos | Toques Figurinha | Cliques Link | Total Interações Neg. (%) | Avanço (%) | Saiu | Próx. Story | Voltar | Reproduções`

---

## 📈 Principais Resultados e Insights

### 🔎 1. ROI não é proporcional ao engajamento
- **@coachmaromba** estimou ROI de 4.0, mas entregou -0.55.
- Público fitness não correspondeu à proposta da campanha, indicando desalinhamento.

### 🔎 2. Instagram teve melhor performance que TikTok
- **@vivabemcomluna** e **@rotinabio** superaram o ROI estimado.
- Melhor custo-benefício nos cliques em links.
- Baixa taxa de rejeição nos Stories.

### 🔎 3. TikTok gerou muito alcance, mas pouca conversão
- Influenciadores como **@thalleszen** e **@duaszen** tiveram alto número de views, mas ROIs abaixo do esperado.

### 🔎 4. Engajamento ≠ intenção de compra
- **@duaszen** teve bom engajamento, mas o ROI foi apenas razoável.
- Curtidas e comentários não garantem conversão.

### 🔎 5. Conteúdos educativos funcionam melhor
- **@rotinabio** teve o maior ROI real (3.5) com receitas e lives.
- Formatos informativos + contexto real de uso geram mais cliques e retenção.

---

## 🏆 Influenciadores com melhor desempenho

| Influenciador      | ROI Estimado | ROI Real | Status     | Insight                              |
|--------------------|--------------|----------|------------|---------------------------------------|
| @vivabemcomluna    | 300%         | 300%     | Consistente| Reels e Stories performaram bem       |
| @rotinabio         | 250%         | 350%     | Superou    | Conteúdo educativo gerou mais valor  |
| @thalleszen        | 200%         | 20%      | Fracasso   | Grande alcance, baixa conversão       |
| @duaszen           | 150%         | 197%     | Superou    | Público qualificado                   |
| @coachmaromba      | 400%         | -55%     | Fracasso   | Público desalinhado com a proposta    |

---

## 🔁 Recomendações Estratégicas

- 📌 **Focar em Instagram**, principalmente em **Stories** e **Reels** com conteúdo educativo.
- 📌 **Reduzir investimento no TikTok**, até ajustar o público-alvo e o tipo de conteúdo.
- 📌 **Reforçar parcerias com @rotinabio e @vivabemcomluna**, que entregaram consistência e alto ROI.
- 📌 Apostar em influenciadores com público feminino e entre 25-35 anos.
- 📌 Utilizar micro e mid influencers para garantir melhor custo-benefício.
- 📌 Analisar mais profundamente a **qualidade do clique**, e não apenas o volume.

---

## 📚 Fontes de Referência

- Dados extraídos de relatórios de influenciadores contratados.
- Benchmarks de engajamento e conversão do setor de wellness e marketing de influência.
- TikTok Business Wellness Insights (2023)
- Influencer Marketing Hub Report (2024)

---

## 👨‍💻 Sobre o Projeto

Este projeto foi desenvolvido pelo grupo **3D Analytics** como parte de estudos em **Análise de Dados aplicada ao Marketing Digital**. O foco foi utilizar ferramentas de ETL, métricas de mídia social, KPI de campanhas e análise crítica de ROI.

---

## 📬 Contato

Caso deseje saber mais ou colaborar com o projeto:

- **Cristiane** https://www.linkedin.com/in/cristiane-meira-b36006a1/
- **Myriam** https://www.linkedin.com/in/myriamnascimento/
- **Layla** https://www.linkedin.com/in/laylafe/
- **Jeferson** https://www.linkedin.com/in/jeferson-d-4a6b74149/
- **Viviane** https://www.linkedin.com/in/viviane-santosads/
- **Luana** https://www.linkedin.com/in/luana-tamaturgo-653ab61aa/
- **Gustavo** https://www.linkedin.com/in/gustavo-ribeiro-de-souza/
- **João Gabriel** https://www.linkedin.com/in/joaogabrielromero/
- **Mariana** https://www.linkedin.com/in/mariana-asm/
- **Maria Eduarda** https://www.linkedin.com/in/mariaeduardavieira/
- **Renato** www.linkedin.com/in/renatocds  


---

**3D Analytics - Transformando dados em decisões**

