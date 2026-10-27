# 07-automacao — Automação Operacional e Runbooks

Execução automática de verificações de saúde e runbooks interativos para auto-remediação de alertas.

## 📂 Subáreas
- [`health-checks/`](./health-checks) — **Stack:** `Probes HTTP, TCP, verificação sintética periódica` — Sondas ativas de monitoramento fora da rota de tráfego de produção.
- [`alertas-runbooks/`](./alertas-runbooks) — **Stack:** `Links de runbook nos alertas, scripts de remediação` — Documentação operacional passo a passo para o operador de plantão (on-call).

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Observability-SRE.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
