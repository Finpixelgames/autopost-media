# FinPixel Autopost Media

Julkinen media-hosting FinPixelin somejulkaisu-automaatiolle. Instagram/TikTok hakevat
julkaistavat kuvat/videot naiden raw-URLien kautta (alustat vaativat julkisen media-URLin).
Sisalto on joka tapauksessa julkista markkinointimateriaalia.

## Rakenne

Julkaisukelpoiset leikkeet projekteittain, jotta autopost-moottori loytaa oikean:

```
<projekti>/clips/<paivamaara>_<aihe>_<muoto>.mp4
```

Esim. `tier-one/clips/2026-09-19_battle_action_9x16.mp4`. Projektiavaimet tasmaavat
social-autopost `config.yaml`:n content_rotationiin. Raaka materiaali ja editointi tapahtuvat
paa-repon `marketing/`-kirjastossa; vain valmiit leikkeet julkaistaan tanne.
