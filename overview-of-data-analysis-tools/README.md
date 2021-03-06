# Overview of Data Analysis Tools README

"Overview of Data Analysis Tools" is a high-level map to the current landscape of general-purpose data analysis tools that are accessible to non-experts.

The objective is to point you in the direction of common tools and what situations they are best suited, with an emphasis on tools that are free or open-source.

## Versions

There are two versions containing the same content:
- A markdown document: overview-of-data-analysis-tools.md
- A slide deck: overview-of-data-analysis-tools-slides.html

## Creating slides

Slides are [remark](https://github.com/gnab/remark) and generated from the markdown document using the [markdown-to-slides](https://www.npmjs.com/package/markdown-to-slides) Node.js package.

To generate slides from the markdown document, run in command line:

    markdown-to-slides overview-of-data-analysis-tools.md -o overview-of-data-analysis-tools-slides.html -s style.css
