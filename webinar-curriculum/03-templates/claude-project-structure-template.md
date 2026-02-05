# Claude Project Structure Template
## Building Your Operations Brain

---

## Overview

A Claude Project is your Tier 2/3 operating system. It holds your firm's operational logic, processes, and decision frameworks in one place, delivering consistent guidance to your entire team.

**Purpose:** Systematize institutional knowledge for team execution
**Platform:** Claude Projects (claude.ai)
**Tier:** 2-3 (Workflow/System Layer)

---

## Project Architecture

### Recommended Structure

```
Operations Brain Project
│
├── Project Instructions (System Prompt)
│   └── How Claude should behave and respond
│
├── Knowledge Base (Uploaded Documents)
│   ├── Core Operations
│   │   ├── Month-end close checklist
│   │   ├── Client onboarding process
│   │   └── Quality review standards
│   │
│   ├── Client Service
│   │   ├── Communication standards
│   │   ├── Escalation decision tree
│   │   └── Common scenarios & responses
│   │
│   ├── HR & Team
│   │   ├── Team policies
│   │   ├── Training guidelines
│   │   └── Performance standards
│   │
│   └── Brand & Voice
│       ├── Communication tone guide
│       ├── Email templates
│       └── Client-facing standards
│
└── Verification Framework
    └── Quality control checklist
```

---

## Project Instructions Template

Copy and customize this system prompt for your Claude Project:

```
You are the Operations Brain for [FIRM NAME], an accounting firm. Your role is to provide consistent operational guidance to our team based on our documented processes, policies, and standards.

## Your Purpose

Help team members execute their work according to our firm's established procedures. When someone asks how to handle a situation, you reference our documented processes and provide guidance that reflects how WE do things—not generic advice.

## How to Respond

1. **Reference Our Documentation**: Always ground your answers in the uploaded documents. If our process addresses the question, cite it specifically.

2. **Maintain Our Standards**: Your guidance should reflect our quality standards, communication style, and operational approach.

3. **Acknowledge Gaps**: If a question isn't covered by our documentation, say so clearly. Don't make up policies we don't have.

4. **Include Verification Steps**: For any guidance that affects clients or deliverables, remind the team member to run through the verification checklist.

5. **Flag Escalations**: When something requires manager/partner review per our escalation policy, note that clearly.

## Our Firm Context

[CUSTOMIZE THIS SECTION]
- We serve [type of clients]
- Our focus areas are [services]
- Our team structure is [describe]
- Our typical month-end timeline is [describe]

## Escalation Triggers

Always note when escalation is needed:
- Decisions over $[X] impact
- Changes to client engagement terms
- Policy exceptions
- Situations not covered by documentation
- Anything involving [specific areas]

## Verification Reminder

For guidance involving client deliverables or significant decisions, always end with:

"Before proceeding, run through the verification checklist:
1. Contract alignment?
2. Timeline impact?
3. Approval required?
4. Client communication needed?
5. Documentation location?"

## Tone

- Professional and clear
- Helpful but not chatty
- Confident when referencing our processes
- Humble when information is incomplete
```

---

## Documents to Upload

### Priority 1: Core Operations (Start Here)

| Document | Purpose | Format Tips |
|----------|---------|-------------|
| **Month-End Close Checklist** | Guide team through close process | Numbered steps, due dates, owners |
| **Client Onboarding Process** | Standardize new client setup | Step-by-step with decision points |
| **Quality Review Standards** | Define what "good" looks like | Checklist format works well |
| **Escalation Decision Tree** | When to escalate, to whom | Clear if/then structure |

### Priority 2: Client Service

| Document | Purpose | Format Tips |
|----------|---------|-------------|
| **Communication Standards** | How we communicate with clients | Examples of good/bad |
| **Common Scenarios** | How to handle frequent situations | Scenario + response pairs |
| **Response Time Expectations** | When clients should hear back | Specific timeframes |

### Priority 3: Team Operations

| Document | Purpose | Format Tips |
|----------|---------|-------------|
| **Team Policies** | Leave, hours, expectations | Clear policies |
| **Training Path** | How new hires learn | Stages and milestones |
| **Tool Usage Guides** | How we use our software | Step-by-step |

---

## Document Formatting Best Practices

### DO:

