# Administrative Law Exam — Hypothetical Analysis Guide

## 🚩 Purpose of This File

This file contains **exam-style hypothetical scenarios (“hypos”)** used to train issue-spotting and structured analysis in administrative law.

These hypos are NOT real cases.  
They are **complex, multi-layered fact patterns** designed to simulate exam questions.

---

## 🌐 Overall Background (Shared Across All Hypos)

All hypotheticals in this file take place against the following shared backdrop:

- A presidential election is approaching (or has just occurred)
- The current administration is **outgoing** — a complete change of administration is imminent
- Congress is also undergoing a **complete change in composition**
- A new vaccine has been developed at extraordinary speed, modeled on **Operation Warp Speed** — compressed timelines, emergency authorizations, and massive interagency coordination
- The situation involves a dense tangle of:
  - Political pressures (lame-duck dynamics, transition uncertainty)
  - Scientific disputes (safety, efficacy, approval standards)
  - Interagency conflicts (jurisdiction, coordination, delegation)
  - Procedural questions (notice-and-comment, guidance vs. binding rules)
  - Judicial review issues (standing, timing, deference, reviewability)

👉 When analyzing any hypo in this file, always keep this backdrop in mind. It affects which doctrines are triggered, which actors have authority, and what policy stakes are at play.

---

## Hypo 1 — Tying Vaccine Approval to a "Science Prize"

### Fact Pattern

The outgoing administration, in its final weeks, seeks to attach an unusual condition to vaccine access and approval. The President publicly uses language like "global recognition," "massive prize for science," and even references the Nobel Prize — suggesting that a vaccine's eligibility for public distribution should be tied to some form of prestigious scientific recognition or award.

This condition is being pursued through one of two possible channels (or both):
1. **Congressional legislation** — written into a statute governing vaccine access
2. **Agency requirement** — imposed by the relevant agency (e.g., FDA) as part of its approval or distribution criteria

### Issues to Spot

**1. Statutory Authority**
- Does the relevant enabling statute authorize the agency to use "scientific prestige" or "prize recognition" as an approval criterion?
- Vaccine approval statutes (e.g., FDCA) authorize FDA to evaluate safety and efficacy — not reputational or award-based metrics
- If no statutory hook exists, the agency lacks authority to impose this requirement → ultra vires action

**2. Relevance / Reasoned Decisionmaking**
- Is there any rational connection between winning a Nobel Prize (or similar award) and a vaccine's safety or effectiveness?
- Under *State Farm* and *Overton Park*, agency action must be based on factors Congress intended the agency to consider
- A Nobel Prize criterion has no nexus to public health protection → fails reasoned decisionmaking

**3. Arbitrary and Capricious Review (APA §706)**
- Even if the agency has some discretion, using an irrational criterion like award status is the definition of arbitrary and capricious
- Court would ask: did the agency "examine the relevant data and articulate a satisfactory explanation"? (*State Farm*)
- Answer here: almost certainly no

**4. Improper Considerations**
- Agency must not rely on factors that are legally irrelevant or outside its mandate
- Political pressure from the White House to use prestige-based criteria is an improper consideration
- Connects to *State Farm*: agency cannot base decisions on factors Congress did not intend

**5. Executive Pressure — White House vs. Agency Expertise**
- The President's public statements ("Nobel," "global recognition") raise the question of whether agency action is being driven by political messaging rather than scientific judgment
- This implicates the tension between presidential control (Article II) and the agency's expert, insulated role
- Courts are sensitive to whether an agency's stated rationale is genuine or a post-hoc rationalization for political pressure (*Fox Television*)

**6. Cross-Branch Problem**

*If pursued through legislation:*
- Congress has broad power to set conditions on federal programs, but rational basis still applies
- A Nobel-linked condition may be so arbitrary it raises due process or equal protection concerns
- Also raises nondelegation concerns if Congress tries to delegate the "prize" determination to a private body (e.g., the Nobel Committee)

*If pursued through agency requirement:*
- Primary issues are delegation + APA: does the statute delegate authority to use this criterion?
- If not, the regulation is invalid regardless of how it was promulgated
- If notice-and-comment was skipped, add a procedural APA §553 violation on top

