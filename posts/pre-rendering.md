---
title: 'Two Forms of Pre-rendering'
date: '2020-01-01'
---

Next.js has two forms of pre-rendering. **Static generation** and **Server-side rendering**. The difference is in **when** it generates the HTML for a page.

- **Static generation** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then __reused_ on each request.
- **Server-side rendering** is the pre-rendeirng method that generates the HTML on **each request**.

Importantly, Next.js lets you **choose** which pre-rendering form to use for each page. You can create a "hybrid" Next.js app by using static generation for most pages and using server-side rendering for others.