# Protocolo Universal de Agentes de IA

Este repositório adota o padrão **Universal Project Memory (UPM)** para sincronização contínua de contexto.

Qualquer agente operando neste projeto deve:
1. Ler `.context/STATUS.md` no cold start / início de sessão.
2. Manter `.context/STATUS.md` atualizado (< 100 linhas).
3. Registrar novas decisões arquiteturais em `.context/DECISIONS.md`.
