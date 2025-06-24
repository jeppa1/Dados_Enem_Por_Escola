# 📊 Desempenho das Escolas do Rio Grande do Norte no ENEM (2009–2015)

Este é um projeto de análise de dados realizado com base nos resultados do Exame Nacional do Ensino Médio (ENEM) entre os anos de 2009 e 2015 nas escolas do Rio Grande do Norte. O objetivo foi investigar padrões de desempenho entre as redes de ensino (Federal, Estadual e Privada), identificar fatores associados ao sucesso acadêmico e analisar a evolução temporal dos resultados educacionais no estado.

O projeto foi desenvolvido utilizando Python no Google Colab, com apoio do Gemini e Qwen na formulação de hipóteses, interpretação de dados e redação final do relatório.

---

## 📌 Objetivos

- Comparar o desempenho médio das redes de ensino (Federal, Estadual e Privada).
- Identificar áreas de maior desigualdade educacional.
- Analisar tendências temporais (2009–2015).
- Investigar correlações entre indicadores internos (como taxa de aprovação e abandono) e o desempenho no ENEM.

---

## 🧪 Metodologia

- **Fonte de Dados:** Resultados do ENEM de 3.033 escolas do Rio Grande do Norte (2009–2015).
- **Tratamento de Dados:**
  - Limpeza e padronização dos dados.
  - Harmonização de escalas de notas (de 0–100 para 0–1000).
  - Remoção de registros inconsistentes (notas totais abaixo de 300).
- **Análise Estatística:**
  - Cálculo da média geral por escola e rede.
  - Análise por disciplina (Matemática, Redação, Ciências da Natureza, Linguagens e Códigos, Ciências Humanas).
  - Correlação entre desempenho no ENEM e indicadores de fluxo escolar (taxa de aprovação e abandono).

---

## 📈 Principais Resultados

### 1. Hierarquia de Desempenho
A análise revelou uma hierarquia consistente entre as redes:
> **Federal > Privada > Estadual**

Esse padrão foi observado em todas as disciplinas, com destaque para Matemática e Redação como maiores diferenciais.

### 2. Tendência Temporal (2009–2015)
Com exceção de Ciências Humanas, houve **estagnação ou queda** no desempenho médio das escolas em todas as áreas. A rede estadual foi a mais afetada.

### 3. Fatores Internos
- **Taxa de Abandono** mostrou a maior correlação negativa com a nota média no ENEM (**–0.61**).
- **Taxa de Aprovação** apresentou correlação positiva (**+0.51**), evidenciando a importância da retenção de alunos.

---

## 📁 Estrutura do Repositório
