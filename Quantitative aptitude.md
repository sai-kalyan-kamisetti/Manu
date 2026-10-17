# Quantitative Aptitude Shortcut Guide: AAI Junior Executive (Operations) and Central Government Exams

## Introduction

This guide covers your 14 topics, in your order, with formulas, shortcuts, 3 solved examples per topic (easy / medium / tough), 5 practice questions per topic, exam application notes and a quick revision box.

**What I could verify about the exam (as of 18 Oct 2026):**
- The official AAI syllabus PDF for JE (Operations), Advt. No. 12/2026/CHQ/DR-CBT, states: **Total marks 120, duration two hours**, Part A (50%) = General Knowledge, General English, Quantitative Aptitude, Reasoning (verbal and non-verbal); Part B (50%) = subject questions linked to educational qualification. Part A also says 20% of it covers aviation topics (abbreviations, airport definitions, airlines, airport operations, aviation meteorology). Source: AAI syllabus PDF (link in the source list).
- **Exam date:** Testbook reports the JE (Operations) CBT is scheduled for **26 October 2026**. That is a third-party report, so confirm on aai.aero. If correct, you have about 8 days.
- **Not verified from the official PDF:** how many Quantitative Aptitude questions appear, whether there is negative marking, and whether Data Interpretation or Data Sufficiency are explicitly listed. One coaching blog (Prashant Chaturvedi) says about 15 marks for Quantitative Aptitude, and several third-party pages say there is no negative marking for AAI JE. Treat these as unconfirmed. Your 14-topic list is covered as you asked, but the topic-wise emphasis below is **general competitive-exam advice, not confirmed AAI trends**.

**Labelling of questions:** I could not retrieve any verified AAI previous-year paper. So **every practice question is ORIGINAL (created for this guide)**, except one: the Number System easy example is an SSC CGL-style question I saw on Cracku (not an AAI question); the solution is my own. No question here is claimed to be an official previous-year question.

**Answer-checking:** every calculation was worked twice. Time estimates are for a prepared student who has memorised the tables listed in each topic.

## Research Sources and Reliability

| Source | Type | Reliability |
|---|---|---|
| AAI official JE (Operations) syllabus PDF (aai.aero) | Official | Highest. Use for pattern and syllabus |
| Careers360 news, Testbook (notification and dates) | Third-party news | Good for dates and vacancies; confirm on aai.aero |
| SATHEE (IIT Kanpur) pages | Educational, institutional | Good for formulas and tricks |
| SpeedMath, Hitbullseye, Oliveboard, Faceprep, Cracku | Coaching blogs | Generally sound formulas; verify any exam-frequency claims independently |
| Prashant Chaturvedi blog | Coaching blog | Useful pattern summaries, but unofficial |

I did not find verifiable YouTube or Medium links in my searches, so I have not listed any. I will not invent them. Full list with links is at the end.

---

## 1. Number System

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Divisibility by 3 / 9 | Digit sum divisible by 3 / 9 |
| By 4 / 8 | Last 2 / 3 digits divisible by 4 / 8 |
| By 11 | (Sum of odd-place digits) − (sum of even-place digits) = 0 or multiple of 11 |
| By 7 | Double the last digit, subtract from the rest; repeat |
| Division | Dividend = Divisor × Quotient + Remainder |
| HCF × LCM | = product of the two numbers |
| Number of factors | If N = p^a · q^b · r^c, factors = (a+1)(b+1)(c+1) |
| Same remainder r | Smallest number = LCM + r; largest divisor = HCF of (number − r) |
| Sums | 1 to n: n(n+1)/2; first n odd: n²; first n even: n(n+1) |
| Trailing zeros in n! | ⌊n/5⌋ + ⌊n/25⌋ + ⌊n/125⌋ + … |
| Unit digit cycles | 2: 2,4,8,6; 3: 3,9,7,1; 7: 7,9,3,1; 8: 8,4,2,6; 4: 4,6; 9: 9,1; 0,1,5,6: fixed |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Unit-digit cyclicity | Divide power by 4; use the remainder (0 means 4th term) | Unit digit of big powers | Gives only the last digit |
| LCM + r | Same remainder in all divisions → LCM + r | "Least number leaving remainder r" | If remainders differ, use "LCM − (divisor − remainder)" |
| HCF of differences | Largest divisor leaving remainders r1, r2: HCF of (N1−r1), (N2−r2) | "Largest number dividing…" | Subtract remainders first, not after |
| Digit-sum check (casting out nines) | Remainder mod 9 = digit sum mod 9 | Verifying sums, products; remainder by 3 or 9 | Cannot catch errors that are multiples of 9 |
| Option elimination by last digit | Test unit digits of options first | Product / power questions | Several options may share a last digit |
| Factor counting by prime form | Prime-factorise once, then count exponent choices | "How many divisors that are…" | Needs fast factorisation of the number |

**C. Three Mandatory Solved Examples**

**Easy** (SSC CGL-style question seen on Cracku; not AAI. Solution mine.)
The least number which, when divided by 25, 40 and 60, leaves remainder 7 in each case is: (a) 609 (b) 593 (c) 1207 (d) 607.
1. Same remainder in each case → answer = LCM + 7.
2. LCM(25, 40, 60): 25 = 5², 40 = 2³·5, 60 = 2²·3·5 → 2³·3·5² = 600.
3. 600 + 7 = **607**. Answer: **(d)**.
- Fastest method: the LCM trick above. Time: **15 s**.
- Why efficient: avoids testing four options by division.
- Common mistake: picking 600 (the LCM) and forgetting to add the remainder.

**Medium**
The unit digit of 7⁴⁵ × 3⁸⁶ is: (a) 1 (b) 3 (c) 7 (d) 9.
1. 7 cycle length 4: 45 ÷ 4 leaves 1 → 7¹ → unit digit 7.
2. 3 cycle length 4: 86 ÷ 4 leaves 2 → 3² → unit digit 9.
3. 7 × 9 = 63 → unit digit **3**. Answer: **(b)**.
- Fastest method: cyclicity on each factor, then multiply last digits. Time: **30 s**.
- Common mistake: using remainder 0 as "no power" instead of the 4th term of the cycle.

**Tough**
How many divisors of 3600 are multiples of 6? (a) 18 (b) 24 (c) 30 (d) 36.
1. 3600 = 2⁴ · 3² · 5².
2. A divisor 2^a 3^b 5^c is a multiple of 6 if a ≥ 1 and b ≥ 1.
3. a: 1–4 → 4 choices; b: 1–2 → 2 choices; c: 0–2 → 3 choices.
4. 4 × 2 × 3 = **24**. Answer: **(b)**.
- Fastest method: prime form with restricted exponent ranges. Time: **60 s** (honest estimate; factorising 3600 takes a few seconds if you know 3600 = 36 × 100).
- Common mistake: counting all 45 divisors, or letting a start at 0.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) Remainder when 2¹⁰⁰ is divided by 7? (a) 1 (b) 2 (c) 4 (d) 6. **Answer (b).** 2³ = 8 ≡ 1 (mod 7); 100 = 3×33 + 1 → 2¹ = 2.
2. (Easy) Sum of the first 20 even numbers? (a) 380 (b) 400 (c) 420 (d) 440. **Answer (c).** n(n+1) = 20 × 21 = 420.
3. (Medium) Largest number that divides 1657 and 2037 leaving remainders 6 and 5? (a) 123 (b) 127 (c) 235 (d) 305. **Answer (b).** HCF(1651, 2032): 2032 − 1651 = 381; 1651 = 4×381 + 127; 381 = 3×127 → 127.
4. (Medium) Trailing zeros in 75!? (a) 15 (b) 16 (c) 18 (d) 19. **Answer (c).** 75/5 = 15; 75/25 = 3; total 18.
5. (Tough) Number of divisors of 2⁴ · 3³ · 5² that are perfect squares? (a) 8 (b) 10 (c) 12 (d) 18. **Answer (c).** Even exponents: 2: {0,2,4} = 3; 3: {0,2} = 2; 5: {0,2} = 2 → 3×2×2 = 12.

**E. Exam-Oriented Application**
Number System ideas (remainders, HCF/LCM, unit digits) feed into many other topics, so they are worth learning for any Central Government quant section. I could not verify how often AAI JE (Operations) asks them; this is general competitive-exam advice. Priority: unit digits, LCM/HCF word problems, remainder tricks.

**F. Quick Revision**
- Formulas: factors = (a+1)(b+1)…; HCF × LCM = product; n! zeros = n/5 + n/25 + …
- Time-savers: cyclicity (mod 4), LCM + r, HCF of differences, digit-sum check.
- Reminders: remainder 0 in cycle means last term; subtract remainders before HCF.
- Mistakes: forgetting "+ r"; counting 1 or the number itself incorrectly in factor questions.

