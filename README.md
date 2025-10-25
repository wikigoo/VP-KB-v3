# AI Chatbot Knowledge Base (VP-KB-v3)

A comprehensive knowledge base covering AI chatbots, journalism, podcasting, video production, research methods, and professional writing.

## About

This is a Jekyll-based knowledge base site using the Chirpy theme, hosted on GitHub Pages.

**Site URL**: [https://wikigoo.github.io/VP-KB-v3](https://wikigoo.github.io/VP-KB-v3)

## Content Structure

The knowledge base is organized into seven main sections:

### 01. AI Chatbot
- Chatbot platforms (Gemini, ChatGPT, Claude)
- AI tools (prompt generators, content generators)
- Prompt library

### 02. Journalism
- AI journalism tools and research
- News writing (articles, headlines, analytical pieces)
- News editing guides
- Data and investigative journalism

### 03. Podcast Production
- Scripting (general and political satire)
- Speaking style guides
- TTS optimization

### 04. Video Production
- News production workflow
- Equipment guides (Canon R8, Sony Z90)
- Software tutorials (Premiere Pro 2025, vMix)
- Video scripting

### 05. Research
- Deep research techniques
- Fact-checking methods
- Citation guides

### 06. Writing
- Writing techniques
- Step-by-step guides
- Templates

## Local Development

### Prerequisites
- Ruby 3.x
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Run locally
bundle exec jekyll serve

# View at http://localhost:4000/VP-KB-v3
```

## Adding Content

### Creating Posts

Posts go in the `_posts` directory with the naming format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "Your Post Title"
date: 2025-10-25 00:00:00 +0000
categories: [Category, Subcategory]
tags: [tag1, tag2]
---

Your content here...
```

### Creating Pages

Pages can be added anywhere in the directory structure with frontmatter:

```markdown
---
layout: page
title: Your Page Title
---

Your content here...
```

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the main/master branch via GitHub Actions.

## Repository Structure

```
├── 01-ai-chatbot/          # AI chatbot platforms and tools
├── 03-journalism/          # Journalism guides and techniques
├── 04-podcast/             # Podcast production
├── 05-video-production/    # Video production guides
├── 06-research/            # Research methods
├── 07-writing/             # Writing techniques
├── _posts/                 # Blog posts
├── _tabs/                  # Navigation tabs
├── assets/                 # Static assets
├── _config.yml             # Jekyll configuration
├── Gemfile                 # Ruby dependencies
└── index.md                # Homepage
```

## Contributing

To contribute content:

1. Create new markdown files in the appropriate directory
2. Follow the frontmatter format
3. Use relative links for internal pages
4. Place images in `assets/images/`

## License

This project is open source and available for educational and professional use.

## Contact

For questions or suggestions, please open an issue on GitHub.
