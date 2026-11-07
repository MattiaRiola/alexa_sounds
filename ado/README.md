# Ado creepy sounds

Clip vocali di Ado (Voicemod), usati dalla modalita "Ado creepy house" in Home Assistant (`script.ado_creepy_engine`).

Sorgenti originali: file MP3 forniti dall'utente (48 kHz stereo, 128-171 kbps).
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