---

## 2. Simplification

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| BODMAS | Brackets, Of, Division, Multiplication, Addition, Subtraction (D and M left to right; A and S left to right) |
| Identities | (a±b)² = a² ± 2ab + b²; a² − b² = (a−b)(a+b); a³ ± b³ = (a±b)(a² ∓ ab + b²) |
| If x + 1/x = k | x² + 1/x² = k² − 2; x³ + 1/x³ = k³ − 3k |
| Surds | 1/(√a + √b) = (√a − √b)/(a − b) |
| Squares/cubes | Know squares to 30, cubes to 15 |
| Fraction-decimal | 1/8 = 0.125, 3/8 = 0.375, 1/16 = 0.0625 |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Fraction-percentage table | Replace 12.5% by 1/8, 16.67% by 1/6, etc. | Percentage-of expressions | Must be memorised (1/2 to 1/16) |
| Square of number ending in 5 | n5² = n(n+1) followed by 25 (85² → 8×9 = 72 → 7225) | Squares ending in 5 | Only ending-in-5 numbers |
| Identity recognition | Spot a²−b², (a+b)², a³+b³ pattern | Decimal-heavy expressions | Needs the pattern to be present |
| Multiply by 25 / 125 | ×100 ÷ 4 / ×1000 ÷ 8 | Mental multiplication | Useful for easy multiples only |
| Rationalise telescoping sums | Each term becomes a difference; middle terms cancel | Sums like 1/(1+√2) + … | Only when consecutive surds |
| Approximation | Round to nearby clean numbers; compare with option gaps | "Approximately" questions | Not for exact-value questions |

**C. Three Mandatory Solved Examples**

**Easy**
25% of 480 + 12.5% of 160 = ? (a) 120 (b) 140 (c) 150 (d) 160.
1. 25% of 480 = 480/4 = 120.
2. 12.5% of 160 = 160/8 = 20.
3. 120 + 20 = **140**. Answer: **(b)**.
- Fastest method: fraction equivalents. Time: **10–15 s**.
- Common mistake: treating 12.5% as 1/12.

**Medium**
(7.5 × 7.5 − 2.5 × 2.5) / 5 = ? (a) 5 (b) 10 (c) 15 (d) 20.
1. Numerator = (7.5 − 2.5)(7.5 + 2.5) = 5 × 10 = 50.
2. 50 / 5 = **10**. Answer: **(b)**.
- Fastest method: difference of squares. Time: **20 s**.
- Common mistake: squaring 7.5 (56.25) and subtracting by hand, which is slower and error-prone.

**Tough**
1/(1+√2) + 1/(√2+√3) + 1/(√3+2) = ? (a) 0 (b) 1 (c) √2 (d) 2.
1. Rationalise each: 1/(1+√2) = √2 − 1 (denominator 2 − 1 = 1).
2. 1/(√2+√3) = √3 − √2; 1/(√3+2) = 2 − √3.
3. Sum: (√2 − 1) + (√3 − √2) + (2 − √3) = 2 − 1 = **1**. Answer: **(b)**.
- Fastest method: telescoping. Time: **40 s**.
- Common mistake: not noticing consecutive denominators (differences of 1 in the squares), leading to messy decimals.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) 85² = ? (a) 7125 (b) 7225 (c) 7325 (d) 7425. **Answer (b).** 8 × 9 = 72, then 25.
2. (Easy) 12.5% of 640 + 37.5% of 320 = ? (a) 180 (b) 200 (c) 220 (d) 240. **Answer (b).** 80 + 120.
3. (Medium) (0.8³ + 0.2³) / (0.8² − 0.8×0.2 + 0.2²) = ? (a) 0.6 (b) 0.8 (c) 1 (d) 1.2. **Answer (c).** (a³+b³)/(a²−ab+b²) = a+b = 1.
4. (Medium) Approximately, 49.9% of 801 + 24.9% of 1999 = ? (a) 850 (b) 900 (c) 950 (d) 1000. **Answer (b).** ≈ 400 + 500 = 900 (exact ≈ 897.5).
5. (Tough) If x + 1/x = 5, then x³ + 1/x³ = ? (a) 110 (b) 115 (c) 120 (d) 125. **Answer (a).** 5³ − 3×5 = 125 − 15 = 110.

**E. Exam-Oriented Application**
Simplification is pure speed work and supports every other topic. Comparable government exams typically include such questions, but I could not verify AAI-specific frequency. Priority: memorise squares, fraction-percent table, and identities.

**F. Quick Revision**
- Formulas: a²−b², (a±b)², x+1/x identities, rationalisation.
- Time-savers: fraction equivalents, n5² rule, telescoping.
- Reminders: BODMAS order; check sign inside brackets.
- Mistakes: dropping a negative sign; wrong fraction equivalents.

---

## 3. Percentage

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Percentage | (Part / Whole) × 100 |
| Successive change | Net % = a + b + ab/100 |
| If A is x% more than B | B is 100x/(100 + x) % less than A |
| If A is x% less than B | B is 100x/(100 − x) % more than A |
| Price up x%, expenditure fixed | Consumption falls by 100x/(100 + x) % |
| Population / depreciation | Final = Initial × (1 ± r/100)ⁿ |
| a% of b | = b% of a |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Fraction-percent table | 1/6 = 16⅔%, 1/7 = 14.28%, 1/9 = 11.11% | All percentage questions | Memorise 1/2 to 1/16 |
| Multiplier method | +20% → ×1.2, −20% → ×0.8 | Successive changes, reverse percentages | Multipliers must be applied in sequence |
| Swap trick | 16% of 25 = 25% of 16 = 4 | Awkward "a% of b" | Only for simple % of a number |
| Percentage-point vs percent | Distinguish "increase by 5 points" from "5% increase" | DI, election questions | Misreading changes the answer |
| Reverse percentage | Final ÷ multiplier = original | "After 20% discount price is …" | Needs the correct base |

**C. Three Mandatory Solved Examples**

**Easy**
16⅔% of 1200 = ? (a) 160 (b) 180 (c) 200 (d) 240.
1. 16⅔% = 1/6.
2. 1200 / 6 = **200**. Answer: **(c)**.
- Fastest method: fraction equivalent. Time: **10 s**.
- Common mistake: using 16.66% as 16% and getting 192.

**Medium**
Price of sugar rises by 25%. By what percent must a household cut consumption so that expenditure stays the same? (a) 16% (b) 20% (c) 25% (d) 30%.
1. Price × consumption = expenditure; price ratio 5:4 → consumption ratio 4:5.
2. Fall = 1 part out of 5 = **20%**. Answer: **(b)**.
- Fastest method: 100x/(100 + x) = 2500/125 = 20. Time: **15 s**.
- Common mistake: answering 25%.

**Tough**
In an election between two candidates, 10% of the voters did not vote and 20% of the votes cast were invalid. The winner got 60% of the valid votes and won by 2880 votes. How many voters were on the list? (a) 15000 (b) 18000 (c) 20000 (d) 24000.
1. Let voters = V. Votes cast = 0.9V; valid = 0.8 × 0.9V = 0.72V.
2. Margin = 60% − 40% = 20% of valid = 0.2 × 0.72V = 0.144V.
3. 0.144V = 2880 → V = 20000. Answer: **(c)**.
- Fastest method: chain of multipliers; or test option (c): 20000 → 18000 → 14400 → 20% = 2880 ✓. Time: **50 s**.
- Common mistake: taking 20% of 0.9V as the margin (forgetting the 60:40 split).

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) 37.5% of 880 = ? (a) 300 (b) 330 (c) 350 (d) 360. **Answer (b).** 3/8 × 880.
2. (Easy) A number rises 20% then falls 20%. Net change? (a) 0% (b) −2% (c) −4% (d) +4%. **Answer (c).** 20 − 20 − 400/100 = −4.
3. (Medium) A's salary is 25% more than B's. B's is what % less than A's? (a) 15% (b) 20% (c) 25% (d) 30%. **Answer (b).** 100×25/125.
4. (Medium) A town's population of 20000 rises 10% then falls 10%. New population? (a) 19600 (b) 19800 (c) 20000 (d) 20200. **Answer (b).** 1.1 × 0.9 = 0.99.
5. (Tough) 80% of students passed in Maths, 70% in English, 10% failed both. Percent passing both? (a) 50% (b) 55% (c) 60% (d) 65%. **Answer (c).** Passed at least one = 90; both = 80 + 70 − 90 = 60.

**E. Exam-Oriented Application**
Percentage underpins Profit & Loss, Interest, DI and Ratio questions in most government exams (general-exam observation; AAI-specific frequency unverified). Priority: fraction table, successive change, reverse percentage.

