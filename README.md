# Mapa Interativo Auto Atendimento — Subway

Nova atualização: menu independente “O QUE APARECE NO KDS?” com capturas numeradas e legendas em HTML.

- KDS 1 — QUENTE: vermelho (#dc2626)
- KDS 2 — FRIOS: azul (#2563eb)
- KDS 3 — EXPEDIÇÃO: verde (#16a34a)
- Itens repetidos entre telas identificados explicitamente nas legendas.
- A legenda não está gravada nas imagens; fica no HTML do painel.
- Ao abrir outro menu, o painel reinicia no topo.

Abra `index.html` em servidor local ou publique no GitHub Pages para testar os vídeos incorporados.


## Correções desta versão — mobile e controle central
- O botão central agora fecha a orientação aberta e recolhe todos os menus no primeiro toque/clique.
- Com o painel fechado, o botão alterna entre expandir e recolher os menus.
- O mesmo comportamento é aplicado no desktop e no mobile.
- No mobile, o botão central fica no fluxo da página, menor e sem sobrepor os cards.
- O card “O QUE APARECE NO KDS?” usa o mesmo acabamento claro do desktop também no mobile.


## Atualização — chamar novamente a senha pelo KDS 3
- O antigo menu “Como Voltar um Pedido no KDS?” foi reaproveitado como “Como chamar novamente a senha?”.
- O procedimento foi delimitado ao KDS 3 — Expedição.
- A sequência de quatro GIFs foi mantida: retorno ao lado da lupa, confirmação, restaurar pedido e finalizar restauração.
- A orientação informa que, ao concluir a restauração no KDS 3, a senha volta para a faixa PRONTO no Painel de Senhas.
- O antigo card separado “Chamar senha novamente” foi retirado para evitar duas orientações concorrentes para a mesma finalidade.

## Atualização — resultado da chamada de senha no painel
- O menu “Como chamar novamente a senha?” diferencia a primeira chamada da restauração de uma senha já chamada.
- A primeira chamada é ilustrada pela captura do alerta visual em tela cheia.
- A restauração pelo KDS 3 é ilustrada pela captura do Painel de Senhas com destaque na coluna PRONTO e no cartão da senha.
- O texto reforça que chamar novamente não repete o alerta inicial: a restauração apenas devolve a senha à coluna PRONTO.
- O procedimento continua exclusivo do KDS 3 — EXPEDIÇÃO; não executar no KDS 1 ou KDS 2.
- Os quatro GIFs originais foram preservados e mantidos na mesma ordem.


## Correção — dois procedimentos independentes
- Restaurado o menu **“Como voltar um pedido no KDS?”**, destinado a pedido baixado por engano no **KDS 1 — QUENTE ou KDS 2 — FRIOS**.
- Criado/mantido separadamente o menu **“Como chamar novamente a senha?”**, exclusivo do **KDS 3 — EXPEDIÇÃO**.
- Os dois menus usam a sequência de quatro GIFs de restauração, com textos contextualizados para cada finalidade.
- Somente o menu de chamada novamente da senha apresenta a comparação do alerta da primeira chamada com o retorno à faixa **PRONTO** no Painel de Senhas.
- Nenhum dos dois procedimentos substitui o outro; ambos ficam disponíveis no mapa.


## Correção de layout — linhas e Painel de Senhas
- Todas as linhas de conexão são geradas entre o núcleo central e cada menu, incluindo o menu Painel de Senhas.
- As linhas são guias visuais, não áreas clicáveis; os próprios cartões continuam sendo os controles.
- Ao recolher os menus, as linhas são removidas; ao expandir, são recalculadas e reaparecem conectadas aos cartões.
- O menu de chamada novamente foi classificado como **Painel**, com destaque vermelho, e renomeado para **Como chamar novamente a senha no Painel de Senhas?**
