# 01 · Contexto e escopo (Etapa 1)

> Convenção: **[FATO]** tem referência em `docs/referencias.md`; **[HIPÓTESE]** precisa ser confirmada.

## 1. Contexto

Animais marinhos (cetáceos, tartarugas, aves, pinípedes) podem ser avistados vivos no mar ou na
praia, ou aparecer encalhados, vivos ou mortos. Registrar essas ocorrências gera informação sobre
a presença de espécies, o estado das populações e as ameaças humanas que elas enfrentam [R2].
Quem primeiro percebe a ocorrência costuma ser quem frequenta a costa: moradores, pescadores e turistas [R4].

## 2. Situação atual

- [FATO][R2][R3] O monitoramento de encalhes no Brasil é feito em grande parte por Projetos de Monitoramento
  de Praias (PMP). Os PMPs surgiram em 2001-2002; o PMP-BS (Bacia de Santos) é uma exigência federal ligada a
  atividades de impacto no mar e começou em agosto de 2015.
- [FATO][R1] Desde 2015, os registros dos PMPs são armazenados no SIMBA para padronizar os dados.
  O SIMBA tem acesso público aberto.
- [FATO][R6] O SIMBA reúne ocorrências de avistamentos e encalhes de cetáceos, com campos como cidade, praia,
  mês/ano, condição do animal, interação antrópica, condição final e causa da morte.
- [FATO][R5] O ICMBio coordena a REMAB (Rede de Encalhe e Informação de Mamíferos Aquáticos do Brasil).
- [FATO][R4][R9] Os primeiros registros de encalhe muitas vezes vêm de comunitários, pescadores e turistas
  que contatam a equipe responsável; instituições locais recebem notificações da população.
- [FATO][R8] Um animal vivo próximo à faixa de areia pode ser confundido com um encalhe.
- [FATO][R7] Em uma análise com dados do SIMBA, pesquisadores precisaram filtrar submissões com inconsistências.

Pontos ainda sem fonte (a confirmar na etapa 2):

- [HIPÓTESE] HIP01: o cidadão não tem um canal único e simples; precisa descobrir qual instituição acionar conforme o trecho de costa.
- [HIPÓTESE] HIP02: avistamentos feitos por cidadãos fora dos PMPs ficam dispersos (redes sociais, mensagens) e sem padronização.
- [HIPÓTESE] HIP03: informação incompleta na notificação (local exato, espécie, condição) atrasa o atendimento.
- [HIPÓTESE] HIP04: registros de cidadãos sem validação especializada têm qualidade variável (ex.: espécie identificada errado).


## 3. Problema

Avistamentos e encalhes de fauna marinha são percebidos primeiro por pessoas comuns, mas o caminho entre
"alguém viu" e "a equipe certa recebe uma informação completa e confiável" não é simples [R4][R9].
Existe infraestrutura robusta de registro técnico (PMPs e SIMBA), porém a entrada de informação vinda do
cidadão e a distinção entre avistamento e encalhe geram incerteza [R8]. Quem é afetado: observadores
(cidadãos, pescadores, turistas), equipes de resposta, pesquisadores e validadores, e os próprios animais.

## 4. Objetivo do sistema

Apoiar o registro padronizado e a validação de avistamentos, e o reporte e acompanhamento de encalhes de
fauna marinha, conectando observadores, validadores e equipes de resposta.

**DECISÃO D01 (confirmar em dupla):** o sistema é **complementar** ao SIMBA/PMP (porta de entrada e fluxo de
validação), e não um substituto deles.

## 5. Justificativa

- Dados de avistamento e encalhe sustentam estudos de populações e ameaças [R2].
- Há dependência da comunicação feita por pessoas leigas [R4][R9].
- Há risco de confusão entre avistamento e encalhe [R8] e de dados inconsistentes [R7].


## 6. Escopo (proposta, a confirmar)

### Dentro do escopo
- **Módulo A, Avistamentos:** registro de avistamento por observadores, consulta de registros e validação por especialista.
- **Módulo B, Encalhes:** reporte de encalhe, encaminhamento à equipe responsável e acompanhamento do caso.

### Fora do escopo desta versão
- Necropsia, laudos e gestão laboratorial.
- Reabilitação veterinária (atendimento clínico ao animal).
- Análise científica e estatística dos dados.
- Integração técnica com o SIMBA (apenas como possibilidade futura).
- Fins comerciais (turismo, venda de passeios).

## 7. Hipóteses iniciais

Ver HIP01 a HIP04 na seção 2. Serão confirmadas, ajustadas ou descartadas na etapa 2 (elicitação).

## 8. Dúvidas em aberto

- DUV01: quais grupos de fauna entram (cetáceos, tartarugas, aves, pinípedes)?
- DUV02: qual região geográfica de cobertura?
- DUV03: quem são os validadores e existe instituição parceira?
- DUV04: como tratar dados pessoais do observador e a localização de animais sensíveis?