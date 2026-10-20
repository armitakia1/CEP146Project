# Who Is Legally Responsible When AI Does Something Unintended?

Version 5 of 5
Status: Done
Author: Merveille Solene Socko Damba
Date: October 19, 2026
References: see [`SOURCES.md`](./SOURCES.md)

---

## 1. Summary

In every case we found, responsibility landed on people and companies, never on the AI. In *Moffatt v. Air Canada*, the tribunal rejected the airline's suggestion that its chatbot was a separate entity responsible for its own statements. Who ends up paying depends on the legal theory in play: misrepresentation by the company that deployed the tool, a defective product, or a failure to supervise. For the most part these are older laws applied to new technology. The EU is the clearest exception, because it has rewritten its product liability law to cover software and AI by name. Canada, by contrast, has no AI-specific liability law and has said it does not plan one. [checked]

## 2. What "unintended" means in law

Philosophers have a name for the problem. Andreas Matthias (2004) argued that when a machine learns from experience, its manufacturer or operator can no longer predict what it will do. He concluded that they therefore cannot be held morally responsible or liable for it in the traditional way, which leaves a "responsibility gap" that old ideas of blame cannot bridge. [checked: we read the abstract and part of the paper; the full article still needs to be read]

The EU's new Product Liability Directive can be read as one legal answer to that gap. Recital 32 says a manufacturer that designs a product able to develop unexpected behaviour stays liable for harm that behaviour causes. Article 7(2)(c) adds that a court assessing whether a product is defective must consider its ability to keep learning after it is sold. So "nobody planned for the AI to do that" does not work as a defence under the new EU rules. The question is whether the product was as safe as people are entitled to expect. [checked against the Directive] Connecting the Directive to Matthias's argument is our own reading. Neither source says so.

## 3. Who can be held responsible

| Party | Basis for blame | Example | Status |
|---|---|---|---|
| Company deploying the AI | Responsible for what its own tools tell customers | *Moffatt v. Air Canada* (2024) | checked |
| Company that built the AI | Defective product, failure to warn | *Benavides v. Tesla*; EU Directive, recital 13 | checked |
| Human operator or driver | Failure to supervise | Uber test driver (2018) | checked |
| Software vendor | May be treated as the employer's agent | *Mobley v. Workday* (allegations) | partly checked |
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



On the night of March 18, 2018, an Uber test vehicle operating in autonomous mode struck and killed Elaine Herzberg as she walked a bicycle across a street in Tempe, Arizona. The NTSB voted 3-0 on November 19, 2019 that the probable cause was the backup operator's failure to monitor the road because she was visually distracted by her personal phone. It also named Uber's inadequate safety risk assessment, ineffective oversight of operators, and no adequate way of dealing with operators' "automation complacency," all tied to what it called an inadequate safety culture (Laing, 2019; Jalopnik, 2019). The pedestrian's impairment and Arizona's limited oversight of testing were listed as further factors (Arizona Republic, 2019).

Reuters adds two details from the NTSB's findings. The vehicle's software did not properly identify Herzberg as a pedestrian, and Uber had turned off the car's automatic emergency braking and relied on the backup driver instead (Reuters, 2020).

On the legal side, prosecutors said in March 2019 that Uber was not criminally liable (Reuters, 2020; Shepardson, 2023). The backup driver, Rafaela Vasquez, was charged with negligent homicide in 2020, and police said she had been streaming a TV show on her phone (Reuters, 2020). In July 2023 she pleaded guilty to endangerment, a reduced charge, and was sentenced to three years of supervised probation (Shepardson, 2023).

NTSB probable-cause findings cannot be used as evidence in court (Arizona Republic, 2019) [partly checked].

Our earlier notes said Uber settled with the victim's family. We still have no source for that, so we have dropped it [not confirmed].

### 4.4 Workday hiring lawsuit (United States, ongoing)

[checked for the 2024 and 2025 rulings; partly checked for 2026]

In *Mobley v. Workday, Inc.* (N.D. Cal., No. 23-cv-00770-RFL), the plaintiff alleges that Workday's AI applicant-recommendation system had a disparate impact on job applicants because of race, age and disability. Workday is a software vendor, not the employer, and the plaintiff does not claim it was his employer. He argues instead that Workday can be held liable as the employers' "agent." In July 2024 the court denied Workday's second motion to dismiss, so the claims went forward. On May 16, 2025 it conditionally certified the age-discrimination claims as a collective action (Morrison et al., 2025).

