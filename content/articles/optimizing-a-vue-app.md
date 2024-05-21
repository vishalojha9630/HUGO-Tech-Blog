---
title: "Optimizing a Vue App"
date: 2022-12-21T15:13:35+05:30
draft: false
author: "Michelle Barker"
cover: "images/author/michelle.avif"
description: "Michelle Barker is a product designer and developer with a deep love for design systems and open-source design."
categories: ["JavaScript"]
---

Prioritizing performance when building our web apps improves the user experience and helps ensure they can be used by as many people as possible. In this article, Michelle Barker will walk you through some of the front-end optimization tips to keep our Vue apps as efficient as possible.
 
 <!--more-->

Single Page Applications (SPAs) can provide a rich, interactive user experience when dealing with real-time, dynamic data. But they can also be heavy, bloated, and perform poorly. In this article, we’ll walk through some of the front-end optimization tips to keep our Vue apps relatively lean and only ship the JS we need when it’s needed.

{{< aws-amplify >}}
{{< progress-kendo-React >}}

## Tables

Tables are created by adding pipes as dividers between each cell, and by adding a line of dashes (also separated by bars) beneath the header. Note that the pipes do not need to be vertically aligned.

```markdown
| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
```
