# Business Taxes for Startups

```yaml
name: business-taxes
version: 1.0.0
description: Help founders understand US business tax obligations including corporate income tax, franchise tax, sales tax, and transfer pricing
source: Stripe Atlas Guide (with PwC expertise)
```

## Overview

This skill demystifies US business taxes for founders. Calculating and paying taxes is a legal obligation, but it doesn't have to be scary. Understanding your obligations early helps you organize your business to make tax season painless.

---

## Tax Planning Philosophy

> "Anyone may arrange his affairs so that his taxes shall be as low as possible; he is not bound to choose that pattern which best pays the treasury." - Judge Learned Hand, 1934

**Tax planning is legal and expected.** There are often multiple valid ways to apply tax laws to your business. Accountants help you find compliant AND efficient approaches.

⚠️ **BUT**: Abusive tax structuring (actions with no rationale except tax avoidance) can trigger substantial penalties. Always have professionals review significant tax decisions.

---

## Types of Business Taxes

### 1. Delaware Franchise Tax

**What it is**: Annual fee to maintain your Delaware incorporation (not based on revenue or profit)

**Who pays**: All Delaware corporations and LLCs

**When due**: 
- Corporations: March 1 (with Annual Report)
- LLCs: June 1 ($300 flat fee)

**How much**:
- Most Atlas companies pay minimum: **$450** ($400 franchise tax + $50 annual report fee)
- Calculate at: corp.delaware.gov/frtaxcalc.shtml
- Use "Assumed Par Value" method for lowest amount

**Pro tip**: File when preparing your corporate tax return (February) so it's ready by March 1

### 2. Sales Tax

⚠️ **Here be dragons.** Sales tax is complicated.

**When you might owe**:
- Transaction takes place in a jurisdiction, AND
- You have "nexus" (connection) to that jurisdiction

**What creates nexus**:
- Physical property in the state
- Employees in the state
- Incorporating in the state (some states)
- Customers in the state (increasingly)
- Paying affiliates in the state for referrals

**What you must do if nexus exists**:
- Register to collect tax
- Collect tax from customers
- Display tax on transactions
- Remit to government (monthly or quarterly)

**Use tax**: Customers are supposed to pay for out-of-jurisdiction purchases. Compliance is... low.

**Cost**: Few hundred dollars professional fees to file, depending on complexity

### 3. Corporate Income Tax (C Corp)

**Main form**: Form 1120

🚨 **DO NOT FILE THIS YOURSELF** - Always use a professional tax preparer

**Key concepts**:
- Tax is on **income** (revenue - expenses), NOT revenue
- Most purchases can be deducted immediately as expenses
- Some items must be capitalized (depreciated over time)
- Internet businesses typically have low capital expenses

**State income taxes**: 
- May owe in states where you have physical presence
- Some states increasingly claiming internet activity creates filing requirements
- Your accountant advises on state obligations

### 4. LLC Federal Income Tax

**Key difference**: Pass-through taxation

- Single-member LLC: Treated as "disregarded entity" by IRS
- Multi-member LLC: Treated as partnership

**Filing requirements**:
- Single-member LLC owned by non-US individual: File Form 5472
- Multi-member LLC: File Form 1065 (partnership return)

**Flexibility**: LLCs can elect to be taxed as C corporations

🚨 **Still use a professional** - LLC tax reporting varies by structure

---

## Taxpayer ID Numbers

### Social Security Number (SSN)
- Format: 123-45-6789
- For US citizens and authorized workers
- Very sensitive - used for authentication
- Companies don't have SSNs

### Individual Taxpayer Identification Number (ITIN)
- Format: 9XX-XX-XXXX (always starts with 9)
- For individuals who need to file but can't get SSN
- Get via Form W-7 (~6 weeks processing)
- Most Atlas company owners don't personally need one

### Employer Identification Number (EIN)
- Format: 12-3456789 (note different hyphen placement!)
- Identifies companies, not people
- Atlas gets this for you during incorporation
- Routinely requested by banks and partners
- Not as sensitive as SSN

---

## Informational Returns

### What They Are
Companies report certain transactions to the government, which matches them against individual tax filings.

### Forms You'll Issue

**W-2**: Wage income to employees
**1099-MISC**: Payments to individual contractors (not companies)

Your accountant files these early in the calendar year. One copy goes to:
- The taxpayer
- The IRS
- Your records

### Forms You'll Request

