# Who Is Legally Responsible When AI Does Something Unintended?

Version 4 
Author: Merveille Solene Socko Damba
Last updated: October 19, 2026
References: see [`SOURCES.md`](./SOURCES.md)

This draft covers the research question for the group video: who is legally responsible when an AI system does something nobody intended, and how the consequences are handled. It was prepared with AI assistance for searching and drafting. Every factual claim has to be checked against its source by a team member, and our use of AI should be disclosed as the course requires.

Notes in square brackets show how far each claim has been checked. "Checked" means we read the full decision, statute, filing or article. "Partly checked" means we only saw a headline, snippet or summary. "Not rechecked" means the claim came from earlier notes and should not go into the video until someone confirms it.

---

## 1. Summary

In every case we found, responsibility landed on people and companies, never on the AI. In *Moffatt v. Air Canada*, the tribunal rejected the airline's suggestion that its chatbot was a separate entity responsible for its own statements. Who ends up paying depends on the legal theory in play: misrepresentation by the company that deployed the tool, a defective product, or a failure to supervise. For the most part these are older laws applied to new technology. The EU is the clearest exception, because it has rewritten its product liability law to cover software and AI by name. [checked]

## 2. What "unintended" means in law

The EU's new Product Liability Directive speaks to this directly. Recital 32 says a manufacturer that designs a product able to develop unexpected behaviour stays liable for harm that behaviour causes. Article 7(2)(c) adds that a court assessing whether a product is defective must consider its ability to keep learning after it is sold. In other words, "nobody planned for the AI to do that" does not work as a defence under the new EU rules. The question is whether the product was as safe as people are entitled to expect. [checked against the Directive]

## 3. Who can be held responsible

| Party | Basis for blame | Example | Status |
|---|---|---|---|
| Company deploying the AI | Responsible for what its own tools tell customers | *Moffatt v. Air Canada* (2024) | checked |
| Company that built the AI | Defective product, failure to warn | *Benavides v. Tesla*; EU Directive, recital 13 | checked |
| Human operator or driver | Failure to supervise | Uber test driver (2018) | partly checked |
| Software vendor | May be treated as the employer's agent | *Mobley v. Workday* (allegations) | not rechecked |
| The AI itself | Not treated as a legal person | Rejected in *Moffatt* | checked |

## 4. Cases

### 4.1 Air Canada's chatbot (Canada, 2024)

[checked against the full decision]

Jake Moffatt's grandmother died on November 11, 2022. Moffatt used the chatbot on Air Canada's website to ask about bereavement fares, and it told him he could apply for the reduced rate after travelling. The airline's actual policy did not allow that (paras. 13 to 17). An Air Canada representative later admitted the chatbot had used "misleading words" (para. 22).

Air Canada argued that it could not be held liable for information given by its agents, servants or representatives, including the chatbot. The tribunal read this as an argument that the chatbot was a separate legal entity responsible for its own actions. Tribunal Member Christopher C. Rivers called it "a remarkable submission" and held that the chatbot is part of the airline's website, so the airline answers for everything on it (para. 27).

The tribunal applied the tort of negligent misrepresentation. It found that Air Canada owed Moffatt a duty of care, did not take reasonable care to make sure the chatbot was accurate, and that Moffatt reasonably relied on what he was told (paras. 24 to 29). Air Canada was ordered to pay $812.02, made up of $650.88 in damages, $36.14 in interest and $125 in tribunal fees (para. 44). Moffatt had claimed $880.

This was a small claims tribunal decision. According to Cox & Palmer (n.d.), it does not bind courts in later cases, so it is persuasive at most.

### 4.2 Tesla Autopilot: *Benavides v. Tesla* (United States, 2025 to present)

[checked, except where noted]

On April 25, 2019, in Key Largo, Florida, George McGee was driving a Model S with Autopilot engaged at about 62 mph. He bent down to look for a phone he had dropped and drove through an intersection into an SUV parked on the shoulder. Naibel Benavides Leon died and Dillon Angulo was seriously injured (Stempel, 2026).

In August 2025 a federal jury in Miami found Tesla 33% responsible. Tesla's share of compensatory damages was $19.5 million to the Benavides estate and $23.1 million to Angulo, and the jury added $200 million in punitive damages, for a total of about $243 million. McGee had settled with the plaintiffs earlier (Stempel, 2026; Condon & Fischer, 2025). Reuters describes it as the first federal jury verdict in a fatal crash involving Autopilot.

