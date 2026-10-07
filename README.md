# suscripcion-politicas

Política de privacidad y términos de uso **públicos** del sistema **Suscripción**, servidos con
GitHub Pages:

> **https://onemindcompany.github.io/suscripcion-politicas/** (política de privacidad)
>
> **https://onemindcompany.github.io/suscripcion-politicas/terminos.html** (términos de uso)

Esas URL son las que declaran las fichas de Google Play y de la App Store, que exigen una política
accesible sin iniciar sesión, y las que abre la pantalla «Sin anuncios» de la app. Esta misma
dirección es también el **sitio web del desarrollador** de las dos fichas.

## Fuente de verdad

Los textos canónicos viven en el repo privado `suscripcion-docs`: `politica-de-privacidad.md`
(espejo: `index.html`) y `terminos-de-uso.md` (espejo: `terminos.html`). **Los cambios se hacen
allá primero** y estas páginas se actualizan como espejo, en el mismo cambio. Si divergen, la
declaración pública deja de coincidir con la interna, y eso es un problema legal.

Desde la versión 1.1.0 la app es gratis con anuncios y tiene la suscripción «Sin anuncios». Las dos
páginas lo describen; tienen que estar publicadas (en `main`) **antes** de enviar la 1.1.0 a
revisión en cualquiera de las dos tiendas, porque los revisores comparan la política con la ficha.

## `app-ads.txt` no vive acá

AdMob busca el archivo `app-ads.txt` en la **raíz del dominio** del sitio del desarrollador:
`https://onemindcompany.github.io/app-ads.txt`. Este repo es un sitio de **proyecto** de GitHub
Pages y se sirve bajo `/suscripcion-politicas/`, así que nada de lo que se ponga acá llega a esa
raíz. El archivo va en el repo del sitio de la **organización**, `onemindcompany.github.io`. Los
pasos están en `suscripcion-docs/publish-android/anuncios-y-suscripcion.md`.

## Desviaciones del estándar de repositorios

Dos, deliberadas y acotadas ([`repositorios-onemind`]):

1. **Es público**: su única razón de existir es que las tiendas y los usuarios puedan leerlo.
   No contiene código de producto.
2. **El commit inicial incluye la página** (`index.html`), no solo el README: GitHub Pages sirve
   desde `main`, y un repo de política sin política no publica nada.

## Ramas

Las de siempre (`main` / `qa` / `develop`, protegidas). Como Pages sirve desde `main`, un cambio de
política no está publicado hasta que llega a `main` por el flujo normal.
