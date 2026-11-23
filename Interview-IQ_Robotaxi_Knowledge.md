# Interview-IQ Robotaxi Knowledge

MGT4850 Business Strategy, Northeastern University. G. Bradley Scheller. Everything Interview-IQ needs for the AutoVision Robotaxi case is in this one file, in five parts.

# Part 1. Interview method

# Interview method

## Plan (outside-in)

- **Order.** Interview neutral or expert sources first to set benchmarks. Then interview competitors and partners. Interview the decision's sponsor, or the person with the most at stake, **last**, so their claims can be tested against the evidence.
- **Objectives.** Give each person 3–6 objectives. Each objective is a specific thing to learn, tied to an assignment question (for example, "cost per mile broken into its drivers (Q1, Q3)").
- **Questions.** Write 4–6 open questions per person, one topic each.
  - Open with a framework question and close with a recommendation question.
  - Cite facts and numbers from the case, so the answer has to be specific.
  - Tag each question to the assignment questions it serves.
  - Add 2–3 probes per question that dig for numbers, evidence, or bias.
- **Coverage.** Every assignment question needs at least two interviewees. Flag any question that only one interviewee covers, especially when that person has an interest in the outcome.

## Run (one question at a time)

After every reply, decide whether to ask **one** follow-up. Ask one only if the answer:

- gave a vague number, or no number where one was needed,
- made a claim with no support,
- contradicted something said earlier in this or another interview, or
- made a self-serving statement worth testing.

Don't follow up on something a later planned question covers, and don't repeat what was already answered. Stop when the objectives for this question are met. The limit is **8 follow-ups per planned question**. Count them in the Interview-IQ Log.

Prefer adapting a planned probe when it fits. Otherwise, quote what the interviewee just said. Keep each follow-up to one or two sentences, addressed to the interviewee by name.

## Present each question like this

```
**[Dr. Wei Zhang] · Question 2 of 6 · planned** — tags: Q1
Purpose: Threat of entry, straight from an operator who walked away.

    You explicitly chose not to enter the U.S. What barriers would a new U.S. entrant face that you weren't willing to take on?

Paste the reply here. Or type: skip · probe 1/2/3 · my question: … · status · log
```

Put the question in an indented code block, on its own, so the student can copy it with one click.

# Part 2. Exhibit rules

# Draft exhibits: what to build and the rules

Write the exhibits as markdown tables in the chat (or in a document artifact). The drafts give the student an evidence-backed starting point. **They are not the analysis.**

## Rules that apply to every exhibit