The size is striking. Workday told the court that 1.1 billion applications were rejected using its tools in the relevant period, and the collective could include hundreds of millions of people (Morrison et al., 2025).

According to the plaintiffs' lawyers, the court authorized notice to potential members on February 17, 2026, and the deadline to opt in was March 7, 2026 (Wiggins Childs, 2026). We have not read the court's orders, and a tracker site reports discovery orders as late as October 2026. Check the docket before relying on any of this [partly checked].

All of these are allegations and procedural rulings. No court has found that Workday discriminated.

### 4.5 Character.AI (United States, 2025 to 2026)



This case involves the death of a child, so we should handle it with care and consider whether to use it in the video at all. (If anyone on the team is affected by this topic, in Canada you can call or text 9-8-8 at any time.)

Megan Garcia sued Character Technologies, its founders and Google after her 14-year-old son, Sewell Setzer III, died by suicide in February 2024 following long conversations with a chatbot. The claims included wrongful death, negligence and product liability (Pickett, 2025). On May 21, 2025, Judge Anne Conway of the federal court in Orlando refused to dismiss the case on free speech grounds. She wrote that the court was "not prepared to hold" that the chatbot's output is speech, which was a first for a case about chatbot harm (Pickett, 2025). Bloomberg Law adds that she allowed most claims to proceed and declined to dismiss Google (Watwe, 2026).

In January 2026 the companies agreed to settle. Families in Florida, Texas, Colorado and New York agreed to negotiate settlements, and Garcia filed a notice of resolution. The article we read gives no terms (Watwe, 2026). In November 2025 Character.AI had also banned children from open-ended chatbot conversations on its platform (Watwe, 2026).

The ruling was an early-stage decision, not a final judgment on liability, and nothing in our sources shows what the settlements contained.

## 5. The law in writing

### European Union

This subsection is read from the text of Directive (EU) 2024/2853 and from news reports on the AI Liability Directive. [checked]

The Directive was signed on October 23, 2024, published on November 18, 2024 and entered into force on December 8, 2024. It applies to products placed on the market or put into service after December 9, 2026 (art. 2(1)), and member states must have their national laws in place by the same date (art. 22). The 1985 directive is repealed from that date (art. 21).

Software counts as a product (art. 4(1)). Recital 13 mentions AI systems by name and says AI system providers are to be treated as manufacturers. Liability is no-fault (recital 6), although the injured person still has to prove the damage, the defect and the link between them (art. 10(1)). Courts must presume a defect or causal link in certain situations, including where technical complexity makes proof excessively difficult for the claimant (art. 10(4); recital 48).

A manufacturer cannot escape liability by pointing out that the problem appeared after the product was sold, if it comes from software, updates, or missing updates within the manufacturer's control (art. 11(2)). Several parties can be liable together (art. 12(1)), and liability can be reduced where the injured person was at fault (art. 13(2)).

The Directive is limited in what it compensates. Article 6 covers death, personal injury, damage to property and loss of private data. Recital 24 says pure economic loss, privacy infringements and discrimination do not trigger liability under the Directive by themselves. A loss like Moffatt's, or a hiring discrimination claim, would therefore need a different route.

The separate AI Liability Directive, proposed in 2022, was dropped in three steps. The Commission listed it for withdrawal in its 2025 work programme on February 11, 2025, stating there was "no foreseeable agreement" and that it would assess whether to propose something else (Andrews, 2025). It confirmed the withdrawal in July 2025 (Euronews, 2025), and a notice appeared in the Official Journal on October 6, 2025 (EAPIL, 2025). No replacement has been proposed in our sources.

### Canada

Canada has no AI-specific liability statute. The proposed Artificial Intelligence and Data Act was part of Bill C-27 and did not pass (Montreal AI Ethics Institute, n.d.; Baker McKenzie, n.d.) [partly checked: we have not reopened these two sources, and the exact date it died should be confirmed]. The AI minister, Evan Solomon, said he would not revive it (BetaKit, 2025) [partly checked].

On June 4, 2026 the federal government launched its National AI Strategy, "AI for All," and in July it opened a consultation on AI transparency that ran until September 23, 2026 (Innovation, Science and Economic Development Canada, 2026a, 2026b). Legal commentator Michael Geist reads the strategy as showing that the government has no plans for AI-specific regulation. It relies instead on updated privacy rules and a reintroduced online safety bill (Geist, 2026) [partly checked: this is commentary]. Canadian Press reporting says the planned online harms bill could cover AI chatbots (BNN Bloomberg, 2026) [partly checked].