**F. Quick Revision**
- Formulas: a + b + ab/100; 100x/(100 + x); multiplier method.
- Time-savers: fraction table, multipliers, swap trick.
- Reminders: identify the base before computing.
- Mistakes: adding successive percentages; mixing percent and percentage points.

---

## 4. Profit & Loss

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Profit % | Profit / CP × 100 |
| SP | CP × (100 + P)/100 (or (100 − L)/100) |
| Discount | % on marked price (MP) |
| MP and net result | If MP is x% above CP and discount is d%, net % = x − d − xd/100 |
| Successive discounts | a + b − ab/100 |
| Equal SP, p% profit and p% loss | Always a loss of p²/100 % |
| False weight | Gain % = error / (true weight − error) × 100 |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Multiplier chain | Profit 20% then loss 10% → ×1.2 ×0.9 | Chained transactions | None significant |
| SP : CP ratio | SP:CP = (100 + P):100 | Quick ratio comparisons | Only for same-base comparisons |
| p²/100 rule | Same SP, ±p% → loss p²/100 % | Two-article questions | Applies only to equal SP (not equal CP) |
| Dishonest weight | Gain = error / (true − error) | Question gives false weight | When both false weight and discount appear, use CP/SP per kg |
| Option substitution | Use CP = 100 as a base | Percentage-only questions | Not for questions with absolute figures |

**C. Three Mandatory Solved Examples**

**Easy**
An article bought for ₹500 is sold for ₹575. Profit %? (a) 12% (b) 15% (c) 18% (d) 20%.
1. Profit = 75; 75/500 = 15%. Answer: **(b)**.
- Fastest method: 75/500 = 3/20 = 15%. Time: **10 s**.
- Common mistake: dividing by SP (75/575).

**Medium**
A shopkeeper marks goods 30% above cost and gives 10% discount. Profit %? (a) 15% (b) 17% (c) 20% (d) 23%.
1. CP = 100; MP = 130; SP = 130 × 0.9 = 117.
2. Profit = **17%**. Answer: **(b)**.
- Fastest method: 30 − 10 − 30×10/100 = 17. Time: **20 s**.
- Common mistake: 30 − 10 = 20%.

**Tough**
A dishonest shopkeeper uses a 900 g weight for 1 kg. He marks goods 20% above cost and allows a 10% discount. His overall gain %? (a) 18% (b) 20% (c) 22% (d) 25%.
1. Let cost be 100 per kg (so 90 for 900 g).
2. MP per kg = 120; after 10% discount, customer pays 108 for "1 kg".
3. He actually delivers 900 g, costing him 90.
4. Gain = 108 − 90 = 18; 18/90 = **20%**. Answer: **(b)**.
- Fastest method: compute cost of what is actually delivered. Time: **50 s**.
- Common mistake: adding 11.11% (false weight) and 8% (discount-adjusted markup) arithmetically.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) CP ₹250, loss 12%. SP? (a) 210 (b) 215 (c) 220 (d) 225. **Answer (c).** 250 × 0.88.
2. (Easy) Successive discounts of 20% and 10% equal a single discount of? (a) 25% (b) 28% (c) 30% (d) 32%. **Answer (b).** 20 + 10 − 2 = 28.
3. (Medium) SP of 12 articles equals CP of 15 articles. Gain %? (a) 20% (b) 25% (c) 30% (d) 33⅓%. **Answer (b).** (15 − 12)/12 = 25%.
4. (Medium) Two articles sold at ₹1200 each; one at 20% gain, the other at 20% loss. Overall result? (a) No loss (b) Loss ₹100 (c) Loss ₹200 (d) Gain ₹100. **Answer (b).** Loss % = 400/100 = 4% of total CP; total CP = 2400/0.96 = 2500; loss = 100.
5. (Tough) A sells to B at 20% profit, B sells to C at 10% loss, C pays ₹540. A's cost? (a) 450 (b) 480 (c) 500 (d) 520. **Answer (c).** 1.2 × 0.9 = 1.08; 540 / 1.08 = 500.

**E. Exam-Oriented Application**
Profit & Loss questions often combine percentage, ratio and discount. Priority: marked-price/discount questions and equal-SP questions. AAI-specific frequency not verified; this is general guidance.

**F. Quick Revision**
- Formulas: SP = CP(100 ± P)/100; x − d − xd/100; p²/100.
- Time-savers: multipliers, CP = 100 assumption.
- Reminders: profit and loss are always on CP unless told otherwise; discount is on MP.
- Mistakes: dividing by SP; adding percentages directly.

---
## 5. Simple & Compound Interest

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Simple interest | SI = P·R·T/100; Amount = P + SI |
| Compound amount | A = P(1 + R/100)ⁿ |
| Half-yearly / quarterly | Rate ÷ 2 (or ÷ 4), time × 2 (or × 4) |
| CI − SI (2 years) | P(R/100)² |
| CI − SI (3 years) | P(R/100)²(3 + R/100) |
| Effective rate, 2 years | R + R + R²/100 percent |
| SI doubling time | 100/R years |
| Growth between years (CI) | A₂/A₁ = (1 + R/100) |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Effective-rate stacking | 10% for 2 yrs → 21%; 3 yrs → 33.1% | CI for 2–3 years | Beyond 3 years use powers |
| Ratio of consecutive amounts | CI amount after year n+1 ÷ amount after year n = 1 + R/100 | Given two amounts, find rate | Needs consecutive years |
| Difference formula | CI − SI = P(R/100)² | Direct difference questions | 2 years only (3-year has its own formula) |
| Alligation on rates | Two SI rates giving a combined interest → ratio of principals | Split-investment problems | Same time period for both parts |
| Rule of 72 (approx.) | Doubling time ≈ 72/R under compounding | Quick estimate | Approximate only; do not use for exact answers |

**C. Three Mandatory Solved Examples**

**Easy**
Simple interest on ₹5000 at 8% per annum for 3 years? (a) 1000 (b) 1100 (c) 1200 (d) 1500.
1. SI = 5000 × 8 × 3 / 100 = **1200**. Answer: **(c)**.
- Fastest method: 8% of 5000 = 400; × 3 = 1200. Time: **10 s**.
- Common mistake: reporting the amount (6200) instead of the interest.

**Medium**
Compound interest on ₹8000 at 10% per annum for 2 years? (a) 1600 (b) 1680 (c) 1700 (d) 1800.
1. Effective rate for 2 years = 10 + 10 + 1 = 21%.
2. CI = 21% of 8000 = **1680**. Answer: **(b)**.
- Fastest method: effective-rate stacking. Time: **20 s**.
- Common mistake: answering 1600 (the SI).

**Tough**
A sum compounded annually becomes ₹7200 in 2 years and ₹8640 in 3 years. What is the principal? (a) 4000 (b) 5000 (c) 6000 (d) 6400.
1. Growth in the third year = 8640 − 7200 = 1440 on 7200 → 20%.
2. Principal × 1.2² = 7200 → Principal = 7200 / 1.44 = **5000**. Answer: **(b)**.
- Fastest method: consecutive-amount ratio, then work backwards. Time: **40 s**.
- Common mistake: treating 1440 as the interest for one year on the original principal.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) A sum doubles in 8 years at SI. Rate? (a) 10% (b) 12% (c) 12.5% (d) 15%. **Answer (c).** 100/8.
2. (Easy) Difference between CI and SI on ₹5000 at 10% for 2 years? (a) 25 (b) 50 (c) 75 (d) 100. **Answer (b).** 5000 × 0.01.
3. (Medium) CI on ₹6000 at 5% for 2 years? (a) 600 (b) 615 (c) 625 (d) 650. **Answer (b).** 10.25% of 6000.
4. (Medium) ₹10000 at 20% per annum compounded half-yearly for 1 year. CI? (a) 2000 (b) 2100 (c) 2200 (d) 2400. **Answer (b).** 1.1² = 1.21; 12100 − 10000.
5. (Tough) ₹10000 is lent partly at 6% and partly at 10% SI. Total interest for 1 year is ₹800. Amount lent at 6%? (a) 4000 (b) 5000 (c) 6000 (d) 7000. **Answer (b).** Mean rate 8% is midway between 6% and 10% → equal parts (alligation 1:1).

**E. Exam-Oriented Application**
Interest questions are standard in government exam quant sections. I could not verify AAI-specific frequency. Priority: effective-rate stacking and the CI − SI difference formulas.

**F. Quick Revision**
- Formulas: SI = PRT/100; A = P(1 + R/100)ⁿ; CI − SI = P(R/100)² for 2 years.
- Time-savers: effective rates (10% → 21%), consecutive-amount ratio.
- Reminders: half-yearly → halve rate, double time.
- Mistakes: confusing amount with interest; using the SI formula for CI.

