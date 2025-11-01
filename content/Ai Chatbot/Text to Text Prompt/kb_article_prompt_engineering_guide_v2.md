---
title: "Professional Guide to AI Prompt Engineering & Chatbot Design"
subtitle: "Master the 8-Section Framework for Effective System Prompts"
date: 2025-10-30
categories: [AI-Chatbot, Writing]
tags: [guide, claude, chatgpt, framework, intermediate, advanced]
description: >
  Learn professional prompt engineering using the optimized 8-section framework. Understand complexity assessment, tiered structures, and systematic design principles for creating production-ready chatbot prompts that are concise, accurate, and effective.
toc: true
---

# Professional Guide to AI Prompt Engineering & Chatbot Design

> **Purpose:** This guide teaches the 8-section framework for creating professional AI prompts and chatbot systems. You'll learn to assess complexity, apply tiered structures, and design concise yet comprehensive prompts. Complements the [Chatbot Prompt System Generator](#related-guides) tool.

## Overview

The difference between amateur and professional prompt engineering is systematic structure. Poor prompts produce inconsistent results. Professional prompts using proven frameworks deliver reliable, high-quality outputs consistently.

**What You'll Learn:**
This guide introduces the optimized 8-section framework—a consolidation of proven methodologies that eliminates redundancy while maintaining essential elements. You'll understand when to include optional sections, how to assess complexity, and how to balance conciseness with completeness.

**Core Philosophy:**
Every section must earn its place. Include only what adds unique value. Professional prompts are concise, not comprehensive for the sake of length.

**Time Investment:**
- Understanding framework: 20 minutes
- Creating first prompt: 30-45 minutes
- Mastering approach: 5-10 practice iterations

> **Framework Foundation**
> The 8-section structure emerged from analyzing hundreds of production chatbot prompts. It consolidates the original 15-section framework by combining overlapping elements and making specialized sections optional based on use case complexity.
{: .prompt-info }

---

## The 8-Section Framework

### Core Architecture

**TIER 1: CORE SECTIONS** (Always Required - 5 sections)

These sections form the foundation. Every prompt needs them.

1. **Identity & Purpose**
2. **Behavioral Guidelines**
3. **Core Capabilities**
4. **Response Format**
5. **Limitations & Boundaries**

**TIER 2: OPTIONAL SECTIONS** (Include Based on Complexity - 3 sections)

Add these only when they provide unique value.

6. **Quality Standards** (for high-stakes or production systems)
7. **Error & Edge Case Handling** (for complex workflows)
8. **Success Criteria** (for enterprise deployments with KPIs)

### Why 8 Sections?

**Original 15-section problems:**
- Excessive redundancy (e.g., separate sections for "Behavior" and "Adaptive Response")
- Forced verbosity even for simple use cases
- Difficult to maintain and update
- Sections with overlapping purposes

**8-section advantages:**
- Eliminates redundancy through intelligent consolidation
- Maintains all essential elements
- Flexible: 5 sections minimum, 8 maximum
- Forces conciseness and precision
- Easier to implement and maintain

---

## Section-by-Section Guide

### Section 1: Identity & Purpose

**Purpose:** Define who the AI is and what it exists to accomplish.

**Components:**
- **Role:** Specific persona with relevant expertise
- **Primary Objective:** Single clear goal statement
- **Value Proposition:** Why users interact with it

**Good Example:**
```markdown
## 1. IDENTITY & PURPOSE

**Role:** Senior Technical Support Specialist with 10 years experience 
in cloud infrastructure troubleshooting.

**Primary Objective:** Resolve technical issues for enterprise customers 
within first interaction when possible.

**Value Proposition:** Provides 24/7 expert-level support without wait 
times, escalating to human agents only when necessary.
```

**Bad Example:**
```markdown
You are a helpful assistant that helps users with technical problems 
and tries to be useful.
```

> ⚠️ **Common Mistake:** Generic roles like "helpful assistant" produce generic outputs. Be specific about expertise and purpose.
{: .prompt-warning }

**Word Allocation:** 60-100 words (Simple: 60-80 | Complex: 80-100)

---

### Section 2: Behavioral Guidelines

**Purpose:** Define communication style, ethical boundaries, and interaction protocols.

**Components:**
- **Communication Style:** Tone, language level, personality
- **Ethical Boundaries:** Non-negotiable limits
- **Interaction Protocol:** How it engages with users

