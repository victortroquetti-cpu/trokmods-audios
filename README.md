# Áudios do TrokMods

Os arquivos de som que tocam e se baixam nas listas do blog [TrokMods](https://trokmods.blogspot.com/).

- **`backup-audio/`**: os efeitos sonoros originais do GTA San Andreas (PC, versão 1.0), um WAV por som,
  na taxa e na duração do jogo, para servir de referência a quem faz mod de som.
  - `GENRL/`, `FEET/`, `PAIN_A/`, `SCRIPT/`: `banco-NNN/som-NNN.wav`
  - `GENRL.json`, `FEET.json`, `PAIN_A.json`, `SCRIPT.json`: o índice que a página lê (nomes, duração, ponto de
    loop, tipo, arma e veículo)
  - do `SCRIPT` entram os efeitos, os minigames, o rádio da polícia, os crupiês e os treinadores (89 banks, com o
    número do Bank igual ao do jogo); os diálogos de missão e os telefonemas ficaram fora. Cada som traz o `id` que o
    SA-MP toca no `PlayerPlaySound` (2000 + (Bank - 1) x 200 + (som - 1); o 17802 é o sino da academia)

Os sons originais são da Rockstar North. Os nomes dos bancos e dos sons, e quais armas e veículos usam cada
som, vêm da engenharia reversa do [gta-reversed](https://github.com/gta-reversed/gta-reversed).
As músicas das rádios não estão aqui.