### Analysis Technique Notes

- Always start by identifying the **channel** (statute vs. regulation) — it determines which doctrines lead
- Do not conflate presidential speech with binding agency action — spot whether a formal rule was actually issued
- Run the *State Farm* checklist: relevant factors considered? Irrelevant factors excluded? Explanation articulated?
- Add policy note: allowing prestige-based approval criteria would politicize the scientific review process, undermine public trust in agencies, and set a dangerous precedent for non-expert interference in technical rulemaking

---

## Hypo 2 — Federal Vaccine Distribution Conditioned on States Dropping Mask Mandates

### Fact Pattern

The federal government announces it will only distribute vaccines to states that do not have mask mandates in place. Alternatively (broader version): any state that adopts public-health restrictions stricter than federal recommendations will be denied vaccine allocation.

The Governor's legal team must advise: Should the Governor sign the agreement? Can the federal government do this legally? What are the strengths and weaknesses of a legal challenge?

---

### Issue Cluster (a) — Federal Authority to Impose This Condition

**Which federal actor is doing this?**
- Identify the agency first: HHS? CDC? FEMA? Each has a different enabling statute with different scope
- The answer matters — an agency can only act within its own statutory grant

**Does the statute authorize conditioning vaccine distribution?**
- Federal spending/distribution programs can attach conditions, but conditions must be:
  - Unambiguous (clear statement rule — *South Dakota v. Dole*)
  - Related to the federal interest in the program
  - Not independently unconstitutional
- A vaccine distribution statute aimed at public health protection almost certainly does not authorize conditions that *reduce* public health protection in recipient states

**Does the condition match the statutory purpose?**
- If the statute's purpose is to maximize vaccine access and protect public health, a condition that withholds vaccines from states with *more* protective health measures is directly contrary to that purpose
- This is a strong arbitrary and capricious argument and a statutory ultra vires argument simultaneously

---

### Issue Cluster (b) — Federalism / Coercion

**Can the federal government tie life-saving resources to state police-power choices?**
- States have broad police power over public health — mask mandates are a classic exercise of that power
- The federal government can attach conditions to spending, but *Dole* and *NFIB v. Sebelius* set limits:
  - Conditions must not be "coercive" — states must have a genuine choice
  - Withholding vaccines (a life-saving resource during a health emergency) in exchange for abandoning health measures looks a lot like the Medicaid expansion coercion struck down in *NFIB*

**Is state "consent" here truly voluntary?**
- If the only way to get vaccines is to sign the agreement, the choice is illusory
- The more severe the public health emergency, the stronger the coercion argument
- Governor's advisors should flag: signing under these conditions may not constitute genuine voluntary agreement

---

### Issue Cluster (c) — Executive Orders Do Not Create New Agency Authority

