# deployment :rocket:

- [Netlify vs Now vs GitHub Pages](https://medium.com/liferaydesign/netlify-vs-zeit-vs-github-pages-5f609dd6912b)

## Front-End

### GitHub Pages

- Gratis para Open Source
- [Docs](https://pages.github.com/) (repo por proyecto, repo `username.github.io`)
- [GitHub Pages Deploy & Domain](https://www.youtube.com/watch?v=SKXkC4SqtRk)

### Netlify

- [GitHub Pages vs Netlify](https://www.netlify.com/github-pages-vs-netlify/)

#### Netlify CLI

- [Get started with Netlify CLI](https://docs.netlify.com/cli/get-started/)
- [Netlify CLI Command List](https://cli.netlify.com/#netlify-cli-command-list)
- [Netlify Dev Crash Course | Easy Dev & Deploy](https://www.youtube.com/watch?v=FMhVXOA54x8)
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

Básicamente podemos hacer todo desde la terminal 🤘

- [Netlify Dev [BETA]](https://www.netlify.com/products/dev/)
- [Netlify Dev docs](https://github.com/netlify/cli/blob/master/docs/netlify-dev.md)

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
