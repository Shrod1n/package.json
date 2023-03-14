{
  "name": "swap.sh",
  "type": "module",
  "version": "0.0.1",
  "private": true,
  "scripts": {
    "dev": "astro dev",
    "start": "astro dev",
    "build": "astro build",
    "preview": "astro preview",
    "astro": "astro",
    "deploy": "NODE_DEBUG=gh-pages gh-pages -d dist -t",
    "compress:jsons": "node bin/compress-jsons.cjs",
    "upgrade": "ncu -u",
    "roadmap-links": "node bin/roadmap-links.cjs",
    "roadmap-content": "node bin/roadmap-content.cjs",
    "best-practice-content": "node bin/best-practice-content.cjs",
    "test:e2e": "playwright test"
  },
  "dependencies": {
    "@astrojs/sitemap": "^1.2.0",
    "@astrojs/tailwind": "^3.1.0",
    "astro": "^2.1.2",
    "astro-compress": "^1.1.35",
    "node-html-parser": "^6.1.5",
    "npm-check-updates": "^16.7.12",
    "rehype-external-links": "^2.0.1",
    "roadmap-renderer": "^1.0.4",
    "tailwindcss": "^3.2.7"
  },
  "devDependencies": {
    "@playwright/test": "^1.31.2",
    "@tailwindcss/typography": "^0.5.9",
    "gh-pages": "^5.0.0",
    "js-yaml": "^4.1.0",
    "markdown-it": "^13.0.1",
    "prettier": "^2.8.4",
    "prettier-plugin-astro": "^0.8.0"
  }
}