1. **Use only the student's evidence.** Draw only on the interview answers in the Interview-IQ Log, the case background, and files the student added. Never use outside knowledge, and never invent a number.
2. **Cite every claim.** Name the source in brackets: `(Zhang)`, `(Okonkwo, follow-up to Q3)`, `(Case: Company tab)`.
3. **Mark missing evidence.** Put a red-flag cell as `[gap: what is missing and who could answer]` rather than guessing.
4. **No conclusions.** Leave out Impact Summaries, the recommendation, ranked alternatives, final ratings, the weighted decision matrix, and memo prose. Where a rating is customary (a force's strength, a VRIN yes/no), give the **evidence for and against** plus a *suggested* rating labeled `suggested: Medium — student to decide`.
5. **Keep it short.** Use table cells of one or two sentences, with at most 8 rows per table.

## Output format

For each exhibit: a heading `Exhibit <letter>. <title>`, one italic line on its purpose, one markdown table, optional short bullets, then the line `Impact Summary: [yours to write]`. End with a list headed **Evidence gaps to close**, saying what is missing and who could supply it.

## Robotaxi exhibit set (course letters)

| Letter | Title | Memo question | What to draft |
|---|---|---|---|
| C | Industry Overview | Q1 | Rows for definition and scope, market players, operating economics (cost per mile, utilization), regulation, and technology approaches. Use only figures the case and the interviews gave. |
| E | Porter's Five Forces | Q1 | One row per force, plus a row for complementors and partners (RideLink). Show evidence for and against, and a suggested strength. |
| I | VRIN Analysis | Q2 | The assignment's resources: fleet, technology (camera-only), vertical integration, manufacturing scale, brand, and founder/CEO. Columns: Resource, Valuable?, Rare?, Inimitable?, Non-substitutable?, each with evidence, then *Suggested implication (student to decide)*. |
| J-1 | Unit Economics and Financial Ratios | Q3 | Cost per mile, revenue per vehicle, vehicle cost, utilization and burn rate, compared across AutoVision, DragonPath, Apex and LogiPod. Add a ratio block for AutoVision 2020–2025 (revenue growth, margins, cash, capex coverage of $18B). Mark `[gap]` wherever the statements were not obtained. |
| K | SWOT | Q2 | Two to four items per quadrant, each with a source. |
| N | Pros and Cons by Alternative | Q5 | For each of the three alternatives in the case, list evidence-based pros and cons with sources. No ranking and no recommendation. |
| P-1 | Five-Year Scenario Inputs | Q4 | Drivers (vehicles, cities, rides, price per mile, cost per mile, revenue) with the **low and high figures executives stated or implied**, and their sources. Leave the "Your projection" column blank. |
| P-2 | Competitor Responses | Q4 | Apex, RideLink and LogiPod: their likely response in their own words, the evidence behind it, and how credible it is (interest or bias noted). |

Exhibits A, B, L and M are **not** drafted. They are in the memo template for the student to complete.

## Other cases

Use the course letters where they fit: C Industry Overview, D PESTEL, E Five Forces, F Strategic Map, G KSFs, H Resources & Capabilities, I VRIO/VRIN, J Value Chain, J-1 Unit Economics, K SWOT, N Pros and Cons. Draft only the exhibits that the case's assignment asks for, or that the interviews actually support.

# Part 3. The AutoVision Robotaxi case (assignment, memo header, alternatives, background, executives, case app link, gaps)

```json
{
 "id": "robotaxi",
 "title": "AutoVision — The Robotaxi Decision",
 "caseApp": "https://case-study-builder-git-staging-johns-projects-9b4c8616.vercel.app/s/_pLLXIQ3SLVQ",
 "assignment": {
  "title": "Robotaxi Investment Decision Analysis",
  "role": "Board member / strategy adviser to AutoVision Inc.",
  "keyQuestion": "Should AutoVision's board approve, modify, or reject Marcus Drake's $18B robotaxi investment plan?",
  "deliverable": "Board memorandum with a recommendation, about 1,500 words plus exhibits (Porter's Five Forces, VRIN, SWOT, financial ratios). Submit the case app's Export Summary with the paper.",
  "questions": [
   {
    "id": "Q1",
    "title": "Industry Attractiveness",
    "words": 250,
    "prompt": "How attractive is the autonomous ride-hailing industry to enter, based on your Porter's Five Forces Analysis?"
   },
   {
    "id": "Q2",
    "title": "Competitive Advantages",
    "words": 250,
    "prompt": "Does AutoVision have any competitive advantages based on your VRIN and SWOT Analyses of their key resources (fleet, tech, vertical integration, manufacturing scale, brand, founder)? Does AutoVision have any sustainable competitive advantages in robotaxis?"
   },
   {
    "id": "Q3",
    "title": "Financial Analysis",
    "words": 250,
    "prompt": "What are some positive financial trends and some negative trends you see in AutoVision's 2020-2025 financials? Do you think AutoVision can financially afford an $18B investment in the robotaxi business?"
   },
   {
    "id": "Q4",
    "title": "Likely Scenario",
    "words": 350,
    "prompt": "What is the likely scenario for AutoVision's entry into autonomous ride-hailing? Will it succeed? How many vehicles, cities, rides and revenue in five years? What operational capabilities must AutoVision develop? How does vertical integration help or hinder? How will Apex, RideLink and LogiPod respond?"
   },
   {
    "id": "Q5",
    "title": "Strategic Recommendation",
    "words": 400,
    "prompt": "Approve the full $18B plan, approve a modified plan (which one), or reject entry? Why is it superior to alternatives? What 2-3 things must go right? What could undermine it, and how should those risks be monitored?"
   }
  ],
  "frameworks": [
   "Porter's Five Forces",
   "VRIN",
   "SWOT",
   "Financial ratios"
  ]
 },
 "memo": {
  "to": "Board of Directors, AutoVision Inc.",
  "subject": "Whether AutoVision should approve, modify, or reject the $18 billion robotaxi investment",
  "cc": "Marcus Drake, CEO; Patricia Lenz, Director",
  "alternatives": [
   "Approve the full $18B plan as proposed",
   "Approve a modified or staged plan (define the stages and gates)",
   "Reject entry and adopt the Lenz alternative ($15B buyback + $3B EV platform defense)"
  ]
 },
 "context": "AutoVision Inc.: world's most valuable EV company. Revenue $95B, ~500,000 employees, market cap $850B, $35B cash.\nCore EV business under pressure: revenue down 7%, margins compressing. Meridian Equity Research projects EV share falling from 18% to 13% by 2027 (Pinnacle Motors and others maturing). Pacific Ventures Capital forecasts core EV EBITDA margin falling from 28% to 21% by 2026 (pricing pressure, warranty costs).\nProposal (CEO Marcus Drake): $18B to enter robotaxis; 500 vehicles in 3-4 cities in 2026, 25,000 vehicles in 8-10 cities by 2027-28, 500,000 vehicles in 40+ cities by 2029-30; profitability 2028-2030; $12B profit by 2032. Camera-only technology, $55,000 vehicles, only 5,000 test rides with safety monitors. Direct-to-consumer app announced October 2025.\nBoard dissent: Director Patricia Lenz (ex-Goldman Sachs) and two directors favor a $15B buyback plus $3B EV platform defense instead.\nDragonPath Mobility (China), CEO Dr. Wei Zhang: only profitable robotaxi operator. 18,500 vehicles, 23 cities, 380M rides/yr, 12% operating margin, $0.42/mile operating cost. Sensor-rich (pivoted from camera-only after safety concerns). Chose not to enter the U.S. (regulation, geopolitics, cultural barriers, uncertain costs). \"An operations business, not a technology business.\"\nApex Autonomous, CTO Dr. Samira Okonkwo: 7 years of operations, 14M commercial rides, zero serious incidents, 5 cities, sensor-rich (lidar, radar, cameras), $72,000 vehicles, 280 engineers, burning $1.2B/yr, not profitable.\nRideLink, SVP Jason Chen: 120M users, 4.2M human drivers, 800+ cities in 45 countries, 65M AV rides/yr (0.8% of volume). Dilemma: move to AVs without destroying the driver platform. AutoVision's D2C app is both a threat and a negotiating opportunity. Chen is the leading CEO candidate for 2027-28.\nLogiPod (Titan Global Logistics), CEO Elena Vasquez: dual-use purpose-built $95,000 vehicles (passengers 6am-10pm, packages overnight), 19 hours/day, 450 vehicles, $128,000 revenue per vehicle vs ~$45,000 for competitors, losing $890M/yr. Titan has invested $8.5B, $15B committed through 2030. Must scale from 50 to 500 vehicles/month by 2028; breakeven at 15,000 vehicles (target 2029). \"You don't enter Formula 1 with a modified street car!\"\nGap: the case app does not show AutoVision's 2020-2025 financial statements, which Question 3 needs. Ask Marcus Drake for them, or check the course materials.",
 "people": [
  {
   "id": "zhang",
   "name": "Dr. Wei Zhang",
   "role": "CEO, DragonPath Mobility · impartial industry expert",
   "stance": "Neutral benchmark. Runs the only profitable robotaxi operator (18,500 vehicles, 23 cities, 12% op margin, $0.42/mile). Pivoted away from camera-only. Chose not to enter the U.S."
  },
  {
   "id": "okonkwo",
   "name": "Dr. Samira Okonkwo",
   "role": "CTO, Apex Autonomous · competitor (sensor-rich)",
   "stance": "Technical critic of camera-only. 7 years of operations, 14M rides, zero serious incidents, 5 cities, $72K vehicles, burning $1.2B/yr."
  },
  {
   "id": "vasquez",
   "name": "Elena Vasquez",
   "role": "CEO, LogiPod Autonomous Systems (Titan Global Logistics) · competitor (purpose-built, dual-use)",
   "stance": "'You don't enter Formula 1 with a modified street car.' 450 purpose-built $95K vehicles, 19 hours/day, $128K revenue per vehicle vs ~$45K, losing $890M/yr, Titan committing $15B through 2030."
  },
  {
   "id": "chen",
   "name": "Jason Chen",
   "role": "SVP Strategic Initiatives, RideLink · potential partner / platform rival",
   "stance": "120M users, 4.2M human drivers, 800+ cities, 65M AV rides (0.8% of volume). Threatened by AutoVision's October 2025 direct-to-consumer app, but also a possible partner. Likely future CEO."
  },
  {
   "id": "drake",
   "name": "Marcus Drake",
   "role": "CEO, AutoVision Inc. · sponsor of the $18B proposal",
   "stance": "Champion of the mobility-platform vision. Owns the $12B-by-2032 projection, camera-only bet, D2C app and the case against the Lenz buyback."
  }
 ],
 "gaps": [
  "AutoVision 2020-2025 financial statements (needed for Q3) are not in the case app Company tab. Ask Marcus Drake, or check the course materials."
 ]
}
```

# Part 4. Pre-built Robotaxi interview plan

This plan is pre-loaded. Show it to the student as the starting plan; the student may keep it, reorder it, or rewrite any question in their own words. Tags refer to assignment questions Q1-Q5 in Part 3.

## Interview order

1. **Dr. Wei Zhang**, CEO, DragonPath Mobility · impartial industry expert. Interview first. He sets the yardstick (economics, ops, safety, U.S. barriers) that every other answer, especially Marcus Drake's, gets tested against.
2. **Dr. Samira Okonkwo**, CTO, Apex Autonomous · competitor (sensor-rich). Second, while the tech and safety questions are fresh. She is the strongest critic, so separate her evidence from her bias.
3. **Elena Vasquez**, CEO, LogiPod Autonomous Systems (Titan Global Logistics) · competitor (purpose-built, dual-use). Third. She tests whether AutoVision's vehicle and manufacturing advantage is real, and shows what patient capital looks like.
4. **Jason Chen**, SVP Strategic Initiatives, RideLink · potential partner / platform rival. Fourth. He holds the demand side (buyers, pricing, channel) and the partner option that a modified plan may need.
5. **Marcus Drake**, CEO, AutoVision Inc. · sponsor of the $18B proposal. Interview last. By now you have outside benchmarks, so each question tests his claims against evidence instead of accepting them.

## 1. Dr. Wei Zhang

**Role:** CEO, DragonPath Mobility · impartial industry expert

**Stance:** Neutral benchmark. Runs the only profitable robotaxi operator (18,500 vehicles, 23 cities, 12% op margin, $0.42/mile). Pivoted away from camera-only. Chose not to enter the U.S.

**Objectives:**
- Get the real unit economics of a profitable robotaxi: cost per mile broken into its drivers, utilization, price per mile, years to profit
- Learn why DragonPath pivoted from camera-only to sensor-rich (evidence for the tech debate)
- Score U.S. Five Forces from an outsider: regulation, city permits, insurance and liability, price pressure from human rideshare
- Define the operational capabilities that took longest to build, and whether a manufacturer can build them
- Get milestones a board should require before committing $18B

**Planned questions:**

1. DragonPath is the only profitable robotaxi operator in the world. What actually determines whether a robotaxi fleet makes money, and how did you get to $0.42 per mile? [Q1, Q3, Q4]
   - Why: Baseline unit economics to compare against AutoVision's projections.
   - Probe 1: How does that $0.42 split across vehicle depreciation, remote operators, insurance, maintenance, cleaning, charging and depots?
   - Probe 2: What utilization (hours per day, paid miles share) do you need to break even?
   - Probe 3: How many years and vehicles did it take before you were profitable?
2. You explicitly chose not to enter the U.S. What barriers would a new U.S. entrant face that you weren't willing to take on? [Q1]
   - Why: Threat of entry, regulatory and buyer forces, straight from an operator who walked away.
   - Probe 1: Which is the hardest: city-by-city permits, federal safety rules, or liability and insurance?
   - Probe 2: How much does competition from human rideshare cap U.S. pricing?
   - Probe 3: Would your U.S. cost per mile be higher than $0.42? By how much?
3. DragonPath started camera-only and moved to sensor-rich systems after safety concerns. What happened, and what would AutoVision have to prove for camera-only to be safe at scale? [Q2, Q4]
   - Why: Independent evidence on the camera-only vs. sensor-rich debate.
   - Probe 1: Which conditions or edge cases broke the camera-only system?
   - Probe 2: How much did adding lidar and radar raise vehicle cost, and was it worth it?
   - Probe 3: Is there a version of camera-only you would trust?
4. You say robotaxis are 'fundamentally an operations business, not a technology business.' Which operational capabilities took you longest to build, and could a car manufacturer build them? [Q2, Q4]
   - Why: Tests whether AutoVision's manufacturing strengths transfer to a 24/7 service.
   - Probe 1: Remote assistance ratio: how many vehicles per remote operator?
   - Probe 2: How do you run incident response, cleaning and depot logistics?
   - Probe 3: Why do you expand city by city instead of all at once?
5. AutoVision has 5,000 test rides and plans large-scale operations by 2028-2030. How far is it from commercial readiness, and what milestones would you require before committing $18B? [Q4, Q5]
   - Why: Converts his experience into stage gates for a modified plan.
   - Probe 1: How many rides or miles before safety data is meaningful?
   - Probe 2: What would a realistic five-year fleet look like: vehicles, cities, rides?
   - Probe 3: What is the most likely way a well-funded entrant fails?
6. If you sat on AutoVision's board, would you fund the full $18B, a staged version, or the $15B buyback plus $3B EV defense? Why? [Q5]
   - Why: Neutral view on the capital allocation choice. Close with this.
   - Probe 1: What would a staged plan's first tranche look like?
   - Probe 2: What signals would make you stop funding?

## 2. Dr. Samira Okonkwo

**Role:** CTO, Apex Autonomous · competitor (sensor-rich)

**Stance:** Technical critic of camera-only. 7 years of operations, 14M rides, zero serious incidents, 5 cities, $72K vehicles, burning $1.2B/yr.

**Objectives:**
- Quantify what an operating track record costs: years, miles, dollars, safety learning
- Find the specific failure modes of camera-only, and where its defenders are right (cost, scale)
- Understand why Apex still loses money: the cost drivers and the path to profit
- Predict Apex's response to AutoVision's entry (pricing, cities, partnerships, regulators)
- Identify which assets can't be bought or copied quickly (VRIN: safety record, regulator trust, data)

**Planned questions:**

1. Apex has 14 million commercial rides with zero serious safety incidents. What did it take, in years, miles and dollars, to build that record? [Q2, Q4]
   - Why: Sets the bar AutoVision's 5,000 rides are measured against.
   - Probe 1: What did you learn in operations that simulation never showed you?
   - Probe 2: How did regulators' trust change as the record grew?
2. What are the specific failure modes of camera-only autonomy, and where are its defenders right? [Q2, Q4]
   - Why: Gets both sides of the tech debate from the critic herself.
   - Probe 1: Which conditions (night, glare, rain, fog, unusual objects) matter most?
   - Probe 2: Is AutoVision's lower vehicle cost a real advantage against your $72,000 vehicle?
   - Probe 3: Could AutoVision's fleet data close the gap?
3. Apex is burning $1.2 billion a year and isn't profitable yet. What are the biggest cost drivers, and what has to change for the unit economics to work? [Q1, Q3, Q4]
   - Why: Unit economics from a U.S. operator, compared with DragonPath's $0.42/mile.
   - Probe 1: What is your cost per mile today, and what is the target?
   - Probe 2: How much of your cost is vehicle hardware vs. operations?
   - Probe 3: How much does utilization matter?
4. How would Apex respond if AutoVision launched in your cities with lower prices and a large fleet? [Q1, Q4]
   - Why: Rivalry and competitor response for Q4.
   - Probe 1: Would you match prices, add cities, or deepen partnerships such as RideLink?
   - Probe 2: Would you press regulators on safety standards?
5. What does Apex have that a well-funded newcomer can't buy or copy quickly? [Q2]
   - Why: VRIN comparison: what is rare and inimitable in this industry.
   - Probe 1: Is it the safety record, regulatory relationships, operations know-how or data?
   - Probe 2: How long would it take AutoVision to catch up?
6. If an AutoVision robotaxi had one serious crash, what would it do to AutoVision and to the industry? [Q5]
   - Why: Downside risk and spillover to the core brand; feeds risk monitoring.
   - Probe 1: How did regulators react to past industry incidents?
   - Probe 2: What safety reporting should AutoVision's board demand?

## 3. Elena Vasquez

**Role:** CEO, LogiPod Autonomous Systems (Titan Global Logistics) · competitor (purpose-built, dual-use)

**Stance:** 'You don't enter Formula 1 with a modified street car.' 450 purpose-built $95K vehicles, 19 hours/day, $128K revenue per vehicle vs ~$45K, losing $890M/yr, Titan committing $15B through 2030.

**Objectives:**
- Test the purpose-built vs. modified consumer car argument (vehicle design as a competitive weapon)
- Understand utilization economics: why $128K revenue per vehicle, and what passenger-only fleets give up
- Learn what is hard about scaling production (50 to 500/month), and whether AutoVision's scale is a real edge
- Predict LogiPod's response, including any partnership interest
- Compare Titan's patient-capital thinking with the AutoVision board's buyback argument

**Planned questions:**

1. You've said 'you don't enter Formula 1 with a modified street car.' What does a purpose-built robotaxi give you that a modified consumer EV can't? [Q2, Q4]
   - Why: Tests vertical integration and vehicle design as a source of advantage.
   - Probe 1: Which design features matter most: durability, interior, sensors, cleaning, serviceability?
   - Probe 2: Does a consumer-based design cap utilization or vehicle life?
2. LogiPod generates $128,000 per vehicle per year against about $45,000 for competitors. How much of a robotaxi business case depends on utilization, and what does a passenger-only fleet give up? [Q1, Q3, Q4]
   - Why: Revenue-per-vehicle assumption to stress-test AutoVision's $12B profit.
   - Probe 1: What share of hours are passenger vs. package?
   - Probe 2: What is your breakeven per vehicle at 15,000 vehicles?
3. You need to scale from 50 to 500 vehicles a month by 2028. What makes that hard, and does AutoVision's manufacturing scale give it a real edge? [Q2]
   - Why: VRIN check on manufacturing scale.
   - Probe 1: Is the bottleneck sensors, supply chain, or quality?
   - Probe 2: Where would AutoVision's scale not help?
4. How would LogiPod respond to AutoVision entering the market, and would you ever partner with them? [Q4]
   - Why: Competitor response for Q4.
   - Probe 1: Would you compete on price, cities, or freight?
   - Probe 2: Would you buy vehicles or components from AutoVision?
5. Titan has committed $15 billion through 2030 while losing $890 million a year. How does Titan's board justify that patience, and what would you tell AutoVision's board about the buyback alternative? [Q3, Q5]
   - Why: Capital allocation and the time horizon of this industry.
   - Probe 1: What milestones does Titan use to keep funding?
   - Probe 2: What would make Titan stop?

## 4. Jason Chen

**Role:** SVP Strategic Initiatives, RideLink · potential partner / platform rival

**Stance:** 120M users, 4.2M human drivers, 800+ cities, 65M AV rides (0.8% of volume). Threatened by AutoVision's October 2025 direct-to-consumer app, but also a possible partner. Likely future CEO.

**Objectives:**
- Size real AV demand: rider acceptance, price per mile, which AV partners and on what terms
- Learn how RideLink read AutoVision's D2C app (threat vs. negotiating leverage)
- Define a workable partnership: fleet supply, revenue share, exclusivity, data
- Find the 24/7 service capabilities manufacturers underestimate
- Predict RideLink's response if AutoVision goes alone

**Planned questions:**

1. RideLink facilitates 65 million AV rides a year, still under 1% of volume. What does rider demand for AVs look like, and what are your AV partnerships based on? [Q1, Q4]
   - Why: Buyer power, demand and channel structure.
   - Probe 1: Do riders pay more, the same, or less for an AV ride?
   - Probe 2: Which AV partners do you use, and on what terms?
2. How did RideLink read AutoVision's October 2025 announcement of its own direct-to-consumer app? [Q1, Q4]
   - Why: Threat vs. negotiating leverage; competitive response.
   - Probe 1: Is a robotaxi app without RideLink's 120M users viable?
   - Probe 2: How long does it take to build demand density in a city?
3. If AutoVision supplied vehicles to RideLink instead of competing with you, what would a partnership need to look like? [Q4, Q5]
   - Why: Tests a partner-led modified plan.
   - Probe 1: Who owns the fleet, the customer, and the data?
   - Probe 2: What revenue split or per-mile fee would work?
   - Probe 3: Would you require exclusivity in any cities?
4. What do manufacturers underestimate about running a 24/7 mobility service? [Q2, Q4]
   - Why: Operational capabilities AutoVision is missing.
   - Probe 1: Customer support, cleaning, lost items, incident handling, surge pricing?
   - Probe 2: How much of your cost base is operations rather than technology?
5. If AutoVision goes it alone with its own app and fleet, how does RideLink respond? [Q4]
   - Why: Competitor response for Q4.
   - Probe 1: Would you deepen ties with Apex or others?
   - Probe 2: Would you compete on price with human drivers?
   - Probe 3: How do you manage the move from 4.2M drivers to AVs?

## 5. Marcus Drake

**Role:** CEO, AutoVision Inc. · sponsor of the $18B proposal

**Stance:** Champion of the mobility-platform vision. Owns the $12B-by-2032 projection, camera-only bet, D2C app and the case against the Lenz buyback.

**Objectives:**
- Get the assumptions behind $18B and $12B profit: vehicles, cities, rides, price, cost per mile, timeline
- Test his cost per mile plan against DragonPath's $0.42 and Apex's losses
- Hear his defense of camera-only and his plan if regulators demand more
- Find which operational capabilities AutoVision has, and which it will build, buy or partner for
- Get his rebuttal to Director Lenz, and his openness to a staged plan with stop points
- Understand how robotaxis help or hurt the core EV business

**Planned questions:**

1. Walk me through the $18 billion: how is it spent, and what assumptions about vehicles, cities, rides, price and cost per mile produce $12 billion in profit by 2032? [Q3, Q4]
   - Why: Gets the business case inputs to stress-test.
   - Probe 1: What fleet size and utilization does 2032 assume?
   - Probe 2: What price per mile, and what cost per mile?
   - Probe 3: What is the cash burn before profit?
2. DragonPath runs at $0.42 per mile after years of operations. What cost per mile do you plan for, and how will you get there? [Q2, Q3]
   - Why: Tests whether vertical integration and scale really lower cost.
   - Probe 1: Where does vertical integration save money, and where does it add risk?
   - Probe 2: How many vehicles per remote operator do you assume?
3. AutoVision has 5,000 test rides; Apex has 14 million with zero serious incidents. Why is camera-only safe enough, and what is your plan if regulators require lidar or radar? [Q2, Q4]
   - Why: Technology and regulatory risk from the sponsor.
   - Probe 1: What safety data will you publish, and when?
   - Probe 2: What would a sensor retrofit cost per vehicle?
4. Running a 24/7 service is different from building cars. Which operational capabilities do you have today, and which will you build, buy or get through partners? [Q2, Q4]
   - Why: Organizational capability gap.
   - Probe 1: Who will run fleet operations, and have they done it before?
   - Probe 2: Is a RideLink partnership on the table, or is the D2C app the plan?
5. Director Lenz argues for a $15 billion buyback plus $3 billion for EV defense. Why is she wrong, and would you accept a staged plan with milestones that release funding? [Q3, Q5]
   - Why: Capital allocation trade-off; openness to a modified plan.
   - Probe 1: Which milestones would you commit to?
   - Probe 2: What result would make you stop?
6. With EV revenue down 7% and margins under pressure, how does the robotaxi business help or hurt the core EV business? [Q3, Q5]
   - Why: Strategic fit and downside if the bet fails.
   - Probe 1: Does robotaxi volume support the factories?
   - Probe 2: What happens to the brand and stock if robotaxi stalls?

## Coverage map (planned questions per assignment question)

| Interviewee | Q1 | Q2 | Q3 | Q4 | Q5 |
|---|---|---|---|---|---|
| Dr. Wei Zhang | 2 | 2 | 1 | 4 | 2 |
| Dr. Samira Okonkwo | 2 | 3 | 1 | 4 | 1 |
| Elena Vasquez | 1 | 2 | 2 | 3 | 1 |
| Jason Chen | 2 | 1 | 0 | 5 | 1 |
| Marcus Drake | 0 | 3 | 4 | 3 | 2 |
| **Total** | **7** | **11** | **8** | **19** | **7** |

# Part 5. Memo template (course format, set up for Robotaxi)

> **How to use this template (delete this box before you submit)**
> - Replace every [bracketed] prompt with your own text.
> - Delete every "Guide:" line. They explain what each section needs and are not part of the memo.
> - Keep the sections in this order. No cover page, and never write in the first person.
> - Length: Board memorandum with a recommendation, about 1,500 words plus exhibits (Porter's Five Forces, VRIN, SWOT, financial ratios). Submit the case app's Export Summary with the paper.
> - Cite exhibits by letter (for example, "see Exhibit E"). Check every figure in the draft exhibits, rewrite them as yours, and write every Impact Summary yourself.
> - Follow the course AI policy. Interview-IQ gives you structure and evidence; the analysis, recommendations and wording must be yours.

# AutoVision — The Robotaxi Decision
## Case Analysis Memo

**TO:** Board of Directors, AutoVision Inc.  
**FROM:** [Your name and title]  
**DATE:** [Date of submission]  
**SUBJECT:** Whether AutoVision should approve, modify, or reject the $18 billion robotaxi investment  
**CC:** Marcus Drake, CEO; Patricia Lenz, Director

## Key Issues
[Paragraph 1: the central problem that requires a decision, and the questions management needs answered.]

[Paragraph 2: the required goals the recommended solution must achieve.]

*Guide: One to two paragraphs. Do not mention your recommendations here, and do not repeat case facts management already knows.*

## Recommendations
1. [Your decision: approve the full plan, approve a modified plan (say exactly what it is), or reject entry.]
2. [The two or three things that must go right for your recommendation to succeed.]
3. [The risks that could undermine it, and how the board should monitor them.]

*Guide: Numbered and specific. Do not explain your rationale here; it belongs in the Analysis.*

## Decision Criteria
[Short paragraph: the criteria the board will use to judge the alternatives, how each ties to a required goal, and how they are weighted. Refer to Exhibit L.]

*Guide: Criteria are indicators that a goal has been achieved. Include only criteria that serve this decision.*

## Analysis
[One or two sentences that explain the two parts: Section 1 answers the key questions from the evidence in the exhibits; Section 2 tests the recommendation against its alternatives.]

### Section 1: Key Questions
**Question 1: Industry Attractiveness** (about 250 words)
*Guide: How attractive is the autonomous ride-hailing industry to enter, based on your Porter's Five Forces Analysis?*

[Answer first, in one sentence.]

[Supporting evidence: about three reasons, each citing the executive who said it and the exhibit that shows it (Exhibit E (Five Forces)).]

[Where the executives disagree, which source is more credible and why.]

**Question 2: Competitive Advantages** (about 250 words)
*Guide: Does AutoVision have any competitive advantages based on your VRIN and SWOT Analyses of their key resources (fleet, tech, vertical integration, manufacturing scale, brand, founder)? Does AutoVision have any sustainable competitive advantages in robotaxis?*

[Answer first, in one sentence.]

[Supporting evidence: about three reasons, each citing the executive who said it and the exhibit that shows it (Exhibits I (VRIN) and K (SWOT)).]

[Where the executives disagree, which source is more credible and why.]

**Question 3: Financial Analysis** (about 250 words)
*Guide: What are some positive financial trends and some negative trends you see in AutoVision's 2020-2025 financials? Do you think AutoVision can financially afford an $18B investment in the robotaxi business?*

[Answer first, in one sentence.]

[Supporting evidence: about three reasons, each citing the executive who said it and the exhibit that shows it (Exhibit J-1 (Unit Economics and Financial Ratios)).]

[Where the executives disagree, which source is more credible and why.]

**Question 4: Likely Scenario** (about 350 words)
*Guide: What is the likely scenario for AutoVision's entry into autonomous ride-hailing? Will it succeed? How many vehicles, cities, rides and revenue in five years? What operational capabilities must AutoVision develop? How does vertical integration help or hinder? How will Apex, RideLink and LogiPod respond?*

[Answer first, in one sentence.]

[Supporting evidence: about three reasons, each citing the executive who said it and the exhibit that shows it (Exhibits P-1 (Scenario Inputs) and P-2 (Competitor Responses)).]

[Where the executives disagree, which source is more credible and why.]

### Section 2: Recommendations
**Recommendation: Strategic Recommendation** (about 400 words)
*Guide: Approve the full $18B plan, approve a modified plan (which one), or reject entry? Why is it superior to alternatives? What 2-3 things must go right? What could undermine it, and how should those risks be monitored?*

[The issue and the alternatives: one short paragraph that defines the decision and the alternatives you evaluate.]

- **Approve the full $18B plan as proposed.** [Pro: ... Con: ... Cite the interviews and exhibits.]
- **Approve a modified or staged plan (define the stages and gates).** [Pro: ... Con: ... Cite the interviews and exhibits.]
- **Reject entry and adopt the Lenz alternative ($15B buyback + $3B EV platform defense).** [Pro: ... Con: ... Cite the interviews and exhibits.]

[Which alternative scores highest in the Decision Matrix (Exhibit M), and why it is superior to the others.]

[What must go right (two or three conditions), and the early-warning signs the board should monitor.]

*Guide: Report the facts; do not predict the outcome. Cover every viable alternative, including doing nothing where relevant.*

## Conclusion
[One to two paragraphs: your key recommendations, and how the decision criteria support them.]

*Guide: Never state a belief or feeling, and never predict results that depend on factors outside management's control.*

## Exhibits
*Guide: Exhibits A, B, L and M are yours to build. The others are drafted by Interview-IQ from your own interviews: verify, edit and paste them here, and write each Impact Summary yourself.*

### Exhibit A. Guiding Questions
[Q1: Question]
[Response: clear analysis and answer]

[Q2: Question]
[Response: clear analysis and answer]

[Q3: Question]
[Response: clear analysis and answer]

*Guide: Examples: What is the core problem? Who are the key stakeholders? What are the time constraints? What resources are available? What are the key success metrics?*

**Impact Summary: Guiding Questions**
[In your own words: what this exhibit shows, and how it affects the decision. Do not restate the exhibit.]

### Exhibit B. Key Issues
[Central problem]

**Management questions**
- [Q1 Industry Attractiveness: restate the question in your own words]
- [Q2 Competitive Advantages: restate the question in your own words]
- [Q3 Financial Analysis: restate the question in your own words]
- [Q4 Likely Scenario: restate the question in your own words]
- [Q5 Strategic Recommendation: restate the question in your own words]

**Required goals**
- [Goal]
- [Goal]
- [Goal]

**Impact Summary: Key Issues**
[In your own words: what this exhibit shows, and how it affects the decision.]

### Exhibit L. Decision Criteria and Weights
| Criterion | Required goal it measures | Weight (1-5) | Why this weight |
|---|---|---|---|
| [ ] | [ ] | [ ] | [ ] |
| [ ] | [ ] | [ ] | [ ] |
| [ ] | [ ] | [ ] | [ ] |
| [ ] | [ ] | [ ] | [ ] |

**Impact Summary: Decision Criteria**
[In your own words.]

### Exhibit M. Decision Matrix
| Criterion (weight) | Alt 1 | Alt 2 | Alt 3 |
|---|---|---|---|
| [criterion (w)] | [1-10] | [1-10] | [1-10] |
| [criterion (w)] | [1-10] | [1-10] | [1-10] |
| [criterion (w)] | [1-10] | [1-10] | [1-10] |
| [criterion (w)] | [1-10] | [1-10] | [1-10] |
| Weighted total | [ ] | [ ] | [ ] |

Alternatives: Alt 1 = Approve the full $18B plan as proposed; Alt 2 = Approve a modified or staged plan (define the stages and gates); Alt 3 = Reject entry and adopt the Lenz alternative ($15B buyback + $3B EV platform defense)

**Impact Summary: Decision Matrix**
[In your own words.]

*Exhibits C, E, I, J-1, K, N, P-1 and P-2: see your Interview-IQ Draft Exhibits.*
