# 03-logs — Gestão Centralizada de Logs

Agregação, parsing estruturado e indexação de logs corporativos com Loki, Promtail, Fluent Bit e OpenSearch.

## 📂 Subáreas
- [`loki/`](./loki) — **Stack:** `Grafana Loki, chunks, index, compactor` — Armazenamento eficiente de logs com indexação baseada exclusivamente em labels.
- [`promtail/`](./promtail) — **Stack:** `promtail.yml, pipeline stages, multiline parsing` — Coleta local de arquivos de log do host e envio formatado ao Loki.
- [`fluent-bit/`](./fluent-bit) — **Stack:** `fluent-bit, inputs, filters, parsers, outputs` — Agente ultraleve em C para roteamento e enriquecimento de telemetria de logs.
- [`elasticsearch-opensearch/`](./elasticsearch-opensearch) — **Stack:** `OpenSearch, indices, mappings, index lifecycles` — Indexação textual distribuída e busca analítica de grandes volumes de log.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Observability-SRE.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
