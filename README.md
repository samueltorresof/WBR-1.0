# 📊 Template de Prompt para WBR (Weekly Business Review) · V4 Company

Este repositório contém um prompt estruturado de engenharia avançada (*Prompt Engineering*) projetado para auxiliar Coordenadores de Growth e Operações da V4 Company a estruturarem a sua **WBR (Weekly Business Review)** de forma cirúrgica, interativa e padronizada.

O principal objetivo deste prompt é transformar qualquer Modelo de Linguagem (LLM), como ChatGPT, Claude ou Gemini, num **Auditor de Governança Interativo**, garantindo que nenhum dado financeiro ou operacional seja omitido ou calculado incorretamente.

## ✨ Funcionalidades e Diferenciais

* **Trava Operacional (Passo a Passo):** A IA atua como uma entrevistadora, solicitando as informações secção por secção. Ela não gera o relatório final até que todos os dados sejam validados por si.
* **Cálculos Automáticos Incorporados:** O prompt instrui a IA a calcular automaticamente métricas de Análise Vertical (AV), Pace de metas, estouros de CSP e variações de margem a partir dos dados brutos fornecidos.
* **Alinhado com o Ecossistema V4:** Já inclui a nomenclatura nativa da rede, como as modalidades de contrato (**SABER, TER, EXECUTAR**), métricas de **SGI**, regras de **CSP sobre Receita Líquida**, **NPS**, **CSAT** e matrizes de **FCA (Fato, Causa e Ação)**.
* **Output Formatado:** O resultado final é gerado perfeitamente em Markdown, pronto para ser copiado para o Notion, Google Docs ou plataformas internas de reporte.

## 🚀 Como Utilizar

1. **Copie o Prompt:** Aceda ao ficheiro `prompt.txt` deste repositório e copie o texto integral do prompt.
2. **Inicie a Conversa:** Cole o prompt na sua IA de preferência (recomendado: ChatGPT Plus, Claude 3.5 Sonnet ou Gemini Advanced).
3. **Responda à Entrevista:** A IA irá iniciar a recolha de dados perguntando sobre a primeira secção (*Restrição da Semana*). Forneça os dados e avance conforme ela for solicitando os pontos seguintes.
4. **Valide os Números:** Caso envie dados consolidados ou em atualização, peça à IA para recalcular as tabelas antes do fecho.
5. **Gere o Relatório:** Quando terminar de preencher todas as secções, digite o comando de gatilho: **"WBR VALIDADA"**. A IA irá compilar o relatório completo formatado.

## 📁 Estrutura do Repositório

```text
├── README.md          # Documentação principal do projeto
└── prompt.txt         # O prompt estruturado pronto para ser copiado
