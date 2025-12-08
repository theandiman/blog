# Andy's Engineering Blog

A Jekyll-based blog for software engineering insights, cloud architecture, and technical deep dives.

## Local Development

### Prerequisites

- Ruby 2.7 or higher
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000
```

## Writing Posts

Create new posts in the `_posts` directory following the naming convention:

```
YYYY-MM-DD-title-of-post.md
```

### Post Template

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS +0000
categories: category-name
tags: [tag1, tag2, tag3]
---

Your content here...
```

## Deployment

This blog is configured for GitHub Pages. Push to the `main` branch to deploy.

## License

Content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
Code snippets are licensed under MIT.
