---
layout: "../../layouts/BlogPost.astro"
title: "How I built my Astro Blog from scratch? Part 1"
description: "My journey to becoming an Astronaut. 🚀"
pubDate: "Sep 23 2022"
author: "By Helitha Rupasinghe"
heroImage: "/placeholder-hero.jpg"
---

<p style="font-size: 1.15rem; margin-bottom: 1rem;"> Astro is the newest javascript based static generator framework on the scene. And if you read more then you'll find out why I am excited about this new web framework. </p>

## What is Astro?

<p style="font-size: 1.15rem; margin-top: 1rem; margin-bottom: 1rem;"> Astro is an all-in-one web framework for building fast, content-focused websites. </p>

## What I like about Astro?

<p style="font-size: 1.15rem; margin-top: 1rem; margin-bottom: 1rem;"> You can create a fantastic developer experience by utilising React, Angular, Svelte, or Vue individually or in combination at any stage of the project.</p>

<p style="font-size: 1.15rem; margin-bottom: 1rem;"> Astro stands apart from other static site generators thanks to its superior support for on-demand JavaScript loading.</p>

<p style="font-size: 1.15rem; margin-bottom: 1rem;"> <b>Progressive Enhancement/Partial Hydration</b> is the name of the idea. Astro believes that your website will always be static and offers the ability to load JavaScript just as and when necessary, in contrast to other suitable frameworks like Next.js or Gatsby.</p>

<p style="font-size: 1.15rem; margin-bottom: 1rem;">Along with all of that, Astro includes built-in support for</p>

<ul style="font-size: 1.15rem; margin-bottom: 1rem;">
<li style="margin-bottom: 1rem;"><b>Component Islands:</b> A new web architecture for building faster websites. </li>
<li style="margin-bottom: 1rem;"><b>Server-first API design:</b> Move expensive hydration off of your users’ devices.</li>
<li style="margin-bottom: 1rem;"><b>Zero JS, by default:</b> No JavaScript runtime overhead to slow you down.</li>
<li style="margin-bottom: 1rem;"><b>Edge-ready:</b> Deploy anywhere, even a global edge runtime like Deno or Cloudflare.</li>
<li style="margin-bottom: 1rem;"><b>Customizable:</b> Tailwind, MDX, and 100+ other integrations to choose from.</li>
<li style="margin-bottom: 1rem;"><b>UI-agnostic:</b> Supports React, Preact, Svelte, Vue, Solid, Lit and more.</li>
</ul>

<p style="font-size: 1.15rem; margin-bottom: 1rem;">If that introduction piqued your attention, then let's move ahead and build something with it.</p>

## Getting started with Astro

<p style="font-size: 1.15rem; margin-top: 1rem; margin-bottom: 1rem;">Start by creating a brand-new directory for your project, then go there:</p>

```
mkdir astro-blog-starter
cd astro-blog-starter
```

<p style="font-size: 1.15rem; margin-top: 1rem; margin-bottom: 1rem;"> Open up your terminal and run either of the following commands based on the package manager of your choice. </p>

```
# create a new project with npm
npm create astro@latest

# create a new project with yarn
yarn create astro
```

<br>

![Astro.jpg](/placeholder-astro.jpg)

<p style="font-size: 1.15rem; margin-top: 1rem; margin-bottom: 1rem;"> You can choose a template of your choice and then follow the instructions given to install dependencies. </p>

```
npm install
```

<p style="font-size: 1.15rem; margin-top: 1rem; margin-bottom: 1rem;"> Then you can start the server: </p>

```
npm run dev
```

<p style="font-size: 1.15rem; margin-top: 1rem; margin-bottom: 1rem;">If all goes well, Astro should now be serving your project on <b>http://localhost:3000/!</b></p>

![Local.jpg](/placeholder-local.jpg)

Default Astro starting point.
