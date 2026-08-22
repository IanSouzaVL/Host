# Tutorial — Skins Custom

## 1. Entre na pasta de skins

Link: https://github.com/IanSouzaVL/Host/tree/main/Skins (https://github.com/IanSouzaVL/Host/tree/main/Skins)

Nessa pasta ficam todas as skins disponíveis para os jogadores do servidor.

---

## 2. Escolha uma skin

O jogador deve clicar no arquivo .png que deseja usar.
Exemplo:

uniforme.png

---

## 3. Copie o endereço do arquivo

Copie a URL da barra de endereço do navegador.
Exemplo de URL normal do GitHub:

https://github.com/IanSouzaVL/Host/blob/main/Skins/uniforme.png

---

## 4. Transforme o link em RAW

1. Troque github.com por raw.githubusercontent.com.
2. Remova /blob.

Transformação completa:

Link original

https://github.com/IanSouzaVL/Host/blob/main/Skins/uniforme.png

Link RAW

https://raw.githubusercontent.com/IanSouzaVL/Host/main/Skins/uniforme.png

> Obs.: Não use o link que contém /blob/. O link precisa começar com https://raw.githubusercontent.com/.

---

## 5. Crie a skin no servidor

Use o comando:

/sr createcustom NomeDaSkin URL

Exemplo:

/sr createcustom uniforme https://raw.githubusercontent.com/IanSouzaVL/Host/main/Skins/uniforme.png

NomeDaSkin é o nome que o jogador escolherá para essa skin.

---

## 6. Use a skin

Aplique a skin com:

/skin NomeDaSkin

Exemplo:

/skin uniforme

O menu de skins também pode ser aberto com:

/skins

---

## 7. Exemplo completo (usando uniforme.png)

1. Abrir a pasta Skins no GitHub.
2. Abrir o arquivo uniforme.png.
3. Copiar a URL do GitHub:

https://github.com/IanSouzaVL/Host/blob/main/Skins/uniforme.png

4. Transformar em link RAW:

https://raw.githubusercontent.com/IanSouzaVL/Host/main/Skins/uniforme.png

5. Executar no servidor:

/sr createcustom uniforme https://raw.githubusercontent.com/IanSouzaVL/Host/main/Skins/uniforme.png

6. Aplicar a skin:

/skin uniforme

---

## 8. Importante

- O link precisa ser RAW; links com /blob/ não devem ser usados.
- A imagem deve ser um arquivo PNG válido do Minecraft.
- Não é necessário instalar nenhum mod no cliente para usar a skin.
- O comando é executado dentro do servidor Minecraft.

---

Resumo rápido:

1. Abra Skins/uniforme.png.
2. Copie a URL.
3. Troque github.com por raw.githubusercontent.com e remova /blob.
4. No servidor, execute /sr createcustom uniforme <link RAW>.
5. Use /skin uniforme para aplicar.

Pronto! Agora você tem sua skin personalizada no servidor.