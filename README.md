<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Pham Van Dung, full-stack developer building Shopify apps" src="assets/header-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://dungpv.id.vn"><img src="https://img.shields.io/badge/Portfolio-6366f1?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://solora.dungpv.id.vn"><img src="https://img.shields.io/badge/Solora_apps-f97316?style=for-the-badge&logo=shopify&logoColor=white" alt="Solora"></a>
  <a href="https://www.linkedin.com/in/phamdung2209"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:phamdung.22092003@gmail.com"><img src="https://img.shields.io/badge/Email-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

I build Shopify apps end to end: React admin UIs, Node.js services and the storefront and checkout code that runs on merchants' stores.

- 🛍️ **At [Mageplaza](https://www.mageplaza.com)** since 2024, on apps used by **10,000+ merchants**.
- 🚀 **On my own**, I took two apps from an empty repository to the **Shopify App Store**.
- 🤖 **Next**, I want to build AI-powered workflows for merchants.

## 🚢 Apps I built and run

<table>
  <tr>
    <td width="88" align="center"><img src="https://dungpv.id.vn/projects/mixly/icon.png" width="56" alt="Mixly"></td>
    <td>
      <b><a href="https://apps.shopify.com/solora-mixly-bundles">Mixly: Bundles &amp; BOGO</a></b> &nbsp;<img src="https://img.shields.io/badge/live-App_Store-22c55e?style=flat-square" alt="live"><br>
      Frequently-bought-together, mix-and-match and BOGO offers. A bundle is a rule checked against the cart, so the app never creates extra products or SKUs.<br>
      <sub>The same rule runs twice, in Liquid on the storefront and in a Shopify Function at checkout. A differential fuzz test over <b>364,500</b> rule × cart pairs keeps the two in agreement. <b>1,100+</b> tests.</sub>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://dungpv.id.vn/projects/tierly/icon.png" width="56" alt="Tierly"></td>
    <td>
      <b><a href="https://apps.shopify.com/solora-tierly">Tierly: Quantity Breaks</a></b> &nbsp;<img src="https://img.shields.io/badge/live-App_Store-22c55e?style=flat-square" alt="live"><br>
      Volume discounts priced inside checkout by a Shopify Function (TypeScript compiled to WebAssembly), not by theme JavaScript.<br>
      <sub>From empty repository to App Store in one month. <b>500+</b> tests. Stores no customer personal data.</sub>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://dungpv.id.vn/projects/swatchbox/icon.png" width="56" alt="Swatchbox"></td>
    <td>
      <b><a href="https://dungpv.id.vn/projects/solora-swatchbox">Swatchbox: Combined Listings</a></b> &nbsp;<img src="https://img.shields.io/badge/in-development-eab308?style=flat-square" alt="in development"><br>
      Colour swatches that link separate products into one listing, on product pages and collection grids.
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://dungpv.id.vn/projects/tierly/tier-ladder.webp" width="49%" alt="Tierly tier ladder on a product page">
  <img src="https://dungpv.id.vn/projects/mixly/bundle-offer.webp" width="49%" alt="Mixly bundle offer on a product page">
</p>

## 🏢 At Mageplaza

| App | What I did |
| --- | --- |
| **Instagram Feed** | Core developer and top contributor. Cut the storefront bundle by ~70% (**~100 KB → 28 KB**) with code splitting and lazy loading, and moved feed data to the Storefront API. |
| **Size Chart** | Built an AI importer on **Gemini vision**: a merchant uploads a chart image and gets structured, editable chart data back, with a preview before applying. |
| **Product Quiz** | Main developer since early 2025: admin, backend and the storefront quiz. |

## 📦 Open source

- **[hank-zilla](https://github.com/phamdung2209/hank_zilla)**: global React state without Providers, built on `useSyncExternalStore`. Zero dependencies, published on [npm](https://www.npmjs.com/package/hank-zilla).
- **[Cipher](https://github.com/phamdung2209/Cipher)**: an AI chat client with streaming responses and visible model reasoning, built with Next.js.
- **[solora](https://github.com/phamdung2209/solora)**: the static marketing and docs site for my Shopify apps.

## 🧰 Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,express,tailwind,prisma,firebase,gcp,mongodb,docker,git,vitest&perline=14" alt="Tech stack">
</p>

**Shopify:** Admin & Storefront GraphQL · Functions · Theme App Extensions · Metafields · Webhooks · Liquid · Polaris<br>
**AI:** Gemini API (vision) · prompt design for structured JSON · Claude Code

---

<p align="center"><sub>Most of my work lives in private repositories. The apps and the <a href="https://dungpv.id.vn">portfolio</a> tell the rest of the story.</sub></p>
