# Fluxo de trabalho

1. Nada vai direto para `main`. Todo trabalho entra por Pull Request.
2. Quem escreve não aprova o próprio PR. O outro integrante revisa (revisão cruzada).
3. Branches: `a/<etapa>-<assunto>` (Módulo A), `b/<etapa>-<assunto>` (Módulo B),
   `ambos/<assunto>` (conjunto). Ex.: `a/etapa-4-requisitos`.
4. Commits curtos, no imperativo, em português. Ex.: "Adiciona RF01 a RF06 do módulo A".
5. Cada PR cita a etapa e os identificadores (RF, NEC, UC...) que cria ou altera.
6. O revisor comenta com base nos critérios de qualidade da etapa 8 (clareza, completude,
   consistência, verificabilidade, rastreabilidade, correção dos modelos, adequação às necessidades).
7. Merge com "Squash and merge", só após aprovação. O histórico serve de registro de participação.

## Regras de integridade

- Não registrar como real uma entrevista, observação ou validação que não aconteceu.
  Cenário fictício deve ser declarado, separando fatos de hipóteses.
- Declarar o uso de IA em docs/09-uso-de-ia.md.
- Não incluir dados pessoais reais no repositório.