**Key principle (professor's direct instruction):**
> Executive orders from the outside world don't really give agencies any more power than the Constitution or statutes already give them.

An EO is essentially the President directing agencies as their boss — it has internal management significance but cannot:
- Override or expand an agency's enabling statute
- Grant authority Congress never delegated
- Transform an agency without statutory authority into one with it

**How to write this on an exam:**
- If the fact pattern says "the President issued an EO directing the agency to condition vaccine distribution" — analyze it this way:
  1. The EO may be a valid exercise of presidential direction over executive agencies
  2. But the EO cannot expand the agency's statutory authority
  3. If the enabling statute doesn't authorize this condition, the EO doesn't fix that — the agency action is still ultra vires
  4. The EO is not itself the source of legal authority; the statute is

---

### Issue Cluster (d) — Arbitrary and Capricious

**What if the scientific basis for the condition is thin or politically motivated?**
- If the condition is justified by anti-mask rhetoric, YouTube videos, or rock-star ad campaigns rather than peer-reviewed science, the agency has:
  - Relied on bad or irrelevant evidence
  - Failed to explain the connection between the condition and the statutory goal
  - Ignored contrary scientific evidence (CDC's own prior guidance)
  - Created an irrational means-ends relationship (withholding vaccines to discourage mask-wearing has no public health logic)
- Under *State Farm*: agency must examine relevant data and articulate a satisfactory explanation — this fails that test
- Under *Fox Television*: if the agency is changing a prior position, it must acknowledge the change and provide a reasoned explanation — especially if reliance interests exist

---

### Issue Cluster (e) — Guidance vs. Binding Condition Problem

**Professor's key point on CDC communications:**
- Guidance changes as scientific information evolves — that alone is not unlawful
- The question is whether guidance is being used *as* a binding condition

**How to analyze on exam:**
- If the condition is imposed through a FAQ, memo, or public health advisory rather than a notice-and-comment rule:
  - It may lack the force of law (not a legislative rule)
  - It cannot legally bind states or create enforceable obligations
  - Using guidance as a de facto binding condition is an APA §553 violation — it bypasses required rulemaking procedures
- Distinguish: guidance *informing* distribution decisions (potentially ok) vs. guidance *constituting* the legal condition (not ok without proper rulemaking)

---

### Issue Cluster (f) — Standing and Reviewability

**Does the state have standing to challenge now?**
- If the state currently has no mask mandate, has it suffered an injury yet?
  - Argument: no current injury → no standing
  - Counter: the *threat* of losing vaccines if a mandate is adopted may be sufficient — chilling effect on state legislative choices, imminent injury
- Distinguish state standing from individual standing:
  - Individuals may need to show more concrete, particularized harm
  - States get *special solicitude* in standing analysis (*Massachusetts v. EPA*) — their sovereign and quasi-sovereign interests count
  - A state's interest in exercising its police power without federal coercion is a cognizable sovereign interest

**Reviewability:**
- Is this committed to agency discretion by law? (APA §701(a)(2))
- Vaccine allocation during an emergency may have some discretionary insulation, but conditions attached to distribution are more likely reviewable — they look like rules, not pure discretion

---

### Governor's Advisor Takeaway

| Question | Answer |
|---|---|
| Should the Governor sign? | Signing under coercion may be legally challengeable; not signing risks public health harm — advise documenting the coercive nature of the offer |
| Can the federal government do this? | Likely not — statutory authority is doubtful, coercion doctrine applies, A&C problems are severe |
| Strengths of a challenge | Ultra vires, coercion, A&C, guidance-as-binding-rule, EO cannot expand authority |
| Weaknesses of a challenge | Federal spending power is broad; courts may defer on emergency public health decisions; standing timing issues |

---

### Analysis Technique Notes

- Always identify the specific agency and its enabling statute before analyzing authority
- Treat EOs as internal management tools, not independent sources of legal power
- Run the *Dole*/*NFIB* coercion analysis whenever federal conditions touch state sovereign functions
- Distinguish guidance from binding rules — if binding effect comes from guidance, that's your APA procedural hook
- On standing: raise state special solicitude, and consider whether the chilling effect on state legislative choices is itself a present injury

---

## Hypo 3 — President Reassigns Statutory Authority from One Agency to Another

### Fact Pattern

President declares: "Consumer Product Safety people, step aside — CDC is handling this." A function Congress statutorily assigned to Agency A is unilaterally redirected to Agency B by presidential order.

Core question: not just *whether* this is allowed, but *why* it is or isn't, and *when* it might be.

---

### Issues

**Cross-agency statutory authority**
- Each agency's power derives from its enabling statute — Congress assigned the function to Agency A specifically
- Agency B (CDC) has no statutory hook for this subject matter → any action it takes is ultra vires
- The President cannot reassign statutory responsibility by fiat; only Congress can rewrite the statute

**Can the President unilaterally reassign statutory functions?**
- Generally no — statutory assignments are Congress's domain (Article I)
- President can direct *how* an agency exercises its authority, but cannot move the authority itself to a different agency
- Exception: if a reorganization statute (e.g., Reorganization Act) grants the President explicit authority to restructure agencies, that changes the analysis — but requires congressional authorization

**If the "wrong" agency acts**
- Action by Agency B on a matter Congress gave to Agency A = ultra vires
- Courts will not defer (no Chevron/Skidmore hook — Agency B is not interpreting its own statute)
- The action is void regardless of how reasonable it might otherwise be

**If the President fires Agency A personnel and installs Agency B**
- Firing raises removal/Article II questions — was the removal lawful? Were there for-cause protections?
- Even after firing, the statutory authority stays with Agency A's office, not with whoever the President prefers
- Personnel changes do not transfer statutory jurisdiction

**A&C layer**
- Even if some authority exists, redirecting a technical function to an agency with no expertise in that domain (e.g., CDC handling consumer product safety) may itself be arbitrary — no reasoned basis connecting the reassignment to the statutory purpose

---

### Issue Cluster Summary (Professor's own framing)

| Layer | Question |
|---|---|
| Constitution | Does Article II give the President power to reassign statutory functions? |
| Statute | Which agency's enabling act covers this? Does it authorize delegation to another agency? |
| Cross-agency authority | Is Agency B acting within its own statutory grant? |
| A&C | Is the reassignment rationally connected to any legitimate regulatory purpose? |
| Presidential power limits | EO/presidential direction cannot override statutory assignment — same principle as Hypo 2(c) |

---

## Hypo 4 — New President Immediately Fires Independent Agency Commissioners

### Fact Pattern

New president takes office. Before full transition, an independent agency (e.g., FTC) takes actions adverse to the new president's interests. New president says: "You're out." Commissioners challenge removal.

---

### Issues

**Article II removal — the case sequence**
- *Myers*: President has plenary removal power over executive officers
- *Humphrey's Executor*: Congress can limit removal of independent agency commissioners to "for cause" — FTC-type multi-member bodies with quasi-legislative/quasi-judicial functions are different from pure executive officers
- *Morrison*: upheld independent counsel with for-cause protection; functional test — does the restriction impede presidential control of executive branch?
- *Free Enterprise Fund*: dual for-cause layers are unconstitutional — too much insulation from presidential control
- *Seila Law*: single-director independent agencies (CFPB) cannot have for-cause protection — *Humphrey's* limited to multi-member bodies with specific characteristics
- *Trump v. Slaughter* (pending): open question on how far *Seila Law* extends; whether *Humphrey's* itself survives in full

**Key distinctions to write**
- Independent agency ≠ executive agency — the structural difference is the whole point
- *Humphrey's* historical status: still good law for traditional multi-member commissions, but under modern pressure
- Whether FTC-style commissioners today still fit *Humphrey's* after *Seila Law* is an open question — flag it

**Twist: agency acts adversely before new president is "fully locked in"**
- Timing matters: was the action taken while prior commissioners were still lawfully in office? Then it's valid agency action regardless of new president's preferences
- Removal of commissioners after the fact doesn't retroactively invalidate prior lawful actions

**Normative / policy discussion (professor explicitly invited this)**
- If president can summarily remove all independent commissioners during a public health crisis:
  - Vaccine approval, distribution, and safety oversight become subject to political turnover
  - Expertise and continuity are disrupted at the worst possible moment
  - Undermines the entire rationale for independent agencies — insulation from short-term political pressure
- Counter: democratic accountability — unelected commissioners shouldn't be able to defy a newly elected president's mandate

---

## Hypo 5 — CPSC Recall of Vaccine Delivery Device

### Fact Pattern

The vaccine is delivered as an inhaled mist. The most effective delivery device is under consideration for recall because a component poses a choking hazard. CPSC's recall process is stalled — commissioners have been summarily dismissed, staff gutted. An internal whistleblower says the device is risky. The agency says "we're going to proceed anyway" with no explanation.

This hypo chains together multiple weeks of doctrine in one fact pattern.

---

### Issues

**Removal / agency staffing**
- Commissioners dismissed → Hypo 4 removal analysis applies directly
- Gutted staff → agency may lack capacity to fulfill statutory mission; raises accountability and functionality questions

**Statutory mission and recall authority**
- Does CPSC's enabling statute cover this device? Is an inhaled vaccine delivery device a "consumer product" within CPSC's jurisdiction?
- If yes: does CPSC have authority to recall, or only to recommend/refer?
- If another agency (FDA) has overlapping jurisdiction over the device as a drug delivery mechanism → cross-agency authority problem from Hypo 3

**Failure to explain / arbitrary and capricious**
- Agency says "we're going to do it anyway" after internal risk warnings, with no explanation
- *State Farm*: must examine relevant data and articulate a satisfactory explanation
- Ignoring the whistleblower's contrary evidence = failure to consider relevant factors
- Proceeding without explanation after flagged risk = paradigm A&C violation

**Guidance vs. order vs. enforcement**
- Is the "we're proceeding" statement a formal order, a guidance document, or an enforcement decision?
- If guidance: not binding, cannot compel recall
- If order: requires procedural compliance (notice, opportunity to respond)
- If enforcement action: different reviewability posture, ripeness/finality questions

**Standing / timing**
- If someone sues before the recall is finalized: ripeness problem — agency action not yet final (*Abbott Labs* vs. *Toilet Goods* framework)
- Who has standing? Manufacturer of the device (economic injury), patients who need the device (health injury), states?
- Injury must be concrete and imminent — "agency is considering recall" may not be enough yet

**Cross-agency substitution**
- If CPSC is dysfunctional, can FDA or HHS step in? → ultra vires unless their statutes cover it
- Presidential EO directing substitution → same limit as Hypo 3: EO cannot reassign statutory authority

---

### Analysis Technique Note

This is the professor's "everything connects" hypo. On an exam, map it layer by layer:
1. Who has authority? (CPSC statute, FDA overlap)
2. Is the agency structurally intact? (removal, staffing)
3. Did it follow procedure? (notice, explanation)
4. Was the decision reasonable? (A&C, ignored evidence)
5. Can anyone challenge it now? (standing, ripeness, finality)

---

## Hypo 6 — Congressional Review Act: Extreme Variation

### Fact Pattern

New Congress seated with unprecedented supermajority (~70%) of opposing party. They invoke the CRA, counting back 60 days to invalidate everything every agency has done. President vetoes. Congress overrides all vetoes.

Professor note: full extreme version is low-probability on exam; a "slightly nutty" variation is fair game.

---

### Issues

**CRA mechanics**
- CRA allows Congress to pass a joint resolution of disapproval to invalidate a "rule" submitted to Congress within the last 60 legislative days
- Normally requires presidential signature (or veto override)
- Here: supermajority enables override → procedurally valid under CRA if rules were properly submitted

**What counts as a "rule" under CRA**
- CRA covers rules as defined under APA §551 — broad, but not everything
- Guidance, interpretive rules, policy statements may not qualify → CRA cannot gut those
- Adjudicatory orders, enforcement decisions also outside CRA scope
- Key issue-spot: not all agency action is a "rule" — CRA's reach has limits

**CRA's "no substantially similar rule" bar**
- Once a rule is invalidated under CRA, the agency cannot issue a substantially similar rule without new congressional authorization
- Mass invalidation → agencies potentially frozen from acting in entire subject areas
- In a public health emergency context: this could mean FDA/CDC cannot re-issue vaccine safety rules without new legislation — severe practical consequence

**Constitutional questions**
- Is a mass, bulk CRA resolution (one resolution covering hundreds of rules) valid, or must each rule get its own resolution? Statute is ambiguous
- Nondelegation in reverse: if Congress uses CRA to strip all agency authority in a domain, does that raise separation of powers concerns?
- No presentment problem if president vetoes and Congress overrides — that's the constitutional process working as designed

**Policy / normative layer**
- Gutting all agency rules during an active public health crisis (vaccine rollout mid-stream) creates regulatory vacuum
- Reliance interests: manufacturers, states, healthcare providers built plans around existing rules
- *Fox*/*State Farm* logic doesn't apply to Congress directly, but the practical disruption is the policy argument against this use of CRA

---

### Exam Technique Note

If a variation appears: identify which specific rules are being targeted, check if they qualify as CRA-covered "rules," flag the "no substantially similar rule" freeze effect, and note any constitutional ambiguity in bulk resolutions. The extreme version is mostly a vehicle for testing CRA mechanics and the "no similar rule" consequence.
