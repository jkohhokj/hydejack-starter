---
layout: about
description: >
  College Student
hide_description: true
redirect_from:
  - /download/
---

# About

  Hey, 👋 I'm Jayden. I currently attend Texas A&M, CO '27. Let's go Aggies! 
  I graduated from a health professions 🩺 high school, DeBakey High School in Houston, Texas but my interests lie in software 🤖 and cybersecurity ⚔️🛡️.
  I enjoy bouldering 🧗‍♂️, working out 🏋️, folding origami 🦢, and playing CTFs 🚩 in my free time.



  This is my open book project where I share my ideas, experience, and knowledge!

## Hydejack


{:.lead}

1. Table Of Contents
{:toc .large-only}

![Screenshot](assets/img/blog/hydejack-9.jpg){:.lead width="1920" height="1080" loading="lazy"}

Custom banner
{:.figcaption}


**Hydejack** is a boutique Jekyll theme for hackers, nerds, and academics, with a focus on personal sites that are meant to impress. 

It includes a blog that is suitable for both prose and technical documentation, a portfolio to showcase your projects, and a resume template that looks amazing on the web and in print.

> Your complete presence on the web — A [blog], [portfolio], and [resume].
{:.lead}



## Download

{% include table.md %}


## A Free Blogging Theme
**Hydejack** started out as a free blogging theme for Jekyll — and continues to be so.

<!--posts-->


## An Impressive Portfolio
A portfolio that's guaranteed to be impressive — no matter what you put into it.

<!--projects-->


## A Printable Resume
Get a resume that's consistent across the board — whether it's on the web, mobile, print, or [PDF](assets/Resume-Spring-2024.8.pdf).

[![Resume PDF](assets/Resume-Spring-2024.8.pdf){:.lead width="884" height="632" loading="lazy"}][resume]{:.no-hover.no-mark}
<!-->[![Resume PDF](assets/resume.png){:.lead width="884" height="632" loading="lazy"}][resume]{:.no-hover.no-mark}-->
Jayden Koh's Resume.
{:.figcaption}


## Just Markdown
Write all content with Markdown. __Hydejack__ gives you [additional CSS classes](docs/writing.md) to stylize your content, without losing compatibility with other Jekyll themes.



## Syntax Highlighting
**Hydejack** features syntax highlighting, powered by [Rouge].

```html
<!-- file: `_includes/my-body.html` -->
<script type="module">
  document.querySelector("hy-push-state").addEventListener("hy-push-state-load", () => {
    const supportsCodeHighlights = false; // TBD!!
  });
</script>
```

Code blocks can have a filename and a caption.
{:.figcaption}


## Beautiful Math
They say math is beautiful — and with **Hydejack**'s [math support][math] it's guaranteed to also look beautiful:

$$
\begin{aligned}
  \phi(x,y) &= \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right) \\[2em]
            &= \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j)            \\[2em]
            &= (x_1, \ldots, x_n)
               \left(\begin{array}{ccc}
                 \phi(e_1, e_1)  & \cdots & \phi(e_1, e_n) \\
                 \vdots          & \ddots & \vdots         \\
                 \phi(e_n, e_1)  & \cdots & \phi(e_n, e_n)
               \end{array}\right)
               \left(\begin{array}{c}
                 y_1    \\
                 \vdots \\
                 y_n
               \end{array}\right)
\end{aligned}
$$

Hydejack uses KaTeX to efficiently render math.
{:.figcaption}

## Features

{% include features.md %}


## Comparison

{% include table.md %}


[blog]: /
[portfolio]: https://github.com/jkohhokj
[resume]: /assets/Resume-Spring-2024.8.pdf
[download]: https://hydejack.com/download/
[welcome]: https://jkoh.dev/
[forms]: https://hydejack.com/forms-by-example/

[features]: #features
[news]: #build-an-audience
[syntax]: syntax-highlighting
[latex]: #beautiful-math
[dark]: https://hydejack.com/blog/hydejack/2018-09-01-introducing-dark-mode/
[search]: https://hydejack.com/#_search-input
[grid]: https://hydejack.com/blog/hydejack/

[lic]: LICENSE.md
[pro]: licenses/PRO.md
[docs]: docs/README.md
[ofln]: docs/advanced.md#enabling-offline-support
[math]: docs/writing.md#adding-math

[kit]: https://github.com/hydecorp/hydejack-starter-kit/releases
[src]: https://github.com/hydecorp/hydejack
[gem]: https://rubygems.org/gems/jekyll-theme-hydejack
[buy]: https://gum.co/nuOluY

[gpss]: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fhydejack.com%2Fdocs%2F
[rouge]: http://rouge.jneen.net
[katex]: https://khan.github.io/KaTeX/
[mathjax]: https://www.mathjax.org/
[tinyletter]: https://tinyletter.com/
