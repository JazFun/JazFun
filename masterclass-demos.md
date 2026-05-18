# SmartAccountant.ai Masterclass
## Demo Scripts
### 4 Live Demos Ready to Run

---

# DEMO 1: TRANSACTION REVIEW WORKFLOW
**Duration:** 8 minutes
**Tool:** ChatGPT, Claude, or Copilot

---

## Setup Before Masterclass

### Sample Data to Prepare:
Create a CSV file with ~50 transactions. Use realistic but messy bank feed data:

```csv
Date,Description,Amount
2026-04-03,PURCHASE AUTHORIZED ON 04/02 CARD 4829 AMAZON MKTPLACE PMTS,-89.47
2026-04-03,ACH DEPOSIT STRIPE TRANSFER,2847.50
2026-04-05,SQ *COFFEE HOUSE,-12.85
2026-04-05,CHECKCARD 0405 OFFICE DEPOT #1247,-234.67
2026-04-07,ZELLE PAYMENT FROM JOHNSON LLC,1500.00
2026-04-08,PURCHASE AUTHORIZED VZWRLSS*APOCC VISN,-156.89
2026-04-08,ACH DEBIT GUSTO PAYROLL,-4521.33
2026-04-10,CHECKCARD 0410 COSTCO WHSE #1089,-567.23
2026-04-10,SQ *THE UPS STORE,-23.45
2026-04-12,PURCHASE AUTHORIZED GOOGLE *GSUITE,-14.40
2026-04-12,TRANSFER FROM SAVINGS,5000.00
2026-04-15,PURCHASE AUTHORIZED CANVA* 03847291,-12.99
2026-04-15,ACH DEPOSIT DIRECT DEP JONES CONSULTING,3200.00
2026-04-17,CHECKCARD 0417 STAPLES #0892,-89.99
2026-04-17,SQ *CHIPOTLE 1892,-34.56
2026-04-19,PURCHASE AUTHORIZED DROPBOX*YKVN782,-11.99
2026-04-19,WIRE TRANSFER INCOMING PACIFIC RIM IMPORTS,15780.00
2026-04-22,CHECKCARD 0422 LOWES #2847,-892.45
2026-04-22,ACH DEBIT QUICKBOOKS PAYROLL,-6234.11
2026-04-24,SQ *UBER TRIP,-45.67
2026-04-24,PURCHASE AUTHORIZED ZOOM.US,-15.99
2026-04-26,ACH DEPOSIT INVOICE 2847 - SMITH CO,4500.00
2026-04-28,CHECKCARD 0428 BEST BUY #1092,-1247.89
2026-04-28,PURCHASE AUTHORIZED ADOBE *CREATIVE CLD,-54.99
2026-04-29,ATM WITHDRAWAL,-500.00
2026-04-30,SQ *DOORDASH,-67.89
2026-04-30,PURCHASE AUTHORIZED LINKEDIN PREMIUM,-59.99
2026-04-30,BANK SERVICE CHARGE,-25.00
```

### Chart of Accounts to Use:
```
Revenue:
- 4000 Service Revenue
- 4100 Product Sales
- 4200 Other Income

Expenses:
- 5000 Cost of Goods Sold
- 6000 Payroll & Benefits
- 6100 Rent & Utilities
- 6200 Office Supplies
- 6300 Software & Subscriptions
- 6400 Marketing & Advertising
- 6500 Travel & Transportation
- 6600 Meals & Entertainment
- 6700 Professional Services
- 6800 Equipment & Hardware
- 6900 Shipping & Postage
- 7000 Bank Fees & Charges
- 7100 Miscellaneous Expense
```

---

## Live Demo Script

### [00:00] Set the Scene

**SAY:**
"Alright, let me share my screen. I've got a bank feed export here—52 transactions from April. Most of these descriptions are terrible. You know the kind.

This would normally take me 30 to 45 minutes to go through. Let's see what happens with AI."

### [00:30] Open AI Tool

**DO:**
- Open ChatGPT/Claude in a new tab (already logged in)
- Make sure the window is clean—no previous conversations visible

**SAY:**
"I'm using ChatGPT Plus here, but this works the same in Claude or Copilot. Any of the main AI assistants."

### [01:00] Paste the Prompt

**DO:**
- Paste the following prompt:

```
You are a senior bookkeeper reviewing transactions for a small marketing agency.

Here is their chart of accounts:

Revenue:
- 4000 Service Revenue
- 4100 Product Sales
- 4200 Other Income

Expenses:
- 5000 Cost of Goods Sold
- 6000 Payroll & Benefits
- 6100 Rent & Utilities
- 6200 Office Supplies
- 6300 Software & Subscriptions
- 6400 Marketing & Advertising
- 6500 Travel & Transportation
- 6600 Meals & Entertainment
- 6700 Professional Services
- 6800 Equipment & Hardware
- 6900 Shipping & Postage
- 7000 Bank Fees & Charges
- 7100 Miscellaneous Expense

Review the following transactions and:
1. Suggest a category (account number and name) for each transaction
2. Flag any transactions that seem unusual or need human review (mark with ⚠️)
3. Write a brief memo for any transaction over $1,000

Here are the transactions:

[PASTE CSV DATA]
```

**SAY:**
"I'm going to paste my prompt. Notice I'm telling it WHO it is—a senior bookkeeper. I'm giving it the chart of accounts. And I'm giving it specific instructions: categorize, flag anomalies, write memos for big ones."

### [02:00] Show the CSV

**DO:**
- Paste the CSV data after the prompt
- Press Enter

**SAY:**
"Now I paste the transactions. 52 of them. Hit enter and let's watch."

### [02:30] Wait for Response

**DO:**
- Let the AI generate the response (typically 20-30 seconds)
- Don't talk too much—let them see it happening

**SAY:**
"It's thinking through each transaction. Watch how it's categorizing them."

### [03:00] Review the Results

**DO:**
- Scroll through the results slowly
- Point out specific categorizations

**SAY:**
"Okay, look at this.

Amazon Marketplace—it categorized as Office Supplies. Makes sense for a marketing agency, probably buying supplies.

Stripe deposits—correctly identified as Service Revenue.

Look at this one—Costco for $567. It flagged it with a warning because it wasn't sure if it was supplies or resale inventory. That's exactly the kind of judgment call I need to make.

And here—the $15,780 wire transfer. It wrote a memo: 'Large incoming wire from Pacific Rim Imports - verify if this is client payment or other income. Unusual vendor name for marketing agency.' That's good. That should be reviewed."

### [05:00] Point Out the Wins

**DO:**
- Scroll to show the full list
- Highlight a few more examples

**SAY:**
"Look at the software subscriptions. Google Workspace, Canva, Dropbox, Zoom, Adobe, LinkedIn—all correctly put in Software & Subscriptions.

Gusto and QuickBooks payroll—correctly in Payroll & Benefits.

The restaurant and food charges—Meals & Entertainment.

Now, did it get everything perfect? Let me check..."

### [06:00] Show the Imperfections

**DO:**
- Find 1-2 things to adjust

**SAY:**
"Here—the Uber trip. It put it in Travel & Transportation, which is fine, but for this client, we might put that in Meals & Entertainment if it was a client dinner trip. So I'd adjust that.

And this Best Buy purchase for $1,247—it's in Equipment & Hardware, but I know this client bought monitor stands. I might recategorize to Office Supplies.

So two adjustments out of 52 transactions. That's a 96% accuracy rate."

### [07:00] The Reveal

**SAY:**
"So what just happened?

I had 52 transactions that would have taken me 30-45 minutes.

AI categorized all of them in about 30 seconds.

It flagged 4 that needed my attention.

It wrote memos for the large transactions.

I spent 3 minutes reviewing and made 2 adjustments.

That's 45 minutes down to 5 minutes. That's the workflow."

### [07:45] Transition

**SAY:**
"Now imagine doing this for every client, every month. That's not a time hack. That's a different way of working.

Let's move to demo two."

---

# DEMO 2: VARIANCE ANALYSIS WORKFLOW
**Duration:** 8 minutes
**Tool:** ChatGPT, Claude, or Copilot

---

## Setup Before Masterclass

### Sample Data to Prepare:
Create two P&L summaries (January vs February) with some clear variances:

**March P&L:**
```
Revenue
  Service Revenue: $45,200
  Product Sales: $12,800
  Total Revenue: $58,000

Expenses
  Payroll & Benefits: $22,000
  Rent & Utilities: $3,500
  Software & Subscriptions: $890
  Marketing & Advertising: $2,400
  Travel & Transportation: $1,200
  Meals & Entertainment: $650
  Professional Services: $1,500
  Office Supplies: $420
  Total Expenses: $32,560

Net Income: $25,440
```

