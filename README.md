> El siguiente contenido fue elaborado por [@_nhsz](https://twitter.com/_nhsz) como guía para las clases de [undefined school](https://twitter.com/undefinedSchool)

> Son bienvenidos los _issues_ y _PRs_ para mejorar el contenido, corregir errores, etc

# :rocket: Deployment

Para una comparación, ver [Netlify vs. Now vs. GitHub Pages](https://medium.com/liferaydesign/netlify-vs-zeit-vs-github-pages-5f609dd6912b)

## Contenido

- [Front-End](#front-end)
  * [GitHub Pages](#github-pages)
  * [Netlify](#netlify)
    + [Netlify CLI](#netlify-cli)
    + [Netlify Dev](#netlify-dev-rocket)
    + [Netlify Forms](#netlify-forms)
    + [Netlify Functions](#netlify-functions)
- [Front-End & Back-End](#front-end--back-end)
  * [Now](#now)

---

## Front-End

### GitHub Pages

- Es **gratis** y **funciona sólo con repositorios Open Source**
- [Docs](https://pages.github.com/) (repo por proyecto, repo `username.github.io`)
- [GitHub Pages Deploy & Domain](https://www.youtube.com/watch?v=SKXkC4SqtRk)

### Netlify

- [GitHub Pages vs. Netlify](https://www.netlify.com/github-pages-vs-netlify/)
- También [**funciona con repositorios privados**](https://docs.netlify.com/configure-builds/repo-permissions-linking/#access-other-repositories-at-build)
- SI usamos la [CLI](#netlify-cli), podemos hacer el _deploy_ directamente de código sin necesidad de que esté en algún repositorio de GitHub, GitLab, etc

#### Netlify CLI

- [Get started with Netlify CLI](https://docs.netlify.com/cli/get-started/)
- [Netlify CLI Command List](https://cli.netlify.com/#netlify-cli-command-list)
- [How to host a website on Netlify with a custom domain for FREE — Step by Step Guide](https://levelup.gitconnected.com/how-to-host-domain-to-netlify-site-for-free-step-by-step-guide-45d0c2102db3)

1. Instalar la CLI

```bash
npm i -g netlify-cli
```

2. Chequear que se haya isntalado correctamente y ver comandos disponibles

```bash
netlify
```

3. [Autenticarnos](https://docs.netlify.com/cli/get-started/#authentication) para linkear la CLI con nuestra cuenta de Netlify

```bash
netlify login
```

4. Setup del repositorio

```bash
netlify init
```

5. Deploy

```bash
netlify deploy
```

#### Netlify Dev :rocket:

Básicamente podemos hacer de todo desde la terminal 🤘

- [Netlify Dev Crash Course | Easy Dev & Deploy](https://www.youtube.com/watch?v=FMhVXOA54x8)
- [Netlify Dev [BETA]](https://www.netlify.com/products/dev/)
- [Netlify Dev docs](https://github.com/netlify/cli/blob/master/docs/netlify-dev.md)

#### Netlify Forms

Podemos recibir las _submissions_ que nos hagan en un [form](https://docs.netlify.com/forms/setup/) sin necesidad de un backend

#### Netlify Functions

_Functions_ es la forma de usar [_serverless_](https://www.netlify.com/products/functions/) con Netlify. Es una capa de abstracción y simplifcación sobre _AWS Lambda_. Esto nos permite, entre otras cosas, [hostear apps que usen _Express_](https://www.netlify.com/blog/2018/09/13/how-to-run-express.js-apps-with-netlify-functions/)

#### Pricing 

Tiene un [_free tier_](https://www.netlify.com/pricing/)

## Front-End & Back-End

### Now

1. [Crear una cuenta](https://zeit.co/signup) en Now
2. `npm i -g now`
3. Configurar el proyecto (si es necesario) con el archivo [`now.json`](https://zeit.co/docs/configuration/)
4. Abrir la terminal en la raíz del proyecto y usar el comando `now`. Eso es todo.
5. [OPCIONAL] Usar un [_alias_](https://zeit.co/blog/automatic-aliasing)
6. [OPCIONAL] Usar un [_custom domain_](https://zeit.co/docs/v2/custom-domains/)

#### Variables de entorno y secrets

Para setear las variables de entorno, ver 
  - [Using Environment Variables and Secrets](https://zeit.co/docs/v2/build-step#using-environment-variables-and-secrets)   
  - [Secrets and Environment Variables in Next.js and Now](https://www.youtube.com/watch?v=pRbQcy9f5ew)

#### Recursos

- [Docs](https://zeit.co/docs)
- [Now for GitHub](https://zeit.co/github)
- [Easy Deployments With Zeit Now](https://www.youtube.com/watch?v=OF9UkxDOSII)
- [Zeit Now Deploy a NodeJS Project](https://www.youtube.com/watch?v=1Bfb8pSvoQo)
- Presets para diferentes tipos de proyectos (frameworks): [`now init`](https://zeit.co/blog/now-init)

#### Pricing

Tiene un [_free tier_](https://zeit.co/pricing)

## Comprar dominio

- [Namecheap](https://namecheap.com)