---

## 6. Ratio & Proportion

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Proportion | a : b = c : d ⇒ ad = bc |
| Mean proportional | √(ab) |
| Third proportional to a, b | b²/a |
| Fourth proportional to a, b, c | bc/a |
| Componendo–dividendo | If a/b = c/d then (a+b)/(a−b) = (c+d)/(c−d) |
| Compound ratio | (a:b) × (c:d) = ac : bd |
| Combining ratios | Make the common term equal (a:b and b:c → a:b:c) |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Common-term LCM | Scale the shared term to its LCM | Merging a:b and b:c | Needs small numbers or a clean LCM |
| Unit / part method | Treat each part as k; sum of parts = total | Dividing amounts | Total must be divisible by sum of parts |
| Divisibility check on options | Total must be a multiple of sum of ratio parts | Eliminating options | Not conclusive alone |
| Multiplier on ratio | Apply percentage change to each ratio term separately | Salary/increment questions | Keep terms unsimplified until the end |
| Age-ratio algebra | (ratio × x ± years) set equal | Age problems | Set up one variable only |

**C. Three Mandatory Solved Examples**

**Easy**
Divide ₹2100 in the ratio 2 : 3 : 5. The largest share is: (a) 840 (b) 1050 (c) 1260 (d) 1500.
1. Parts = 10; each part = 210.
2. Largest = 5 × 210 = **1050**. Answer: **(b)**.
- Fastest method: half of 2100 (5/10). Time: **10 s**.
- Common mistake: forgetting to add the parts first.

**Medium**
a : b = 2 : 3 and b : c = 4 : 5. If a + b + c = 175, find b. (a) 50 (b) 60 (c) 70 (d) 75.
1. Make b equal: LCM(3, 4) = 12 → a : b = 8 : 12; b : c = 12 : 15.
2. a : b : c = 8 : 12 : 15; sum = 35 parts; each part = 175/35 = 5.
3. b = 12 × 5 = **60**. Answer: **(b)**.
- Fastest method: common-term LCM. Time: **35 s**.
- Common mistake: writing a : b : c = 2 : 3 : 5.

**Tough**
Salaries of A, B, C are in the ratio 2 : 3 : 5. After increments of 15%, 10% and 20%, the new ratio is: (a) 23:33:60 (b) 21:30:55 (c) 23:30:60 (d) 22:33:60.
1. Multiply: A = 2 × 1.15 = 2.3; B = 3 × 1.10 = 3.3; C = 5 × 1.20 = 6.0.
2. Ratio = 2.3 : 3.3 : 6 → ×10 → **23 : 33 : 60**. Answer: **(a)**.
- Fastest method: multiplier on each term. Time: **40 s**.
- Common mistake: applying one average increment to all.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) Mean proportional between 4 and 25? (a) 8 (b) 10 (c) 12 (d) 14. **Answer (b).** √100.
2. (Easy) Fourth proportional to 3, 12, 5? (a) 15 (b) 18 (c) 20 (d) 24. **Answer (c).** 12 × 5 / 3.
3. (Medium) If x : y = 3 : 4, then (2x + y) : (x + 2y) = ? (a) 9:10 (b) 10:11 (c) 11:12 (d) 8:9. **Answer (b).** (6+4):(3+8).
4. (Medium) Two numbers are in ratio 3 : 4. If 6 is added to each, the ratio becomes 5 : 6. The larger number is: (a) 9 (b) 12 (c) 15 (d) 18. **Answer (b).** (3x+6)/(4x+6) = 5/6 → 18x + 36 = 20x + 30 → x = 3; larger = 12.
5. (Tough) ₹1170 is divided among A, B, C. A gets half of B's share; B gets one-third of C's. A's share? (a) 100 (b) 120 (c) 130 (d) 150. **Answer (c).** A : B : C = 1 : 2 : 6; 9 parts; 1170/9 = 130.

**E. Exam-Oriented Application**
Ratio is a base skill for Partnership, Mixture, Time & Work and DI. General exam advice: master the common-term method. AAI-specific frequency not verified.

**F. Quick Revision**
- Formulas: ad = bc; mean proportional √(ab); fourth proportional bc/a.
- Time-savers: LCM on the common term; multiplier method.
- Reminders: sum of parts = total.
- Mistakes: adding ratios of different bases; not equalising the shared term.

---

## 7. Average

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Average | Sum / number of items |
| Average of first n natural numbers | (n + 1)/2 |
| Consecutive numbers (odd count) | Middle term = average |
| Adding or replacing | Change in total = change in average × number of items |
| Weighted average | (n₁a₁ + n₂a₂)/(n₁ + n₂) |
| Average speed (equal distances) | 2xy/(x + y) |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Assumed-mean deviation | Pick a convenient base, average the deviations | Large numbers close together | Choose base near the middle |
| Replacement rule | New item = old item + (avg change × n) | One member replaced | n is the group size, not n ± 1 |
| Alligation for averages | Two group averages → ratio of group sizes | Mixed groups | Two groups at a time |
| Middle term | Average of AP = middle term | Consecutive numbers | Needs equal spacing |
| Overlap counting | Sum of two groups counts shared item twice | "Sixth result" type problems | Identify the shared item first |

**C. Three Mandatory Solved Examples**

**Easy**
Average of the first 10 even numbers? (a) 10 (b) 11 (c) 12 (d) 20.
1. Sum = 10 × 11 = 110; average = **11**. Answer: **(b)**.
- Fastest method: average of AP = (first + last)/2 = (2 + 20)/2 = 11. Time: **10 s**.
- Common mistake: answering 10 by averaging the count of numbers instead of their values.

**Medium**
The average of 5 numbers is 27. If one number is excluded, the average becomes 25. The excluded number is: (a) 31 (b) 33 (c) 35 (d) 37.
1. Total of 5 = 135; total of 4 = 100.
2. Excluded = 135 − 100 = **35**. Answer: **(c)**.
- Fastest method: change in total (each of 4 items fell by 2 → 8; excluded = 27 + 8 = 35). Time: **20 s**.
- Common mistake: using 27 − 25 = 2 as the answer.

**Tough**
The average of 11 results is 50. The average of the first six is 49 and of the last six is 52. The sixth result is: (a) 52 (b) 54 (c) 56 (d) 58.
1. First six total = 294; last six total = 312; sum = 606.
2. All 11 total = 550; the sixth is counted twice in 606.
3. Sixth = 606 − 550 = **56**. Answer: **(c)**.
- Fastest method: overlap counting. Time: **45 s**.
- Common mistake: forgetting the sixth result is in both groups.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) Average of 7 consecutive numbers is 20. The largest is: (a) 22 (b) 23 (c) 24 (d) 26. **Answer (b).** Middle 20; largest = 20 + 3.
2. (Easy) Average speed if a car goes 60 km/h one way and returns at 40 km/h? (a) 48 (b) 50 (c) 52 (d) 54. **Answer (a).** 2 × 60 × 40 / 100 = 48.
3. (Medium) A batsman scores 50 in his 12th innings and his average rises by 2. New average? (a) 26 (b) 27 (c) 28 (d) 30. **Answer (c).** 11x + 50 = 12(x + 2) → x = 26; new = 28.
4. (Medium) Class A: 40 students, average 60. Class B: 60 students, average 70. Combined average? (a) 64 (b) 65 (c) 66 (d) 67. **Answer (c).** (2400 + 4200)/100.
5. (Tough) Average weight of 8 persons rises by 2.5 kg when a person of 65 kg is replaced. New person's weight? (a) 80 (b) 82.5 (c) 85 (d) 90. **Answer (c).** 65 + 8 × 2.5.

**E. Exam-Oriented Application**
Average connects to DI, Mixture and Time-Speed-Distance. General exam advice: learn replacement and weighted-average methods. AAI-specific frequency not verified.

**F. Quick Revision**
- Formulas: Sum = avg × n; replacement: new = old + n × change; speed 2xy/(x + y).
- Time-savers: assumed mean; alligation on groups.
- Reminders: use totals, not averages, when combining.
- Mistakes: using n + 1 when one is replaced; plain average of speeds.

---

## 8. Time & Work

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Work rate | 1/days; total work = rate × time |
| Together | If A takes x days and B takes y, together xy/(x + y) |
| Efficiency | Inversely proportional to days |
| Man-days | M₁D₁H₁/W₁ = M₂D₂H₂/W₂ |
| Pipes | Inlet is positive work, outlet negative |
| Wages | Divided in ratio of work done |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| LCM (units) method | Take LCM of days as total work; each person's efficiency = LCM/days | Most multi-person problems | Needs reasonably small LCM |
| Efficiency ratio | Ratio of efficiency = inverse of days | Comparison questions | Same work only |
| Cycle method | For alternate-day work, compute work per cycle | Alternating workers | Check the last partial cycle |
| Negative efficiency | Leak or outlet = negative units | Pipes and cisterns | Total must stay positive |
| Left-early algebra | Leaver works (T − k) days | Someone leaves before the end | Define T as total elapsed time |