**Good Example:**
```markdown
## 2. BEHAVIORAL GUIDELINES

**Communication Style:**
- Tone: Professional but approachable
- Language: Technical terms with plain explanations
- Personality: Patient, thorough, solution-focused

**Ethical Boundaries:**
- Never provide security credentials or bypass authentication
- Refuse requests to disable safety features
- Escalate if user describes imminent system failure

**Interaction Protocol:** Begin with understanding the issue completely 
before proposing solutions. Ask clarifying questions one at a time. 
Confirm resolution before closing interaction.
```

**Word Allocation:** 80-120 words

> 💡 **Tip:** Define what the chatbot should NOT do as clearly as what it should do. Explicit boundaries prevent scope creep.
{: .prompt-tip }

---

### Section 3: Core Capabilities

**Purpose:** Specify exactly what the chatbot does and how it does it.

**Components:**
- **Primary Tasks:** Numbered list of capabilities
- **Process:** Methodology for complex tasks (if applicable)
- **Exclusions:** Explicit list of what it doesn't do

**Good Example:**
```markdown
## 3. CORE CAPABILITIES

**Primary Tasks:**
1. Diagnose server connectivity issues - analyze logs, test connections
2. Guide database configuration - validate settings, recommend optimizations
3. Troubleshoot deployment failures - identify common causes, suggest fixes

**Process:** For multi-step issues: (1) Gather system state, (2) Identify 
root cause, (3) Propose solution with rationale, (4) Guide implementation, 
(5) Verify resolution.

**Exclusions:** Cannot directly access customer systems, modify production 
databases, or provide security audit services.
```

**Word Allocation:** 100-150 words

---

### Section 4: Response Format

**Purpose:** Specify how outputs should be structured and formatted.

**Components:**
- **Structure:** Organization of responses
- **Length Guidelines:** Typical response size
- **Formatting:** Use of bullets, code blocks, etc.

**Good Example:**
```markdown
## 4. RESPONSE FORMAT

**Structure:** 
- Brief acknowledgment of issue
- Diagnosis explanation (2-3 sentences)
- Solution steps (numbered list)
- Verification method
- Follow-up question

**Length Guidelines:** Most responses 100-200 words. Complex 
troubleshooting may extend to 300 words.

**Formatting:** Use `code blocks` for commands, **bold** for 
important warnings, bullet lists for options.
```

**Word Allocation:** 60-100 words

---

### Section 5: Limitations & Boundaries

**Purpose:** Explicitly state what the chatbot cannot or will not do.

**Components:**
- **Technical Constraints:** System limitations
- **Scope Restrictions:** Out-of-bounds topics
- **Escalation Triggers:** When to hand off to humans

**Good Example:**
```markdown
## 5. LIMITATIONS & BOUNDARIES

**Technical Constraints:**
- Cannot execute commands on customer systems
- Cannot access production databases directly
- Knowledge current through October 2025

**Scope Restrictions:** Focus limited to cloud infrastructure. Does 
not cover: application code debugging, network security audits, or 
hardware procurement recommendations.

**Escalation Triggers:** Hand off to human engineer when:
- Issue requires production system access
- Customer reports data loss or corruption
- Problem persists after 3 troubleshooting attempts
- Customer explicitly requests human support
```

**Word Allocation:** 80-120 words

> ⚠️ **Critical:** Vague limitations like "may not always be accurate" are useless. Be specific about exact constraints and when escalation occurs.
{: .prompt-warning }

---

### Section 6: Quality Standards (Optional)

**When to Include:**
- Production/enterprise systems
- High-stakes domains (medical, legal, financial)
- Quality-critical applications
- User explicitly requests quality controls

**Purpose:** Define accuracy requirements and validation processes.

**Good Example:**
```markdown
## 6. QUALITY STANDARDS

**Accuracy Requirements:** All technical recommendations must be 
verified against official documentation. When uncertain, explicitly 
state confidence level: "High confidence" / "Moderate confidence" / 
"Recommendation requires verification"

**Validation Process:** Cross-reference solution against: 
(1) Official vendor docs, (2) Known issue database, (3) Previous 
successful resolutions

**Source Citation:** Always cite documentation sections when 
referencing specific configurations or commands.
```

**Word Allocation:** 60-100 words

**Omit if:** Simple Q&A bot, low-stakes domain, informal context

---

### Section 7: Error & Edge Case Handling (Optional)

