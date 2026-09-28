# Mods de som do TrokMods

Os sons de mod que tocam e se baixam na página de mods de som do blog [TrokMods](https://trokmods.blogspot.com/).
Cada categoria tem a sua pasta e o seu índice, que o `ferramentas/indice-mods-audio.js` do blog monta a partir
das pastas: `armas.json` e `hitsound.json`.

## Armas

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

## Hitsound

```
mods-audio/hitsound/<mod>/hit.wav
mods-audio/hitsound/<mod>/info.txt
```

- Uma pasta por hitsound, com qualquer nome. O arquivo pode ter qualquer nome; se a pasta tiver mais de um, cada
  um aparece separado.

## O info.txt (opcional, nas duas categorias)

```
Nome: AK realista
Autor: Fulano
Fonte: https://link-da-pagina-original
```

WAV é o melhor formato (a página mostra a taxa e a duração); MP3 e OGG tocam, mas sem esses dados.