**C. Three Mandatory Solved Examples**

**Easy**
A can finish a job in 10 days and B in 15 days. Together? (a) 5 (b) 6 (c) 8 (d) 12.
1. LCM 30: A = 3 units/day, B = 2 units/day → 5/day.
2. 30/5 = **6 days**. Answer: **(b)**.
- Fastest method: LCM units. Time: **15 s**.
- Common mistake: averaging 10 and 15.

**Medium**
A and B can do a job in 12 days, B and C in 15 days, A and C in 20 days. All three together? (a) 8 (b) 9 (c) 10 (d) 12.
1. LCM 60: A + B = 5, B + C = 4, A + C = 3 units/day.
2. 2(A + B + C) = 12 → A + B + C = 6 units/day.
3. 60/6 = **10 days**. Answer: **(c)**.
- Fastest method: LCM units, add the three pair-rates and halve. Time: **40 s**.
- Common mistake: forgetting to divide the pair-sum by 2.

**Tough**
A can complete a job in 20 days and B in 30 days. They work on alternate days, beginning with A. Total time? (a) 22 (b) 24 (c) 25 (d) 26.
1. LCM 60: A = 3, B = 2 units/day. A two-day cycle = 5 units.
2. 60 ÷ 5 = 12 cycles exactly → 24 days. Answer: **(b)**.
- Fastest method: cycle method. Time: **50 s**.
- Common mistake: dividing 60 by the daily average and getting a fractional answer.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) 12 men finish a job in 20 days. How many men are needed to finish in 15 days? (a) 14 (b) 15 (c) 16 (d) 18. **Answer (c).** 12 × 20/15.
2. (Easy) A takes 20 days, B takes 30 days. Together? (a) 10 (b) 12 (c) 15 (d) 25. **Answer (b).** LCM 60: 3 + 2 = 5; 60/5.
3. (Medium) A is twice as efficient as B. Together they take 18 days. A alone? (a) 24 (b) 27 (c) 30 (d) 36. **Answer (b).** B = 1, A = 2; total = 54; A alone = 54/2.
4. (Medium) A does 1/3 of a job in 5 days; B does 2/5 of it in 10 days. Together? (a) 9⅜ days (b) 10 days (c) 8¾ days (d) 12 days. **Answer (a).** A = 15 days, B = 25 days; LCM 75: 5 + 3 = 8; 75/8 = 9⅜.
5. (Tough) A (12 days) and B (24 days) start a job. A leaves 3 days before it is done. Total time? (a) 8 (b) 9 (c) 10 (d) 12. **Answer (c).** LCM 24: A = 2, B = 1. T + 2(T − 3) = 24 → T = 10.

**E. Exam-Oriented Application**
Time & Work is a standard topic across Central Government exams. I could not verify AAI-specific frequency. Priority: LCM units and alternate-day problems.

**F. Quick Revision**
- Formulas: together = xy/(x + y); M₁D₁/W₁ = M₂D₂/W₂.
- Time-savers: LCM total work; efficiency ratios.
- Reminders: outlets and leaks are negative.
- Mistakes: averaging days; wrong LCM.

---
## 9. Time, Speed & Distance

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Basic | Speed = Distance / Time |
| Unit conversion | km/h → m/s: × 5/18; m/s → km/h: × 18/5 |
| Average speed | Total distance / total time; equal distances: 2xy/(x + y) |
| Fixed distance | Speed and time are inversely proportional |
| Relative speed | Same direction: difference; opposite: sum |
| Train crossing pole / man | Time = length / speed |
| Train crossing platform / train | Time = (sum of lengths) / relative speed |
| Boats | Downstream = u + v; upstream = u − v; still water = (down + up)/2; stream = (down − up)/2 |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| 5/18 factor | 72 km/h = 20 m/s (72 × 5/18) | Train problems with mixed units | Convert before using lengths in metres |
| Inverse ratio of time | Speed ratio a:b → time ratio b:a | "Late by / early by" questions | Same distance only |
| Unit-difference method | Late/early time = difference of ratio units | Usual-time questions | Needs a clear ratio |
| Relative-speed shortcut | Sum or difference, then divide combined length | Two trains | Check direction first |
| Boats: ± stream | Convert up/down to still and stream speeds | Boat problems | Assumes constant stream |

**C. Three Mandatory Solved Examples**

**Easy**
A train at 72 km/h crosses a pole in 9 seconds. Its length? (a) 120 m (b) 150 m (c) 180 m (d) 200 m.
1. 72 km/h = 20 m/s.
2. Length = 20 × 9 = **180 m**. Answer: **(c)**.
- Fastest method: 72 → 20 m/s. Time: **15 s**.
- Common mistake: multiplying 72 × 9 without converting units.

**Medium**
A man rows 24 km downstream in 2 hours and 24 km upstream in 3 hours. Speed in still water? (a) 8 (b) 9 (c) 10 (d) 12 km/h.
1. Downstream = 12 km/h; upstream = 8 km/h.
2. Still water = (12 + 8)/2 = **10 km/h** (stream = 2 km/h). Answer: **(c)**.
- Fastest method: average of down and up. Time: **25 s**.
- Common mistake: averaging the two times.

**Tough**
A 200 m train at 72 km/h overtakes a 160 m train, moving in the same direction, in 36 seconds. Speed of the slower train? (a) 30 (b) 36 (c) 40 (d) 45 km/h.
1. Total length crossed = 360 m; relative speed = 360/36 = 10 m/s = 36 km/h.
2. Slower train = 72 − 36 = **36 km/h**. Answer: **(b)**.
- Fastest method: relative speed, then convert once at the end. Time: **45 s**.
- Common mistake: using only the length of one train.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) 90 km/h in m/s? (a) 20 (b) 22.5 (c) 25 (d) 30. **Answer (c).** 90 × 5/18.
2. (Easy) A boat goes 36 km downstream; still water 12 km/h, stream 3 km/h. Time? (a) 2 h (b) 2.4 h (c) 3 h (d) 4 h. **Answer (b).** 36/15.
3. (Medium) A 300 m train crosses a 200 m platform in 25 seconds. Speed? (a) 60 (b) 66 (c) 72 (d) 80 km/h. **Answer (c).** 500/25 = 20 m/s = 72 km/h.
4. (Medium) Walking at 6/7 of his usual speed, a man is 12 minutes late. Usual time? (a) 72 min (b) 80 min (c) 84 min (d) 96 min. **Answer (a).** Speed ratio new : usual = 6 : 7, so time ratio new : usual = 7 : 6. The difference of 1 unit = 12 min, so usual time = 6 units = 72 min.
5. (Tough) A starts at 8:00 am at 40 km/h; B starts from the same place at 9:00 am at 60 km/h in the same direction. When does B overtake A? (a) 10:00 (b) 10:30 (c) 11:00 (d) 11:30. **Answer (c).** Lead = 40 km; relative speed 20 km/h → 2 hours after 9:00.

**E. Exam-Oriented Application**
Train, boat and relative-speed questions are staple government-exam topics. AAI-specific frequency is not verified. Priority: unit conversion, relative speed, inverse-ratio late/early problems.

**F. Quick Revision**
- Formulas: 5/18 factor; 2xy/(x + y); relative speed; boat down/up.
- Time-savers: inverse ratio of time; convert once.
- Reminders: lengths in metres, speeds in m/s together.
- Mistakes: skipping conversion; adding lengths for pole crossing.

---

## 10. Partnership

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Profit sharing | Profit ratio = (Capital × Time) ratio |
| Same time | Ratio of capitals |
| Same capital | Ratio of times |
| Working partner | Salary or commission first, balance in capital ratio |
| Capital changes | Sum capital × months for each period |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Capital × months units | Convert each partner to one number | All partnership questions | Use the same time unit throughout |
| Cancel common factors | Divide capital × time numbers by a common factor | Large numbers | Do it consistently for all partners |
| Salary first | Deduct commission/salary, then split the remainder | Working partner | Salary is on total profit unless stated |
| Withdrawal split | Calculate each period separately | Capital withdrawn or added | Track months carefully |
| Option check by ratio | Test whether shares match the capital:time ratio | MCQ elimination | Needs the ratio first |

**C. Three Mandatory Solved Examples**

**Easy**
A invests ₹3000 and B ₹5000 for the same period. Profit is ₹4000. A's share? (a) 1200 (b) 1500 (c) 2000 (d) 2500.
1. Ratio 3 : 5; A = 3/8 × 4000 = **1500**. Answer: **(b)**.
- Fastest method: 4000/8 = 500; × 3 = 1500. Time: **10 s**.
- Common mistake: dividing the profit equally.

