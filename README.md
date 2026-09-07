# builderownership.com

The site served at [builderownership.com](https://builderownership.com).

Shala Phansalkar, technical recruiting for startups.
AI and machine learning, blockchain, fintech and trading systems.

[linkedin.com/in/shalaphansalkar](https://www.linkedin.com/in/shalaphansalkar/)

## What is in here

Static HTML on GitHub Pages. No build step, no dependencies, nothing to install.

| File | Served at |
|---|---|
| `index.html` | the root, which forwards to LinkedIn |
| `<role>/index.html` | builderownership.com/`<role>` |
| `CNAME` | tells GitHub Pages which domain to answer for |
| `robots.txt` | crawling rules |

Role pages carry a no-index tag, so they stay out of search results. The root
does not, so the domain itself can be found and sends anyone who looks to
LinkedIn.

## Editing

Changing a file changes what is live at the same address. A page that has
already been shared keeps its link and simply shows the newer version.
