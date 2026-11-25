# SFX Pack para editores 🎬🔊

Pack gratuito de **efectos de sonido para editar vídeo** (DaVinci Resolve, Premiere Pro, Final Cut, CapCut, After Effects…). Son todo WAV listos para arrastrar al timeline, **gratis y para uso comercial**.

| Pack | Sonidos | Formato | Licencia | Dónde está |
| --- | --: | --- | --- | --- |
| **SFX Kit** (Wyzowl) | 320 | WAV 48 kHz / 24-bit | CC0 (sin crédito) | [`wyzowl-sfx-kit/`](wyzowl-sfx-kit/) |
| **Interface Sounds** (Kenney) | 100 | WAV | CC0 (sin crédito) | [`kenney-interface-sounds/`](kenney-interface-sounds/) |
| **FilmCow Recorded SFX** | ~3.800 | WAV 48 kHz / 24-bit | Royalty-free (ver abajo) | [`filmcow/`](filmcow/) (submódulo, opcional) |

**Total: unos 4.200 efectos.**

## Descargar

**Solo lo esencial (420 sonidos, ~65 MB):** botón verde **Code → Download ZIP**, o:

```bash
git clone https://github.com/juantoc7755-alt/sfx-pack-editores.git
```

**Con FilmCow incluido (~2 GB más):**

```bash
git clone --recursive https://github.com/juantoc7755-alt/sfx-pack-editores.git
```

> Si descargas el ZIP, la carpeta `filmcow/` saldrá vacía. Descárgalo desde su web oficial: <https://filmcow.itch.io/filmcow-sfx>.

## Qué hay dentro

### `wyzowl-sfx-kit/` — 320 sonidos para vídeos de marca y motion graphics
Organizados por carpetas: whooshes, swishes, swipes, reverse whooshes, risers y fallers, impactos, cinematic hits, booms y bass, pops, aparecer/desaparecer, cambios de forma, interfaz, teclado, escritura, teléfono, mecánicos, foley, objetos cotidianos, notificaciones, tonos, shimmers, **logo stings**, celebración, tiempo, dinero, digital/glitch y datos.

- [`catalogue.md`](wyzowl-sfx-kit/catalogue.md): lista de todos los sonidos con una línea de descripción. Busca aquí por palabra.
- [`GUIDE.md`](wyzowl-sfx-kit/GUIDE.md) y [`sounds.json`](wyzowl-sfx-kit/sounds.json): para cada sonido indican cuándo usarlo, cuánto dura, dónde está su punto de sincronía y cuánto bajarlo bajo la voz. Sirve para editar con IA (Claude, ChatGPT…).

### `kenney-interface-sounds/` — 100 sonidos de interfaz
Clics, select, toggles, switches, scroll, abrir/cerrar, maximizar/minimizar, confirmaciones, errores, glitches, cristal… Ideales para demos de apps, webs y textos animados.

### `filmcow/` — ~3.800 grabaciones reales
Pasos, golpes de metal, oficina, papel, agua, puertas, materiales… ordenados alfabéticamente (A–Z).

## Licencias

- **Wyzowl SFX Kit** y **Kenney Interface Sounds**: [CC0 1.0](LICENCIAS/) (dominio público). Uso personal y comercial, sin dar crédito.
- **FilmCow**: royalty-free, uso personal y comercial ilimitado sin dar crédito. **No permitido** en proyectos de gobiernos nacionales (p. ej. reclutamiento militar), de fuerzas de seguridad ni de grupos de odio. Licencia oficial: <https://filmcow.itch.io/filmcow-sfx>.

Créditos: [Wyzowl](https://github.com/wyzowl/sfx-kit) · [Kenney](https://kenney.nl/assets/interface-sounds) · [FilmCow](https://filmcow.itch.io/filmcow-sfx). Si te sirven, apoya a los creadores originales.

## Cómo usarlos en tu editor

- **DaVinci Resolve:** Media Pool → clic derecho → *Import Media* (o arrastra la carpeta). Puedes añadirla en *Sound Library* para buscar por nombre.
- **Premiere Pro:** *File → Import* o arrastra la carpeta al panel Project.
- **CapCut / Final Cut:** arrastra los WAV al proyecto.

Truco: pon los whooshes **un poco antes** del corte para que el pico caiga justo en la transición, y baja los efectos 6–12 dB cuando haya voz.
