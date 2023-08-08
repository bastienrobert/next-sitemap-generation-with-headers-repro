# next-sitemap generation with headers repro

- create a new project with `pnpm create next-app`
- install `next sitemap`
- create a basic `next-sitemap.config.js` file
- add postbuild script
- add `headers()` call (from next/headers) in layout.js
- run `pnpm build`
- run `pnpm postbuild`

**sitemap is empty**

- remove `headers()` in layout.js
- run `pnpm build`
- run `pnpm postbuild`

**sitemap-0.xml is generated**