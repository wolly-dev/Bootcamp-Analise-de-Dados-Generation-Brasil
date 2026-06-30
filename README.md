# 📊 Análise de Desempenho e Feedback do Usuário – NetGuard Pro

> **Exercício de Análise de Dados com Suporte de IA**  
> Bootcamp de Análise de Dados | 30 de Junho de 2026

---

## 📌 Visão Geral do Projeto

Este repositório documenta um **exercício prático de Análise de Dados** realizado durante um bootcamp, com um objetivo duplo:

1. **Simular um cenário real de avaliação de software** (o fictício **NetGuard Pro**), utilizando dados quantitativos (métricas de servidores) e qualitativos (feedback de usuários).
2. **Exercitar o uso de IA generativa como ferramenta de apoio ao analista de dados**, em todas as etapas do processo: desde a interpretação e categorização de grandes volumes de dados textuais até a estruturação de relatórios técnicos e recomendações estratégicas.

O exercício foi deliberadamente desenhado para que o analista atuasse como **curador e estrategista**, enquanto a IA atuava como **assistente inteligente** — agilizando tarefas repetitivas, sugerindo padrões e organizando informações, sem substituir o julgamento crítico humano.

**Principais aprendizados práticos do exercício:**
- Como integrar IA no fluxo de trabalho de um analista de dados.
- Como extrair insights acionáveis a partir de dados não estruturados (textos).
- Como cruzar dados qualitativos e quantitativos para embasar decisões.
- Como estruturar um relatório técnico claro, objetivo e com recomendações priorizadas.

---

## 🎯 Objetivos da Análise

- Avaliar a qualidade da experiência dos usuários com base em feedbacks e métricas de desempenho.
- Identificar os principais bugs ou problemas relatados.
- Propor mudanças e melhorias com base nos dados analisados.
- Estruturar um relatório técnico claro e objetivo para tomada de decisão.

---

## 🤖 Papel da IA neste Exercício

Diferentemente de uma análise de dados tradicional, este exercício foi planejado para **integrar ativamente ferramentas de IA generativa** ao processo analítico. A IA foi utilizada como:

| Etapa | Como a IA foi utilizada |
|-------|--------------------------|
| **Leitura e interpretação** | Auxiliou na leitura e interpretação de grandes volumes de dados textuais (50 feedbacks de usuários). |
| **Categorização** | Sugeriu categorias de funcionalidades e agrupamentos semânticos para os comentários. |
| **Análise de sentimento** | Apoiou a identificação de tons (positivo, neutro, negativo) em cada feedback. |
| **Estruturação do relatório** | Organizou as informações no formato do template técnico, garantindo coerência e fluidez. |
| **Geração de recomendações** | Propôs soluções com base nos padrões identificados, que foram validadas e priorizadas pelo analista. |

**Importante:** em nenhum momento a IA substituiu o julgamento do analista. Todas as conclusões, priorizações e recomendações finais foram **validadas e refinadas manualmente**, garantindo que o produto final refletisse a visão estratégica e o senso crítico do profissional.

> 🧠 **Objetivo pedagógico:** Este exercício demonstra que a IA é uma **ferramenta de aumento de capacidade** (augmentation), não de substituição. O analista mantém o controle do processo, enquanto a IA acelera tarefas operacionais e amplia a capacidade de processamento de informações.

---

## 📁 Estrutura dos Dados

### 1. Relatório de Desempenho (`SA-AIR_Performance_Report_pt-BR.xlsx`)
- Contém métricas de **100 servidores**, incluindo:
  - Uso de CPU, memória e disco.
  - Latência, perda de pacotes e taxa de sucesso de conexão.
  - Eventos de failover, tipos de erro e serviços afetados.

### 2. Feedback dos Usuários (`SA-AIR_User_Feedback_pt-BR.xlsx`)
- Contém **50 avaliações** de usuários reais (fictícios), com:
  - Avaliação por estrelas (1 a 5).
  - Comentários qualitativos sobre funcionalidades.
  - Sugestões e reclamações específicas.

### 3. Template de Relatório Técnico (`SA-AIR_Template-TECH_pt-BR.docx`)
- Estrutura utilizada para organizar os achados da análise.
- Inclui categorias de funcionalidades, identificação de problemas e resumo executivo.

---

## 🧠 Metodologia Aplicada

A análise foi conduzida em **5 marcos principais**, com **integração contínua de IA** em todas as etapas:

