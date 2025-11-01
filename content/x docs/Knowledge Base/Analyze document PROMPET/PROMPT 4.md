## PROMPT 4 COMPLETE GUIDE DOCUMENTATION

### INPUTS:
- PROMPT 1 OUTPUT: Original extracted data
- PROMPT 2 OUTPUT: Initial guide structure
- PROMPT 3 OUTPUT: Enhanced guide with details

### TASK:
Transform the enhanced guide into a complete knowledge base article 
using the template structure below.

CONTENT DEVELOPMENT STRATEGY:

1. FLEXIBLE WORD COUNT ALLOCATION

   Base allocation on Prompt 3 complexity:
   
   • Overview: 200-300 words
   • Each major step: 150-250 words (varies by complexity)
   • Examples: 200-400 words
   • Best Practices: 150-250 words
   • Supporting sections: 100-200 words each
   
   TARGET RANGE: 800-3000 words total
   
   Let content complexity dictate final length:
   - Simple 3-5 step guides: 800-1500 words
   - Medium 6-8 step guides: 1500-2200 words
   - Complex 9+ step guides: 2200-3000 words

2. CATEGORY & TAG ASSIGNMENT

   CATEGORIES (Select 1-2):
   • AI-Chatbot
   • Journalism
   • Podcast-Production
   • Video-Production
   • Research
   • Writing

   TAGS (Select 3-6):
   
   Content Type (pick 1):
   - guide, tutorial, template, checklist, reference
   
   Tools/Platforms (pick 1-3 as relevant):
   - chatgpt, claude, gemini
   - premiere-pro, vmix
   - canon-r8, sony-z90
   - tts, scripting-tools
   
   Themes (pick 1-2 as relevant):
   - ai-assisted, workflow, optimization, troubleshooting
   - beginner, intermediate, advanced
   -
   ## Document Title Formula

**Format:** `[Type]: [Topic] - [Specific Focus]`

3. Document Naming Rules
✅ **DO:**
- Use title case: `Guide: Building Knowledge Bases`
- Be specific: `FAQ: Claude Projects File Size Limits`
- Keep under 60 characters
- Front-load keywords for search

❌ **DON'T:**
- Use generic titles: `Document1`, `Notes`
- Include dates: `Guide_2024_final`
- Use special characters: `Setup!!!`

4. TEMPLATE POPULATION GUIDE

   A. FRONT MATTER
````yaml
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
  
   B. TITLE & PURPOSE
