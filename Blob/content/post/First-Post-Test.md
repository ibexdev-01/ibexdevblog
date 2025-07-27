---
title: "First-Post-Test" # Must be present and unique
date: 2025-07-26T20:01:00+05:30 # Use a specific date/time format, e.g., YYYY-MM-DDTHH:MM:SS+HH:MM
draft: false # VERY IMPORTANT: Change to 'false' to make the post visible
author: "Your Name" # As defined in your hugo.toml params.author
description: "A short, engaging description for SEO and social media." # Good for SEO
summary: "This is the summary that appears on the list page. Keep it concise." # Optional, but good for list pages
tags:
  - tag1 # Use a list format for multiple tags
  - tag2
categories:
  - category1 # Use a list format for multiple categories (if used by theme)
# Optional fields from README:
# pin: true # To pin the post (if theme supports it)
# katex: math # For LaTeX support
# mathJax: true # For MathJax support
---

This is the **main body** of my first test blog post.

It begins here, just after the front matter. I'm writing a few paragraphs to make sure that the full content renders when I click on the post title from the main blog page.

### What I'm Testing

* **Full Content Display:** The primary goal is to see if everything written below the front matter and `` tag appears on the single post page.
* **Markdown Rendering:** Basic markdown like **bold text**, *italic text*, and `inline code` should work.
* **Code Blocks:**
    ```python
    def hello_world():
        print("Hello, Hugo!")
    ```
    This is a Python code block.
* **Lists:**
    * Item one
    * Item two
        * Nested item A
        * Nested item B

This section appears *after* the `` tag. This is specifically designed to be part of the full post content but **NOT** part of the summary if the `` approach is used for summaries (the `summary` front matter takes precedence if both are present).

Here's another paragraph to ensure there's enough content to scroll. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Conclusion of Test Post

If you are reading this entire section, it means the `{{- .Content -}}` variable is correctly pulling and rendering the full Markdown into HTML on your single post page. Success!