| Marco | Descrição | Participação da IA |
|-------|-----------|---------------------|
| **1. Preparação dos Dados** | Revisão e organização dos conjuntos de dados (planilhas). | Auxílio na validação de consistência e identificação de campos relevantes. |
| **2. Análise do Feedback dos Usuários** | Categorização por funcionalidade, avaliação de sentimento e extração de sugestões. | **Papel central:** categorização semântica dos 50 textos, sugestão de agrupamentos e identificação de padrões de sentimento. |
| **3. Análise dos Dados de Desempenho** | Identificação de padrões, cálculo de estatísticas e cruzamento com feedbacks. | Geração automática de estatísticas descritivas e correlações iniciais. |
| **4. Sumarização das Descobertas** | Criação de documento resumo com insights e recomendações. | Estruturação do texto do relatório, mantendo a coerência lógica entre as seções. |
| **5. Revisão e Refinamento** | Ajustes finais, validação de referências e preparação para entrega. | Verificação de consistência das referências e sugestões de melhorias na redação. |

> 💡 **Diferencial do exercício:** a IA não foi usada como "geradora automática de respostas", mas como **copiloto inteligente** — sugerindo, organizando e acelerando, enquanto o analista validava, ajustava e dava o tom estratégico final.

---

## 🔍 Principais Descobertas

### ✅ Pontos Fortes
- **Failover** e **estabilidade de rede** (baixa perda de pacotes) são altamente elogiados.
- **Monitoramento de sessões e disco** é considerado completo e confiável.

### ⚠️ Problemas Identificados
| Problema | Frequência | Gravidade |
|----------|------------|-----------|
| Alto consumo de CPU e lentidão no painel | 36% dos feedbacks | **Crítica** |
| Complexidade na configuração de firewall | 24% dos feedbacks | **Alta** |
| Falta de priorização inteligente de largura de banda | 18% dos feedbacks | **Média** |

---

## 🛠️ Recomendações Propostas

1. **Otimizar o uso de CPU** – Revisar arquitetura, implementar cache e separar processos críticos.
2. **Simplificar a configuração de firewall** – Criar assistente de configuração e templates visuais.
3. **Implementar QoS para largura de banda** – Priorizar tarefas críticas dinamicamente.

---

## 📄 Entregáveis

- `Relatorio_Analise_NetGuard_Pro.pdf` – Relatório final completo com análise, problemas e recomendações.
- Este arquivo `README.md` – Documentação resumida do projeto.

---

## 🧩 Tecnologias e Ferramentas

- **Planilhas:** Leitura e análise de dados estruturados (Excel).
- **IA Generativa:** Suporte na interpretação, categorização e estruturação do relatório.
- **Processamento de Texto:** Organização e formatação do documento final.

---

## 💭 Reflexão sobre o Uso de IA em Análise de Dados

Este exercício evidenciou que a IA generativa pode ser uma **aliada poderosa** para analistas de dados, especialmente em tarefas que envolvem:

- **Dados textuais não estruturados:** onde a IA acelera a categorização e análise de sentimentos.
- **Geração de relatórios:** onde a IA auxilia na estruturação e formatação, permitindo que o analista foque no conteúdo estratégico.
- **Sugestões de padrões:** onde a IA identifica correlações iniciais que podem ser validadas ou refutadas pelo analista.

**Lições aprendidas:**
- A IA é eficiente para tarefas de **baixo esforço cognitivo e alto volume**, como leitura e categorização de textos.
- O **julgamento humano** continua sendo essencial para priorização, validação de contexto e tomada de decisão.
- A **curadoria do analista** sobre as saídas da IA é o que garante a qualidade final do trabalho.

> "A IA não substitui o analista; ela amplia sua capacidade de processar informações e focar no que realmente importa: interpretar, priorizar e recomendar."

---

## 👩‍💻 Sobre o Autor

Este projeto foi desenvolvido como parte de um bootcamp de Análise de Dados, com o objetivo de simular um cenário real de avaliação de software e tomada de decisão baseada em dados, integrando IA como ferramenta de apoio ao longo de todo o processo.

---

## 📌 Licença

Este projeto é de uso educacional e não possui fins comerciais. Os dados utilizados são fictícios e foram criados exclusivamente para fins de aprendizado.

---

**📬 Contato:**  
Em caso de dúvidas ou sugestões, fique à vontade para abrir uma *issue* ou entrar em contato.

---
