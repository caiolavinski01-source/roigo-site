# Como publicar no GitHub (pelo navegador, sem instalar nada)

O site do GitHub aceita no máximo **100 arquivos por envio**. Este projeto tem 107,
então são **2 envios**. Arraste sempre as pastas inteiras, para os caminhos ficarem certos.

## 1. Criar o repositório
1. Acesse https://github.com/new
2. Nome: `roigo-site` · marque **Public** · **Create repository**.

## 2. Envio 1 — pasta `wp-content` (96 arquivos)
1. Na página do repositório vazio, clique em **uploading an existing file**.
2. Abra a pasta `roigo-site` no Explorador e arraste **só a pasta `wp-content`** para a área de upload.
3. Espere terminar de carregar e clique em **Commit changes**.

## 3. Envio 2 — o resto (11 arquivos)
1. No repositório, clique em **Add file > Upload files**.
2. Arraste de dentro de `roigo-site`: `index.html`, `.nojekyll`, `README.md`,
   `COMO-PUBLICAR-NO-GITHUB.md` e as pastas `assets`, `ext` e `wp-includes`.
   (`.nojekyll` é um arquivo oculto: no Explorador, **Exibir > Mostrar > Itens ocultos**.)
3. **Commit changes**.

## 4. Colocar o site no ar (GitHub Pages)
1. No repositório: **Settings > Pages**.
2. *Source*: **Deploy from a branch** · Branch **main** · pasta **/(root)** · **Save**.
3. Em 1–2 minutos o site fica em `https://SEU-USUARIO.github.io/roigo-site/`.

**Domínio próprio** (ex.: roigo.com.br): *Settings > Pages > Custom domain* e, no provedor do
domínio, crie um registro **CNAME** apontando para `SEU-USUARIO.github.io`.

> Alternativa: o **GitHub Desktop** (https://desktop.github.com) envia a pasta inteira de uma vez.