The plaintiffs argued that Autopilot could be switched on for roads it was not designed for, that its driver monitoring was weak, and that the name itself misled drivers (Condon & Fischer, 2025). That is the plaintiffs' account as reported, not a court finding [partly checked]. Tesla argued that McGee alone was to blame and that the car was not defective. Tesla also says a pre-trial agreement limits punitive damages to three times compensatory damages, which it puts at $172 million. The plaintiffs dispute that reading, and our sources do not resolve it.

Judge Beth Bloom denied Tesla's motion to overturn the verdict on February 20, 2026, saying the evidence "more than supports" it (Stempel, 2026). Tesla filed its notice of appeal on March 16, 2026 (Tesla, Inc., 2026). The appeal is pending in the Eleventh Circuit as No. 26-10858 (U.S. Chamber of Commerce, n.d.). Briefing dates and the stay of payment come from a tracker site, so check the docket on CourtListener before the video is recorded [partly checked].

The case matters here because the driver admitted being distracted and a jury still assigned part of the blame, and a large punishment, to the company.

### 4.3 Uber self-driving test crash (United States, 2018 to 2023)

On March 18, 2018, an Uber test vehicle operating in autonomous mode struck and killed Elaine Herzberg in Tempe, Arizona. The NTSB voted 3-0 on November 19, 2019 that the probable cause was the backup operator's failure to monitor the road because she was visually distracted by her phone. The board also listed contributing factors on Uber's side: inadequate safety risk assessment, ineffective oversight of operators, and no adequate way of dealing with operators' automation complacency, all tied to what it called an inadequate safety culture (Laing, 2019; Jalopnik, 2019). It named the pedestrian's impairment and Arizona's limited oversight of testing as further factors (Arizona Republic, 2019). [checked]

NTSB probable-cause findings cannot be used as evidence in court (Arizona Republic, 2019) [partly checked]. The backup driver was charged with negligent homicide in 2020 and later pleaded guilty (Reuters, 2020; Reuters, 2023). We have only confirmed the headlines of those two articles, so the exact charge and sentence need to be read in the text [partly checked].

Our earlier notes said prosecutors declined to charge Uber and that Uber settled with the victim's family. We could not confirm either point, so both are removed from this version until someone finds a source [not rechecked].

### 4.4 Workday hiring lawsuit (United States, ongoing)

Applicants allege that an AI screening tool discriminated against them. The court allowed the claims to proceed against the software vendor on the theory that it acts as the employers' agent, and it conditionally certified a large age-discrimination group (Proskauer Rose LLP, 2025; Civil Rights Litigation Clearinghouse, n.d.). These are allegations and procedural rulings. No court has found that Workday discriminated. [not rechecked: verify against the docket and the Proskauer article before use]

### 4.5 Character.AI (United States, 2025 to 2026)

A court declined at an early stage to treat a chatbot's output as protected speech, and the case later settled. [not rechecked] The case involves the death of a child. If the group uses it, the wording needs care, and a different example may be the better choice.

## 5. The law in writing

### European Union

This subsection is read from the text of Directive (EU) 2024/2853. [checked]

The Directive was signed on October 23, 2024, published on November 18, 2024 and entered into force on December 8, 2024. It applies to products placed on the market or put into service after December 9, 2026 (art. 2(1)), and member states must have their national laws in place by the same date (art. 22). The 1985 directive is repealed from that date (art. 21).

Software counts as a product (art. 4(1)). Recital 13 mentions AI systems by name and says AI system providers are to be treated as manufacturers. Liability is no-fault (recital 6), although the injured person still has to prove the damage, the defect and the link between them (art. 10(1)). Courts must presume a defect or causal link in certain situations, including where technical complexity makes proof excessively difficult for the claimant (art. 10(4); recital 48).

A manufacturer cannot escape liability by pointing out that the problem appeared after the product was sold, if it comes from software, updates, or missing updates within the manufacturer's control (art. 11(2)). Several parties can be liable together (art. 12(1)), and liability can be reduced where the injured person was at fault (art. 13(2)).

