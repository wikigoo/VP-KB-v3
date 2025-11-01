─────────────────────────────
PROMPT 3: VALIDATION AND ENHANCEMENT
─────────────────────────────

INPUTS:
- PROMPT 1 OUTPUT: Original extracted data
- PROMPT 2 OUTPUT: Current guide structure

TASK:
Enhance the guide by cross-referencing with source documents and 
adding practical depth.

ENHANCEMENT PROCESS:

For each step in Prompt 2:

1. ACCURACY VERIFICATION
   → Cross-check against Prompt 1 data
   → Ensure critical information wasn't omitted
   → Verify technical accuracy

2. DETAIL EXPANSION
   Add to each sub-action:
   • Specific parameters, values, or settings
   • Exact commands, file paths, or tool names
   • Version numbers or specifications (if relevant)
   • Time estimates for completion

3. PRACTICAL ADDITIONS
   For each step, add:
   • Validation: "How to verify this step worked"
   • Common mistakes: "Typical errors to avoid"
   • Quick fixes: "If X fails, try Y"

4. CROSS-REFERENCING
   Identify related content in your KB:
   • Prerequisites: "Read first: [article name]"
   • Related workflows: "Similar to: [article name]"
   • Next steps: "Continue with: [article name]"

ENHANCED STRUCTURE TEMPLATE:
─────────────────────────────
[GUIDE TITLE]
─────────────────────────────

PREREQUISITES:
- [Item with specific versions/models]
- [Item with specific versions/models]

ESTIMATED TIME: [X minutes/hours]

RELATED GUIDES:
- Read First: [prerequisite article if applicable]
- See Also: [related workflow article if applicable]

─────────────────────────────
STEP 1: [Action-Oriented Title]
─────────────────────────────
1.1 [Sub-action with specific parameters]
    → Details: [Exact values, settings, commands]
    → Tool: [Specific tool/software used]
    
1.2 [Sub-action with specific parameters]
    → Details: [Exact values, settings]
    ⚠️ Warning: [If applicable]
    
1.3 [Sub-action with specific parameters]
    → Details: [Exact values, settings]
    → Time: [Estimate if relevant]

✓ CHECKPOINT: [Detailed success criteria]
   Verify by: [Specific validation method]

💡 TIPS:
- [Helpful shortcut or best practice]
- [Common mistake to avoid]

🔧 IF PROBLEMS:
- If [issue], then [quick fix]

─────────────────────────────
STEP 2: [Action-Oriented Title]
─────────────────────────────
[Same enhanced structure]

─────────────────────────────
[Continue for all steps...]
─────────────────────────────

IMPORTANT WARNINGS:
⚠️ [Critical warning 1]
⚠️ [Critical warning 2]

FINAL RESULT:
✓ [Expected final outcome]
✓ [Quality indicators]

─────────────────────────────

TARGET LENGTH: ~800 words
FOCUS: Actionable precision

CONSTRAINTS:
- Maintain step sequence from Prompt 2
- Expand depth within existing steps
- Every sub-action needs specific details
- Add validation for each step

QUALITY CHECKLIST:
☐ All steps have specific parameters/values
☐ Tips provided for complex steps
☐ Quick fixes for common issues
☐ Related articles identified
☐ Time estimates included where relevant