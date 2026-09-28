# Mods de som do TrokMods

Os sons de mod que tocam e se baixam na página de mods de som do blog [TrokMods](https://trokmods.blogspot.com/).

```
mods-audio/armas/<grupo>/<papel>-NN.wav     tiro-07.wav, eco-01.wav...
mods-audio/hitsound/hitsound-NN.wav
mods-audio/sons.tsv                         a planilha: uma linha por arquivo
```

- **`<grupo>`** é o conjunto de armas que o jogo faz tocar o MESMO arquivo. Trocar o tiro da AK troca o da M4 junto.
  Os grupos são `ak-m4`, `deagle-9mm` (a 9mm toca o tiro da Deagle mais rápido), `uzi-tec9`, `mp5`, `shotgun` (as
  três), `sniper-country` e `silenciada`. Quem ainda não tem arma definida fica em `sem-arma`.
- **`<papel>`**: `tiro`, `tiro-com-eco`, `eco`, `recarga`, `sem-municao` ou `grave`.
- **`sons.tsv`** diz, para cada arquivo:
  - o nome que a página mostra;
  - o som do jogo que ele substitui (GENRL, Bank 137), que é o que o botão "original" toca;
  - em que armas a comunidade já usou o mesmo áudio;
  - com que nomes ele circula (`sound_007z (25).wav`...).

Os índices que a página lê (`armas.json` e `hitsound.json`) saem da planilha pelo `ferramentas/indice-mods-audio.js`
do blog. A classificação dos sons que vieram da comunidade é do `ferramentas/renomeia-sons-mod.js`: o grupo e o papel
saem dos nomes com que cada áudio circulava. O Victor revisa ouvindo, na página.
