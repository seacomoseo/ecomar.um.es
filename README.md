# ecomar.um.es

[![ecomar.um.es](/assets/media/base/icon.png)](https://ecomar.um.es/)


## STEPS


### Local

- Design
  - GENERAL
    - `config.yml`
    - `data/*.{yml,md}`
  - HTML: `data/config.yml ⏩ langs[*].html.{head,body}`
  - CSS: `assets/css/` ⏩ `{*,_variables-custom.scss,_custom.scss}`
  - JS: `assets/js/*,custom.js`
  - IMG: `assets/media/*`
  - REDIRECTS: `assets/redirects.md`
  - ROBOTS: `assets/robots.md`
  - If Multilanguaje and Multihosting, add `cp ./public/[es|en]/404.html ./public/` in `netlify.toml ⏩ build.command`
  - Try in Safari and Firefox
  - Check in [W3 Validator](https://validator.w3.org/)
  - Check in [PageSpeed Insights](https://pagespeed.web.dev/)


### After client validate web

##### Delivery

Send to all collaborators next:

###### WhatsApp

```md
*ENTREGA WEB ecomar.um.es*

Te dejo aquí este mensaje como referencia (también te lo paso por email con el asunto `ENTREGA WEB ecomar.um.es`).

En el siguiente enlace tienes instrucciones sobre cosas referentes a tu sitio web (cómo modificar cosas, información extra, ect.):

https://seacomoseo.com/entrega/

No es necesario que lo veas, solo lo es si quieres hacer cosas por tu cuenta o si no estoy disponible.

¡Un saludo!
```

###### Mail

```
Asunto: ENTREGA WEB ecomar.um.es
Cuerpo:
Te dejo aquí este email como referencia.

En el siguiente enlace tienes instrucciones sobre cosas referentes a tu sitio web (cómo modificar cosas, información extra, ect.):

https://seacomoseo.com/entrega/

No es necesario que lo veas, solo lo es si quieres hacer cosas por tu cuenta o si no estoy disponible.

¡Un saludo!
```
