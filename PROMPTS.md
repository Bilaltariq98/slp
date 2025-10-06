# Claude Prompt Library

> **Purpose:** Ready-to-use prompts for enhancing notes, generating question logs, and maintaining consistent learning documentation.

---

## 📚 Table of Contents

1. [Note Enhancement](#note-enhancement)
2. [Question Log Generation](#question-log-generation)
3. [Diagram Generation](#diagram-generation)
4. [Knowledge Verification](#knowledge-verification)

---

## 📝 Note Enhancement

### Basic Note Enhancement

**When to use:** You have raw/WIP notes that need structure and Obsidian features

**Prompt:**
```
I have WIP notes at [path/to/note]. Can you:

1. Enrich with appropriate Obsidian features (callouts, tables, links)
2. Structure for better retention and learning
3. Add mental models and analogies where helpful
4. Only enhance up to where I've written (don't add new content)
5. Preserve my questions and observations
6. Add visual hierarchy with emojis and formatting

Keep my voice and learning style, just make it more structured.

Use the guidelines from CLAUDE.md
```

**Example:**
```
I have WIP notes at Network Fundamentals/2. OSI Model.md. Can you:

1. Enrich with appropriate Obsidian features (callouts, tables, links)
2. Structure for better retention and learning
3. Add mental models and analogies where helpful
4. Only enhance up to where I've written (don't add new content)
5. Preserve my questions and observations
6. Add visual hierarchy with emojis and formatting

Keep my voice and learning style, just make it more structured.

Use the guidelines from CLAUDE.md
```

---

### Dense Technical Content Enhancement

**When to use:** Complex technical material that needs breaking down

**Prompt:**
```
I have dense technical notes on [topic] at [path]. Break this into chunks with:

1. Quick reference table at top
2. Mental models for complex concepts
3. Progressive disclosure (simple → detailed)
4. Mermaid diagrams where helpful
5. Collapsible callouts for advanced details

Follow CLAUDE.md enhancement patterns.
```

---

### Conceptual Topic Enhancement

**When to use:** Theory-heavy or conceptual material

**Prompt:**
```
Enhance my conceptual notes on [topic] at [path] by adding:

1. Analogies to real-world scenarios
2. Visual comparisons (tables/diagrams)
3. Questions for self-testing
4. Mental models for retention
5. Progressive difficulty levels

Use CLAUDE.md guidelines for structure.
```

---

### Procedural Content Enhancement

**When to use:** Step-by-step processes or how-to guides

**Prompt:**
```
Structure my procedural notes on [topic] at [path] as:

1. Numbered steps with clear outcomes
2. Expected results at each stage
3. Common pitfalls callout
4. Practice exercises checklist
5. Troubleshooting section

Follow CLAUDE.md patterns.
```

---

## 📋 Question Log Generation

### Comprehensive Question Log

**When to use:** After completing a major topic/module

**Prompt:**
```
I've completed my notes on [Topic Name]. Generate a comprehensive
Question Log using the pattern from CLAUDE.md.

Requirements:
1. Extract key concepts from the notes
2. Create questions at multiple difficulty levels
3. Include scenario-based and practical questions
4. Add security-focused questions where relevant
5. Use collapsible accordions for complex questions with answers
6. Organize by subtopic and difficulty
7. Include completion tracking section

Source notes: [[Link to completed notes]]

Format: Follow the Question Log pattern in CLAUDE.md
```

**Example:**
```
I've completed my notes on OSI Model (2. OSI Model.md).
Generate a comprehensive Question Log using the pattern from CLAUDE.md.

Requirements:
1. Extract key concepts from the notes
2. Create questions at multiple difficulty levels
3. Include scenario-based and practical questions
4. Add security-focused questions where relevant
5. Use collapsible accordions for complex questions with answers
6. Organize by layer and difficulty
7. Include completion tracking section

Source notes: [[2. OSI Model]]

Format: Follow the Question Log pattern in CLAUDE.md
```

---

### Security-Focused Question Log

**When to use:** Topics with significant security implications

**Prompt:**
```
Generate a security-focused Question Log for [topic] from [[notes]].

Emphasis on:
1. Attack vectors and vulnerabilities
2. Mitigation strategies
3. Real-world exploit scenarios
4. Detection and response
5. Security misconfigurations

Include:
- Threat modeling questions
- Defense-in-depth concepts
- Common CVEs/attacks related to topic
- Hands-on lab scenarios

Follow CLAUDE.md Question Log pattern.
```

---

### Quick Quiz Generation

**When to use:** Need quick review questions for a specific concept

**Prompt:**
```
Create a quick quiz (10-15 questions) on [specific concept] from my notes at [path].

Include:
- 5 recall questions
- 3 scenario questions
- 2 comparison questions
- Use checkboxes for self-testing
- No answers (for active recall practice)

Keep it concise for rapid review.
```

---

## 🎨 Diagram Generation

### Network Path Visualization

**When to use:** Need to visualize packet/data flow through network

**Prompt:**
```
Create a Mermaid diagram showing [network scenario].

Include:
1. All hops in the path
2. Layer information (L2/L3)
3. What addresses change at each hop
4. Color coding for device types
5. Labels for MAC/IP addresses

Add a supporting table showing what changes vs what stays constant.
```

**Example:**
```
Create a Mermaid diagram showing a packet traveling from PC A (192.168.1.10)
to PC B (10.0.0.50) through switches, routers, and the internet.

Include:
1. All hops in the path (6 total)
2. Layer information (L2/L3)
3. What addresses change at each hop
4. Color coding for device types
5. Labels for MAC/IP addresses

Add a supporting table showing what changes vs what stays constant.
```

---

### Process Flow Diagram

**When to use:** Explaining multi-step processes

**Prompt:**
```
Create a Mermaid flowchart showing [process/protocol].

Requirements:
1. Step-by-step flow from start to finish
2. Decision points (if applicable)
3. Color coding by layer/stage
4. Clear labels on each step
5. Show what data is added/modified at each stage

Include brief text explanation of key transition points.
```

---

### Comparison Diagram

**When to use:** Comparing different technologies/approaches

**Prompt:**
```
Create a visual comparison of [Technology A] vs [Technology B] using:

1. Side-by-side Mermaid diagrams
2. Comparison table with key differences
3. Use cases for each
4. Pros/cons in callouts

Highlight security implications of each approach.
```

---

### Layer Model Visualization

**When to use:** Understanding protocol stacks or layered architectures

**Prompt:**
```
Create a Mermaid diagram showing [layer model/stack].

Show:
1. Each layer with clear labels
2. Data flow direction (top→bottom for sending, bottom→top for receiving)
3. What each layer adds/removes
4. Color gradient by layer
5. Real-world example of data transformation

Add mnemonic or memory aid if applicable.
```

---

## ✅ Knowledge Verification

### Concept Checker

**When to use:** Verify your understanding of a completed topic

**Prompt:**
```
I've completed studying [topic]. Quiz me on the key concepts to verify my understanding.

1. Ask me 5 progressively difficult questions
2. Wait for my answer to each before giving the next
3. Provide gentle corrections if I'm wrong
4. Point to specific sections in my notes if I need review
5. Summarize what I understand well vs what needs work

My notes: [[link to notes]]
```

---

### Gap Analyzer

**When to use:** Identify what you're missing in your knowledge

**Prompt:**
```
Review my notes on [topic] at [path] and identify:

1. Concepts that are incomplete or unclear
2. Important subtopics not covered
3. Security aspects that need more depth
4. Practical applications missing
5. Common misconceptions I should address

Suggest specific additions or clarifications needed.
```

---

### Real-World Application

**When to use:** Connect theoretical knowledge to practice

**Prompt:**
```
Based on my notes on [topic], create 3-5 real-world scenarios where this knowledge applies.

For each scenario:
1. Describe the situation
2. Ask what I would do
3. What concepts from my notes are relevant
4. Common mistakes to avoid
5. Security implications

Format as problem-based learning exercises.
```

---

## 🔄 Maintenance & Updates

### Note Review & Update

**When to use:** Periodic review of older notes

**Prompt:**
```
Review my notes on [topic] from [date] and:

1. Update any outdated information
2. Add new callout patterns from CLAUDE.md
3. Enhance with any missing Obsidian features
4. Add cross-links to newer related notes
5. Update completion status and next steps

Preserve all original content, only enhance structure.
```

---

### Consolidate Multiple Notes

**When to use:** Multiple related notes need merging

**Prompt:**
```
I have several notes on [topic] that should be consolidated:

Notes:
- [[Note 1]]
- [[Note 2]]
- [[Note 3]]

Create a unified note that:
1. Removes redundancy
2. Maintains all unique information
3. Organizes by logical flow
4. Uses progressive disclosure for complexity
5. Adds comparison sections where topics overlap

Follow CLAUDE.md structure guidelines.
```

---

## 🎯 Security-Specific Prompts

### Threat Modeling Exercise

**When to use:** Analyzing security of a system/protocol

**Prompt:**
```
Based on my notes on [technology/protocol], create a threat model:

1. Identify attack surface
2. List potential threat actors
3. Enumerate attack vectors (organized by OSI layer if applicable)
4. Mitigation strategies for each threat
5. Detection mechanisms
6. Real-world examples of exploits

Use STRIDE or other threat modeling framework.
Format with collapsible callouts for each threat.
```

---

### CVE Deep Dive

**When to use:** Understanding a specific vulnerability

**Prompt:**
```
Explain [CVE-XXXX-XXXXX] in the context of my [topic] notes:

1. What vulnerability exists
2. Why it exists (root cause)
3. How it's exploited (attack chain)
4. What concepts from my notes relate to this
5. Mitigation and patches
6. Detection strategies
7. Lessons learned for secure development

Add to my notes as a real-world example.
```

---

### Attack Chain Diagram

**When to use:** Understanding multi-stage attacks

**Prompt:**
```
Create a Mermaid diagram showing the attack chain for [attack type]:

1. Initial access
2. Each stage of the attack
3. What layer/protocol is targeted at each stage
4. Detection opportunities (in different color)
5. Mitigation points

Add accompanying text explaining:
- Prerequisites for the attack
- Indicators of compromise (IOCs)
- Defense-in-depth strategies
```

---

## 🚀 Quick Reference

### Common Combinations

**Complete Topic Workflow:**
```
1. Enhance raw notes: [Use Basic Note Enhancement prompt]
2. Generate question log: [Use Comprehensive Question Log prompt]
3. Create diagrams: [Use relevant diagram prompt]
4. Verify understanding: [Use Concept Checker prompt]
```

**Security Topic Workflow:**
```
1. Enhance with security focus: [Use Conceptual Topic Enhancement]
2. Add threat model: [Use Threat Modeling Exercise prompt]
3. Generate security questions: [Use Security-Focused Question Log]
4. Real-world CVEs: [Use CVE Deep Dive prompt]
```

---

## 💡 Tips for Using These Prompts

### Customization
- Replace `[placeholders]` with your specific topic/path
- Adjust requirements list based on your needs
- Combine prompts for complex tasks

### Best Practices
1. **Be Specific:** Include file paths and exact topic names
2. **Set Boundaries:** Specify "don't add content beyond what I've written"
3. **Reference CLAUDE.md:** Ensures consistent formatting
4. **Iterate:** Start with basic prompt, then refine based on output

### When to Use Which Prompt
- **Raw notes** → Note Enhancement prompts
- **Completed notes** → Question Log prompts
- **Complex flows** → Diagram prompts
- **Self-assessment** → Knowledge Verification prompts
- **Security topics** → Security-Specific prompts

---

## 📝 Prompt Template Builder

### Create Your Own Prompt

```
I need help with [task] for my notes on [topic].

Context:
- Current state: [describe current notes]
- Goal: [what you want to achieve]
- Constraints: [any limitations or preferences]

Requirements:
1. [Requirement 1]
2. [Requirement 2]
3. [Requirement 3]

Format: Follow [specific pattern] from CLAUDE.md

Source: [[link to relevant notes]]
```

---

## 🔗 Related Documents

- [[CLAUDE.md]] - Full enhancement guidelines and patterns
- [[README]] - Learning roadmap overview
- [[NOTES]] - Personal action items and links

---

_Last updated: 2025-10-06_
_Add new prompts as you discover useful patterns_
