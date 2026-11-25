# Avisos de terceros (NOTICE)

LD Studio es un proyecto no oficial. Este archivo lista componentes y datos de terceros usados o
reutilizados, con su licencia.

## Código y algoritmos

| Componente | Licencia | Uso |
|---|---|---|
| [node-ld](https://github.com/ags131/node-ld) — Adam Shumann | **ISC** | Algoritmos de TEA, derivación de clave, PWDGen y `UpgradeManager`. Reimplementados en `app/src/main/assets/js/ld.js`; el aviso ISC se conserva acá. |
| [Ellerbach/LegoDimensions](https://github.com/Ellerbach/LegoDimensions) — Laurent Ellerbach | **MIT** | Tablas de referencia de personajes/vehículos y habilidades (`legacy/reference/*.cs`). El encabezado MIT original se conserva en esos archivos. |

Texto de la licencia ISC de node-ld:

```
Copyright (c) 2015, Adam Shumann

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY
SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION
OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN
CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

Texto de la licencia MIT de Ellerbach/LegoDimensions:

```
The MIT License (MIT)

Copyright (c) Laurent Ellerbach and contributors

All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Recursos de Android

| Componente | Licencia | Uso |
|---|---|---|
| AndroidX AppCompat y Material Components (Google) | **Apache 2.0** | Recursos `abc_*`, `design_*`, `notification_*` y `select_dialog_*` en `app/src/main/res/`. Texto incluido en el APK (`assets/legal/Apache-2.0.txt`): https://www.apache.org/licenses/LICENSE-2.0 |

## Marcas

"LEGO", "LEGO Dimensions", el logo LEGO y los nombres de personajes/vehículos son marcas de
The LEGO Group y/o sus licenciantes. Se usan únicamente con fines descriptivos e informativos. Este
proyecto no está afiliado, patrocinado ni respaldado por The LEGO Group ni por Warner Bros.

## Imágenes

El logo y el ícono de LD Studio son propios (`art/logo.svg`, rediseñados en la 4.2.3). La imagen del tag NFC (`nfc_tag.png`) es
propia desde la 4.2.2. Desde la 4.2.2 el APK no incluye arte de LEGO Dimensions (se quitó
`background.jpg`).
