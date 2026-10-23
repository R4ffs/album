# Álbum dos Contratos — como usar

## O que tem aqui

- `index.html`: o álbum (e a tela de cadastro, no endereço com `#cadastro`)
- `figurinhas.js`: os seus dados (links e a lista de figurinhas). É o único arquivo que você edita no dia a dia.
- `imagens/`: onde ficam os prints de cada figurinha

## 1. Colocar no ar (uma vez só)

1. Crie uma conta em github.com.
2. Clique em **New repository**. Nome: `album`. Deixe como **Public** e clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file** (ou **Add file > Upload files**).
4. Arraste `index.html`, `figurinhas.js`, `COMO-USAR.md` e a pasta `imagens`. Clique em **Commit changes**.
5. Vá em **Settings > Pages**. Em **Branch**, escolha `main` e `/ (root)` e clique em **Save**.
6. Em um ou dois minutos o álbum fica no ar em `https://SEUUSUARIO.github.io/album/`.

## 2. Configurar os links

No GitHub, abra `figurinhas.js`, clique no lápis (editar) e preencha:

- `linkContrato`: o link da sua página do LivePix
- `linkTwitch`: o link do seu canal

Clique em **Commit changes**.

## 3. Depois de cada live: cadastrar as figurinhas

1. **Print:** no OBS, vá em Configurações > Atalhos e procure o atalho de captura de tela da saída. Aperte quando o contrato for cumprido.
2. **Clipe:** na Twitch, abra o clipe, clique em Compartilhar e copie o link.
3. **Cadastro:** abra `https://SEUUSUARIO.github.io/album/#cadastro`, preencha tudo e clique em **Copiar linha**.
4. **Print no GitHub:** entre na pasta `imagens`, clique em **Add file > Upload files** e suba o print com o nome que a tela de cadastro mostrou (ex: `013.jpg`).
5. **Figurinha no GitHub:** edite `figurinhas.js`, cole a linha logo abaixo de `cole as novas figurinhas abaixo desta linha` e clique em **Commit changes**.

Em um minuto a figurinha aparece no álbum.

## Dicas

- **Brilhante:** escolha "Brilhante" na raridade pros contratos mais épicos. Dá pra deixar o chat votar.
- **Link de cada figurinha:** dentro da figurinha tem o botão **Copiar link**. Ele abre o álbum já mostrando aquela figurinha. Bom pra mandar pra quem pagou.
- **Baixar figurinha:** o botão gera uma imagem da figurinha pra pessoa postar no story.
- **O clipe só toca dentro do álbum depois que ele estiver no ar** (no GitHub). Abrindo o arquivo direto no PC, aparece só o link.
- **Print grande demais?** Converta pra JPG antes de subir (o site squoosh.app faz isso de graça). Fica mais leve pra carregar.
- **Errou alguma coisa?** É só editar a linha da figurinha no `figurinhas.js`. Se o álbum mostrar uma faixa amarela dizendo que as figurinhas não carregaram, é sinal de que o `figurinhas.js` quebrou: provavelmente faltou uma vírgula ou aspas na última linha que você colou.