````markdown
   # [Repeat title]
   
   > **Purpose:** [State what user will accomplish and any 
   > prerequisites. 40-60 words max.]

   C. SECTION 1: OVERVIEW (200-300 words)
   
   Include:
   • Why this guide exists (context from Prompt 1)
   • What you'll accomplish (outcomes)
   • What you need before starting (prerequisites)
   • Key terms defined (from Prompt 1)
   
   Structure:
   - 2-3 paragraphs (each ≤400 words)
   - Use > blockquotes for definitions
   - Add tip if helpful:
     > [Helpful tip]
     {: .prompt-tip }

   D. SECTION 2: STEP-BY-STEP GUIDE (Primary content - 40-50% of words)
   
   Transfer ALL steps from Prompt 3:

   ### Step 1: [Title from Prompt 3]
   
   [1-2 sentence intro about what this step accomplishes]
   
   1. **[Sub-action 1.1]**
      
      [Expand details from Prompt 3]
      [Include specific settings/parameters]

      # Code or commands if applicable
      [exact command]
      
      Expected: [What you should see]
   
   2. **[Sub-action 1.2]**
      
      [Expanded explanation]
      
      > ⚠️ **Warning:** [From Prompt 3]
      {: .prompt-warning }
   
   **✓ Checkpoint:** [From Prompt 3]  
   **Verify:** [Validation method]
   
   > 💡 **Tips:**  
   > • [Tip 1 from Prompt 3]  
   > • [Tip 2 from Prompt 3]
   {: .prompt-info }
   
   ---
   
   [Repeat for all steps]
   
   FORMATTING:
   • Use ### for step titles
   • Use **bold** for sub-actions
   • Use ``` for code/commands (specify language)
   • Use > with {: .prompt-warning/info/tip } for callouts
   • Use --- between major steps

   E. SECTION 3: EXAMPLES (200-400 words)
   
   Provide 1-3 practical examples:
   
   **Example 1: [Scenario Name]**
   
   Context: [Brief setup]
````[language]
   [Working example code/workflow]
   
   Result: [Expected output]
   
   Key Points: [What makes this work]
   
   ---
   
   [Add 1-2 more examples if source material provides them]

   F. SECTION 4: BEST PRACTICES (150-250 words)
   
   **✅ Best Practices:**
   
   - [Practice 1 from Prompt 3]
   - [Practice 2 from Prompt 3]
   - [Practice 3 from Prompt 3]
   
   **❌ Avoid These:**
   
   - [Common mistake 1 from Prompt 3]
   - [Common mistake 2 from Prompt 3]
   - [Common mistake 3 from Prompt 3]
   
   > 💡 [Pro tip or key insight]
   {: .prompt-tip }

   G. SECTION 5: RELATED GUIDES (50-100 words)
   
   Based on Prompt 3 cross-references:
   
   **Prerequisites:**
   - [Article you should read first]
   
   **Related Workflows:**
   - [Similar process article]
   - [Alternative approach article]
   
   **Next Steps:**
   - [Advanced follow-up article]

   H. SECTION 6: REFERENCES (if applicable)
   
   List authoritative sources:
   - [Official tool documentation](URL)
   - [Tutorial or guide referenced](URL)
   - [Equipment specifications](URL)

   I. SECTION 7: QUICK REFERENCE (Optional - for complex guides)
   
   | Action | Command/Setting | Notes |
   |--------|-----------------|-------|
   | [Task] | [Exact command] | [Tip] |
   | [Task] | [Exact setting] | [Tip] |

4. FINDABILITY OPTIMIZATION (Personal KB)

   At the top of your notes (not in published article), record:
   
   **Alternative Search Terms:**
   - [Synonym 1], [Synonym 2], [Synonym 3]
   
   **Common Questions This Answers:**
   - "How do I [specific task]?"
   - "What's the best way to [goal]?"
   
   **Quick Answer:**
   - [One-sentence summary of solution]

5. QUALITY CHECKLIST

   ☐ ALL steps from Prompt 3 fully documented
   ☐ ALL warnings included with {: .prompt-warning }
   ☐ ALL tips/troubleshooting integrated
   ☐ Code blocks use proper syntax (```language)
   ☐ Word count: 800-3000 (appropriate to complexity)
   ☐ No paragraph exceeds 400 words
   ☐ Front matter description ≤300 characters
   ☐ Title ≤70 characters
   ☐ Categories match your 6-category taxonomy
   ☐ Tags follow your defined tag system (3-6 tags)
   ☐ At least 1 practical example provided
   ☐ Related guides section filled (or marked N/A if truly none)
   ☐ All checkpoints from Prompt 3 clearly marked

6. WRITING STYLE

   • Use active voice: "Click the button" not "The button should be clicked"
   • Be specific: "Set to 4K 30fps" not "Set appropriate resolution"
   • Present tense: "This creates..." not "This will create..."
   • Keep sentences under 25 words when possible
   • Define technical terms at first use
   • Use parallel structure in lists

OUTPUT FORMAT:
Complete markdown document ready for your knowledge base.

Begin with:

---
[complete front matter]
---

# [Title]
...

End with:

---
**Word Count:** [Actual count]
**Last Updated:** [Current date]

PERSONAL KB CATEGORY REFERENCE

Your 6 Main Categories:
1. AI-Chatbot → Platforms, tools, prompts
2. Journalism → News writing, editing, data journalism
3. Podcast-Production → Scripting, TTS, speaking guides
4. Video-Production → Workflow, equipment, software
5. Research → Techniques, fact-checking, citations
6. Writing → Techniques, guides, templates

Common Cross-Category Articles:
- AI + Journalism = AI journalism tools
- Research + Journalism = Investigative techniques
- Writing + ALL = Universal writing principles
- Video + Podcast = Production workflows
- AI + Writing = AI-assisted content
