# josemora.dev

Portafolio personal de **José Mora**, Full-Stack Developer (React · Node.js · Python).

Sitio estático de un solo archivo (`index.html`), bilingüe ES/EN (`#es` / `#en`), sin dependencias ni paso de build.

## Desarrollo local

Abre `index.html` en el navegador, o:

```bash
npx serve .
```

## Despliegue

- **Cloudflare Pages:** conecta este repo, framework preset *None*, build command vacío, output directory `/`. Agrega `josemora.dev` en *Custom domains*.
- **GitHub Pages (alternativa):** Settings → Pages → Deploy from branch `main` / root. El archivo `CNAME` ya apunta a `josemora.dev`.