**April P&L:**
```
Revenue
  Service Revenue: $38,500
  Product Sales: $8,200
  Total Revenue: $46,700

Expenses
  Payroll & Benefits: $22,000
  Rent & Utilities: $3,500
  Software & Subscriptions: $2,340
  Marketing & Advertising: $8,900
  Travel & Transportation: $3,450
  Meals & Entertainment: $1,890
  Professional Services: $1,500
  Office Supplies: $780
  Total Expenses: $44,360

Net Income: $2,340
```

---

## Live Demo Script

### [00:00] Set the Scene

**SAY:**
"Demo two: Variance Analysis.

Here's the scenario. I've got a client meeting in two hours. I'm looking at their P&L and something's wrong. Revenue dropped, expenses went up, net income fell off a cliff.

I need to walk into that meeting knowing what happened. Let's see how fast AI can get me there."

### [00:30] Show the Data

**DO:**
- Display both P&Ls side by side (or describe them)

**SAY:**
"March: $58,000 revenue, $25,000 net income.
April: $46,700 revenue, $2,300 net income.

Net income dropped 91%. The client is going to ask me why. Let's find out."

### [01:00] Paste the Prompt

**DO:**
- Open new chat in AI tool
- Paste the following prompt:

```
You are a senior accountant preparing for a client meeting. Analyze the following two months of P&L data and help me understand what happened.

MARCH P&L:
Revenue
  Service Revenue: $45,200
  Product Sales: $12,800
  Total Revenue: $58,000

Expenses
  Payroll & Benefits: $22,000
  Rent & Utilities: $3,500
  Software & Subscriptions: $890
  Marketing & Advertising: $2,400
  Travel & Transportation: $1,200
  Meals & Entertainment: $650
  Professional Services: $1,500
  Office Supplies: $420
  Total Expenses: $32,560

Net Income: $25,440

APRIL P&L:
Revenue
  Service Revenue: $38,500
  Product Sales: $8,200
  Total Revenue: $46,700

Expenses
  Payroll & Benefits: $22,000
  Rent & Utilities: $3,500
  Software & Subscriptions: $2,340
  Marketing & Advertising: $8,900
  Travel & Transportation: $3,450
  Meals & Entertainment: $1,890
  Professional Services: $1,500
  Office Supplies: $780
  Total Expenses: $44,360

Net Income: $2,340

Please:
1. Identify the TOP 5 variances by dollar impact
2. Calculate the percentage change for each
3. Provide a plain-English explanation for what might have caused each variance
4. Give me 3 talking points for my client meeting
5. Suggest 2-3 questions I should ask the client
```

**SAY:**
"I'm giving it both months of data and asking for five things: top variances, percentages, explanations, talking points, and questions to ask. Let's see what we get."

### [02:00] Wait for Response

**DO:**
- Let the AI generate (typically 30-45 seconds for this)

**SAY:**
"This is the kind of analysis that would take me 20-30 minutes to do properly. Digging through line items, calculating percentages, thinking about what to tell the client."

### [02:45] Review the Variance Analysis

**DO:**
- Scroll through the AI's response
- Highlight each major variance

**SAY:**
"Look at this. It ranked the variances by impact.

Number one: Marketing & Advertising jumped from $2,400 to $8,900. That's a 271% increase, $6,500 hit. It's suggesting maybe a new campaign launch or agency retainer started.

Number two: Service Revenue dropped from $45,200 to $38,500. That's a 15% drop, $6,700 impact. It's asking if we lost a client or had a project end.

Number three: Product Sales down from $12,800 to $8,200. 36% drop. Seasonal? Inventory issues? Something changed.

Number four: Travel & Transportation nearly tripled. From $1,200 to $3,450. Conference? New client onboarding? Site visits?

Number five: Meals & Entertainment almost tripled too. $650 to $1,890. Client entertainment? Team events?"

### [04:30] Show the Talking Points

**DO:**
- Scroll to the talking points section

**SAY:**
"Now look at the talking points it generated for my meeting:

'Revenue decreased 19.5% primarily driven by declines in both service revenue and product sales. We should discuss whether this reflects client churn, project timing, or seasonal patterns.'