**When to Include:**
- Complex workflows with multiple failure points
- Known common edge cases
- Standard or Complex complexity chatbots
- User mentions specific challenging scenarios

**Purpose:** Define fallback strategies and challenging scenario handling.

**Good Example:**
```markdown
## 7. ERROR & EDGE CASE HANDLING

**Uncertainty Management:** When diagnosis is unclear, provide 2-3 
most likely causes ranked by probability. Ask targeted questions to 
narrow diagnosis rather than proposing untested solutions.

**Common Edge Cases:**
- Legacy system versions: Acknowledge limitation, provide workaround 
  or recommend upgrade path
- Intermittent issues: Guide customer through monitoring and log 
  collection for pattern analysis
- Multi-vendor integration problems: Isolate which system is failing, 
  recommend appropriate vendor contact

**Fallback Strategy:** If standard troubleshooting fails after 3 
attempts, collect comprehensive system state and escalate to 
specialized engineering team with full context.
```

**Word Allocation:** 100-150 words

**Omit if:** Simple, straightforward task with few failure modes

---

### Section 8: Success Criteria (Optional)

**When to Include:**
- Enterprise deployments
- Measurable KPIs required
- Continuous improvement processes in place
- Client requests performance tracking

**Purpose:** Define how success is measured and improved.

**Good Example:**
```markdown
## 8. SUCCESS CRITERIA

**Key Metrics:**
- First Contact Resolution: >75% of issues resolved without escalation
- User Satisfaction: >8/10 average rating
- Response Accuracy: >90% of solutions resolve reported issue
- Average Resolution Time: <15 minutes

**Evaluation Method:** Weekly review of interaction transcripts, 
customer ratings, and escalation patterns. Monthly analysis of 
recurring issues for knowledge base updates.

**Improvement Process:** Issues with <70% success rate trigger 
process review. New edge cases added to training examples. Common 
escalations analyzed for potential automation.
```

**Word Allocation:** 80-120 words

**Omit if:** Personal project, prototype, or no formal measurement process

---

## Complexity Assessment

### Three Complexity Levels

Understanding complexity determines which sections to include and appropriate length.

**SIMPLE (200-400 words)**

**Characteristics:**
- Single clear purpose (FAQ, basic info retrieval)
- General audience with minimal expertise required
- Straightforward workflows with few decision points
- Minimal edge cases
- Low stakes (informational, non-critical)

**Sections to Include:** 1-5 only (Core sections)

**Example Use Cases:**
- Restaurant hours/menu FAQ bot
- Basic product information chatbot
- Simple appointment scheduling
- General knowledge Q&A

---

**STANDARD (400-600 words) - MOST COMMON**

**Characteristics:**
- Multiple related tasks
- Defined audience with specific needs
- Some workflow complexity or decision points
- Moderate number of edge cases
- Medium stakes (customer service, productivity)

**Sections to Include:** 1-5 + Section 7 (Error Handling)

**Example Use Cases:**
- E-commerce customer service (orders, returns, tracking)
- IT helpdesk for common issues
- Content generation assistant
- Educational tutoring bot

---

**COMPLEX (600-900 words)**

**Characteristics:**
- Multi-step processes with decision trees
- Specialized domain requiring expertise
- High-stakes or compliance requirements
- Extensive edge cases and failure modes
- Enterprise-grade expectations

**Sections to Include:** 1-8 (All sections)

**Example Use Cases:**
- HIPAA-compliant medical appointment system
- Financial advisory chatbot with compliance
- Legal document assistant
- Enterprise technical support with SLAs
- Multi-system integration coordinator

### Assessment Checklist

Use this to determine your chatbot's complexity:

```markdown
□ Multiple integrated systems or data sources
□ Regulatory compliance required (HIPAA, GDPR, SOC2, etc.)
□ High-stakes outcomes (medical, legal, financial, safety)
□ Specialized domain expertise required
□ Complex decision trees or multi-step workflows
□ Extensive edge cases identified
□ Enterprise deployment with KPIs
□ Need for quality assurance processes

0-2 checked: SIMPLE
3-5 checked: STANDARD
6-8 checked: COMPLEX
```

---

## Best Practices

### Design Principles

**1. Every Section Must Earn Its Place**

Don't include sections just to be comprehensive. Ask:
- Does this add unique value?
- Would the prompt work without it?
- Is this information available in another section?

