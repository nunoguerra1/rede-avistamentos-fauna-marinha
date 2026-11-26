# Plano de PRs

A = Módulo A (Avistamentos) · B = Módulo B (Encalhes) · AB = conjunto. O autor abre o PR; o outro revisa.

| # | Branch | Etapa | Autor | Revisor | Entregável |
|---|---|---|---|---|---|
| 0 | ambos/setup-repo | — | A | B | Estrutura e regras |
| 1 | ambos/etapa-1-contexto | 1 | AB | AB | Contexto, problema e escopo |
| 2 | a/etapa-2-envolvidos | 2 | A | B | Envolvidos e elicitação do módulo A |
| 3 | b/etapa-2-envolvidos | 2 | B | A | Idem, módulo B |
| 4 | a/etapa-3-necessidades | 3 | A | B | NEC do módulo A |
| 5 | b/etapa-3-necessidades | 3 | B | A | NEC do módulo B |
| 6 | a/etapa-4-requisitos | 4 | A | B | RF e RN do módulo A + RNF (usabilidade, desempenho, disponibilidade) |
| 7 | b/etapa-4-requisitos | 4 | B | A | RF e RN do módulo B + RNF (segurança, privacidade, auditabilidade) |
| 8 | ambos/etapa-5-priorizacao | 5 | AB | AB | Prioridades e conflitos |
| 9 | ambos/etapa-6-diagrama-uc | 6 | AB | AB | Diagrama de casos de uso |
| 10 | a/etapa-6-uc | 6 | A | B | Descrição de 1 UC do módulo A |
| 11 | b/etapa-6-uc | 6 | B | A | Descrição de 1 UC do módulo B |
| 12 | a/etapa-7-rastreabilidade | 7 | A | B | Matriz do módulo A |
| 13 | b/etapa-7-rastreabilidade | 7 | B | A | Matriz do módulo B |
| 14 | a/etapa-8-auditoria | 8 | A | B | A audita o módulo B |
| 15 | b/etapa-8-auditoria | 8 | B | A | B audita o módulo A |
| 16 | ambos/etapa-8-correcoes | 8 | cada um | o outro | Correções e situação final dos DEF |
| 17 | ambos/etapa-9-consolidacao | 9 | AB | AB | Padronização, PDF final e apresentação |