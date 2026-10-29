# Rota 404 — página da equipe

Página de apresentação da equipe Rota 404, da Universidade Estadual de Santa Cruz (UESC), para o Hack Turismo Costa do Cacau. É um site estático: basta publicar o `index.html` no GitHub Pages, Vercel ou outro serviço gratuito de hospedagem estática.

## Personalizar integrantes

As cinco fotos recebidas já estão em `fotos/` e aparecem na página. Para trocar uma delas, substituam o arquivo correspondente mantendo o nome, ou alterem o caminho no HTML. Os perfis resumidos também estão preenchidos; revisem nomes e descrições antes da publicação.

1. Para atualizar uma foto, substituam o arquivo correspondente dentro de `fotos/`. Sugestão: JPG ou WebP em formato retrato.
2. Em `index.html`, cada perfil tem uma imagem como:

   ```html
   <img src="fotos/nome-sobrenome.jpg" alt="Nome Sobrenome, integrante da equipe Rota 404">
   ```

   Mantenham o `<span class="number">01</span>` que vem logo depois da imagem.
3. Atualizem nome, papel, biografia e texto alternativo (`alt`) da imagem conforme necessário.

## Publicar gratuitamente

### GitHub Pages

Enviem estes arquivos para um repositório GitHub. No repositório, abram **Settings → Pages**, escolham a publicação a partir da branch principal (normalmente `main`) e a pasta raiz (`/`). O GitHub Pages publica o `index.html` como página inicial.

### Vercel

Importem o repositório GitHub na Vercel. Como este projeto é HTML/CSS estático, não precisa de build: deixem o comando de build vazio e publiquem a pasta raiz (`.`).

## Arquivos

- `index.html`: página, estilos e conteúdo.
- `fotos/`: pasta a criar para as fotos dos cinco integrantes.
