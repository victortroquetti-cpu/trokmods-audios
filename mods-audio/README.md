# Mods de som do TrokMods

Os sons de mod que tocam e se baixam na página de sons de arma do blog [TrokMods](https://trokmods.blogspot.com/).
A página lê o `armas.json`, que o `ferramentas/indice-mods-audio.js` do blog monta a partir destas pastas.

## Como entra um mod

```
mods-audio/armas/<arma>/<mod>/AK_SHOT_L.wav
mods-audio/armas/<arma>/<mod>/info.txt
```

- **`<arma>`**: `pistola-9mm`, `pistola-com-silenciador`, `desert-eagle`, `shotgun`, `sawn-off`, `combat-shotgun`, `uzi`,
  `mp5`, `tec-9`, `ak-47`, `m4`, `country-rifle`, `sniper-rifle`, `minigun` ou `lanca-foguete`.
- **`<mod>`**: uma pasta por mod, com qualquer nome (`ak-realista`, `deagle-cod`...).
- **O nome do arquivo diz qual som do jogo ele substitui**: `AK_SHOT_L.wav` substitui o AK_SHOT_L (GENRL, Bank 137,
  som 004). Os nomes são os da lista de sons do blog. Com esse nome, a página mostra o que o arquivo substitui e
  ganha o botão de ouvir o original. Arquivo com outro nome entra também, só sem essas duas coisas.
- **`info.txt`** (opcional), uma linha por campo:

  ```
  Nome: AK realista
  Autor: Fulano
  Fonte: https://link-da-pagina-original
  ```

WAV é o melhor formato (a página mostra a taxa e a duração); MP3 e OGG tocam, mas sem esses dados.
