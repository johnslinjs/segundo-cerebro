---
type: TechnicalGuide
status: active
tags:
  - obsidian
  - engram
  - github
  - sincronização
---

# Obsidian, Engram e GitHub — funcionamento

## Papéis
- **Obsidian:** ambiente de leitura, edição, navegação e utilização diária do cofre.
- **Engram AI Memory:** conector utilizado nesta implantação para criar, ler e atualizar notas no cofre e sincronizá-las com o Obsidian conectado.
- **GitHub:** repositório remoto que, segundo a configuração informada pelo titular, participa de sincronização bidirecional com o Obsidian.

## Fluxo pretendido
1. Uma nota é criada ou editada no Obsidian.
2. O mecanismo de sincronização configurado envia a alteração ao GitHub.
3. Uma alteração remota no GitHub é refletida de volta no Obsidian.
4. O Engram pode criar ou atualizar notas no cofre conectado; a propagação ao GitHub depende do funcionamento da sincronização configurada.

**Limite de verificação:** a gravação das notas pelo Engram foi confirmada no cofre. A entrega efetiva de cada arquivo ao repositório GitHub remoto não foi verificada independentemente nesta implantação.

## Atenção a conflitos
- Evite editar o mesmo arquivo simultaneamente em dois lugares.
- Aguarde a sincronização terminar antes de fazer alterações grandes.
- Antes de renomear ou mover pastas, confirme como o plugin trata conflitos e links.
- Mantenha histórico de versões e backup.
- Nunca coloque tokens, senhas, chaves ou credenciais em notas.
- Verifique se o repositório é privado e se arquivos sensíveis estão excluídos.

## GitHub Wiki não é necessariamente o mesmo que o repositório
O GitHub possui um recurso chamado **Wiki**, com páginas de documentação separadas do conteúdo principal do repositório. Um cofre Obsidian sincronizado com o GitHub normalmente armazena arquivos Markdown no repositório. Isso não significa, por si só, que esses arquivos estejam publicados na aba Wiki do GitHub.

Este manual está sendo criado como notas Markdown dentro do cofre, para permanecer acessível no Obsidian e seguir o mecanismo de sincronização já configurado. Se o titular quiser também a aba Wiki nativa do GitHub, será necessário verificar e configurar esse recurso separadamente.

## Checklist de conferência
- [ ] Cofre correto selecionado no Obsidian.
- [ ] Repositório remoto correto.
- [ ] Repositório privado.
- [ ] Sincronização concluída sem conflitos.
- [ ] Arquivos Markdown aparecem no repositório.
- [ ] Exclusões de arquivos sensíveis conferidas.
- [ ] Backup disponível.