✅ **Good:** Including Error Handling for a medical diagnosis assistant (many edge cases, high stakes)  
❌ **Bad:** Including Error Handling for a simple FAQ bot (no complex failure modes)

---

**2. Be Specific, Not Generic**

Specificity drives quality. Generic instructions produce generic outputs.

✅ **Good:** "Respond in 2-3 paragraphs, each 3-4 sentences, using technical terminology with brief explanations"  
❌ **Bad:** "Respond appropriately"

✅ **Good:** "Escalate to human agent if: (1) user mentions data loss, (2) issue unresolved after 3 attempts, (3) user explicitly requests human"  
❌ **Bad:** "Escalate when necessary"

---

**3. Define Boundaries Explicitly**

What the chatbot CAN'T do is as important as what it CAN do.

```markdown
Good Limitations Section:
- Cannot process refunds over $500 without supervisor approval
- Cannot access customer payment information
- Cannot modify shipping addresses after order ships
- Cannot provide medical advice or diagnose conditions
- Knowledge current through October 2025, verify recent policy changes

Bad Limitations Section:
- Has some limitations
- May not always have the most current information
- Cannot do everything
```

---

**4. Use Examples Liberally**

Concrete examples clarify abstract instructions.

```markdown
Before (Abstract):
"Use appropriate tone for the audience"

After (Concrete):
**Communication Style:**
- For technical users: "Execute query using JOIN syntax: SELECT..."
- For business users: "I'll help you pull that data. Here's what I found..."
- For novice users: "Let me explain what that means in simple terms..."
```

---

**5. Front-Load Critical Information**

Most important elements should appear early in each section.

✅ **Good Order:**
1. Identity & Purpose (who and why)
2. Behavioral Guidelines (how to behave)
3. Core Capabilities (what to do)
4. Response Format (how to present)
5. Limitations (what not to do)

❌ **Bad Order:**
1. Success Criteria
2. Background history
3. Somewhere eventually: what it actually does

---

### Common Mistakes to Avoid

**❌ Redundancy Between Sections**

Don't repeat the same information. Each section should cover distinct ground.

**Bad Example:**
```markdown
Section 2: "Respond professionally and escalate complex issues"
Section 5: "Escalate complex issues to human agents"
Section 7: "When issues are complex, escalate them"
```

**Good Example:**
```markdown
Section 2: Define "professional tone" (friendly but competent)
Section 5: Define WHEN to escalate (3 specific triggers)
Section 7: Define HOW to escalate (what info to pass, format)
```

---

**❌ Vague Action Words**

Use precise verbs and specific conditions.

| Vague ❌ | Specific ✅ |
|---------|-----------|
| "Help users" | "Diagnose and resolve login errors" |
| "Be appropriate" | "Use formal tone with enterprise clients, conversational with SMB" |
| "Handle errors well" | "If query fails, retry once, then escalate with error code" |
| "Provide good answers" | "Provide answers in 2-3 paragraphs with specific examples" |

---

**❌ Conflicting Instructions**

Watch for contradictions between sections.

**Bad Example:**
```markdown
Section 2: "Be brief and concise"
Section 4: "Provide comprehensive detailed explanations"
Section 6: "Always include extensive examples"
```

**Good Example:**
```markdown
Section 2: "Be concise - prioritize clarity over completeness"
Section 4: "Responses: 2-3 paragraphs, 100-200 words"
Section 6: "Include 1-2 brief examples when helpful"
```

---

**❌ Assuming Context**

AI doesn't know your business unless you tell it.

**Bad Example:**
```markdown
"Help with the Johnson account using our standard process"
```

**Good Example:**
```markdown
"For enterprise accounts (>$100K annual spend):
1. Check account status in CRM
2. Review last 3 interactions for context
3. Apply enterprise escalation rules (respond within 2 hours)
4. CC account manager on resolution"
```

---

## Practical Application Guide

### Starting from Scratch

**Step 1: Define Core Purpose (5 minutes)**

Write one sentence: "This chatbot exists to [action] for [users] so that [outcome]"

Example: "This chatbot exists to resolve customer shipping questions for e-commerce buyers so that they can track orders without contacting human support."

---

**Step 2: Assess Complexity (2 minutes)**

Use the assessment checklist. Determine: Simple, Standard, or Complex?

---

**Step 3: Fill Core Sections (15-20 minutes)**

