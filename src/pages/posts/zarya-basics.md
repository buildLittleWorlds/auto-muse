---
title: "Zarya of the Dawn -- the Basics and Sources"
description: "We're excited to announce Astro as a new way to build static websites and deliver lightning-fast performance without sacrificing a modern developer experience."
pubDate: "2023-09-16"
hero: "/images/zarya-basics.png"
tags: ["astro"]
layout: "../../layouts/BlogPostLayout.astro"
---

In September 2022, artist Kristina Kashtanova registered a copyright for her graphic novel "Zarya of the Dawn." The work contained both text and images that Kashtanova claimed she authored. However, it later came out that Kashtanova had used an AI image generator called Midjourney to create some or all of the images. This raised questions about whether AI-generated content is eligible for copyright protection. 

The Copyright Office initiated a cancellation review since Kashtanova's application did not disclose the AI origins of some content. Copyright law requires "human authorship" for protection. Works produced solely by machines without creative input or intervention from a human are not eligible. The Office stated that Midjourney's autonomous, unpredictable image generation process did not qualify as human authorship.

In response, Kashtanova's lawyer argued she did author the images through her creative choices in prompts, selection and refinement of images, and arrangement of the graphic novel. The letter argues this process is no different than using other computer tools like Photoshop. It asks the Office to affirm Kashtanova's copyright based on her overall authorship of selection and arrangement.

The case raises interesting issues about whether current copyright law, with its human authorship requirement, is adequate to address creative works using AI. It illustrates the legal complexities around protecting AI art. The Office's final decision could have significant implications for the copyright eligibility of AI-generated content.

Here are some key takeaways on AI and copyright issues from the Zarya of the Dawn case:

- Using AI tools like Midjourney does not automatically disqualify copyright protection. The work may still meet "human authorship" standards based on the creator's overall creative process.

- However, AI-generated content itself, created autonomously without creative input, may not qualify for copyright protection under current law.

- The selection and arrangement of AI-generated elements can potentially make a work copyrightable, even if individual AI-generated pieces are not protected.

- Properly disclosing the use of AI tools in copyright applications is important, so that authorship and ownership are clear.

- Copyright law trails behind technology. Expect legal uncertainty around AI authorship until laws are updated.

- For now, document your creative choices when using AI tools, like prompts and selection steps, to strengthen your authorship claims.

- AI art raises fascinating philosophical questions about creativity and authorship that current copyright law doesn't fully address.

> For the exchange between Kashtanova's lawyer and the U.S. Copyright office, check out [the letters here.](https://www.copyright.gov/docs/zarya-of-the-dawn.pdf).

## A few other links related to the case

Astro works a lot like a static site generator. If you have ever used Eleventy, Hugo, or Jekyll (or even a server-side web framework like Rails, Laravel, or Django) then you should feel right at home with Astro.

In Astro, you compose your website using UI components from your favorite JavaScript web framework (React, Svelte, Vue, etc). Astro renders your entire site to static HTML during the build. The result is a fully static website with all JavaScript removed from the final page. No monolithic JavaScript application required, just static HTML that loads as fast as possible in the browser regardless of how many UI components you used to generate it.

Of course, sometimes client-side JavaScript is inevitable. Image carousels, shopping carts, and auto-complete search bars are just a few examples of things that require some JavaScript to run in the browser. This is where Astro really shines: When a component needs some JavaScript, Astro only loads that one component (and any dependencies). The rest of your site continues to exist as static, lightweight HTML.

In other full-stack web frameworks this level of per-component optimization would be impossible without loading the entire page in JavaScript, delaying interactivity. In Astro, this kind of [partial hydration](https://addyosmani.com/blog/rehydration/) is built into the tool itself.

You can even [automatically defer components](https://codepen.io/jonneal/full/ZELvMvw) to only load once they become visible on the page with the `client:visible` directive.

This new approach to web architecture is called [islands architecture](https://jasonformat.com/islands-architecture/). We didn't coin the term, but Astro may have perfected the technique. We are confident that an HTML-first, JavaScript-only-as-needed approach is the best solution for the majority of content-based websites.

> To learn more about Astro and start building your first site, check out [the project README.](https://github.com/snowpackjs/astro#-guides)

## Embracing the Pit of Success

> A well-designed system makes it easy to do the right things and annoying (but not impossible) to do the wrong things<div class="source"><p>– Jeff Atwood</p>[Falling Into The Pit of Success](https://blog.codinghorror.com/falling-into-the-pit-of-success/)</div>

Poor performance is often framed as a failure of the developer, but we respectfully disagree. In many cases, poor performance is a failure of tooling. It should be difficult to build a slow website.

Astro's main design principle is to lead developers into what [Rico Mariani](https://twitter.com/ricomariani) dubbed "the pit of success". It is our goal to build every site "fast by default" while also delivering a familiar, modern developer experience.

By building your site to static HTML by default, Astro makes it difficult (but never impossible 😉) to build a slow site.

## Long-Term Sustainability

Astro is built by the team of open source developers behind [Snowpack](https://snowpack.dev) and [Skypack](https://skypack.dev), with additional contributions from the community.

**Astro is and always will be free.** It is an open source project released under the [MIT license](https://github.com/snowpackjs/astro/blob/main/LICENSE).

We care deeply about building a more sustainable future for open source software. At the same time, we need to support Astro's development long-term. This requires money (donations alone aren't enough.)

We're inspired by the early success of projects like [Tailwind](https://tailwindcss.com/), [Rome](https://rome.tools/), [Remix](https://remix.run/), [Ionic](https://ionicframework.com/), and others who are experimenting with long-term financial sustainability on top of Open Source. Over the next year we'll be exploring how we can create a sustainable business to support a 100% free, open source Astro for years to come.

If your company is as excited about Astro as we are, [we'd love to hear from you.](https://astro.build/chat)

Finally, I'd like to give a **HUGE** thanks to the 300+ developers who joined our earliest private beta. Your feedback has been essential in shaping Astro into the tool it is today. If you're interested in getting involved (or just following along with development) please [join us on Discord.](https://astro.build/chat)

> To learn more about Astro and start building your first site, check out [the project README.](https://github.com/snowpackjs/astro#-guides)