'Expenses increased 36% driven by a significant marketing investment and increased travel and entertainment. If this marketing spend was intentional, we should discuss expected ROI timeline.'

'Net margin fell from 43.9% to 5.0%. This isn't sustainable. We need to understand if February was an anomaly or a trend.'

That's exactly what I'd want to say in the meeting. But I didn't have to write it."

### [05:45] Show the Questions

**DO:**
- Scroll to the suggested questions

**SAY:**
"And look at the questions it's suggesting I ask:

'Was the marketing spend a planned investment? What's the expected return timeline?'

'Did you lose any recurring clients in February, or were there project delays?'

'Are the travel and entertainment increases ongoing, or was this a one-time event?'

Those are the right questions. I would have thought of them eventually—but AI got me there in 45 seconds."

### [06:30] The Insight

**SAY:**
"Here's what I want you to notice.

My job used to be: Find the variances. Figure out what happened. Prepare talking points. Think of questions.

Now my job is: Review the analysis. Decide if I agree. Walk into the meeting prepared.

I'm not the detective anymore. I'm the advisor. AI does the hunting. I provide the judgment.

That's a fundamental shift in what it means to be an accountant."

### [07:30] Transition

**SAY:**
"One more demo. This one's about the thing that eats your day in small bites—client communication."

---

# DEMO 3: CLIENT COMMUNICATION WORKFLOW
**Duration:** 9 minutes
**Tool:** ChatGPT, Claude, or Copilot

---

## Setup Before Masterclass

### Sample Emails to Prepare:
Create 3-4 realistic client emails:

**Email 1 - Status Request:**
```
From: Sarah Chen <sarah@chendesign.co>
Subject: Quick question

Hi Jan,

Where are we with January's books? My business partner is asking for the P&L and I want to make sure we're on track.

Thanks!
Sarah
```

**Email 2 - Missing Document:**
```
From: Marcus Johnson <marcus@johnsonlegal.com>
Subject: RE: April reconciliation

Jan,

I got your message about the missing receipt. I'm pretty sure that $347 charge at Office Depot was for printer ink and paper, but I can't find the receipt. Can we just categorize it without the receipt or do you need me to keep looking?

Marcus
```

**Email 3 - Clarification Request:**
```
From: Lisa Park <lisa@parkconsulting.net>
Subject: Confused about something

Hi,

I was looking at the QuickBooks dashboard and I'm seeing a number for "Accounts Receivable" that seems high. Can you explain what that means and if I should be worried? I thought everyone had paid their invoices.

Thanks,
Lisa
```

**Email 4 - Frustrated Client:**
```
From: Tom Bradley <tom@bradleymanufacturing.com>
Subject: Need this ASAP

Jan -

I've got a bank meeting tomorrow morning and I need updated financials. Can you get me a P&L and balance sheet by end of day? I know it's last minute but this is important.

Tom
```

---

## Live Demo Script

### [00:00] Set the Scene

**SAY:**
"Last demo: Client Communication.

This is the one that eats your day in small bites. You sit down to do real work, and then—ping. Client email. 'Quick question.' 'Can you explain this?' 'I need something ASAP.'

Each one takes 5-10 minutes. Not because the answer is hard, but because you have to context-switch, think about tone, type it all out.

Let me show you a different way."

### [00:30] Show the Emails

**DO:**
- Display the sample emails (or describe them)

**SAY:**
"I've got four client emails here.

Sarah wants a status update.
Marcus has a missing receipt question.
Lisa is confused about her AR balance.
Tom needs financials for a bank meeting tomorrow—and he's stressed about it.

Different clients, different needs, different tones required. Let's see how AI handles this."

### [01:00] Paste the Prompt

**DO:**
- Open new chat in AI tool
- Paste the following prompt:

```
You are Jan, a bookkeeper and accountant who communicates in a warm, professional, and reassuring tone. You're efficient but never cold.

Here are 4 client emails I need to respond to. For each one:
1. Draft a response that matches my communication style
2. Keep responses concise but complete
3. If I need more information from the client, ask clearly
4. If there's urgency, acknowledge it without promising what I can't deliver

---

EMAIL 1 - From Sarah Chen (small design firm, been a client for 2 years):
Subject: Quick question
"Hi Jan, Where are we with January's books? My business partner is asking for the P&L and I want to make sure we're on track. Thanks! Sarah"

CONTEXT: April books are 90% done, should be finished by Wednesday.

---

EMAIL 2 - From Marcus Johnson (attorney, been a client for 6 months, very detail-oriented):
Subject: RE: April reconciliation
"Jan, I got your message about the missing receipt. I'm pretty sure that $347 charge at Office Depot was for printer ink and paper, but I can't find the receipt. Can we just categorize it without the receipt or do you need me to keep looking? Marcus"

CONTEXT: We can categorize without receipt but should note it in the file.

---

EMAIL 3 - From Lisa Park (consultant, new client, tends to worry about finances):
Subject: Confused about something
"Hi, I was looking at the QuickBooks dashboard and I'm seeing a number for 'Accounts Receivable' that seems high. Can you explain what that means and if I should be worried? I thought everyone had paid their invoices. Thanks, Lisa"

CONTEXT: She has $8,400 in AR. Two invoices are 30+ days old (total $3,200). The rest are current.

---

EMAIL 4 - From Tom Bradley (manufacturing company, long-time client, can be demanding):
Subject: Need this ASAP
"Jan - I've got a bank meeting tomorrow morning and I need updated financials. Can you get me a P&L and balance sheet by end of day? I know it's last minute but this is important. Tom"

CONTEXT: His books are current. I can generate reports in 10 minutes but I have other commitments today.
```

**SAY:**
"Notice what I'm doing. I'm giving AI context about each client—how long they've been with me, their personality, their situation. And I'm telling it the facts it needs to give an accurate response.

Watch what happens."

### [02:30] Wait for Response

**DO:**
- Let the AI generate all four responses

**SAY:**
"This would normally take me 20-30 minutes. Four emails, four context switches, four different tones."

### [03:15] Review Email 1 - Sarah

**DO:**
- Scroll to the first response

**SAY:**
"Okay, here's Sarah's response:

'Hi Sarah! Great timing on your question. April books are about 90% complete—I'm wrapping up the final reconciliations and you should have the P&L by Wednesday. I'll send it over as soon as it's ready so you and your partner can review. Let me know if you need anything in the meantime! Best, Jan'

Warm, gives a specific timeline, reassuring. That's how I'd write it. But I didn't have to."

### [04:00] Review Email 2 - Marcus

**DO:**
- Scroll to the second response

**SAY:**
"Marcus—the detail-oriented attorney:

'Hi Marcus, Good news—we can absolutely categorize that $347 Office Depot charge as office supplies without the receipt. I'll note in the file that it was for printer ink and paper per your confirmation. For future reference, we try to keep receipts for anything over $75, but this won't cause any issues. Thanks for getting back to me quickly. Best, Jan'

See how it's more formal? More precise? Because Marcus is detail-oriented. It even proactively mentioned the receipt policy for the future. Smart."

### [04:45] Review Email 3 - Lisa

**DO:**
- Scroll to the third response

**SAY:**
"Lisa—the new client who worries:

'Hi Lisa, Great question, and no need to worry! Accounts Receivable simply shows money that's been invoiced but not yet received—so it's actually a good thing. It means you've done work that you're owed payment for.

Looking at your numbers: You have $8,400 in AR total. About $5,200 of that is from recent invoices that aren't due yet—totally normal. There are two older invoices totaling $3,200 that are 30+ days old. Those might be worth a gentle follow-up with those clients.

Would you like me to send you a quick aging report so you can see exactly which invoices are outstanding? Happy to walk through it with you.

Best, Jan'

Educational, reassuring, offers next steps. For a client who tends to worry, that's perfect. It doesn't just answer the question—it teaches and calms."

### [05:45] Review Email 4 - Tom

**DO:**
- Scroll to the fourth response

**SAY:**
"And Tom—the demanding one with the urgent request:

'Hi Tom, I can get you the P&L and balance sheet for your bank meeting—your books are current so the reports will be accurate. I have a few commitments this afternoon, but I'll prioritize this and have them in your inbox by 4pm. Does that work for your prep time?

If you need anything specific formatted or highlighted for the bank, let me know and I'll make sure it's presentation-ready.

Good luck with the meeting tomorrow. Jan'

Direct, confident, specific commitment. Acknowledges the urgency without overpromising. Offers to go the extra mile. That's how you handle Tom."

### [06:45] The Review Process

**DO:**
- Scroll back through all responses

**SAY:**
"So what do I do with these?

