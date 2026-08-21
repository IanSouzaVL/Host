# Textura Precoce — publicação e SHA-1

Sempre que atualizar `TexturaPrecoce.zip`, gere um novo SHA-1 e atualize-o no
`server.properties` do servidor. O Minecraft usa esse valor para identificar a
versão do resource pack; se ele estiver desatualizado, o cliente pode manter uma
cópia em cache ou recusar o download.

## Gerar o SHA-1

No diretório que contém o ZIP, execute:

```bash
sha1sum TexturaPrecoce.zip
```

O primeiro valor retornado é o SHA-1. Exemplo:

```text
f28839b95d2017f37068e61d4baff3d995e89fd1  TexturaPrecoce.zip
```

No Windows (PowerShell), use:

```powershell
(Get-FileHash .\TexturaPrecoce.zip -Algorithm SHA1).Hash.ToLower()
```

## Atualizar o servidor

Depois de enviar o novo ZIP para a branch `main`, substitua o hash no arquivo
`server.properties`:

```properties
resource-pack=https\://raw.githubusercontent.com/IanSouzaVL/Host/main/TexturaPrecoce.zip
resource-pack-sha1=COLE_O_NOVO_SHA1_AQUI
```

Por fim, reinicie o servidor. A URL deve usar `raw.githubusercontent.com`; links
com `github.com/.../blob/...` apontam para a página do GitHub, não para o ZIP.
