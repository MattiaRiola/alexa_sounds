# alexa_sounds
Here all the sounds I use in my personal alexa

## Alexa-compatible encoding

Amazon SSML (`<audio src="...">`) only accepts MP3 **MPEG-2**, **48 kbps**, sample rate **16000/22050/24000 Hz**, max **240 s**, served over public HTTPS with a valid certificate. Stereo files, embedded cover art or other bitrates make Alexa answer with a "Simon says skill" error.

Files with the `_48k` suffix are encoded with:

```bash
ffmpeg -i input.mp3 -map 0:a -ac 1 -ar 24000 -b:a 48k -codec:a libmp3lame output_48k.mp3
```

| File | Contenuto |
|---|---|
| `alexa_be_at_home_48k.mp3` | "Be at Home" (Isamu Ohira) — `script.be_at_home_audio` |
| `ora_esatta_48k.mp3` | "Ora Esatta" (Stonehenge) — `script.ora_esatta_audio` |
| `ado_meme_48k.mp3` | meme "Ado Odo Odo Ado Abo Ado Odo Avocado Ado Obo Ado" — `script.ado_meme_audio` |