So for harm like Moffatt's, Canadian law still means general rules such as negligent misrepresentation.

### United States

None of our sources point to a single federal law on AI liability. Cases are decided under existing product liability, negligence, anti-discrimination and criminal law, which is why outcomes differ from case to case.

## 6. How consequences are handled

| Consequence | Where we saw it |
|---|---|
| Compensation | *Moffatt* ($650.88 in damages); *Benavides* (about $42.6 million, Tesla's share) |
| Shared blame | *Benavides* (Tesla 33%); the NTSB spread its findings across the operator, Uber and the state |
| Punitive damages | *Benavides* ($200 million, under appeal) |
| Criminal charge against an individual | Uber backup driver (guilty plea to endangerment, three years of probation) |
| Settlement | McGee in *Benavides*; Character.AI and Google agreed to negotiate settlements in January 2026 |
| Changes to the product | Character.AI banned open-ended chats for children in November 2025 |
| New regulation | EU Directive applying from December 9, 2026; Canada's privacy and online harms bills |

## 7. Open questions

First, what happens when nobody could reasonably have predicted what the AI did? Matthias (2004) says traditional ideas of responsibility cannot handle that case. The EU answers by keeping the manufacturer liable for unexpected behaviour, but we found no equivalent written rule in the US or Canadian material. We still need to read the full Matthias article and at least one later academic response.

Second, the largest US verdict, *Benavides*, is under appeal and could change.

Third, the EU Directive leaves out pure economic loss and discrimination, and the EU dropped its AI-specific liability proposal, so some harms have no clear route to compensation.

Fourth, Canada has chosen not to write AI-specific liability rules and relies on general law, as in *Moffatt*.

## 8. Video outline (2:30 to 3:00, about 400 to 450 words)

1. 0:00 to 0:20. Opening: an airline argued its chatbot was responsible for its own words, and the tribunal called that "a remarkable submission." (4.1)
2. 0:20 to 0:50. What "unintended" means: the responsibility gap and why it makes blame harder to assign. (Section 2)
3. 0:50 to 1:50. Three examples: Air Canada (the company), Tesla (shared blame), Uber (the individual). (4.1 to 4.3)
4. 1:50 to 2:25. The law: Canada's choice not to regulate and the EU rules starting on December 9, 2026. (Section 5)
5. 2:25 to 3:00. The open question and a closing line. (Section 7)
5. 2:25 to 3:00. The open question and a closing line. (Section 7)

Changes in this version:
- Uber: both Reuters articles are now read in full. The charge, the plea to endangerment, the probation, the March 2019 decision on Uber, and the NTSB's findings about the software and the braking system are confirmed. The Uber settlement is still unconfirmed.
- Workday: the Proskauer article is read in full, and the case number, the agent theory and the 1.1 billion figure are added. The 2026 steps are added, marked partly checked.
- Character.AI: both articles are read. We corrected "settled" to "agreed to settle," and added the claims, the judge, and the November 2025 ban.
- EU: the AI Liability Directive's withdrawal is now dated in three steps.
- Canada: added the June 2026 strategy, the transparency consultation and the government's stance on AI-specific regulation.
- Added Matthias (2004) on the responsibility gap.

Still to do:
- Check the Tesla appeal docket on CourtListener and the Workday docket.
- Read the full Matthias article and add one later academic response.
- Reopen the Canadian sources on AIDA and confirm how and when it died.
- Read the NTSB report itself.
- Find a source for the Uber settlement or leave it out.
- Fix the entries in `SOURCES.md` that carry a "To fix" note.
- Add teammates' comments from the pull request.

---

## How to comment and proofread

Open the pull request for the branch `research-ai-liability`, go to the Files changed tab and find `research/RESEARCH-DRAFT.md`. Hover over a line, click the blue plus sign and write your comment, or drag across several lines to comment on a range. To propose exact wording, use the Suggest changes icon. When you are done, choose Review changes and select Comment, Approve or Request changes. Broader ideas belong in GitHub Discussions.

Please check each of the following as you read:
- [ ] Does every factual claim have a source in `SOURCES.md`?
- [ ] Is anything stated more strongly than its source supports?
- [ ] Is it clear enough for a three-minute video?
- [ ] Are there any spelling, grammar or APA errors?
- [ ] Should we keep the Character.AI example, given the subject?
