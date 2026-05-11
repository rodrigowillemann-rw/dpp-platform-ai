# DPP Platform AI

## Descricao

Projeto de plataforma e estudo de caso para apoiar pequenas e medias empresas na adequacao ao Digital Product Passport (DPP), combinando rastreabilidade, sustentabilidade, gestao documental e inteligencia artificial aplicada.

## Problema que Resolve

Empresas inseridas em cadeias globais precisam organizar dados de produto, origem de materiais, fornecedores, processos, documentos tecnicos e indicadores ambientais. Essas informacoes normalmente estao dispersas em planilhas, relatorios e sistemas internos, dificultando a preparacao para exigencias regulatorias e comerciais.

## Para Quem Gera Valor

- Pequenas e medias empresas industriais
- Cadeias produtivas texteis
- Exportadores e fornecedores de marcas internacionais
- Consultorias de sustentabilidade e conformidade
- Instituicoes de inovacao e desenvolvimento industrial

## Solucao Proposta

A proposta e estruturar uma plataforma para cadastrar produtos, materiais, fornecedores, documentos e evidencias, gerando diagnosticos de lacunas, indicadores de rastreabilidade e uma base preparada para uso de OCR, LLMs e RAG na analise documental.

## Tecnologias e Metodos

- Python
- IA aplicada
- OCR
- LLMs
- RAG
- APIs
- Modelagem de dados
- Indicadores ESG e rastreabilidade
- Gestao de projetos e inovacao

## Estrutura do Projeto

```text
data/       requisitos e dados sinteticos para demonstracao
notebooks/  analises e simulacoes iniciais
docs/       estudo de caso e requisitos do setor textil
src/        futuras rotinas de processamento e diagnostico
```

## Como Executar

```sh
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/dpp-readiness-demo.ipynb
```

## Resultados e Aprendizados

- Matriz inicial de requisitos para DPP textil
- Diagnostico sintetico de prontidao de empresas
- Base para prototipo de analise documental com IA
- Aprendizado sobre regulacao, sustentabilidade e produto digital

## Resultado Demonstrativo

Com os dados sinteticos em `data/requisitos_dpp_textil_exemplo.csv`, o diagnostico inicial calcula um score de prontidao DPP de **25,0%**. O resultado indica uma base parcialmente estruturada para identificacao do produto, composicao e certificacoes, com lacunas relevantes em origem da materia-prima, impactos ambientais e circularidade.

| Indicador | Resultado |
| --- | ---: |
| Requisitos avaliados | 7 |
| Score sintetico de prontidao | 25,0% |
| Itens de alta criticidade pendentes | 1 |
| Itens parcialmente atendidos | 3 |

## Autor

Rodrigo Willemann  
Email: rodrigo.willemann@gmail.com

