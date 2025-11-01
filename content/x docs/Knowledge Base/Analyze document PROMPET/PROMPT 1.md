
```
─────────────────────────────
PROMPT 1: SOURCE DOCUMENT EXTRACTION
─────────────────────────────
CONTEXT:
You will analyze attached documents to extract actionable information
for creating practical guides in a personal knowledge base covering:
AI Chatbots, Journalism, Podcast Production, Video Production,
Research, and Writing.

TASK:
For each document, extract and categorize:

1. PRIMARY PURPOSE (1-2 sentences)
What problem does this document solve or what process does it describe?
2. ACTIONABLE ITEMS (numbered list)
    - Concrete steps, procedures, or instructions
    - Methods or techniques to implement
    - Specific actions to execute
    - Tool settings or configurations
    
    ✓ Include: "Set Canon R8 to 4K 30fps", "Write headline under 70 chars"
    ✗ Exclude: Background theory, historical context, conceptual explanations
    
3. CRITICAL INFORMATION
    - Prerequisites or requirements
    - Equipment/software needed
    - Warnings, constraints, or limitations
    - Quality criteria or success indicators
    - Time estimates (if mentioned)
4. KEY TERMINOLOGY
    - Technical terms essential for understanding
    - Tool-specific vocabulary
    - Domain jargon used
5. VISUAL ELEMENTS (if present)
    - Screenshots or images described
    - Diagrams or flowcharts mentioned
    - Tables or reference data

OUTPUT FORMAT:
─────────────────────────────
DOCUMENT 1: [Document Name/Title]
─────────────────────────────

Purpose:
[1-2 sentence description]

Actionable Items:

1. [Specific action or step]
2. [Specific action or step]
3. [Specific action or step]
[Continue as needed]

Critical Information:

- Prerequisites: [list]
- Equipment/Software: [list]
- Warnings: [list]
- Success Criteria: [list]
- Time Required: [if mentioned]

Key Terms:
[term1], [term2], [term3]

Visual Elements:

- [Screenshot/diagram description]
- [Table/reference data description]
─────────────────────────────
DOCUMENT 2: [Document Name/Title]
─────────────────────────────
[Repeat same structure]
─────────────────────────────
[Continue for all documents]
─────────────────────────────
VALIDATION CHECK:
☐ Each document has at least 3 actionable items
☐ No theoretical content in actionable items
☐ Critical information clearly separated
☐ Terminology is concise and relevant
```