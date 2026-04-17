# Ji & Sarah Student Loan Repayment Simulator — User Manual

---

## What is this simulator?

This tool simulates how Ji and Sarah can pay off Sarah's U.S. student loans ($169,907) while living together in Japan after marriage.

You enter your income, expenses, employment status, baby plans, and job changes **for each year**, and the simulator automatically calculates when the loans will be paid off, how much interest you'll pay, and how much savings you'll accumulate.

**Language toggle**: Use the EN/한국어 button in the top right to switch languages.

---

## Screen Layout

There are 4 tabs at the top:

| Tab | What it does |
|---|---|
| Plan | Enter yearly income and expenses, adjust loan settings |
| Results | See year-by-year repayment breakdown with explanations |
| Compare | Compare scenarios side by side (Sarah employed/unemployed, baby/no baby, etc.) |
| Loans | View loan details, interest rates, priorities, Graduated structure explained, strategy guide |

---

## Top Summary Numbers (always visible)

Six numbers are displayed at the top. They update in real time as you change settings.

| Item | Meaning |
|---|---|
| Est. Payoff | When all loans will be fully paid off with current settings |
| Total Interest | Total interest paid over the life of the loans ($ + ¥) |
| Savings | Cumulative emergency fund savings at end of simulation |
| Yr 1 Extra Repay | How much extra you can pay in year 1. Shows "Deficit" if negative |
| Start Savings | Combined starting savings (Sarah + Ji) |
| Total Paid | Principal + interest — everything you'll pay in total |

---

## Tab 1: Yearly Plan

### Yearly Income & Expense Table

This table is the heart of the simulator.

**What each column means:**

| Column | What to enter | Example |
|---|---|---|
| Ji ¥ | Ji's monthly income (after tax) | 300,000 |
| Sarah ¥ | Sarah's monthly income (after tax). Enter 0 if unemployed | 0 or 220,000 |
| Living ¥ | Monthly living expenses for two (excluding loan payment) | 300,000 |
| Baby ¥ | Monthly childcare/baby costs. Enter 0 if none | 0 or 50,000 |
| Notes | What's happening that year | "Sarah arch job", "Baby born" |
| Surplus | Auto-calculated. Click to expand formula | ¥129,440 |

**Currency toggle**: Use the ¥ JPY / $ USD buttons above the table to switch input currency. If you enter dollars, they're automatically converted to yen.

**Comma formatting**: Amounts display with commas (300,000). Click a cell to edit, press Enter or click outside to confirm.

**Conversion display**: Small text below each cell shows the converted amount in the other currency (e.g., $2,000 below ¥300,000).

**Add/remove years**: Use the [+ Add] [- Remove] buttons to add up to 15 years.

### What is "Surplus"?

Surplus is calculated as:

```
Surplus = Ji income + Sarah income - Living costs - Loan minimum payment - Baby costs - Monthly savings
```

- **Positive (+)**: This amount goes to extra loan repayment each month
- **Deficit (-)**: No extra repayment possible. Only minimum payment continues
- **Click the surplus number** to expand the full formula

**Important**: Even in deficit, loan repayment does NOT stop. The minimum payment always continues.

### Starting Savings & Emergency Fund

| Item | Meaning | Default |
|---|---|---|
| Sarah savings ($) | Sarah's current savings | $12,000 |
| Ji savings ($) | Ji's current savings | Enter your amount |
| Monthly savings target | Amount set aside for emergency fund each month | ¥30,000 |

The monthly savings target is deducted from income first, then the remainder goes to extra repayment. In deficit years, savings automatically reduce to what's affordable.

### Loan Settings

**Graduated Increase Rate (most important setting)**

Graduated repayment means your minimum payment increases every 2 years. Use the slider to set the increase rate.

- Default: 15%
- Range: 0% to 30%
- Set to 0% for fixed payment calculation
- Preview shows below the slider: Now $1,004 → yr2 $1,155 → yr4 $1,328

**Auto Pay Rate Discount (-0.25%)**

If you register Auto Pay on aidvantage, interest rates drop by 0.25%. Toggle ON/OFF. See the Compare tab for the impact.

**2027 Plan End Simulation**

The current Graduated Extended plan ends Sep-Oct 2027. Turn this ON to simulate a new payment amount after the plan ends.

**Lump Sum Payment**

Simulate putting a one-time lump sum toward the loans. Set the amount and timing (which month).

**Repayment Strategy**

| Strategy | Description |
|---|---|
| Highest Rate First (Avalanche) | Pay highest-rate loan first. Maximizes interest savings. Recommended. |
| Smallest Balance First (Snowball) | Pay smallest balance first. Psychological wins. |

---

## Tab 2: Results

