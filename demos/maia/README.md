# MAIA — Demonstração comercial v5

Projeto independente, não afiliado ao criador. URL de produção antiga preservada até aceitação da nova versão.

## Visões
- `/`: portfólio público com editorias e rede Instagram confirmada pelo usuário.
- `/marcas`: mídia kit (sem números de audiência inventados), possibilidades configuráveis e formulário que gera somente um rascunho de e-mail ou cópia.
- `/gestao`: painel demonstrativo sem autenticação com CRUD, ordem, visibilidade, links, apresentação e formatos, persistindo em `localStorage` exclusivamente no navegador do visitante. **Não é um painel de produção.**

## Execução local
`python3 -m http.server 8800 --directory .` serve apenas a raiz. Para testar as rotas sem reescrita do servidor, configure fallback para `index.html` ou teste em Workers.

## Fatos e placeholders
- Instagram `@ofcmaiazin` fornecido no contato comercial; link `https://www.instagram.com/ofcmaiazin/`.
- Não foi possível verificar vídeos oficiais, YouTube, TikTok, e-mail profissional ou métricas. Todos os exemplos estão identificados como ilustrativos.
- Fotografias ilustrativas de Unsplash, não representam MAIA nem suas publicações. Imagem de modelo masculino usada apenas no hero.
- Links de vídeos só têm função de assistir quando usuário incluir URL válida no painel.
- Sem APIs, envio real de formulário, banco compartilhado, armazenamento de leads ou autenticação.

## Direitos de imagem / UX
Imagens remotas de Unsplash; fontes Google Fonts com fallback; atenção a conexões lentas. `prefers-reduced-motion` desativa animações. Dados preenchidos no formulário ficam somente na aba para preparar email, sem transmissão.

## Para produção
Solicitar autorização e ativos do criador; validar links e números com fonte/período; autenticar painel, persistir em banco isolado, adicionar política de privacidade e integrar envio de lead com consentimento e medidas anti-spam. Não publicar dados privados ou inventados.