# Sitio de la Red de Humanidades Digitales UN

Sitio hecho con Jekyll y publicado en GitHub Pages.

## Archivos que vas a editar

| Archivo o carpeta | Para qué sirve |
|---|---|
| `_config.yml` | Nombre, lema, correo, afiliación y fecha del próximo Ágora IA |
| `_data/red.yml` | El mapa de la red (página `mapa.html`): anfitriones, personas y grupos |
| `_posts/` | Las entradas de la bitácora, una por archivo |
| `nosotros.md` | Página "Quiénes somos" |
| `agora-ia.html` | Página del Ágora IA |
| `participar.md` | Cómo participar y qué entra bajo el paraguas |
| `humanidades-digitales.md` | Definición de trabajo |
| `index.html` | Portada |
| `assets/img/` | Imágenes de las entradas |
| `PLANTILLA-ENTRADA.md` | Modelo para una entrada normal |
| `PLANTILLA-AGORA.md` | Modelo para la relatoría de una sesión del Ágora IA |

No necesitas tocar `_layouts/`, `_includes/` ni `assets/css/` salvo que quieras cambiar el diseño.

## Publicar una entrada nueva

1. En GitHub, entra a la carpeta `_posts` y pulsa **Add file → Create new file**.
2. Ponle un nombre con este formato exacto: `AAAA-MM-DD-titulo-corto.md`
   Ejemplo: `2026-12-01-mapas-literarios.md` (sin tildes ni espacios).
3. Copia el contenido de `PLANTILLA-ENTRADA.md`, cambia los datos y pega el texto.
4. Pulsa **Commit changes**. En uno o dos minutos la entrada aparece en el sitio.

## Imágenes

Súbelas a `assets/img/` con **Add file → Upload files** y llámalas así dentro de la entrada:

    ![Descripción](/assets/img/nombre.jpg)

## Formato básico (Markdown)

- `**negrita**`, `*cursiva*`
- `## Subtítulo`
- `[texto del enlace](https://...)`
- `> cita`
- Líneas que empiezan con `- ` forman una lista.

## Relatorías del Ágora IA

Usa `PLANTILLA-AGORA.md`. Deja el tema `Ágora IA` escrito exactamente así: es lo que hace que la relatoría aparezca en la página del Ágora.

## Anunciar la próxima sesión

En `_config.yml` escribe la fecha y el lugar, por ejemplo:

    agora_proxima: "jueves 4 de diciembre, 4:00 p. m."
    agora_lugar: "Edificio 225, salón 301"

Cuando pase la sesión, vuelve a dejarlos vacíos ("").
