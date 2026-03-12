# desafio_IA_financas_dio
# Miniguia de Estudos: Inteligência Financeira com NotebookLM 📈

Este repositório foi desenvolvido como parte de um desafio prático na **DIO (Digital Innovation One)**. O objetivo é utilizar a IA Generativa (NotebookLM) para criar um caderno temático estruturado sobre finanças introdutórias, exercitando a curadoria de fontes e a engenharia de prompts.

## 🎯 Contexto e Objetivos
O foco deste estudo é a **Educação Financeira Básica**, abordando conceitos de poupança, juros compostos e a diferença entre Renda Fixa e Renda Variável. O objetivo é transformar documentos técnicos em um guia acessível para quem está começando a investir.

## 📚 Curadoria de Fontes
Utilizei as seguintes fontes oficiais e educativas para alimentar o NotebookLM:
1. **Guia CVM de Planejamento Financeiro** (PDF oficial da Comissão de Valores Mobiliarios).
2. **Caderno de Educação Financeira do Banco Central do Brasil**.
3. **Relatório Focus (Resumo)**: Para entender indicadores de inflação e taxa Selic.

## 🧠 Engenharia de Prompts e "Cicatrizes"
Aqui registro o processo de refinamento da comunicação com a IA:

* **Tentativa 1 (Prompt Genérico):** "Explique o que é investimento."
    * *Resultado:* Resposta muito vaga, misturando conceitos avançados com básicos.
* **Tentativa 2 (Ajuste de Contexto):** "Com base nos PDFs carregados, crie uma tabela comparando CDB e Tesouro Direto para um investidor iniciante."
    * *Resultado:* Melhor, mas faltou explicar os riscos de liquidez.
* **Tentativa 3 (Prompt "Nota 10"):** "Atue como um educador financeiro. Usando a fonte [Caderno BCB], explique o conceito de Juros Compostos usando uma metáfora e liste 3 passos práticos para montar uma reserva de emergência."
    * *Solução (Troubleshooting):* Foi necessário pedir para a IA citar especificamente as páginas para garantir a precisão dos dados.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **Reserva de Emergência:** O primeiro passo de qualquer investidor. Deve cobrir de 6 a 12 meses de custo de vida em ativos de alta liquidez.
* **Renda Fixa vs. Variável:** Na Fixa, você "empresta" dinheiro (ex: Tesouro Direto); na Variável, você se torna "sócio" (ex: Ações).

### 2. Glossário de Conceitos
* **SELIC:** A taxa básica de juros da economia brasileira.
* **IPCA:** O indice oficial que mede a inflação (aumento de preços).
* **Liquidez:** O quão rápido você consegue sacar seu dinheiro sem perder valor.

### 3. Prompts Reutilizáveis para Revisão
* *"Analise este novo artigo financeiro e compare-o com as diretrizes de risco da CVM que estudamos anteriormente."*
* *"Crie um quiz de 5 perguntas sobre a diferença entre inflação real e nominal baseada no conteúdo deste caderno."*

---

## 🛠️ Ferramentas Utilizadas
* [NotebookLM](https://notebooklm.google.com/) - Curadoria e síntese de conhecimento.
* [ChatGPT/Gemini] - Apoio na estruturação do repositório.
* GitHub - Hospedagem  e documentação do projeto.
