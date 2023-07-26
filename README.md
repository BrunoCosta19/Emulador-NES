# cfxnes

Emulador JavaScript NES e biblioteca de emulação.

![cfxnes logo](logo.png)

:video_game: [Live demo](https://brunocosta19.github.io/Emulador-NES/#/)

:information_source: [Como usar o cfxnes como uma biblioteca](lib)

## Características

- Imagens ROM suportadas: iNES, NES 2.0.
- Mapeadores suportados: NROM, MMC1, MMC3, UNROM, CNROM, AOROM, BNROM,
  NINA-001, Sonhos coloridos.
- As imagens ROM podem ser carregadas do arquivo ZIP.
- Persistência de RAM alimentada por bateria (jogos salvos) no IndexedDB.
- Renderização usando WebGL (com fallback de API de tela).
- Modo tela cheia.
- Emulação de som usando Web Audio.
- Emulação de Zapper usando o mouse.
- Suporte para gamepad.
- Atalhos de teclas personalizáveis.
- Muitas opções de configuração.

## Navegadores suportados

- Chrome (últimas 2 versões)
- Firefox (últimas 2 versões)
- Opera (últimas 2 versões)
- IE 11, Borda >= 12
- Safári >= 9

## Problemas conhecidos

- Sem som no IE devido à falta de suporte de áudio da Web.
- Baixo desempenho no IE, Edge.
- Desempenho muito ruim em dispositivos móveis.
- Falhas gráficas ocasionais em jogos usando o mapeador MMC3.
- Veja [lista de jogos para baixar](https://www.romsgames.net/roms/nintendo/).



