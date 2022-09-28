---
title: Astro 1.0
slug: astro-1-0
image: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2MDDN_Nmae6BnI1TgdHpjTN9NfLiRtUML2A&usqp=CAU
excerpt: The Astro team has released version 1.0, noting that organisations which already have some deployments built with this web framework include Google’s Firebase, Trivago, The Guardian and IKEA.
date: 08-10-2022
author: Tim Anderson
---

Astro is 16 months old according to the team. It is unusual in that it is both a static site generator and aims to remove JavaScript from the final build whenever possible. It also favors multi-page applications over single page apps (SPAs). The project is aimed primarily at content-focused sites rather than web applications.

“The SPA model has its benefits. However, these come at the expense of additional complexity and performance tradeoffs,” the docs claim.

Typically, a SPA retrieves content via JavaScript so while the initial page load is fast, client-side processing and further calls to microservices are required before a page is fully rendered. That said, the Astro team also states that “SPAs are the superior architecture for websites that deal with complex, multi-page state management,” thanks to easier state management and shared memory across what the user perceives as multiple pages.

Astro is supported by a Visual Studio Code extension

While Atro sounds in some ways like a return to the PHP approach, which drives content management systems like WordPress and Drupal, or other traditional frameworks like ASP.NET, “with Astro, everything is still just HTML, CSS, and JavaScript (or TypeScript, if you prefer),” said the team. The claim is that “An Astro website can load 40% faster with 90% less JavaScript than the same site built with the most popular React web framework.”

Astro has its own UI language, stored in files with a .astro extension, which gets compiled to HTML when a project is built. One key feature is the ability to use components from one or more other frameworks, including React, Preact, Svelte, Vue and more. By default these components are pre-built and rendered as static HTML, but it is also possible to use a directive that renders them on the client. This uses the concept of Astro Islands, where an island means “an interactive UI component on an otherwise static page of HTML.”

The idea was not invented by the Astro team but it is now one of the main implementations. “Islands are the secret to Astro’s fast-by-default performance story,” the docs claim.
