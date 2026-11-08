# Web CV · Cynthia Fuentes García

Página personal con mi CV. Español / inglés, modo oscuro / claro.

## Archivos
- `index.html` → toda la web (estilos y código incluidos)
- `cv.pdf` → el CV que se descarga con el botón "Descargar CV"
- `CNAME` → (lo creas al final) tu dominio propio

## Publicarla gratis con GitHub Pages (GitHub Desktop)
1. GitHub Desktop → File → Add Local Repository → elige esta carpeta `cv-web`
   (si te dice que no es un repositorio, pulsa "create a repository").
2. Haz el primer commit ("Primera versión") y pulsa **Publish repository**.
   Desmarca "Keep this code private".
3. En github.com, abre el repositorio → Settings → Pages →
   Source: "Deploy from a branch", Branch: `main` / `(root)` → Save.
4. En 1–2 minutos estará en `https://TU-USUARIO.github.io/cv-web/`.

## Dominio propio
1. Compra el dominio (p. ej. en Cloudflare, Namecheap o DonDominio).
2. En el panel DNS del dominio crea 4 registros **A** para `@` apuntando a:
   185.199.108.153 · 185.199.109.153 · 185.199.110.153 · 185.199.111.153
   y un registro **CNAME** para `www` apuntando a `TU-USUARIO.github.io`.
3. En GitHub → Settings → Pages → Custom domain: escribe tu dominio y guarda.
   Marca "Enforce HTTPS" cuando aparezca.

## Editar
Los textos en español están en el HTML; los textos en inglés están en el
bloque `<script>` al final, en el objeto `en`. Cambia `cv.pdf` cuando
actualices tu CV.
