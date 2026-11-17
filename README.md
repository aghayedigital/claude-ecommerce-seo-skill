# Claude Ecommerce SEO Skill (Amoo Ehsan SEO)

**A Claude skill that does ecommerce SEO for online stores, with a focus on product category pages. Built for Persian (Farsi) stores on WooCommerce and WordPress.**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)](https://github.com/aghayedigital/claude-ecommerce-seo-skill/releases)
[![Claude Code plugin](https://img.shields.io/badge/Claude%20Code-plugin-orange.svg)](#install)

[فارسی](README.fa.md) | English

Category pages bring most of the organic traffic to an online store, and they are usually the weakest pages on the site. This skill gives Claude a repeatable process to audit them, find the right keywords and structure, write the content, and check the results in Google Search Console.

Made by Ehsan Ahmadzadeh, [Aghaye Digital](https://www.aghayedigital.com/).

## What it does

- Ecommerce SEO audit of an online store
- Keyword research and structure for product category pages
- SEO content writing in natural Persian
- Google Search Console analysis
- Automatic internal linking (keyword to target URL, links built when the page renders)
- A five-step check for every category: Search Console, category status, indexing, pillar and cluster, internal links

## Install

In Claude Code or Cowork:

```
/plugin marketplace add aghayedigital/claude-ecommerce-seo-skill
/plugin install amoo-ehsan-seo@aghayedigital-seo
```

## Recommended tools

To let Claude see real project data, connect these two:

1. **Claude in Chrome** to read Search Console. Chrome must be signed in to the Google account that has access to the property. [Setup guide](https://support.claude.com/en/articles/12012173-getting-started-with-claude-in-chrome)
2. **WPVibe WordPress plugin** to read the site itself (pages, categories, products, SEO settings). [Plugin page](https://wordpress.org/plugins/vibe-ai/)

Without them the skill still works, but you provide the data yourself (Search Console CSV export, list of URLs).

## Usage

After installing, just ask:

- "Audit the SEO of the home appliances category on my site"
- "Suggest a content structure and keywords for this category"
- «سئوی صفحه دسته‌بندی لوازم برقی سایتم را بررسی کن»

## Roadmap

- [x] Skill skeleton and five-step category checklist
- [ ] Category content templates
- [ ] Search Console report template
- [ ] Example outputs from real stores

## Contributing

Issues and pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE)