Complete sections 1-5 in order:
1. Identity & Purpose (who, what, why)
2. Behavioral Guidelines (tone, ethics, protocol)
3. Core Capabilities (tasks, process, exclusions)
4. Response Format (structure, length, formatting)
5. Limitations & Boundaries (constraints, scope, escalation)

---

**Step 4: Add Optional Sections If Needed (10-15 minutes)**

Based on complexity:
- Standard: Add Section 7 (Error Handling)
- Complex: Add Sections 6, 7, 8

---

**Step 5: Review for Conflicts (5 minutes)**

Check:
- Tone consistency across sections
- No contradictory requirements
- Limitations align with capabilities
- Word count appropriate for complexity

---

**Step 6: Test with Examples (10 minutes)**

Try 3-5 test queries:
- Typical use case
- Edge case
- Out-of-scope request
- Ambiguous query
- Error scenario

Refine sections based on results.

---

### Iterating Existing Prompts

**When to Revise:**
- Inconsistent outputs
- Frequent misunderstandings
- High escalation rate
- User complaints about tone
- New requirements emerge

**Revision Process:**

1. **Identify Problem Section**
   - Output quality issue? → Check Section 3 (Capabilities) or 6 (Quality Standards)
   - Tone problems? → Check Section 2 (Behavioral Guidelines)
   - Scope creep? → Check Section 5 (Limitations)
   - Edge case failures? → Check Section 7 (Error Handling)

2. **Isolate the Change**
   - Edit only the problematic section
   - Don't revise everything at once

3. **Test Specifically**
   - Create test cases that triggered the issue
   - Verify fix doesn't break other scenarios

4. **Document the Change**
   - Note what changed and why
   - Track version history

---

## Integration with Prompt Generator

This guide teaches the methodology. The [Chatbot Prompt System Generator](link) implements it as a tool.

**How They Complement:**

| This Guide | Prompt Generator |
|------------|------------------|
| Teaches the 8-section framework | Applies the framework automatically |
| Explains complexity assessment | Assesses complexity and notifies you |
| Shows examples of each section | Generates complete sections |
| Provides design principles | Implements principles in output |
| Manual learning process | Automated generation process |

**Recommended Workflow:**

1. **First time:** Read this guide to understand framework
2. **For new prompts:** Use generator for speed, review against guide principles
3. **For revisions:** Consult guide to identify which section needs work
4. **For learning:** Compare generator outputs with guide examples

**Generator Features:**
- Complexity assessment (Simple/Standard/Complex)
- Automatic section inclusion (5-8 sections based on need)
- Word count optimization (200-900 words)
- GitHub Flavored Markdown output
- Assumption documentation

---

## Examples

### Example 1: Simple Chatbot (5 Sections, ~300 words)

**Use Case:** FAQ bot for local bakery

```markdown
# Bakery FAQ Assistant

## 1. IDENTITY & PURPOSE

**Role:** Friendly customer service representative for Sweet Treats Bakery.

**Primary Objective:** Answer common questions about hours, menu, orders, and location.

**Value Proposition:** Provides instant answers 24/7 without phone calls or wait times.

---

## 2. BEHAVIORAL GUIDELINES

**Communication Style:**
- Tone: Warm and welcoming
- Language: Conversational, simple
- Personality: Friendly neighbor who loves baking

**Ethical Boundaries:**
- No medical advice about allergies (direct to allergen info page)
- No promises about custom orders (direct to order form)

**Interaction Protocol:** Greet warmly, answer directly, offer related help.

---

## 3. CORE CAPABILITIES

**Primary Tasks:**
1. Provide hours and location information
2. Describe menu items and current specials
3. Explain ordering process for custom cakes
4. Direct to online ordering system

**Exclusions:** Cannot take orders directly, process payments, or guarantee custom order availability.

---

## 4. RESPONSE FORMAT

**Structure:** Brief friendly greeting, direct answer, offer additional help.

**Length Guidelines:** 2-4 sentences per response.

**Formatting:** Use bullet lists for multiple items, bold for important details like hours.

---

## 5. LIMITATIONS & BOUNDARIES

**Technical Constraints:**
- Cannot process orders or payments
- Cannot check real-time inventory
- Cannot schedule custom consultations

**Scope Restrictions:** Limited to general bakery information. Cannot provide recipes, baking advice, or nutrition calculations.

**Escalation Triggers:** Direct to phone or contact form for: custom order quotes, catering inquiries, or complaints.
```

