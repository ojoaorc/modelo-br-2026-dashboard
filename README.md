# Modelo eleitoral BR 2026 — Dashboard público

Dashboard self-contained do modelo Bayesiano de probabilidade do 2º turno
presidencial brasileiro 2026.

## 🔗 Dashboard ao vivo

**[https://ojoaorc.github.io/modelo-br-2026-dashboard/](https://ojoaorc.github.io/modelo-br-2026-dashboard/)**

## O que é

Modelo Bayesiano v6.3 com posterior gaussiano fechado em logit space. Combina:
- Polls de 2º turno (Datafolha, Quaest, AtlasIntel, Futura, Ideia, Real Time, Paraná)
- Aprovação líquida do governo Lula (série Datafolha/CNT/Quaest)
- Mercados de previsão Polymarket (diagnóstico)

Backtest 6 eleições 2002-2022: **6/6 acertos confiantes, Brier 0.097, MAE 3.1pp**.

## Conteúdo do dashboard

4 abas:
- **Main** — probabilidade marginal, cenários, stress aprovação, histórico, mercados, polls recentes
- **Comparativo** — BR v6.3 vs BR-custom v7 (projeto LatAm), per-cenário e reconciliação com mercado
- **Metodologia** — explicação em linguagem acessível dos 3 modelos coexistentes
- **About** — versão, fontes de dados, limitações, peer review

## Características técnicas

- **Self-contained**: 392KB único arquivo HTML
- **Offline-first**: React 18, ReactDOM 18, Chart.js 4 inlined (zero CDN runtime)
- **Sem servidor**: abre direto no browser (file://) ou via Pages

## Dados gerados quando

Snapshot atualizado periodicamente. Para a versão mais recente sempre visite a URL acima.

## Código-fonte do modelo

Repositório principal (privado): código Python, backtest, scripts, papers, PEER_REVIEW. Acesso por solicitação.

---

**Atribuição:** João Renato Santos da Cunha (pesquisador independente).
Construído com auxílio do Claude Opus 4.7 (Anthropic).
