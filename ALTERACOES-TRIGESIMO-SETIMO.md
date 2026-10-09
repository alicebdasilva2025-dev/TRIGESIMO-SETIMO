# LiDire — TRIGÉSIMO SÉTIMO

Base: `trigesimo-sexto.zip` (projeto completo).

## Alterações
1. **Botão de excluir familiar dentro do cartão:** ajustados flexbox, dimensões, quebra de linha e limites de largura dos cartões e ações em telas pequenas.
2. **Termos de Uso e Política de Privacidade no cadastro:** os links agora abrem o conteúdo correspondente em uma janela/modal, em vez de exibir uma mensagem de que os documentos estariam disponíveis futuramente.
3. **Aceite obrigatório:** mantido o checkbox obrigatório no cadastro e a validação no envio do formulário; a criação da conta só prossegue se estiver marcado.

## Validação
`app.js` e `index.js` passaram em `node --check`. O CSS foi revisado por alteração textual. Testar em dispositivo móvel e no Worker publicado antes de considerar validado em produção.