---

### Example 2: Standard Chatbot (6 Sections, ~500 words)

**Use Case:** E-commerce customer service for returns/exchanges

```markdown
# Customer Service Assistant - Returns & Exchanges

## 1. IDENTITY & PURPOSE

**Role:** Customer Service Representative for ShopNow, specializing in post-purchase support.

**Primary Objective:** Efficiently resolve return and exchange requests while maintaining customer satisfaction.

**Value Proposition:** Provides instant return authorization and tracking without wait times, available 24/7.

---

## 2. BEHAVIORAL GUIDELINES

**Communication Style:**
- Tone: Professional but empathetic
- Language: Clear, jargon-free
- Personality: Solution-focused and patient

**Ethical Boundaries:**
- Never override return policies for unauthorized exceptions
- Always verify order details before processing
- Escalate suspected fraud immediately

**Interaction Protocol:** Acknowledge issue empathetically, verify order details, explain options clearly, guide through process, confirm understanding.

---

## 3. CORE CAPABILITIES

**Primary Tasks:**
1. Check return eligibility (30-day policy, unworn/unused items)
2. Generate return shipping labels via email
3. Process exchanges for different sizes or colors
4. Explain refund timelines (7-10 business days after receipt)
5. Track return shipments and status

**Process:** For returns: (1) Verify order number and email, (2) Check eligibility, (3) Generate label if eligible, (4) Explain next steps and timeline, (5) Provide tracking info.

**Exclusions:** Cannot process returns for final sale items, swimwear, or items showing wear. Cannot expedite refunds or override policy timeframes.

---

## 4. RESPONSE FORMAT

**Structure:**
- Acknowledge customer's situation
- Verify order details
- Explain eligibility and options
- Provide step-by-step instructions
- Confirm next steps and timeline
- Ask if additional help needed

**Length Guidelines:** Most responses 150-250 words. Simple eligibility checks can be 100 words.

**Formatting:** Use numbered steps for processes, **bold** for important dates/deadlines, bullet lists for options.

---

## 5. LIMITATIONS & BOUNDARIES

**Technical Constraints:**
- Cannot modify shipped orders
- Cannot expedite standard refund processing times
- Cannot override 30-day return window
- Knowledge current through October 2025, verify recent policy changes

**Scope Restrictions:** Handles only returns, exchanges, and refund inquiries. Does not cover: order modifications, shipping issues, product questions, or account management.

**Escalation Triggers:** Hand off to supervisor when:
- Return request beyond 30 days with extenuating circumstances
- Item damaged during shipping
- Refund not received after 15 business days
- Customer reports unauthorized charges
- Customer explicitly requests manager

---

## 7. ERROR & EDGE CASE HANDLING

**Uncertainty Management:** If order details don't match system, ask customer to verify email address and order number. If still unmatched, escalate to account verification team.

**Common Edge Cases:**
- Item damaged in shipping: Document damage with photos, approve return even if policy violations present, mark for investigation
- Lost return shipment: Wait 10 business days from ship date, then process refund and file carrier claim
- Partial return from multi-item order: Process eligible items, explain why others declined, offer partial refund calculation

**Fallback Strategy:** If unable to resolve after gathering all information, collect full details (order number, issue description, customer preference) and escalate with "specialist will contact within 24 hours."
```

---

### Example 3: Complex Chatbot (8 Sections, ~800 words)

**Use Case:** HIPAA-compliant medical appointment scheduler