**W-9**: Request tax ID from US persons
**W-8BEN**: For non-US individuals (documents why you didn't file 1099)
**W-8BEN-E**: For non-US corporate entities

### Common Mistakes
- Asking non-US persons for W-9 (should be W-8BEN)
- A US company owned by foreigners is still a US person (uses W-9)
- Asking for forms when not legally required

### Forms You'll Receive

**1099-K from Stripe**: Shows total payment volume (NOT taxable income)
- Don't worry - this will be in your books already
- It's revenue, not profit
- IRS expects this number to be subset of your reported revenue

---

## Transfer Pricing

### What It Is
How companies document money movement between their own international operations, priced as if they were unrelated "arm's length" companies.

### Why It Matters
International businesses must allocate profits appropriately between jurisdictions. Tax authorities scrutinize this, especially when money flows to low-tax jurisdictions.

### Key Principle: Fair Prices
- Document justification for prices between related entities
- Research what unrelated parties would charge
- Keep formal agreements between entities
- Ensure books match stipulated reality and actual fund flows

### Example 1: Software Company (India + US)

**Setup**: Indian PLC develops software, Delaware C Corp sells to US/international customers

**Approach**: 
- US entity is reseller of Indian company's software
- Research shows unrelated resellers typically get 20%
- US entity pays 80% of billings to Indian PLC
- Indian PLC books this as revenue, pays Indian taxes
- US entity keeps 20%, covers US operating costs, pays US taxes on modest profit

### Example 2: Physical Products (Hong Kong + US)

**Setup**: Hong Kong founders make iPhone cases, take Silicon Valley investment

**Approach**:
- US entity contracts with HK for design/branding services (funds initial operations)
- HK manufactures cases, sells wholesale to US entity at ~40% of retail
- US entity sells retail to customers worldwide
- Document pricing rationale based on comparable manufacturers

### Transfer Pricing Warnings

⚠️ **Direction matters**: 
- Recognizing revenue in high-tax jurisdiction (US) = less scrutiny
- Recognizing revenue in low-tax jurisdiction = heavy scrutiny
- HK corporate rate is <50% of US rate, so IRS watches closely

⚠️ **Document everything**:
- No documentation = difficult to defend against penalties
- Larger businesses need specialized accountants

---

## Audits

**Don't panic.** An audit is simply a formal inquiry into your tax return correctness.

### Types of Audits

**Correspondence Audit** (most common):
- Letter from IRS
- Computer flagged a discrepancy
- Usually resolved with simple written explanation
- Your accountant handles this

**In-Person Examination** (rare):
- At IRS office or your office
- IRS has offices in US embassies for international issues
- 🚨 Get professional representation immediately

### How to Handle Audits

1. Follow your accountant/tax attorney's advice exactly
2. Don't volunteer information beyond what's asked
3. Don't provide all financial data proactively (can expand scope)
4. Treat it as routine professional matter

### Prevention

- Hire accountant
- File honest returns
- Retain organized information
- Spend time growing business, not worrying about unlikely audits

---

## Checklist: Tax Compliance

### At Incorporation
- [ ] Get EIN (Atlas handles this)
- [ ] Choose accounting method (cash vs accrual)
- [ ] Set up proper bookkeeping
- [ ] Understand state nexus implications

### Quarterly
- [ ] Review sales tax collection requirements
- [ ] Ensure payments to contractors are documented
- [ ] Collect W-9/W-8BEN from vendors as needed

### Annually
- [ ] File Delaware franchise tax + Annual Report (due March 1)
- [ ] File federal corporate income tax (due April 15)
- [ ] Issue W-2s and 1099s (early in year)
- [ ] Review state income tax obligations
- [ ] Review transfer pricing documentation (if international)

### Ongoing
- [ ] Work with accountant at least yearly
- [ ] Track tax law changes
- [ ] Maintain organized records
- [ ] Document rationale for any inter-company transactions

---

## How to Help Founders

### Common Questions

1. **"Do I need an accountant?"**
   - YES. Absolutely. This is not optional.
   - Professional advice saves money and stress.
   - Corporate tax returns should never be DIY.

2. **"What taxes do I definitely owe?"**
   - Delaware franchise tax ($450 minimum annually)
   - Federal corporate income tax (if profitable)
   - Possibly state income tax and sales tax

3. **"How do I handle international operations?"**
   - Set up proper transfer pricing documentation
   - Research fair market rates for inter-company services
   - Document everything
   - Get specialized accounting help

4. **"I got a letter from the IRS!"**
   - Don't panic
   - Contact your accountant immediately
   - It's probably a simple correspondence audit
   - Let professionals handle response

5. **"Do I need to collect sales tax?"**
   - Depends on nexus in each state
   - Check where you have employees/property
   - Increasingly, customer presence matters
   - Talk to accountant about registration requirements

### Red Flags
- No accountant involved
- Missing Delaware franchise tax filing
- International entities without transfer pricing documentation
- Collecting sales in states without checking nexus
- Not issuing 1099s to US contractors

---

## Key Takeaways

1. **Get an accountant** - Non-negotiable for any business
2. **Delaware franchise tax is simple** - $450/year, due March 1
3. **Sales tax is complicated** - Check nexus carefully
4. **Document international transactions** - Transfer pricing protects you
5. **Audits aren't emergencies** - File honest returns, keep organized records
6. **Tax law changes** - Review strategy with professionals annually

---

*Disclaimer: This guide is not legal or tax advice. Consult a qualified accountant or attorney for your specific situation.*