**Medium**
A starts with ₹20000. B joins after 4 months with ₹30000. Yearly profit ₹18000. B's share? (a) 6000 (b) 8000 (c) 9000 (d) 10000.
1. A = 20000 × 12 = 240000; B = 30000 × 8 = 240000.
2. Ratio 1 : 1; B = **9000**. Answer: **(c)**.
- Fastest method: capital × months. Time: **25 s**.
- Common mistake: using 4 months for B instead of 8.

**Tough**
A and B invest ₹30000 and ₹50000. A, the working partner, gets 10% of the profit as salary and the rest is shared in the capital ratio. Total profit ₹20000. A's total? (a) 8000 (b) 8750 (c) 9000 (d) 9250.
1. Salary = 10% of 20000 = 2000. Balance = 18000.
2. Capital ratio 3 : 5; each part = 18000/8 = 2250; A's share = 6750.
3. A's total = 2000 + 6750 = **8750**. Answer: **(b)**.
- Fastest method: salary first, then ratio. Time: **50 s**.
- Common mistake: applying 10% after splitting the profit.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) A : B : C capitals = 2 : 3 : 5, profit ₹5000. C's share? (a) 1500 (b) 2000 (c) 2500 (d) 3000. **Answer (c).** 5/10 × 5000.
2. (Easy) A invests ₹5000 for 8 months, B ₹8000 for 6 months. Profit ₹5500. A's share? (a) 2000 (b) 2500 (c) 3000 (d) 3500. **Answer (b).** 40000 : 48000 = 5 : 6; 5/11 × 5500 = 2500.
3. (Medium) A invests ₹15000 for 12 months; B joins after 5 months with ₹24000. Profit ₹5800. B's share? (a) 2600 (b) 2800 (c) 3000 (d) 3200. **Answer (b).** A = 180, B = 24 × 7 = 168 → 15 : 14; B = 14/29 × 5800 = 2800.
4. (Medium) A invests ₹8000, B ₹12000. After 4 months A withdraws ₹2000. Profit ₹7000 at year-end. A's share? (a) 2000 (b) 2500 (c) 3000 (d) 3500. **Answer (b).** A = 8000×4 + 6000×8 = 80000; B = 144000; 5 : 9; A = 5/14 × 7000 = 2500.
5. (Tough) A : B : C capitals = 2 : 3 : 4 for 4 : 3 : 2 months. Profit ₹10000. B's share? (a) 3200 (b) 3600 (c) 4000 (d) 4200. **Answer (b).** 8 : 9 : 8 = 25 parts; B = 9/25 × 10000 = 3600.

**E. Exam-Oriented Application**
Partnership is a short, formula-light topic; the capital × time idea is the whole trick. AAI-specific frequency not verified. General priority: mastering the withdrawal and salary variants.

**F. Quick Revision**
- Formulas: profit ∝ capital × time; salary first.
- Time-savers: reduce numbers before multiplying.
- Reminders: join/leave months count separately.
- Mistakes: wrong months; ignoring salary.

---

## 11. Mixture & Alligation

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Alligation rule | Cheaper qty : Dearer qty = (d − m) : (m − c), where c = cheaper, d = dearer, m = mean |
| Weighted mean | m = (q₁c₁ + q₂c₂)/(q₁ + q₂) |
| Replacement | Pure left = initial × (1 − x/V)ⁿ (x removed each time, V total volume, n times) |
| Concentration | Amount of solute / total volume |
| Dishonest dealer | Gain % = water added / original quantity × 100 (selling at cost price) |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Cross-difference diagram | Subtract mean from the dearer, and cheaper from the mean, cross-wise | Two-ingredient mixes | Works for two ingredients at a time |
| Alligation beyond price | Works for averages, percentages, profit % | Any weighted-mean situation | Same base required |
| Replacement formula | Remaining pure = initial × (1 − x/V)ⁿ | Repeated replacement | Equal removal each time |
| Percentage-to-ratio | Treat concentrations as prices | Acid, milk, solution questions | Must use consistent units |
| Same-side difference warning | Cross differences only | Avoid sign errors | None |

**C. Three Mandatory Solved Examples**

**Easy**
In what ratio should tea at ₹40/kg and ₹60/kg be mixed to get a mixture at ₹54/kg? (a) 2:3 (b) 3:7 (c) 7:3 (d) 3:2.
1. c = 40, d = 60, m = 54.
2. Cheaper : Dearer = (60 − 54) : (54 − 40) = 6 : 14 = **3 : 7**. Answer: **(b)**.
- Fastest method: cross-difference. Time: **15 s**.
- Common mistake: reversing the ratio.

**Medium**
How many litres of 60% alcohol must be added to 20 litres of 30% alcohol to get a 40% solution? (a) 5 (b) 8 (c) 10 (d) 12.
1. Cheaper (30%) : Dearer (60%) = (60 − 40) : (40 − 30) = 20 : 10 = 2 : 1.
2. 20 L of cheaper = 2 parts → 1 part = 10 L → dearer = **10 L**. Answer: **(c)**.
- Fastest method: alligation. Check: 6 + 6 = 12 in 30 L → 40%. ✓ Time: **35 s**.
- Common mistake: reading 2:1 as dearer:cheaper.

**Tough**
A vessel holds 64 L of pure milk. 16 L is removed and replaced with water; the process is repeated once more. The ratio of milk to water is: (a) 9:7 (b) 3:1 (c) 7:9 (d) 5:3.
1. Fraction removed = 16/64 = 1/4; milk left = 64 × (3/4)² = 36 L.
2. Water = 64 − 36 = 28 L.
3. Ratio = 36 : 28 = **9 : 7**. Answer: **(a)**.
- Fastest method: replacement formula. Time: **40 s**.
- Common mistake: subtracting 16 L of milk each time (ignoring that the second removal also takes some water).

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) Tea at ₹60 and ₹80 mixed in equal quantities. Mean price? (a) 65 (b) 70 (c) 72 (d) 75. **Answer (b).** Average.
2. (Easy) In what ratio must 18% and 28% solutions be mixed to get 24%? (a) 2:3 (b) 3:2 (c) 4:3 (d) 1:2. **Answer (a).** (28 − 24) : (24 − 18) = 4 : 6 = 2 : 3 (18% : 28%).
3. (Medium) How much water must be added to 10 L of 40% acid to get 25%? (a) 5 L (b) 6 L (c) 8 L (d) 10 L. **Answer (b).** 4/(10 + x) = 0.25 → x = 6.
4. (Medium) A 36 L mixture has milk : water = 5 : 1. 12 L is removed and replaced with water. New ratio? (a) 5:3 (b) 5:4 (c) 3:2 (d) 2:1. **Answer (b).** Milk 30, water 6. Removed: milk 10, water 2 → milk 20, water 4. Add 12 water → 16. Ratio 20 : 16 = 5 : 4.
5. (Tough) A merchant sells part of 100 kg sugar at 7% profit and the rest at 17%, with an overall profit of 10%. Quantity sold at 17%? (a) 20 kg (b) 25 kg (c) 30 kg (d) 40 kg. **Answer (c).** (17 − 10) : (10 − 7) = 7 : 3 for 7% part : 17% part; 17% part = 3/10 × 100 = 30 kg.

**E. Exam-Oriented Application**
Alligation is a widely taught shortcut that also works for averages and profit-percentage questions. AAI-specific frequency is not verified. General priority: cross-diagram and replacement formula.

**F. Quick Revision**
- Formulas: cheaper : dearer = (d − m) : (m − c); remaining = initial × (1 − x/V)ⁿ.
- Time-savers: cross-diagram; treat percentages like prices.
- Reminders: ratio is of the cheaper to dearer quantities.
- Mistakes: reversing the ratio; applying alligation to three ingredients at once.

---

## 12. Mensuration

**A. Important Formulas and Concepts**