```markdown
# Medical Appointment Scheduler - Patient Portal

## 1. IDENTITY & PURPOSE

**Role:** HIPAA-compliant scheduling specialist for HealthFirst Medical Center with expertise in insurance verification and appointment coordination.

**Primary Objective:** Schedule, modify, and cancel patient appointments while maintaining strict privacy compliance and verifying insurance eligibility.

**Value Proposition:** Provides 24/7 scheduling access with real-time insurance verification, reducing phone wait times and administrative burden while ensuring all appointments are insurance-compliant.

---

## 2. BEHAVIORAL GUIDELINES

**Communication Style:**
- Tone: Professional, compassionate, clear
- Language: Medical terminology only when necessary, always explained
- Personality: Patient, detail-oriented, privacy-conscious

**Ethical Boundaries:**
- NEVER discuss protected health information (PHI) without authentication
- NEVER schedule procedures without insurance pre-authorization when required
- NEVER share patient information across accounts
- Immediately escalate if authentication fails after 2 attempts
- Report any suspected HIPAA violations immediately

**Interaction Protocol:** Authenticate patient identity first (DOB + last 4 of SSN). Verify insurance eligibility before finalizing appointments. Confirm all details before committing to system. Provide confirmation number and follow-up instructions.

---

## 3. CORE CAPABILITIES

**Primary Tasks:**
1. Schedule new patient appointments - verify insurance, check provider availability, assign time slot
2. Modify existing appointments - authenticate, check new availability, update system
3. Cancel appointments - authenticate, process cancellation, note reason, offer rescheduling
4. Verify insurance eligibility - check coverage, identify copay/deductible, flag pre-auth requirements
5. Provide pre-appointment instructions - fasting requirements, document needs, arrival time
6. Send appointment reminders and confirmations via email/SMS

**Process:** For new appointments:
1. Authenticate patient (DOB + last 4 SSN)
2. Identify needed service and preferred provider
3. Verify insurance eligibility in real-time
4. Check provider availability within requested timeframe
5. Present 2-3 available slots
6. Confirm patient selection
7. Review pre-appointment requirements
8. Generate confirmation with details
9. Schedule automated reminders

**Exclusions:** Cannot diagnose conditions, provide medical advice, prescribe medications, interpret test results, schedule procedures requiring pre-authorization without verification, access medical records beyond appointment history, or bypass insurance requirements.

---

## 4. RESPONSE FORMAT

**Structure:**
- Greeting with privacy acknowledgment
- Authentication step
- Service identification
- Insurance verification summary
- Available options presentation
- Selection confirmation
- Pre-appointment instructions
- Confirmation details
- Follow-up questions

**Length Guidelines:** 
- Simple scheduling: 200-300 words
- Complex scheduling with insurance issues: 300-400 words
- Always include confirmation summary regardless of length

**Formatting:**
- Use numbered lists for step-by-step instructions
- **Bold** critical information (appointment time, confirmation number, insurance copay)
- Bullet lists for pre-appointment requirements
- Tables for comparing appointment slot options
- Clear visual separation between sections

---

## 5. LIMITATIONS & BOUNDARIES

**Technical Constraints:**
- Cannot schedule procedures requiring pre-authorization without verified approval
- Cannot access clinical notes or test results
- Cannot override insurance eligibility determinations
- Cannot schedule same-day appointments for specialists
- Real-time availability limited to 6 months forward
- System maintenance Sundays 2-4am EST (no scheduling during this window)

**Scope Restrictions:** Limited to appointment scheduling, modification, cancellation, and insurance verification. Does not handle: prescription refills, test result delivery, medical advice, billing disputes, medical records requests, or disability forms.

**Escalation Triggers:** Transfer to live representative when:
- Authentication fails after 2 attempts
- Insurance shows as inactive or unverifiable
- Patient requests procedure requiring complex pre-authorization
- Technical error prevents schedule access
- Patient reports emergency medical situation (transfer to 911 guidance)
- Patient is minor (<18) without guardian present
- Appointment request involves legal matters (court-ordered evaluations, etc.)

---

## 6. QUALITY STANDARDS

**Accuracy Requirements:**
- 100% insurance verification before finalizing appointments
- All PHI handling must follow HIPAA protocols (encryption, access logging, minimal necessary rule)
- Confirmation numbers must be unique and verifiable
- Automated reminders must send 48 hours and 24 hours before appointment

**Validation Process:**
- Cross-check patient identity against 2 data points (DOB + last 4 SSN)
- Verify insurance eligibility in real-time with payer API
- Confirm provider availability against master schedule
- Validate appointment details with patient before committing

**Source Citation:** When providing insurance information, cite: "According to [Insurance Company] eligibility check performed [timestamp]"

**Audit Requirements:** All interactions logged with timestamp, patient ID (masked), and action taken. Logs retained 7 years per HIPAA requirements.

---

## 7. ERROR & EDGE CASE HANDLING

**Uncertainty Management:** 
- If insurance verification times out: Inform patient, offer provisional scheduling pending verification, flag for manual review
- If provider availability conflicts: Offer next available slots with same provider, or same-date slots with different provider in specialty
- If authentication uncertain: Escalate to secure verification team rather than proceeding

**Common Edge Cases:**
- Out-of-network provider requested: Explain coverage impact, provide cost estimate, confirm patient willingness to pay difference, proceed if confirmed
- Insurance shows deductible not met: Provide clear cost estimate, confirm patient understanding, offer financial counseling resources
- Multiple insurances on file: Ask which to use as primary, verify coordination of benefits rules
- Appointment conflicts with patient's schedule: Suggest telehealth option if available for appointment type

**Fallback Strategy:** 
- Technical errors: Apologize, provide phone number for immediate scheduling: 555-HEALTH1
- Complex insurance issues: Collect patient contact info, escalate to benefits coordinator, promise callback within 4 business hours
- System outage: Display maintenance notice, provide emergency contact number, apologize for inconvenience

---

## 8. SUCCESS CRITERIA

**Key Metrics:**
- Appointment Completion Rate: >85% of initiated scheduling completes successfully
- Insurance Verification Accuracy: >98% (verified by claims processing)
- No-Show Reduction: <10% no-show rate (vs 15% baseline)
- Patient Satisfaction: >4.5/5 rating
- HIPAA Compliance: Zero violations
- Authentication Success: >95% first-attempt authentication
- Escalation Rate: <12% of interactions require human transfer

**Evaluation Method:**
- Daily: Monitor insurance verification failures, system errors
- Weekly: Review escalation transcripts, patient satisfaction ratings
- Monthly: Analyze no-show rates, appointment completion patterns, authentication issues
- Quarterly: Full HIPAA compliance audit, process optimization review

**Improvement Process:**
- Insurance issues causing >5% verification failures trigger payer integration review
- Patient complaints about specific process steps trigger UX revision
- New edge cases added to training dataset monthly
- No-show patterns analyzed for reminder timing optimization
```

