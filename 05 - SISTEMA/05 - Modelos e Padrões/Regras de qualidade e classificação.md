---
type: Standard
status: active
tags:
  - sistema
  - qualidade
  - classificação
---

# Regras de qualidade e classificação

## Tipos de informação
- **FATO DOCUMENTADO:** apoiado por documento ou registro verificável.
- **RELATO PESSOAL:** informação narrada pelo titular, ainda que não haja documento externo.
- **INTERPRETAÇÃO:** leitura ou significado atribuído a um acontecimento.
- **HIPÓTESE:** explicação possível que ainda precisa ser testada.
- **OBJETIVO:** resultado desejado.
- **PLANO:** intenção organizada para agir.
- **PENDENTE:** informação incompleta, contraditória ou sem confirmação.
- **HISTÓRICO:** registro válido para um período passado, não necessariamente atual.

## Metadados recomendados
```yaml
---
type: 
status: active
created: YYYY-MM-DD
updated: YYYY-MM-DD
source: 
confidence: 
tags: []
---
```

## Regras
1. Preservar a redação e o sentido da fonte original.
2. Não converter relato em fato documentado.
3. Não resolver contradições por palpite.
4. Não atribuir causalidade psicológica sem evidências e avaliação apropriada.
5. Não produzir diagnósticos.
6. Registrar datas como informadas e sinalizar datas aproximadas.
7. Distinguir estado atual, histórico, plano e hipótese.
8. Registrar correções sem apagar silenciosamente o histórico.
9. Evitar duplicação; preferir links internos.
10. Não criar links artificiais apenas para aumentar a conectividade.

## Privacidade
Conteúdo familiar, médico, emocional, financeiro e identificável é confidencial. Antes de sincronizar ou compartilhar, verificar as regras do repositório. Não inserir credenciais, senhas, tokens, documentos de identidade ou dados bancários completos.
