# FreeTube para FLinux-JC64

Paquete `.tcz` de **FreeTube (cliente de YouTube con API de Invidious)** empaquetado para
[Tiny Core](https://www.tinycorelinux.net) **de 64 bits**.

> ⚠️ **SOLO 64 bits.** Es exclusivo para **FLinux-JC64** (kernel 6.18.35 x86_64).
> **No** sirve para la edición de 32 bits (FLinux-JC). Si buscas YouTube en 32 bits,
> usa FLTubePlus.

## Release v1.0

Archivos (descargar los tres):

- `freetube.tcz` — el paquete (127 361 024 bytes)
- `freetube.tcz.dep` — dependencias (23 paquetes del repo oficial)
- `freetube.tcz.md5.txt` — digest para verificar

## Instalación

```sh
md5sum -c freetube.tcz.md5.txt   # debe decir OK
sudo tce-load -i freetube.tcz
```

El icono aparece automáticamente en el wbar.

## Verificación

MD5 esperado: `3782d0a6b5e8d286769e09740c09c2b5`

GPL-3.0.
