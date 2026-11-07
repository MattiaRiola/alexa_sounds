# Ado creepy sounds

Clip vocali di Ado (Voicemod), usati dalla modalita "Ado creepy house" in Home Assistant (`script.ado_creepy_engine`).

Sorgenti:
- 10 file MP3 forniti dall'utente (48 kHz stereo, 128-171 kbps);
- video [*1 hour of silence occasionally broken up by Ado*](https://www.youtube.com/watch?v=HKeKBqvsy64),
  da cui sono stati isolati 19 suoni (16 aggiunti, 3 scartati come doppioni: `gyaru` due volte,
  identico al `gyaru.mp3` già presente, e `yamero` a 13:25, identico a `scream.mp3`).
Ogni clip e' stata rifilata, normalizzata a -1.5 dBFS di picco (guadagno max +12 dB) e codificata per Amazon SSML:
MP3 MPEG-2, mono, 24000 Hz, 48 kbps, senza cover art.

`loca_loca.mp3` e' un loop continuo di "loca loca": non avendo pause nette e' stato tenuto intero (17 s).
Tutti gli altri clip sono sotto i 4 s.

**Durata minima (07/11/2026).** Alexa rifiuta gli audio molto corti: con clip da 0,4-0,6 s l'Echo
risponde "non riesco ad accedere alla skill per riprodurre quell'audio" (messaggio fuorviante: il file
e' raggiungibile, e' la durata). I clip sotto 1,7 s sono quindi stati riportati a **1,75 s** aggiungendo
silenzio in coda; il suono vero e' solo la parte iniziale indicata qui sotto.

| File | Suono | Durata |
|---|---|---|
| `cringe.mp3` | Ado - "cringe" | 1.75 s (0.62 di suono) |
| `gyaru.mp3` | Ado - "gyaru" | 1.75 s (1.06 di suono) |
| `heheh.mp3` | Ado - "heheh" | 3.70 s |
| `hehe.mp3` | Ado - "hehe" | 1.75 s (0.38 di suono) |
| `laugh.mp3` | Ado - risata | 3.12 s |
| `oooo.mp3` | Ado - "oooo" | 1.75 s (1.49 di suono) |
| `scream.mp3` | Ado - urlo | 2.33 s |
| `yamero.mp3` | Ado - "yamero" | 3.98 s |
| `nyau_nyau.mp3` | Ado - "nyau nyau" | 3.05 s |
| `loca_loca.mp3` | Ado - "loca loca" (loop intero) | 16.90 s |

### Video 2 (HKeKBqvsy64)

| File | Video | Suono | Durata file |
|---|---|---|---|
| `ahhh.mp3` | 0:51 | ahhh | 1.80 s |
| `doki_doki.mp3` | 2:25 | doki doki | 3.50 s |
| `ohayo.mp3` | 5:11 | ohayo | 1.80 s |
| `dr_stone_op.mp3` | 10:20 | dr stone op | 5.66 s |
| `sugoi.mp3` | 10:37 | sugoi | 1.80 s |
| `ado_gibberish.mp3` | 17:07 | ado gibberish | 2.88 s |
| `ah.mp3` | 21:30 | ah | 1.80 s |
| `ohayo_sekai.mp3` | 24:09 | ohayo sekai | 4.06 s |
| `uregh.mp3` | 30:57 | uregh | 1.80 s |
| `warning_horny.mp3` | 35:16 | warning horny | 1.80 s |
| `hah.mp3` | 40:36 | hah | 1.80 s |
| `ado_gibberish_v2.mp3` | 40:38 | ado gibberish v2 | 1.80 s |
| `tidei.mp3` | 45:48 | tidei | 1.80 s |
| `ado_sound.mp3` | 47:40 | ado sound | 1.80 s |
| `sconosciuto.mp3` | 50:19 | sconosciuto | 1.80 s |
| `cho_kawaii.mp3` | 54:27 | cho kawaii | 2.18 s |
