---
seo:
  title: Nuxt Docs Template
  description: Create stunning, fast and SEO-optimized documentation sites with Nuxt UI.
---

::u-page-hero{class="dark:bg-gradient-to-b from-neutral-900 to-neutral-950"}
---
orientation: horizontal
---
#top
:hero-background

#title
Ship Beautiful [Documentation]{.text-primary}.

#description
Build professional documentation with Nuxt UI's powerful components, enhanced typography, and seamless Nuxt Content integration. The same system trusted by the entire [Nuxt ecosystem](https://nuxt.com).

#links
  :::u-button
  ---
  to: /getting-started
  size: xl
  trailing-icon: i-lucide-arrow-right
  ---
  Get started
  :::

  :::u-button
  ---
  icon: i-simple-icons-github
  color: neutral
  variant: outline
  size: xl
  to: https://github.com/nuxt-ui-templates/docs
  target: _blank
  ---
  Use this template
  :::

#default
  :::prose-pre
  ---
  code: |
    export default defineNuxtConfig({
      modules: [
        '@nuxt/ui',
        '@nuxt/content',
        'nuxt-og-image',
        'nuxt-llms'
      ],

      css: ['~/assets/css/main.css']
    })
  filename: nuxt.config.ts
  ---

  ```ts [nuxt.config.ts]
  export default defineNuxtConfig({
    modules: [
      '@nuxt/ui',
      '@nuxt/content',
      'nuxt-og-image',
      'nuxt-llms'
    ],

    css: ['~/assets/css/main.css']
  })
  ```
  :::
::
