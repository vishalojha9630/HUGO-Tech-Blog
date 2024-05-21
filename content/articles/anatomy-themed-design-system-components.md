---
title: "Anatomy Themed Design System Components"
date: 2022-12-26T11:33:55+05:30
draft: false
author: "Dan Donald"
cover: "images/author/donald.avif"
description: "Dan is a Design Advocate for zeroheight, a design system documentation product, drawing on his experience at Auto Trader in the UK, looking after the design system and helping to improve the consumer experience there"
categories: ["Designer"]
---


The world of design systems can be overwhelming sometimes. There’s a lot to take in when you get into that space! In this article, Dan Donald dives into a simple component and explores some issues, complexity, and power we can encounter.
 
 <!--more-->

Before we start with a deep dive into the details and the anatomy of a component, let’s start at a higher level and see what we’re working on within our design system.

<!-- ![Jane Doe](/images/featureImg/scrollCover.webp) -->
<!-- {{< figure src="/images/featureImg/scrollCover.webp" title="Illustration from Victor Hugo et son temps (1881)" >}} -->

### Laying It All Out **[#](#laying-it-all-out)**

Whether we’re at the beginning of our design systems journey or working on improving what we have, **audits are a useful process to get clarity on what is actually used in our websites or apps**. At the beginning of a design system, assuming it’s for an existing product, an audit of what design artifacts we have helps get an appreciation of the current state of play. You might use an online collaboration tool or walls in your office with printouts and post-its. Laying out what exists where and grouping and categorizing them helps to quantify what’s used ‘in the wild.’

From this, we can zoom in a little, picking one component at a time, and ask some questions about it: What is the purpose of this component? What is it for? Early on, this engages us with a line of questioning that seeks out the intent of a given component, giving clarity to the problem which is there to solve. Our components are a collection of solved problems, after all.

There may be a lot to go at, and there may be many variants of the same or similar-looking components out there already, so how do we rationalize them and go deeper into what they are?

<!-- ![Summary view](/assets/images/5-connecting-fonts-extensis.webp) -->

{{< aws-amplify >}}

The Image figure looks like this:

```html
<figure>
    <img src="/images/lighthouse.jpg"/>
    <figcaption>
        <h4>Lighthouse (figure)</h4>
    </figcaption>
</figure>
```

{{< progress-kendo-React >}}


The CSS figure looks like this:
```css

  pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;
  }

  media {
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  code {
    background: none !important;
    color: #ccc;
    padding: 0;
    font-size: inherit;
  }

  copyable {
  position: absolute;
  height: 0;
  z-index: -1;
  opacity: .01;
}

```

```html
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

# Table of Contents
  * [Chapter 1](#chapter-1)
  * [Chapter 2](#chapter-2)
  * [Chapter 3](#chapter-3)
