# Bar Nova Cabana

Web estática lista para publicar en GitHub Pages.

## Publicar en GitHub Pages

1. Crea un repositorio llamado `bar-nova-cabana`.
2. Sube todos los archivos de esta carpeta.
3. En GitHub: Settings → Pages.
4. En “Build and deployment”, selecciona `Deploy from a branch`.
5. Elige `main` y carpeta `/root`.
6. Guarda y espera a que GitHub genere la URL.

La URL será parecida a:

`https://TU-USUARIO.github.io/bar-nova-cabana/`

## Generar QR

Cuando tengas la URL final, genera un QR con esa dirección. Puedes usar Canva, QR Code Monkey o este comando:

```bash
pip install qrcode[pil]
qr "https://TU-USUARIO.github.io/bar-nova-cabana/" > qr-nova-cabana.png
```

Después sustituye el QR del cartel por `qr-nova-cabana.png`.