### Year-by-Year Repayment Breakdown

Each row shows one year:

| Column | Meaning |
|---|---|
| Start | Loan balance at the beginning of the year |
| Interest | Interest paid that year |
| Principal | Principal paid down that year |
| End | Loan balance at year end + reduction percentage |
| Paid Off | Individual loans that were fully paid off that year |
| Why | Explanation of what happened and why |

**How to read the "Why" column:**

The colored badge at the top shows your strategy phase:
- Red **Phase 1: Survive** — Deficit period. Minimum payment only
- Orange **Phase 2: Stabilize** — Small surplus. Small extra payments begin
- Brown **Phase 3: Attack** — Room to breathe. Aggressive extra payments
- Green **Phase 4: Eliminate** — Full speed. Paying off loans one by one

Below that you'll see:
- Sarah's income status
- Deficit/surplus amount and extra repayment
- Minimum payment amount (reflects Graduated increases)
- Savings activity (in both $ and ¥)
- Events from your notes

**All dollar amounts show yen conversion in small text below.**

### Narrative Summary

Below the table, a text summary shows the overall trajectory — each year's balance change and cumulative repayment percentage.

---

## Tab 3: Compare

### Scenario Comparison

Compares your current plan against variations where one variable changes:

| Scenario | What changes |
|---|---|
| Current plan | Your yearly plan as-is |
| Sarah always unemployed | Sarah income = 0 for all years |
| Sarah arch job from yr 1 | Sarah = ¥300,000 for all years |
| No baby | Baby cost = 0 for all years |
| With Auto Pay | Rates -0.25% (only shown when Auto Pay is OFF) |

Each scenario shows payoff time and total interest as a horizontal bar for easy comparison.

### Key Insights

Auto-generated analysis based on the comparison. Shows specific numbers like "Immediate arch job saves X years and $X in interest."

---

## Tab 4: Loan Details

### Loan Breakdown

Shows all 4 loans sorted by interest rate with repayment priority:

| Loan | Principal | Rate | Priority |
|---|---|---|---|
| 1-06 | $33,142 | 7.08% | Top |
| 1-03 | $49,079 | 7.00% | 2nd |
| 1-01 | $43,393 | 6.84% | 3rd |
| 1-02 | $44,292 | 6.31% | 4th |

### End Balances

Shows each loan's remaining balance (or "Paid") at the end of the simulation.

### Understanding Graduated Repayment

Explains why Graduated costs more overall and the 4 ways to beat it:

1. Pay more than the minimum — minimum only maintains the structure
2. Extra payments go straight to principal — reduces the interest base
3. Pay highest-rate loans first (Avalanche) — eliminate the most expensive interest
4. Lump sums: all at once, as soon as possible — delay means more interest

### 4-Phase Strategy Guide

Shows which strategy phase fits your current situation:

- **Phase 1 (Survive)**: Unstable income. Maintain minimum, preserve cash
- **Phase 2 (Stabilize)**: Dual income starts. Small extra payments, build emergency fund
- **Phase 3 (Attack)**: Stable income. Aggressive extra payments $500+/month
- **Phase 4 (Eliminate)**: Surplus secured. Lump sums, pay off loans one by one

---

## Frequently Asked Questions

**Q: The surplus is negative but there's still a payoff date?**
A: The minimum payment continues even in deficit. Negative surplus means "no extra repayment," not "no payment at all."

**Q: What Graduated increase rate should I use?**
A: Check your actual rate on aidvantage. Typical range is 10-20%. If unsure, 15% is a realistic middle value.

**Q: Do savings accumulate in deficit years?**
A: No. In deficit years, savings are zero. If there's some surplus but less than the savings target, only the affordable amount is saved.

**Q: When should I put in a lump sum?**
A: As early as possible. But always keep 3-6 months of emergency fund before putting money toward the loans.

**Q: Which loan should I pay off first?**
A: Avalanche (highest rate first) saves the most interest. Order: 1-06 (7.08%) → 1-03 (7.00%) → 1-01 (6.84%) → 1-02 (6.31%).

**Q: What's the difference between "minimum payment" and "extra repayment"?**
A: Minimum payment is the amount you must pay to aidvantage every month (starts at ~$1,004 and increases with Graduated). Extra repayment is anything above that — it goes directly to principal and shortens your payoff timeline.

**Q: Can I change the repayment plan from Graduated?**
A: Yes, you can change at any time through aidvantage. Use the "2027 Plan End" toggle to simulate what happens with a different payment amount. However, changing to Standard means higher mandatory monthly payments, so make sure you can afford it.

---

*This simulator is for reference purposes. Actual repayment amounts may differ from your servicer (aidvantage).*
