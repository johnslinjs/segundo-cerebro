---
type: Procedure
status: active
tags:
  - fontes
  - registro
  - qualidade
---

# Como registrar informações e fontes

## Tipos de registro
- **FATO DOCUMENTADO:** há documento, registro ou evidência verificável.
- **RELATO PESSOAL:** o titular conta que algo ocorreu. É uma fonte válida sobre sua experiência, mas não equivale a confirmação independente.
- **INTERPRETAÇÃO:** significado atribuído a uma experiência.
- **HIPÓTESE:** explicação possível ainda não confirmada.
- **OBJETIVO:** resultado desejado.
- **PLANO:** intenção de ação.
- **PENDENTE:** dado incompleto ou contraditório.
- **HISTÓRICO:** informação válida para um período anterior.

## Modelo de registro
Use este formato quando o assunto exigir rastreabilidade:

```yaml
---
type: PersonalRecord
status: needs-review
event_date:
recorded_date: YYYY-MM-DD
source:
classification: personal-report
confidence: not-assessed
tags: []
---
```

## Corpo da nota
- **O que foi informado:**
- **Contexto:**
- **Fonte original:**
- **O que está confirmado:**
- **O que é interpretação:**
- **O que falta confirmar:**
- **Links relacionados:**

## Datas
Diferencie:
- data em que o acontecimento ocorreu;
- data em que a informação foi registrada;
- data em que a informação foi atualizada.

Se não souber a data exata, escreva “aproximadamente”, “entre X e Y” ou “data não informada”.

## Correções
Não substitua silenciosamente uma informação antiga. Registre a correção, sua fonte e quando foi feita. Mantenha pendências em [[05 - SISTEMA/05 - Modelos e Padrões/Pendências de confirmação]].

## Padrões e autoconhecimento
Uma ocorrência isolada não prova um padrão. Registre exemplos, contexto, frequência observada e explicações alternativas. Não atribua diagnóstico nem causalidade psicológica.

## Dados de terceiros
Registre somente o que for necessário para compreender sua própria história e seus vínculos. Respeite privacidade e evite especular sobre pensamentos ou intenções de outras pessoas.
