# QA — MAIA v5

## Testes executados localmente

- Playwright Chromium offline: home, marcas e gestão.
- Larguras testadas 320, 360, 390, 430, 768, 1024 e 1440 px: sem overflow horizontal após correção.
- Galeria com três exemplos.
- Formulário de proposta: campos preenchidos, resumo e link de rascunho gerados sem envio real.
- CRUD localStorage: adicionar, editar, ocultar e visualização refletida na página pública no mesmo navegador.
- Sem erros JavaScript detectados no teste.

## Limitações

- Teste de navegador local usa HTML/CSS/JS embutidos por bloqueio de navegação local da ferramenta; não testa rede real nem recursos externos.
- Fotos externas não carregaram no navegador local; imagens são URLs do Unsplash e dependem de disponibilidade pública.
- Player real, YouTube, TikTok e dados estatísticos não verificados: não atribuídos ao MAIA.
- Painel apenas localStorage, sem autenticação e sem sincronização entre dispositivos.
- Formulário não faz envio.