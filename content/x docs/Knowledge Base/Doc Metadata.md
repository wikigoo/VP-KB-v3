
## Document Title Formula

**Format:** `[Type]: [Topic] - [Specific Focus]`

## Document Naming Rules

✅ **DO:**
- Use title case: `Guide: Building Knowledge Bases`
- Be specific: `FAQ: Claude Projects File Size Limits`
- Keep under 60 characters
- Front-load keywords for search

❌ **DON'T:**
- Use generic titles: `Document1`, `Notes`
- Include dates: `Guide_2024_final`
- Use special characters: `Setup!!!`

## Frontmatter Template

Use this YAML structure at the top of every document:
```yaml
---
title: "Guide: Your Document Title"
subtitle: "Brief explanatory subtitle (optional)"
description: "One-sentence summary for search results and chatbot retrieval"
categories:
  - primary-category
  - secondary-category
tags:
  - keyword-1
  - keyword-2
  - keyword-3
  - tool-name
  - task-type
date: YYYY-MM-DD
toc: true
lang: en
words: 500
summary: "2-3 sentence overview of document content for quick reference"
---
```

