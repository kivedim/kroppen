# Kroppen i 3D

Interaktiv 3D-anatomi i tecknad stil med lager (hud, muskler, skelett, organ, blodkärl), klickbara delar och fakta på svenska och engelska. Egen WebGL-motor, inga externa bibliotek.

## Källa och licens för 3D-data
3D-modellerna kommer från **BodyParts3D**, © The Database Center for Life Science (DBCLS), licensierade under
[Creative Commons Attribution-Share Alike 2.1 Japan](https://creativecommons.org/licenses/by-sa/2.1/jp/).
De har förenklats, slagits ihop och färgsatts för den här appen. Lungorna och ryggmärgen finns inte i BodyParts3D och har räknats fram utifrån luftvägsträdet, lungkärlen och ryggradens kotkanal. Den bearbetade datan (`body.bin`, `body.json`) delas under samma licens.
Källa: https://dbarchive.biosciencedbc.jp/en/bodyparts3d/

## Egna ljudfiler (valfritt)
Lägg mp3-filer i `audio/sv/<id>.mp3` och `audio/en/<id>.mp3`, och lista dem i `audio/index.json`, till exempel
`{"sv":["heart","lungs"],"en":["heart"]}`. Delar som saknar ljudfil läses upp med telefonens talsyntes.