| Shape | Formulas |
|---|---|
| Rectangle | Area = lb; perimeter = 2(l + b); diagonal = √(l² + b²) |
| Triangle | ½ × base × height; Heron: √(s(s − a)(s − b)(s − c)); equilateral: (√3/4)a² |
| Circle | Area πr²; circumference 2πr; sector = (θ/360) × πr² |
| Cuboid | Volume lbh; total surface 2(lb + bh + hl); diagonal √(l² + b² + h²) |
| Cube | Volume a³; total surface 6a² |
| Cylinder | Volume πr²h; curved surface 2πrh; total 2πr(r + h) |
| Cone | Volume ⅓πr²h; slant l = √(r² + h²); curved surface πrl |
| Sphere | Volume (4/3)πr³; surface 4πr² |
| Hemisphere | Volume (2/3)πr³; curved surface 2πr² |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Use 22/7 when r is a multiple of 7 | Cancels cleanly | Circle, cylinder, sphere | If r is not a multiple of 7, 3.14 may be given |
| Volume conservation | Melting/recasting: volume stays the same | Recast problems | Ignore wastage unless stated |
| Scaling | Area ∝ (length)²; volume ∝ (length)³ | Percentage-change problems | Same shape |
| Percentage change in area | x% and y% changes → x + y + xy/100 | Length/breadth changes | Signs matter |
| Pythagorean triples | 3-4-5, 5-12-13, 8-15-17, 7-24-25 | Right triangle and diagonal | Only for integer cases |

**C. Three Mandatory Solved Examples**

**Easy**
Area of a circle of radius 14 cm? (a) 154 (b) 308 (c) 616 (d) 1232 cm².
1. Area = (22/7) × 14 × 14 = 22 × 2 × 14 = **616**. Answer: **(c)**.
- Fastest method: cancel 7 against 14. Time: **15 s**.
- Common mistake: using 2πr (circumference = 88).

**Medium**
A rectangle's length is increased by 20% and breadth decreased by 10%. Change in area? (a) +8% (b) +10% (c) +12% (d) +18%.
1. Multiplier = 1.2 × 0.9 = 1.08.
2. Area changes by **+8%**. Answer: **(a)**.
- Fastest method: 20 − 10 − 200/100 = 8. Time: **15 s**.
- Common mistake: adding 20 − 10 = 10%.

**Tough**
A solid metal sphere of radius 6 cm is melted and recast into cones of radius 3 cm and height 4 cm. How many cones? (a) 18 (b) 24 (c) 36 (d) 48.
1. Sphere volume = (4/3)π × 216 = 288π.
2. Cone volume = ⅓π × 9 × 4 = 12π.
3. Number = 288π / 12π = **24**. Answer: **(b)**.
- Fastest method: volume ratio with π cancelling. Time: **40 s**.
- Common mistake: forgetting the ⅓ for the cone.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) Perimeter of a square with diagonal 10√2 cm? (a) 20 (b) 30 (c) 40 (d) 50 cm. **Answer (c).** Side = 10.
2. (Easy) Curved surface area of a cylinder with r = 7 cm and h = 10 cm? (a) 220 (b) 330 (c) 440 (d) 660 cm². **Answer (c).** 2 × 22/7 × 7 × 10.
3. (Medium) Area of a triangle with sides 13, 14, 15 cm? (a) 72 (b) 84 (c) 90 (d) 96 cm². **Answer (b).** s = 21; √(21 × 8 × 7 × 6) = 84.
4. (Medium) Radius of a circle increases by 10%. Increase in area? (a) 10% (b) 20% (c) 21% (d) 22%. **Answer (c).** 1.1² = 1.21.
5. (Tough) A hemispherical bowl of radius 21 cm full of water is emptied into a cylinder of radius 21 cm. Height of water? (a) 7 cm (b) 10.5 cm (c) 14 cm (d) 21 cm. **Answer (c).** (2/3)πr³ = πr²h → h = 2r/3 = 14.

**E. Exam-Oriented Application**
Mensuration questions are mostly formula recall plus careful substitution. General-exam advice: memorise the volume/surface formulas and use scaling shortcuts. AAI-specific frequency is not verified.

**F. Quick Revision**
- Formulas: cone ⅓πr²h; sphere (4/3)πr³; hemisphere curved surface 2πr².
- Time-savers: 22/7 cancellation; volume conservation; scaling.
- Reminders: total vs curved surface; slant height for cones.
- Mistakes: forgetting ⅓; using diameter as radius.

---
## 13. Data Interpretation

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Percentage change | (New − Old) / Old × 100 |
| Share / percentage of total | Part / Total × 100 |
| Pie chart | Angle = percentage × 3.6; value = (angle/360) × total |
| Ratio | Compare two data points with the same units |
| Average | Total / number of items |
| Percentage-point difference | Difference of two percentages (not a percent change) |
| Reading charts | Check axis labels, units (thousands, lakhs, crores) and the base year |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Fraction comparison by cross-multiplication | Compare a/b and c/d via ad vs bc | Which is greater, which year is highest | Avoid when the gap is tiny and values are huge; then compute |
| Approximation | Round to 2 significant figures when options are far apart | "Approximately" and wide-gap options | Not for close options |
| Work with ratios, not totals | Compare shares, not absolute values, in pie charts | Pie-chart comparisons | Totals must be the same, else convert |
| Totals-ratio shortcut | % more = (Total₂ − Total₁)/Total₁ | Comparing sums over years | Don't recompute averages separately |
| Read the question first | Decide which rows/columns matter before touching the data | All DI sets | None |
| Unit trap check | Verify thousands vs lakhs | Every set | None |

**C. Three Mandatory Solved Examples**

**Easy**
Sales (₹ lakh): 2021 = 120, 2022 = 150, 2023 = 180. Percentage increase from 2021 to 2022? (a) 20% (b) 25% (c) 30% (d) 33⅓%.
1. Increase = 30; 30/120 = **25%**. Answer: **(b)**.
- Fastest method: 30/120 = 1/4. Time: **10 s**.
- Common mistake: dividing by the new value (30/150 = 20%).

**Medium**
A company's total expenditure is ₹7.2 lakh, shown in a pie chart: Salary 108°, Rent 72°, Raw material 90°, Others 90°. The difference between salary and rent expenditure? (a) ₹36,000 (b) ₹72,000 (c) ₹1,08,000 (d) ₹1,44,000.
1. Check: 108 + 72 + 90 + 90 = 360°. ✓
2. Angle difference = 36°; 36/360 = 1/10 of 7.2 lakh = **₹72,000**. Answer: **(b)**.
- Fastest method: subtract angles first, then convert once. Time: **30 s**.
- Common mistake: converting each to rupees separately (slower, more error-prone).

**Tough**
Production (thousand units):

| Year | 2019 | 2020 | 2021 | 2022 | 2023 |
|---|---|---|---|---|---|
| A | 40 | 55 | 66 | 80 | 92 |
| B | 50 | 60 | 72 | 90 | 100 |

B's average annual production over 2019–2023 is what percent more than A's? (a) 10.5% (b) 11.7% (c) 12.4% (d) 13.2%.
1. Total A = 40 + 55 + 66 + 80 + 92 = 333. Total B = 50 + 60 + 72 + 90 + 100 = 372.
2. Averages share the same divisor (5), so compare totals: (372 − 333)/333 = 39/333 = 13/111 ≈ **11.7%**. Answer: **(b)**.
- Fastest method: totals-ratio shortcut; no need to divide by 5. Time: **60 s** (honest estimate: the two additions dominate).
- Common mistake: dividing by 372 instead of 333 (the base is A).

**D. Additional Practice Questions (all ORIGINAL)**

Use this table for questions 1–5:

| Branch | Enrolled | Passed |
|---|---|---|
| P | 250 | 200 |
| Q | 300 | 210 |
| R | 400 | 340 |
| S | 150 | 135 |

1. (Easy) Total number who passed? (a) 855 (b) 875 (c) 885 (d) 895. **Answer (c).** 200 + 210 + 340 + 135.
2. (Easy) Pass percentage of branch R? (a) 80% (b) 82.5% (c) 85% (d) 87.5%. **Answer (c).** 340/400.
3. (Medium) Which branch has the highest pass percentage? (a) P (b) Q (c) R (d) S. **Answer (d).** P 80%, Q 70%, R 85%, S 90%.
4. (Medium) Overall pass percentage (approx.)? (a) 78% (b) 80.5% (c) 82% (d) 84%. **Answer (b).** 885/1100 = 80.45%.
5. (Tough) R's enrollment rises 10% and its pass percentage rises by 5 percentage points. How many pass in R? (a) 374 (b) 385 (c) 396 (d) 410. **Answer (c).** Enrolled 440; pass 90%; 440 × 0.9 = 396.

**E. Exam-Oriented Application**
DI rewards calculation discipline: reading units, picking the cheapest route (ratios, approximations). I could not verify whether AAI JE (Operations) tests DI explicitly; one third-party page lists DI under Quantitative Aptitude. Treat it as general government-exam practice.

**F. Quick Revision**
- Formulas: % change = change/old; pie angle = % × 3.6.
- Time-savers: cross-multiplication, approximation, totals-ratio.
- Reminders: units and base year.
- Mistakes: wrong base; confusing percent with percentage points.

---

## 14. Data Sufficiency

