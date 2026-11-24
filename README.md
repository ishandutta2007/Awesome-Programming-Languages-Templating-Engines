# Awesome-Programming-Languages-Templating-Engines

# Top Programming Languages & Templating Engines Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Server-Side & Client-Side Templating Engines, Compile-Time Type-Safe Templates, Static Site Generators & HTML-over-the-Wire Languages*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Programming Languages & Templating Engines**. These tools power dynamic HTML/markup rendering, server-driven UI fragments, compile-time type-safe templates across Rust, Go, Python, JavaScript, PHP, and Java, and logic-less cross-language templating workflows.

**Examples** include Jinja2 Cloud, Mustache, Handlebars.js, EJS, Liquid by Shopify, Pug.js, Twig, Smarty, Blade, Nunjucks, and `hmpl-language/hmpl` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for ultra-fast compile-time template engines, server-oriented HTML languages, logic-less parsers, and static site templating runtimes — ideal for web architects, backend engineers, frontend developers, and language designers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Shopify Liquid Cloud (Shopify Theme & Storefront Engine)](https://shopify.dev)**  
  Hosted commercial storefront templating runtime powering millions of Shopify themes with Liquid tags, objects, and filters.

- **[Webflow & Contentful Rich Template Cloud](https://webflow.com)**  
  Cloud visual web development and dynamic CMS templating platforms compiling structured content models into production HTML/CSS.

- **[Vercel & Netlify Edge Template Rendering](https://vercel.com)**  
  Managed global edge compute and static/SSR hosting platforms executing template engines and server-rendered pages at low latency.

- **[Cloudflare Pages & Workers HTMLRewriter](https://cloudflare.com)**  
  Edge-hosted streaming HTML transformation and dynamic template injection runtime operating globally on Cloudflare's network.

- **[HubSpot HubL (HubSpot Markup Language)](https://hubspot.com)**  
  Proprietary Jinja-inspired cloud templating language powering dynamic pages, emails, and modules within HubSpot CMS.

- **[Salesforce Lightning & Visualforce Cloud](https://salesforce.com)**  
  Enterprise cloud component and markup templating frameworks for building data-bound CRM user interfaces.

- **[SendGrid & Mailchimp Dynamic Templates](https://sendgrid.com)**  
  Cloud transactional email platforms providing hosted Handlebars and merge-tag templating engines for personalized email rendering.

- **[Jinja2 Live / Online Template Playgrounds (Jinja2 Cloud Sandboxes)](https://palletsprojects.com)**  
  Web-hosted interactive template sandboxes and documentation playgrounds for testing Jinja2, Liquid, and Handlebars expressions in the browser.


## Open-Source GitHub Projects

- **[hmpl-language/hmpl](https://github.com)**  
  Lightweight, open-source server-oriented template language for displaying UI from server to client via customizable `fetch` requests, offering a tiny footprint and modular alternative to HTMX/Alpine.js.

- **[Jinja2 (Pallets Projects)](https://github.com)**  
  Premier open-source Python templating engine featuring sandboxed execution, template inheritance, automatic HTML escaping, and fast bytecode compilation.

- **[Liquid (Shopify Open-Source Ruby / LiquidJS)](https://github.com)**  
  Safe, customer-facing open-source template language created by Shopify (with **[LiquidJS](https://github.com)** for Node.js/browsers) designed for untrusted user templates.

- **[Handlebars.js](https://github.com)**  
  Popular open-source semantic templating engine extending Mustache with helpers, partials, block expressions, and precompiled JavaScript templates.

- **[Mustache (Spec & Multi-Language Implementations)](https://github.com)**  
  Foundational open-source "logic-less" template specification implemented across 40+ programming languages including JavaScript, Python, Ruby, Go, Rust, and Java.

- **[EJS (Embedded JavaScript Templates)](https://github.com)**  
  Simple, fast open-source templating language that lets developers generate HTML markup with plain JavaScript tags.

- **[Pug (formerly Jade)](https://github.com)**  
  Clean, whitespace-sensitive open-source Node.js templating engine compiling concise indentation-based syntax into standard HTML.

- **[Twig (Symfony)](https://github.com)**  
  Modern, secure, and flexible open-source templating engine for PHP featuring compilation to native PHP classes, inheritance, and strict sandboxing.

- **[Smarty](https://github.com)**  
  Veteran open-source PHP template engine separating presentation logic from application code with built-in caching and plugin extensibility.

- **[Laravel Blade (Illuminate View)](https://github.com)**  
  Expressive, zero-overhead open-source PHP templating engine bundled with Laravel that compiles clean `@directives` directly into cached plain PHP.

- **[Nunjucks (Mozilla)](https://github.com)**  
  Rich, powerful open-source templating engine for JavaScript heavily inspired by Jinja2, supporting asynchronous control, macros, and block inheritance.

- **[Askama](https://github.com)**  
  Type-safe, compiled Jinja-like open-source template engine for Rust that generates zero-overhead Rust code at compile time.

- **[Tera](https://github.com)**  
  Powerful open-source template engine for Rust inspired by Jinja2 and Django templates, featuring runtime template reloading and custom filters.

- **[MiniJinja](https://github.com)**  
  Lightweight, dependency-minimal open-source Jinja2-compatible template engine written in Rust by Jinja's original creator with Python and WebAssembly bindings.

- **[Templ (Go)](https://github.com)**  
  Modern open-source HTML templating language for Go that compiles strongly typed `.templ` components into native Go code for high-speed SSR.

- **[Go `html/template` & `text/template`](https://github.com)**  
  Built-in standard-library open-source Go templating packages providing context-aware automatic escaping against XSS vulnerabilities.

- **[Eta](https://github.com)**  
  Lightweight, ultra-fast open-source embedded JS template engine for Node, Deno, and browsers offering TypeScript support and a smaller footprint than EJS.

### Additional Strong Open-Source Options

- **[Thymeleaf](https://github.com)** and **[Freemarker](https://github.com)** for enterprise Java/Spring server-side natural HTML and XML/text templating.
- **[Razor (ASP.NET Core)](https://github.com)** for C#-powered server-side markup syntax seamlessly blending HTML and .NET types.
- **[HEEx / Phoenix Templates (Elixir)](https://github.com)** for compile-time validated HTML-aware templates powering real-time LiveView applications.
- **[Hugo Templates](https://github.com)** and **[Eleventy (11ty)](https://github.com)** for static site generation orchestrating Go templates, Nunjucks, Liquid, EJS, and Pug.
- Many community **SQL templating engines (`JinjaSQL` / `dbt` macros)**, **YAML/Helm (`Sprig`) infrastructure templates**, and **VS Code syntax-highlighting extensions** for polyglot templating.

**Frameworks for building custom systems**: Combine **hmpl-language/hmpl**, **MiniJinja / Askama** (Rust), **Templ** (Go), or **Jinja2** (Python) with **LiquidJS** for fast, type-safe, server-rendered web applications.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Allowing end users to author or upload custom templates (e.g., Jinja2, Twig, Smarty) introduces Server-Side Template Injection (SSTI) risks; always enable strict sandboxing or use logic-less engines (e.g., Mustache, Liquid) for untrusted inputs.
- Ensure contextual auto-escaping is enabled when rendering untrusted variables into HTML, JavaScript, or CSS contexts to prevent Cross-Site Scripting (XSS).

---

**Made for web architects, backend developers, language designers, and full-stack engineers.**  
Let's make server-side and client-side templating faster, safer, and more open.
