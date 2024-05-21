---
title: "Guide Command Line Data Manipulation Cli Miller"
date: 2022-12-29T19:05:11+05:30
author: "Alvin Bryan"
cover: "images/author/alvin-bryan.avif"
description: "Alvin Bryan is a Developer Advocate and an avid online learner. He is currently working at Contentful, previously at the Wall Street Journal."
categories: ["Python", "Apps", "Editior" ]
draft: false
---

No more random scripts in Python and JavaScript to transform CSV or JSON data. In this article, Alvin Bryan shows you how to use Miller, a small and powerful CLI tool, to do all your data processing.
 
 <!--more-->

Allow me to preface this article by saying that I’m not a terminal person. I don’t use Vim. I find sed, grep, and awk convoluted and counter-intuitive. I prefer seeing my files in a nice UI. Despite all that, I got into the habit of reaching for command-line interfaces (CLIs) when I had small, dedicated tasks to complete. Why? I’ll explain all of that below. In this article, you’ll also learn how to use a CLI tool named Miller to manipulate data from CSV, TSV and/or JSON files.

### Why Use The Command Line? **[#](#why-use-the-command-line?)**
Everything that I’m showing here can be done with regular code. You can load the file, parse the CSV data, and then transform it using regular JavaScript, Python, or any other language. But there are a few reasons why I reach out for command-line interfaces (CLIs) whenever I need to transform data:

- **Easier to read:-**
It is faster (for me) to write a script in JavaScript or Python for my usual data processing. But, a script can be confusing to come back to. In my experience, command-line manipulations are harder to write initially but easier to read afterward.

- **Easier to reproduce:-**
Thanks to package managers like Homebrew, CLIs are much easier to install than they used to be. No need to figure out the correct version of Node.js or Python, the package manager takes care of that for you.

- **Ages well:-**
Compared to modern programming languages, CLIs are old. They change a lot more slowly than languages and frameworks.

### What Is Miller? **[#](#what-is-miller?)**
The main reason I love Miller is that it’s a standalone tool. There are many great tools for data manipulation, but every other tool I found was part of a specific ecosystem. The tools written in Python required knowing how to use pip and virtual environments; for those written in Rust, it was cargo, and so on.

On top of that, it’s fast. The data files are streamed, not held in memory, which means that you can **`perform operations on large files without freezing your computer.`**

As a bonus, Miller is actively maintained, John Kerl really keeps on top of PRs and issues. As a developer, I always get a satisfying feeling when I see a neat and maintained open-source `project with great documentation.`


{{< aws-amplify >}}

{{<highlight html>}}
Paragraph in Markdown.

<div class="class">
    This is <b>HTML</b>
</div>

Paragraph in Markdown.
{{< / highlight >}}

{{< progress-kendo-React >}}


{{<highlight Shell>}}
# some code
echo "Hello World"

{{< / highlight >}}


The JSON looks like:

{{<highlight Json>}}
[
    {
      "title": "apples",
      "count": [12000, 20000],
      "description": {"text": "...", "sensitive": false}
    },
    {
      "title": "oranges",
      "count": [17500, null],
      "description": {"text": "...", "sensitive": false}
    }
]
{{< / highlight >}}
    

**Code block with Hugo’s internal highlight shortcode**

{{<highlight html>}}
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
{{< / highlight >}}

<!-- ![Jane Doe](/images/featureImg/themes.webp) -->

The HTML looks like this:

```html
<strong>rendered as bold text</strong>
```