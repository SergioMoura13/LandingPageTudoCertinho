# Tudo Certinho — publicação na Vercel

Versão aprovada da landing page, com imagens, vídeos desktop/mobile, PT/EN e checkout Kiwify.

## Subir no repositório existente

1. Extraia este ZIP. Envie seu CONTEÚDO ao repositório, não o arquivo ZIP.
2. Coloque `public/`, `vercel.json` e este README na raiz do projeto que a Vercel utiliza. Não deixe uma pasta extra envolvendo esses arquivos.
3. Este pacote é um site estático independente. Faça backup da versão antiga e substitua os arquivos da LP antiga; não misture configurações de um framework antigo com este pacote.
4. No projeto existente da Vercel: Framework Preset = Other; Root Directory = raiz do projeto (./); Output Directory = public. Desative comandos personalizados antigos de build e instalação. O vercel.json já define build e instalação vazios.
5. Faça commit na branch vinculada à produção. Se o deploy automático estiver ativo, a Vercel publicará a alteração no endereço existente.
6. Confira na URL da Vercel: imagens do financeiro, abas, vídeo, mobile, PT/EN e botões de compra.

## Arquivos

- public/index.html: página de vendas.
- public/style.css: estilos responsivos.
- public/app.js: abas, ampliação das imagens, idiomas e seleção do vídeo.
- public/assets/: somente imagens e vídeos utilizados na página.
- vercel.json: configuração para servir a pasta public sem build.

Checkout: https://pay.kiwify.com.br/DFjL4y9

Não inclui painel de revisão nem dependências do ChatGPT Sites. Não precisa instalar Node ou rodar npm para editar os arquivos estáticos. Para uma prévia local com Python instalado, execute `python -m http.server 8080 --directory public` na pasta extraída e abra http://localhost:8080.

## Antes de divulgar

Confirme a entrega do sistema, dos vídeos e do ebook na Kiwify e o canal de suporte. O checkout e a entrega ficam na Kiwify; este pacote é a landing page. Não contém pixels ou ferramentas de análise configurados. As imagens e o vídeo continuam em português, mesmo quando o texto da página é alternado para inglês.
