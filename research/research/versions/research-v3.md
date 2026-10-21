# Who Is Legally Responsible When AI Does Something Unintended?

Version 3 
Author: Merveille Solene Socko Damba
Last date Updated: October 19, 2026
References: see [`SOURCES.md`](./SOURCES.md)

First full draft. It was written mostly from summaries, which will be removed or several points corrected in next version, including the Uber settlement and the prosecutors' decision on Uber. Record kept unchanged. It was prepared with AI assistance and its facts must be checked against the sources.

---

## 1. Summary

No court in our research treated an AI as a legal person that could be blamed. Responsibility fell on people and companies: the business that put the AI in front of customers, the company that built it, and sometimes the human supervising it. Which of them pays depends on the legal theory used. For now the rules are mostly old laws stretched over new technology, with the European Union the main place writing AI-relevant liability rules into statute.

## 2. Why "unintended" matters

In these cases nobody designed the AI to cause the harm. A chatbot invents a refund policy, or a driver-assist system fails to stop. The legal question is whether the people behind the AI should have prevented it, not whether they wanted it to happen. That is why most cases turn on negligence, defects or a failure to supervise.

## 3. Who could be responsible

| Party | Basis for blame | Example in our research |
|---|---|---|
| Company deploying the AI | Responsible for what its own tools tell or do to customers | *Moffatt v. Air Canada* (2024) |
| Company that built the AI | Defective product, or failure to warn | *Benavides v. Tesla* (2025); EU Product Liability Directive |
| Software vendor | May count as the employer's agent | *Mobley v. Workday* (allegations only) |
| Human operator or driver | Failure to supervise or stay alert | Uber safety driver |
| The AI itself | Not treated as a legal person | Air Canada's "separate entity" argument was rejected |

## 4. Cases

### Air Canada's chatbot (Canada, 2024)

A chatbot told a grieving customer that a bereavement fare could be claimed after travel, but Air Canada's real policy said otherwise. Air Canada argued, in effect, that the chatbot was responsible for itself. The British Columbia tribunal rejected that, held that the chatbot is part of the airline's website and found negligent misrepresentation (*Moffatt v. Air Canada*, 2024; Law360 Canada, 2024; Foster & Company, n.d.). The sum involved was small, but the principle is clear: a company cannot hand its blame to its chatbot. This was a small claims tribunal decision, so its weight as precedent is limited, and we still need to confirm that.

### Tesla Autopilot (United States, 2025 to present)

A federal jury in Miami found Tesla 33% responsible and the driver 67% for a 2019 fatal crash involving Autopilot. Tesla owes its share of $129 million in compensatory damages plus $200 million in punitive damages, roughly $243 million (Reuters, 2025; Associated Press, 2025). The judge refused to overturn the verdict in February 2026 (Reuters, 2026) and Tesla has appealed (Tesla, Inc., 2026), so the verdict is not final. Tesla argues the driver alone was to blame, and a business-law advocacy group argues the punitive award is unconstitutional (Washington Legal Foundation, 2026). Even where a human driver behaved badly, a company can still carry part of the blame and the punishment.

### Uber self-driving test crash (United States, 2018 to 2023)

Prosecutors decided Uber was not criminally liable (Reuters, 2020). The backup driver was charged with negligent homicide and later pleaded guilty to a reduced charge, receiving probation (Reuters, 2023). Investigators also said Uber had not adequately controlled the risk of the operator becoming distracted (WAMC, 2020), and Uber settled with the victim's family. Criminal blame landed on the individual, and the company dealt with it through a civil settlement.

### Workday AI hiring lawsuit (United States, ongoing)

Applicants say an AI screening tool discriminated against them. The key development is that the court allowed the claim to continue against the software vendor on the theory that it acts as the employers' agent, and it conditionally certified a large age-discrimination group (Proskauer Rose LLP, 2025; Civil Rights Litigation Clearinghouse, n.d.). These are allegations and early rulings, and no court has found that Workday discriminated. The current status still needs checking.

### Character.AI (United States, 2025 to 2026)

A court declined at an early stage to treat a chatbot's output as protected speech, which let product liability and negligence claims go ahead (Courthouse News Service, 2025; Branum, 2026). The case settled in January 2026 (Bloomberg Law, 2026). It involves a child's death, so if we use it in the video the wording needs care. We could choose a different example.

## 5. The law in writing

Canada. The proposed federal Artificial Intelligence and Data Act died in January 2025 when Parliament was prorogued (Montreal AI Ethics Institute, n.d.; Baker McKenzie, n.d.). Canada has no dedicated federal AI liability statute, so harms are handled through existing law, as in *Moffatt*. We still need an official government source for current plans.

European Union. The updated Product Liability Directive (EU) 2024/2853 treats software and AI as products and keeps no-fault liability, so victims need not prove negligence (Taylor Wessing, 2025; LexisNexis, 2025). It applies to products placed on the market after December 9, 2026, which is under two months away (LexisNexis, 2025; Covington & Burling LLP, 2026). The separate AI Liability Directive was withdrawn in 2025 because no agreement was expected (Bird & Bird, 2025; Wiggin LLP, n.d.).

United States. No single AI liability law appears in our sources. Cases run on existing product liability, negligence, anti-discrimination and criminal law, which is why outcomes differ from case to case.

## 6. How consequences are handled

| Consequence | Where we saw it |
|---|---|
| Compensation | *Moffatt* (a small award); *Benavides* ($129 million compensatory) |
| Shared blame | *Benavides*: 33% company, 67% driver |
| Punitive damages | *Benavides*: $200 million, under appeal |
| Criminal charge against a person | Uber safety driver: probation |
| Settlement | Uber and the victim's family; the Character.AI cases |
| Business changes | Character.AI restricted open-ended chats for minors (Bloomberg Law, 2026) |
| New regulation | EU Product Liability Directive taking effect in December 2026 |

## 7. Open questions

1. If neither the builder nor the user could reasonably have predicted what the AI did, who pays? Our sources describe cases with some human fault. We still need an academic source on the "responsibility gap."
2. The biggest verdict, *Benavides*, can still be changed on appeal.
3. Canada has no federal AI statute yet.
4. *Workday* could widen who counts as responsible.

## 8. Video outline (2:30 to 3:00, about 400 to 450 words)

1. 0:00 to 0:20. Opening: an airline argued its chatbot was responsible for itself, and lost. (Air Canada)
2. 0:20 to 0:50. What "unintended" means and why it makes blame hard.
3. 0:50 to 1:50. Three examples: Air Canada (company), Tesla (shared blame), Uber (individual).
4. 1:50 to 2:25. The law: Canada's gap and the EU rules arriving in December 2026.
5. 2:25 to 3:00. The open question and a closing line.

## 9. Limits of this draft
The Tesla appeal and the Workday case are still active, so their status may have changed since I wrote this. I read the abstract and part of the Matthias paper, not the whole article. Several 2026 Workday details come from the plaintiffs' lawyers, not the court. I couldn't find a source for the Uber settlement, so it isn't included.

Comments are welcome in the pull request for this branch.