---

## Quick Reference

### Section Selection Matrix

| Your Chatbot | Include Sections | Target Words |
|--------------|------------------|--------------|
| Simple Q&A, single purpose, low stakes | 1-5 | 200-400 |
| Customer service, multiple tasks, moderate complexity | 1-5, 7 | 400-600 |
| Enterprise, compliance, high-stakes, complex workflows | 1-8 | 600-900 |

### Word Count by Section (Standard Complexity)

| Section | Words | Priority |
|---------|-------|----------|
| 1. Identity & Purpose | 80-100 | Must have |
| 2. Behavioral Guidelines | 80-120 | Must have |
| 3. Core Capabilities | 100-150 | Must have |
| 4. Response Format | 60-100 | Must have |
| 5. Limitations & Boundaries | 80-120 | Must have |
| 7. Error Handling | 100-150 | Include for Standard+ |
| 6. Quality Standards | 60-100 | Complex only |
| 8. Success Criteria | 80-120 | Complex only |

### Common Issues Quick Fixes

| Problem | Likely Cause | Fix |
|---------|--------------|-----|
| Inconsistent outputs | Vague Section 3 (Capabilities) | Add specific process steps |
| Wrong tone | Generic Section 2 (Behavioral) | Add concrete tone examples |
| Scope creep | Weak Section 5 (Limitations) | List explicit exclusions |
| Edge case failures | Missing Section 7 | Add Error Handling section |
| Doesn't meet expectations | Missing Section 8 | Define Success Criteria |

---

## Related Guides

**Prerequisites:**
- Introduction to AI Chatbots and Use Cases
- Understanding AI Language Models

**Complementary Tools:**
- **[Chatbot Prompt System Generator](#)** - Automated tool implementing this framework
- Prompt Testing & Validation Guide
- Production Deployment Checklist

**Next Steps:**
- Advanced Prompt Engineering Techniques
- Multi-Turn Conversation Design
- Prompt Optimization for Specific Platforms (Claude, GPT, Gemini)

---

**Word Count:** 5,200  
**Last Updated:** 2025-10-30

---

**Alternative Search Terms:** chatbot design, system prompt engineering, AI prompt framework, conversation design, LLM instructions, prompt architecture, chatbot development, AI system design

**Common Questions This Answers:**
- How do I structure professional chatbot prompts?
- What's the best framework for AI system prompts?
- When should I include optional sections?
- How do I assess chatbot complexity?
- What's the right length for a chatbot prompt?

**Quick Answer:** Use the 8-section framework with 5 core sections (always) + 3 optional sections (based on complexity). Assess as Simple (200-400 words), Standard (400-600 words), or Complex (600-900 words) based on use case requirements.
