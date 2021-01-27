

# Nuxt.JS & Tailwind

<img src="https://img.shields.io/static/v1?label=v1.1&message=ARJOS&color=7159c1&style=for-the-badge&logo=ghost"/>
   
<img src="https://tailwindui.com/img/tailwindui-logo-on-dark.svg"/>

Por [Artur J Medeiros](https://github.com/arjosweb) 

### SETUP

##### Criar projeto usando NPX

```
npx create-nuxt-app { NOME DO PROJETO }
```

##### Configurar boilerplate
```
create-nuxt-app v3.5.0
✨  Generating Nuxt.js project in nuxt-app-tailwind
? Project name: nuxt-app-tailwind
? Programming language: JavaScript
? Package manager: Yarn
? UI framework: Tailwind CSS
? Nuxt.js modules: Axios - Promise based HTTP client, Progressive Web App (PWA)
? Linting tools: (Press <space> to select, <a> to toggle all, <i> to invert sele
ction)
? Testing framework: None
? Rendering mode: Universal (SSR / SSG)
? Deployment target: Static (Static/JAMStack hosting)
? Development tools: (Press <space> to select, <a> to toggle all, <i> to invert 
selection)
? What is your GitHub username? arjosweb
? Version control system: None
```

##### Implementar UI do [Tailwind](https://tailwindcss.com/docs/guides/nuxtjs)

- Criar arquivo CSS (./assets/css/tailwind.css)

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

- Referenciar estilo no Nuxt (`nuxt.config.js`)

```
css: [
     '@/assets/css/tailwind.css'
  ],
```