I read each one. I check the facts—did AI get the details right? I tweak anything that doesn't sound like me.

For these four? I might change one or two words. Maybe I'd add a personal note to Sarah about her upcoming vacation she mentioned last week.

But the heavy lifting is done. I'm editing, not writing."

### [07:30] The Impact

**SAY:**
"Four emails. Normally 20-30 minutes of my day.

With AI? Maybe 5 minutes total—including review.

And here's the thing: clients don't know. They just know they got a fast, thoughtful, personalized response.

Responsiveness is a competitive advantage. The firms that reply quickly, that make clients feel heard—those firms keep clients.

AI makes you faster than humanly possible. Use it."

### [08:30] Transition

**SAY:**
"Those are your three demos. Transaction review, variance analysis, client communication.

Same AI tools you already have access to. Different results because of how you use them.

Now let's talk about why most firms try this... and fail."

---

# DEMO 4: THE HOMEWORK WORKFLOW (LIVE WALKTHROUGH)
**Duration:** 3 minutes
**Purpose:** Quick reinforcement during "Your Workflow to Deploy" section

---

## Live Demo Script

### [00:00] Set Up

**SAY:**
"Let me show you one more time how simple this is. Fresh data. Fresh prompt. Watch how fast it happens."

### [00:15] Open New Chat

**DO:**
- Open new chat window in AI tool
- Have a different, smaller set of transactions ready (~15-20)

**Smaller CSV for this demo:**
```csv
Date,Description,Amount
2026-05-01,PURCHASE AUTHORIZED AMAZON,-67.89
2026-05-02,ZELLE FROM CLIENT ABC,2500.00
2026-05-03,SQ *STARBUCKS,-8.45
2026-05-04,ACH DEBIT GUSTO,-3200.00
2026-05-05,CHECKCARD HOME DEPOT,-189.34
2026-05-06,PURCHASE CANVA,-12.99
2026-05-07,WIRE INCOMING SMITH LLC,8500.00
2026-05-08,SQ *UBER,-34.56
2026-05-09,PURCHASE ZOOM.US,-15.99
2026-05-10,CHECKCARD COSTCO,-234.56
```

### [00:30] Paste Prompt

**SAY:**
"Here's the prompt. I'm going to type it out so you see exactly what I'm doing."

**DO:**
- Type (or paste, pretending to type) a simpler version:

```
You are a senior bookkeeper. Review these transactions for a small consulting business.

Categorize each one, flag anything unusual, and write a memo for anything over $1,000.

Transactions:
[PASTE CSV]
```

**SAY:**
"That's it. Simple prompt. Paste the data. Hit enter."

### [01:15] Show Results

**DO:**
- Let AI generate results
- Quickly scroll through

**SAY:**
"Ten seconds later—everything categorized. The $8,500 wire has a memo. The $3,200 payroll is correctly identified.

That's it. That's the workflow you're going to do before Friday."

### [02:00] Reinforce the Call to Action

**SAY:**
"Pick one client. Export their transactions. Run this prompt. See what happens.

Don't overthink it. Don't wait for the perfect moment. Just do it once and see.

That's your homework. Screenshot the results. Reply to my email. Make it real."

---

# APPENDIX: BACKUP PLANS

---

## If AI Tool Won't Load:
- Have screenshots ready of successful outputs
- Say: "Looks like we're having a technical hiccup. Let me show you screenshots of exactly what this produces—I ran this earlier today."

## If AI Gives Bad Output:
- Don't panic—this is a teaching moment
- Say: "Okay, this is actually perfect. See how it miscategorized this? This is why we REVIEW the output. Let me show you how I'd adjust the prompt to fix this."
- Rerun with a more specific prompt

## If Output Takes Too Long:
- Have pre-generated outputs ready
- Say: "While this is thinking, let me show you what the output typically looks like—I ran this earlier with the same data."

---

# TECH CHECKLIST

Before the masterclass:
- [ ] AI tool logged in and tested
- [ ] Sample CSV files ready (in a folder you can access quickly)
- [ ] Prompts saved in a text file for easy copy/paste
- [ ] Pre-generated outputs saved as backup screenshots
- [ ] Screen sharing tested
- [ ] Browser tabs arranged in order of demos
- [ ] Notifications turned off on computer
- [ ] Phone on silent

---

*Demo Scripts v1.0 - May 2026*