The Directive is limited in what it compensates. Article 6 covers death, personal injury, damage to property and loss of private data. Recital 24 says pure economic loss, privacy infringements and discrimination do not trigger liability under the Directive by themselves. A loss like Moffatt's, or a hiring discrimination claim, would therefore need a different route.

The separate AI Liability Directive was withdrawn in 2025 (Bird & Bird, 2025; Wiggin LLP, n.d.). [partly checked: we have not confirmed the exact date or the Commission's reasons]

### Canada

The proposed Artificial Intelligence and Data Act died when Parliament was prorogued in January 2025, so Canada has no dedicated federal statute on AI liability (Montreal AI Ethics Institute, n.d.; Baker McKenzie, n.d.). Harms are handled under existing law, as in *Moffatt*. [not rechecked: an official Government of Canada source is still needed for current plans]

### United States

None of our sources point to a single federal law on AI liability. Cases are decided under existing product liability, negligence, anti-discrimination and criminal law, which is why outcomes differ from case to case.

## 6. How consequences are handled

| Consequence | Where we saw it |
|---|---|
| Compensation | *Moffatt* ($650.88 in damages); *Benavides* (about $42.6 million, Tesla's share) |
| Shared blame | *Benavides* (Tesla 33%); the NTSB spread its findings across several parties |
| Punitive damages | *Benavides* ($200 million, under appeal) |
| Criminal charge against an individual | Uber backup driver [partly checked] |
| Settlement | McGee settled with the plaintiffs in *Benavides* |
| New regulation | EU Directive applying from December 9, 2026; NTSB recommendations after the Uber crash |

## 7. Open questions

First, what happens when nobody could reasonably have predicted what the AI did? The EU text keeps the manufacturer liable for unexpected behaviour of a learning product, but we found no equivalent written rule in the US or Canadian material. We still need a peer-reviewed source on the "responsibility gap." [not yet researched]

Second, the largest US verdict, *Benavides*, is under appeal and could change.

Third, the EU Directive leaves out pure economic loss and discrimination, and the EU dropped its AI-specific liability proposal, so some harms have no clear route to compensation.

Fourth, Canada still relies on general law, as in *Moffatt*.

## 8. Video outline (2:30 to 3:00, about 400 to 450 words)

1. 0:00 to 0:20. Opening: an airline argued its chatbot was responsible for its own words, and the tribunal called that "a remarkable submission." (4.1)
2. 0:20 to 0:50. What "unintended" means and why it makes blame harder to assign. (Section 2)
3. 0:50 to 1:50. Three examples: Air Canada (the company), Tesla (shared blame), Uber (the individual). (4.1 to 4.3)
4. 1:50 to 2:25. The law: Canada's gap and the EU rules starting on December 9, 2026. (Section 5)
5. 2:25 to 3:00. The open question and a closing line. (Section 7)

## 9. Changes since v3 and work still to do

Corrected in this version: the AP article's authors are Bernard Condon and David Fischer, and the page is dated August 4, 2025. The *Moffatt* amounts, paragraph numbers and tribunal member's name now come from the decision itself. The Directive's application date is December 9, 2026 under art. 2(1). One wiki page said December 8 and was not used. For *Benavides* we added the compensatory split, McGee's earlier settlement, Tesla's argument about the punitive cap and the appeal number. We removed the unconfirmed Uber claims, and we added the Directive's text on unexpected behaviour and on what damage it covers.

Still to do: recheck Workday, Character.AI, the withdrawal of the AI Liability Directive and the Canadian position; confirm the Uber criminal case details in the article text; and add an academic source.

---

## How to comment and proofread

Open the pull request for the branch `research-ai-liability`, go to the Files changed tab and find `research/RESEARCH-DRAFT.md`. Hover over a line, click the blue plus sign and write your comment, or drag across several lines to comment on a range. To propose exact wording, use the Suggest changes icon. When you are done, choose Review changes and select Comment, Approve or Request changes. Broader ideas belong in GitHub Discussions.

Please check each of the following as you read:
- [ ] Does every factual claim have a source in `SOURCES.md`?
- [ ] Is anything stated more strongly than its source supports?
- [ ] Is it clear enough for a three-minute video?
- [ ] Are there any spelling, grammar or APA errors?
- [ ] Should we swap out the Character.AI example?
