# Conectividade e infraestrutura municipal

Apresentação web da CI 598/2026, Prefeitura Municipal de Ibirité. Código estático em HTML, CSS e JavaScript, sem dependências, servidor de aplicação ou login. Layout adaptável, navegação por toque e teclado, índice com busca, imagens ampliáveis, notas, modo leitura e impressão.

## Publicar pelo navegador no GitHub Pages

1. Crie um repositório público. Sugestão de nome: `conectividade-ibirite`.
2. Extraia o ZIP no computador. Em **Add file > Upload files**, envie os arquivos extraídos e a pasta `assets`, preservando sua estrutura. Não envie somente o ZIP.
3. Verifique que `index.html`, `style.css`, `app.js` e `assets/` estão na raiz do repositório, sem outra pasta intermediária.
4. Confirme o envio com **Commit changes**.
5. Abra **Settings > Pages**. Em **Source**, escolha **Deploy from a branch**.
6. Escolha **main** e **/ (root)** e clique em **Save**.
7. Aguarde a publicação. O endereço aparece na própria tela Pages. O formato habitual é `https://SEU-USUARIO.github.io/conectividade-ibirite/`.

O arquivo `.nojekyll` é opcional para este conteúdo, mas está incluído para desativar o processamento Jekyll. Se não aparecer no explorador, o envio dos demais arquivos mantém a apresentação funcional.

Documentação oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Conteúdo do pacote

- `index.html`: página e controles de navegação.
- `style.css`: identidade visual, adaptação às telas e impressão.
- `app.js`: conteúdo dos 21 slides e interações.
- `assets/`: fotografias e relatório assinado usado como fonte.
- `.nojekyll`: publicação como site estático.

Os caminhos dos arquivos são relativos para funcionar também sob o nome do repositório. Mantenha nomes e maiúsculas/minúsculas exatamente como no pacote.

## Editar

Edite a lista `slides` em `app.js` para alterar textos, notas e fotos. Edite `style.css` para cores e tipografia. Atualizações na branch publicada atualizam o site após nova implantação pelo GitHub.

## Uso

Setas e gestos horizontais navegam. Home e End vão ao início/fim. O índice permite buscar temas. Fotos podem ser ampliadas. Leitura exibe todos os slides. Imprimir/salvar PDF usa a função nativa do navegador. Tela cheia depende do suporte do navegador; no celular, todos os demais controles continuam disponíveis.

## Acesso público

Não há autenticação neste pacote. Após a publicação pública, visitantes com o link podem consultar a apresentação, as fotos e o PDF assinado incluído. Este pacote não contém credenciais nem a configuração do serviço de hospedagem privado anterior.

## Verificações

Sintaxe JavaScript, presença do conteúdo, caminhos das imagens e arquivo PDF foram verificados. O projeto foi preparado para navegadores modernos; não foi executada validação visual em todos os aparelhos Android/iOS e navegadores.
