# VolumiDrurit

Kalkulator i thjeshtë për llogaritjen e volumit të drurit, i optimizuar për telefon dhe desktop.

## Përdorimi lokal

```bash
python3 -m http.server 8000
```

Pastaj hap:
- `http://localhost:8000/volumidrurit.html`

## Formula

`V = π × d² × h × f / 40000`

- `d`: diametri në cm
- `h`: lartësia në m
- `f`: koeficienti sipas llojit të drurit

## PWA (App në telefon)

Aplikacioni ka:
- `manifest.webmanifest`
- `service worker (sw.js)`

Kjo lejon instalimin në home screen dhe përdorim bazik offline.