**Use Clear Headers**
```
# MONTH-END CLOSE PROCESS

## Overview
[Brief description]

## Timeline
- Day 1-3: [Tasks]
- Day 4-6: [Tasks]
- Day 7: [Tasks]

## Step-by-Step Process

### Step 1: Bank Reconciliation
- Pull bank statements from [location]
- Compare to GL balance
- Research any variances over $[X]
- Document reconciling items

### Step 2: [Next Step]
...
```

**Use Decision Trees for Judgment Calls**
```
## Handling Client Change Requests

IF request involves scope change:
  → Route to manager for review
  → May require engagement letter amendment

IF request is within current scope:
  → Check timeline impact
  → Confirm capacity
  → Proceed with standard process

IF urgent/emergency:
  → Notify manager immediately
  → Document the situation
  → Follow emergency protocol
```

### DON'T:

- Don't upload raw, unformatted text dumps
- Don't include outdated policies
- Don't upload conflicting versions
- Don't bury key information in long paragraphs

---

## Testing Your Operations Brain

Before rolling out to the team, test with these scenarios:

### Test Questions (Customize for Your Firm)

1. **Process Question:**
   "A client just sent their January bank statements late. We're now on Day 5 of close. How should we handle this?"

2. **Escalation Question:**
   "A client wants to change from quarterly to monthly reporting starting next month. Can I approve this?"

3. **Gap Question:**
   "A client asked if we can help with their personal taxes. What should I tell them?"
   (Tests whether it acknowledges what's NOT in your docs)

4. **Verification Question:**
   "Client approved a scope change verbally over the phone. Can I proceed?"
   (Should trigger verification checklist)

5. **Judgment Question:**
   "The client's month-end is showing a $500 variance I can't explain. Should I just adjust it?"
   (Tests escalation awareness)

### Evaluation Criteria

For each test:
- [ ] Did it reference your actual documentation?
- [ ] Was the guidance accurate to your process?
- [ ] Did it include appropriate escalation notes?
- [ ] Did it remind about verification when needed?
- [ ] Did it acknowledge gaps honestly?

---

## Rollout Plan

### Week 1: Build & Test

**Day 1-2:**
- Create Claude Project
- Upload Priority 1 documents
- Add system prompt

**Day 3-4:**
- Run all 5 test questions
- Refine documents based on gaps
- Adjust system prompt if needed

**Day 5:**
- Add Priority 2 documents
- Retest with 3 new scenarios

### Week 2: Pilot

**Day 1-3:**
- Share with 1-2 trusted team members
- Gather real-world questions
- Note where guidance is unclear

**Day 4-5:**
- Refine based on feedback
- Add clarifying documentation
- Update system prompt

### Week 3: Team Rollout

**Day 1:**
- Team training (15-30 minutes)
- Demonstrate how to use
- Explain verification process

**Day 2-5:**
- Open to full team
- Collect questions/feedback
- Iterate continuously

---

## Maintenance

### Weekly
- Review questions the team asked
- Note any gaps or confusion
- Quick documentation updates

### Monthly
- Comprehensive review of guidance quality
- Update processes that have changed
- Add new scenarios from real situations

### Quarterly
- Full documentation audit
- Team feedback session
- Major updates if needed

---

## Common Questions

**Q: How much documentation is enough?**
A: Start with 3-5 core documents that cover 80% of daily questions. Add more as gaps emerge.

**Q: What if our processes aren't documented?**
A: This is actually an opportunity. Use the project-building process to document what's in your head. Start with how YOU answer common questions.

**Q: Can the team add to the knowledge base?**
A: Yes, but have a review process. New documents should be reviewed before upload to ensure accuracy and consistency.

**Q: What about confidential information?**
A: Claude Projects don't train on your data, but follow your firm's security policies. Don't upload client-specific data—keep it to processes and frameworks.

**Q: How do I handle conflicting guidance?**
A: If Claude gives guidance that conflicts with what you'd say, update the documentation. The goal is for the Operations Brain to reflect your judgment, not replace it.

---

## Quick Start Checklist

- [ ] Create new Claude Project
- [ ] Name it "[Firm Name] Operations Brain"
- [ ] Copy system prompt template and customize
- [ ] Upload month-end close checklist
- [ ] Upload escalation decision tree
- [ ] Upload 1-2 other core documents
- [ ] Run 5 test questions
- [ ] Refine based on test results
- [ ] Pilot with 1-2 team members
- [ ] Roll out to team with training

---

*Template from: The Accountant's AI Operating System Webinar*
*Presented by Callan for Insightful Accountant*
