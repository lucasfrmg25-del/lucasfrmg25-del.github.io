# SINAL by LFM

**[FEITO COM AUXÍLIO DIRETO DE INTELIGÊNCIA ARTIFICIAL]**

SINAL by LFM é uma ferramenta local-first para preparar, cruzar, visualizar e mapear dados CSV sem esconder as decisões da análise.

> Nome anterior do projeto: Data Analyst Studio. O rebranding foi feito para evitar associação indevida com produtos já existentes e construir uma identidade própria.

## Ideia do produto

**Do arquivo bruto ao sinal.**

O usuário escolhe os campos, filtros, agregações e visualizações. O SINAL transforma essas escolhas em leituras visuais reproduzíveis, sem depender de geração automática de números por IA.

## Recursos

- importação de CSV;
- diagnóstico e limpeza de dados;
- filtros combináveis;
- KPIs contextuais;
- barras, agrupadas, empilhadas e 100% empilhadas;
- linha e área;
- dispersão;
- histograma e boxplot;
- heatmap;
- nuvem de palavras;
- donut e ranking;
- mapa geográfico por latitude/longitude ou cidade/estado/país;
- painel de sessão com múltiplos visuais.

## Identidade

A interface usa uma linguagem visual editorial/técnica: grafite profundo, verde-lima como sinal ativo, tipografia Space Grotesk + IBM Plex Mono, grade modular e navegação conceitual:

`CARREGAR → PREPARAR → EXPLORAR → MAPEAR → PAINEL`

## Transparência de desenvolvimento

A assistência de IA foi usada diretamente para apoiar arquitetura, geração e revisão de código, implementação de recursos, identificação de bugs, refatoração e design de interface. O projeto não é apresentado como código produzido sem assistência.

## Estado técnico

A versão Python refatorada corrige o parser numérico, usa SHA-256 para identificar arquivos, reduz recomputações no Streamlit, otimiza contagem de nulos e agregações geográficas, adiciona cache, separa responsabilidades em módulos e inclui testes unitários.

## Demo

GitHub Pages: `/sinal.html`