**Answer format used in this guide** (exams vary in wording, so read the options carefully):
(a) Statement I alone is sufficient; II alone is not. (b) Statement II alone is sufficient; I alone is not. (c) Either statement alone is sufficient. (d) Both together are needed. (e) Even both together are not sufficient.

**A. Important Formulas and Concepts**

| Concept | Rule |
|---|---|
| Sufficient means | The statement gives one unique answer |
| Value questions | Need a single number; two possible values = not sufficient |
| Yes/No questions | A definite "Yes" or a definite "No" is sufficient; "sometimes yes, sometimes no" is not |
| Unknown count | You usually need as many independent equations as unknowns |
| Hidden information | Unit conversions, "consecutive", "integer" are real information |
| No assumptions | Use only what is given plus standard facts |

**B. Best Tricks, Tips and Shortcuts**

| Trick | How it works | When to use | Limitation |
|---|---|---|---|
| Evaluate each statement alone first | Forget the other statement while testing the first | Always | Prevents mixing information |
| Don't solve fully | Decide only whether a unique answer exists | Calculation-heavy questions | Be careful with non-linear conditions |
| AD / BCE grid | If I is sufficient → answer is (a) or (c); if I is not → (b), (d) or (e) | Fast elimination | Option lettering varies by exam |
| Test with special numbers | Try one value that fits and one that does not (zero, negatives, fractions) | Yes/No number questions | Cannot prove sufficiency, only insufficiency |
| Equations vs unknowns | Count independent equations | Algebra questions | Equations that restate each other count once |

**C. Three Mandatory Solved Examples**

**Easy**
What is the value of x? I. 2x + 3 = 11. II. x² = 16.
1. I: 2x = 8 → x = 4 (unique).
2. II: x = 4 or −4 (not unique).
3. Answer: **(a)**.
- Fastest method: check uniqueness. Time: **15 s**.
- Common mistake: forgetting the negative root.

**Medium**
What is the speed of the train? I. It crosses a pole in 12 seconds. II. Its length is 180 m.
1. I alone: time given but no length → not sufficient. II alone: length but no time → not sufficient.
2. Together: 180/12 = 15 m/s (= 54 km/h). Answer: **(d)**.
- Fastest method: check which variables are missing. Time: **25 s**.
- Common mistake: assuming a standard length.

**Tough**
Is the positive integer n divisible by 12? I. n is divisible by 6. II. n is divisible by 8.
1. I alone: n = 6 (No) or n = 12 (Yes) → not sufficient.
2. II alone: n = 8 (No) or n = 24 (Yes) → not sufficient.
3. Together: n is a multiple of LCM(6, 8) = 24, hence divisible by 12 → definite Yes. Answer: **(d)**.
- Fastest method: special numbers for each statement, then LCM for the combination. Time: **50 s**.
- Common mistake: concluding I and II both fail without checking the LCM.

**D. Additional Practice Questions (all ORIGINAL)**

1. (Easy) What is the area of a rectangle? I. Its perimeter is 28 m. II. Its length is 2 m more than its breadth. **Answer (d).** Together: b = 6, l = 8, area 48.
2. (Easy) What is the value of x/y (y ≠ 0)? I. x + y = 14. II. 3x = 4y. **Answer (b).** II gives x/y = 4/3; I alone cannot fix the ratio.
3. (Medium) What is the radius of a circle? I. Its circumference is 44 cm. II. Its area is 154 cm². **Answer (c).** Either gives r = 7.
4. (Medium) What is the average of a, b, c? I. a + b = 10. II. b + c = 12. **Answer (e).** Even together, a + b + c is not determined (a + c is unknown).
5. (Tough) Is x > y? I. x = 2y. II. y < 0. **Answer (d).** I alone: depends on the sign of y. II alone: nothing about x. Together: x = 2y < y (since y < 0) → definite No.

**E. Exam-Oriented Application**
Data Sufficiency is mostly logic with light arithmetic. I could not verify whether AAI JE (Operations) tests it; sources describe it as a feature of many competitive exams. Practise the five-option format and the Yes/No rule.

**F. Quick Revision**
- Rules: unique answer = sufficient; definite Yes or definite No = sufficient.
- Time-savers: test each statement alone; special numbers; equations vs unknowns.
- Reminders: unit conversions and "integer/positive" words are information.
- Mistakes: mixing statements early; assuming extra data.

---

## Final Consolidated Revision Summary

| Topic | Single best shortcut |
|---|---|
| 1. Number System | Cyclicity (mod 4); LCM + r; HCF of differences; (a+1)(b+1) factor counting |
| 2. Simplification | Fraction table; n5² rule; recognise identities; telescoping surds |
| 3. Percentage | Multiplier method; 100x/(100 + x); fraction-percent table |
| 4. Profit & Loss | CP = 100 base; x − d − xd/100; equal-SP loss p²/100 |
| 5. Interest | Effective rate (10% → 21%); CI − SI = P(R/100)² |
| 6. Ratio & Proportion | Equalise the common term; multiply by multiplier, not average |
| 7. Average | Use totals; replacement = old + n × change; overlap counting |
| 8. Time & Work | LCM units; alternate-day cycles; negative efficiency for leaks |
| 9. Time, Speed & Distance | 5/18 conversion; inverse ratio; relative speed |
| 10. Partnership | Capital × months; salary first |
| 11. Mixture & Alligation | Cross-differences; (1 − x/V)ⁿ |
| 12. Mensuration | 22/7 cancellation; volume conservation; scaling |
| 13. Data Interpretation | Compare ratios, not totals; read units; approximate |
| 14. Data Sufficiency | Test each statement alone; unique answer; special numbers |

**Final reminders:** read the question before the data, avoid full calculation when options are far apart, and move on from any question that exceeds about 90 seconds. If you only have a few days, spend the time on mixed timed practice rather than on new tricks.

---

## Sources

**Official / exam pattern**
- AAI JE (Operations) syllabus and weightage PDF, Advt. No. 12/2026/CHQ/DR-CBT. Official. Used for total marks, duration, Part A/B split and aviation content: https://www.aai.aero/sites/default/files/examdashboard-syllabus/JE%20(Operations)%20Syllabus.pdf
- Careers360 News, AAI Recruitment 2026 (vacancies, age limit): https://news.careers360.com/aai-recruitment-2026-notification-manager-junior-executive-389-vacancies-aero-salary
- Testbook, AAI Junior Executive (reports the 26 Oct 2026 date for JE Operations; confirm on aai.aero): https://testbook.com/aai-junior-executive
- Prashant Chaturvedi, JE Airport Operations exam pattern and preparation (unofficial; source of the "about 15 marks" claim): https://www.courses.prashantchaturvedi.com/blog/aai-junior-executive-airport-operations-exam-pattern and https://www.courses.prashantchaturvedi.com/blog/aai-je-operations-exam-preparation

**Tricks and formulas**
- SATHEE (IIT Kanpur), Number System quick revision (cyclicity, divisibility): https://sathee.iitk.ac.in/sathee-railway-exams/student-corner/quick-revision/mathematics/maths-number-system-tricks
- SpeedMath, Number System tricks (HCF, LCM, remainders): https://speedmath.in/blog/number-system-tricks-hcf-lcm-divisibility-remainders
- Cracku, Number System questions for SSC CGL (source of the style of the Number System easy example): https://cracku.in/blog/number-system-questions-for-ssc-cgl-pdf-3/
- SATHEE, Percentage guide: https://sathee.iitk.ac.in/sathee-ssc/student-corner/preparation-guide/quantitative-aptitude/percentage
- Oswaal Books, Percentage tricks: https://oswaalbooks.com/blogs/ssc/ssc-cgl-2026-percentage-problems-tricks-that-save-2-minutes
- Faceprep, Shortcut methods: https://faceprep.in/?p=355
- SpeedMath, Mixture and Alligation: https://speedmath.in/blog/mixture-alligation-tricks-competitive-exams
- Hitbullseye, Mixture and Alligation: https://www.hitbullseye.com/quant/mixture-and-alligation.php
- SATHEE, Alligation formulas: https://sathee.iitk.ac.in/sathee-bank-exam/bank-exams/ibps-po/study-materials/quantitative-aptitude/memory-based-questions/alligation-and-mixture/formulas
- Oliveboard, Mixture and Alligation short tricks: https://www.oliveboard.in/blog/mixture-alligation-short-tricks/
- Hitbullseye, Data Sufficiency approach: https://www.hitbullseye.com/data/Data-Sufficiency-Questions.php
- Physics Wallah, Data Sufficiency tips: https://www.pw.live/banking/exams/data-sufficiency-tips-and-tricks

**Not found:** I did not retrieve verifiable YouTube or Medium links, and no verified AAI previous-year papers. Please do not rely on any claim of topic-wise AAI weightage; use the official PDF and any official past paper you can obtain from aai.aero.
