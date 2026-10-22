# Who Is Legally Responsible When AI Does Something Unintended?

Status: Done
Author: Merveille Solene Socko Damba
Last Update: October 19, 2026


---

## AI Liability research version

In every case I looked at, responsibility landed on people and companies, never on the AI. In *Moffatt v. Air Canada*, a tribunal rejected the airline's argument that its chatbot was a separate entity responsible for its own statements. Who ends up paying depends on the legal theory in play: misrepresentation by the company that deployed the tool, a defective product, or a failure to supervise. Mostly these are older laws applied to new technology. The EU is the clearest exception, since it has rewritten its product liability law to cover software and AI by name. Canada has no AI-specific liability law and has signalled it doesn't plan one.

## What "unintended" means in law

Philosophers call this the responsibility gap. Matthias (2004) argued that once a machine learns from experience, its manufacturer or operator can no longer predict what it will do, and so can't be held morally responsible or liable for it in the traditional way. He saw a gap that old ideas of blame can't bridge.

The EU's new Product Liability Directive can be read as one answer to that gap. Recital 32 says a manufacturer that designs a product able to develop unexpected behaviour stays liable for the harm it causes, and article 7(2)(c) tells courts to consider a product's ability to keep learning after it is sold when deciding whether it is defective. In other words, "nobody planned for the AI to do that" doesn't work as a defence in the EU. Linking the Directive to Matthias's argument is my own reading, and neither source says it.

## Who can be held responsible

| Party | Basis for blame | Example |
|---|---|---|
| Company using the AI | Answers for what its own tools tell customers | *Moffatt v. Air Canada* |
| Company that built the AI | Defective product, failure to warn | *Benavides v. Tesla*; EU Directive |
| Human operator or driver | Failure to supervise | Uber backup driver |
| Software vendor | May be treated as the employer's agent | *Mobley v. Workday* (allegations) |
| The AI itself | Not treated as a legal person | Rejected in *Moffatt* |

## Cases

### Air Canada's chatbot (Canada, 2024)

Jake Moffatt's grandmother died on November 11, 2022. He used the chatbot on Air Canada's website to ask about bereavement fares, and it told him he could apply for the reduced rate after travelling. The airline's real policy didn't allow that (paras. 13 to 17), and an Air Canada representative later admitted the chatbot had used "misleading words" (para. 22).

Air Canada argued it wasn't liable for information given by its agents, servants or representatives, including the chatbot. The tribunal read that as claiming the chatbot was a separate legal entity. Tribunal Member Christopher C. Rivers called it "a remarkable submission" and held that the chatbot is part of the airline's website, so the airline answers for everything on it (para. 27).

The tribunal applied negligent misrepresentation. It found that Air Canada owed Moffatt a duty of care, didn't take reasonable care to make sure the chatbot was accurate, and that Moffatt reasonably relied on what he was told (paras. 24 to 29). Air Canada had to pay $812.02: $650.88 in damages, $36.14 in interest and $125 in fees (para. 44). Moffatt had claimed $880.

This was a small claims tribunal decision, and according to Cox & Palmer (n.d.) it doesn't bind courts in later cases. It is persuasive at most.

### Tesla Autopilot: *Benavides v. Tesla* (United States, 2025 to present)

On April 25, 2019, in Key Largo, Florida, George McGee was driving a Model S with Autopilot on at about 62 mph. He bent down to look for a dropped phone and hit an SUV parked on the shoulder. Naibel Benavides Leon died and Dillon Angulo was seriously injured (Stempel, 2026).

In August 2025 a federal jury in Miami found Tesla 33% responsible. Tesla's share of compensatory damages was $19.5 million to the Benavides estate and $23.1 million to Angulo, and the jury added $200 million in punitive damages, about $243 million in total. McGee had settled with the plaintiffs earlier (Stempel, 2026; Condon & Fischer, 2025). According to Reuters, it was the first federal jury verdict in a fatal crash involving Autopilot.

The plaintiffs argued that Autopilot could be turned on for roads it wasn't designed for, that its driver monitoring was weak, and that the name itself misled drivers (Condon & Fischer, 2025). Those are the plaintiffs' arguments as reported, not court findings. Tesla argued McGee alone was to blame and that the car wasn't defective. Tesla also says an agreement made before trial limits punitive damages to three times compensatory damages, which it puts at $172 million, and the plaintiffs dispute that.

Judge Beth Bloom refused to overturn the verdict on February 20, 2026, saying the evidence "more than supports" it (Stempel, 2026). Tesla filed its notice of appeal on March 16, 2026 (Tesla, Inc., 2026), and the appeal is pending in the Eleventh Circuit as No. 26-10858 (U.S. Chamber of Commerce, n.d.). The verdict isn't final.

What stands out is that the driver admitted being distracted, and a jury still gave the company part of the blame and a large punishment.

### Uber self-driving test crash (United States, 2018 to 2023)

On the night of March 18, 2018, an Uber test vehicle in autonomous mode struck and killed Elaine Herzberg as she walked a bicycle across a street in Tempe, Arizona. The NTSB said the probable cause was the backup driver's failure to watch the road because she was distracted by her phone. It also said Uber made development decisions that contributed to the crash. The vehicle's software didn't properly identify Herzberg as a pedestrian and didn't address operators' "automation complacency," and Uber had turned off the car's automatic emergency braking and relied on the backup driver instead (Reuters, 2020).

Prosecutors said in March 2019 that Uber wasn't criminally liable. The backup driver, Rafaela Vasquez, was charged with negligent homicide in 2020, and police said she had been streaming a TV show on her phone (Reuters, 2020). In July 2023 she pleaded guilty to endangerment, a reduced charge, and was sentenced to three years of supervised probation (Shepardson, 2023). I read reports that Uber settled with the victim's family but couldn't find a source, so I left it out.

### Workday hiring lawsuit (United States, ongoing)

In *Mobley v. Workday* (N.D. Cal., No. 23-cv-00770-RFL), the plaintiff says Workday's AI applicant-recommendation system had a disparate impact on applicants because of race, age and disability. Workday is a software vendor, not the employer. The plaintiff argues it is liable as the employers' agent. In July 2024 the court denied Workday's second motion to dismiss, and on May 16, 2025 it conditionally certified the age-discrimination claims as a collective action (Morrison et al., 2025).

The scale is large. Workday told the court that 1.1 billion applications were rejected using its tools in the period at issue, and the collective could include hundreds of millions of people (Morrison et al., 2025). According to the plaintiffs' lawyers, the court authorized notice to potential members on February 17, 2026, with an opt-in deadline of March 7, 2026 (Wiggins Childs, 2026). That is one side's account. I didn't read the court orders.

All of this is allegations and procedural rulings. No court has found that Workday discriminated.

### Character.AI (United States, 2025 to 2026)

This case involves a child's death, so I'd handle it with care and think about whether to use it in the video. If anyone is affected by the topic, in Canada you can call or text 9-8-8 at any time.

Megan Garcia sued Character Technologies, its founders and Google after her 14-year-old son, Sewell Setzer III, died by suicide in February 2024 following long conversations with a chatbot. The claims included wrongful death, negligence and product liability (Pickett, 2025). On May 21, 2025, Judge Anne Conway in Orlando refused to dismiss the case on free speech grounds, writing that the court was "not prepared to hold" the chatbot's output is speech. Bloomberg Law adds that she let most claims proceed and declined to dismiss Google (Watwe, 2026).

In January 2026 the companies agreed to settle. Families in Florida, Texas, Colorado and New York agreed to negotiate settlements, and Garcia filed a notice of resolution (Watwe, 2026). The article gives no terms. In November 2025, Character.AI had also banned children from open-ended chatbot conversations (Watwe, 2026). The ruling was an early-stage decision, not a final judgment on liability.

## The law in writing

### European Union

I read this from the text of Directive (EU) 2024/2853 and from news reports on the AI Liability Directive.

The Directive was signed on October 23, 2024, published on November 18, 2024 and entered into force on December 8, 2024. It applies to products placed on the market or put into service after December 9, 2026 (art. 2(1)), and member states must have their national laws in place by the same date (art. 22).

Software counts as a product (art. 4(1)), and recital 13 says AI system providers are treated as manufacturers. Liability is no-fault (recital 6), though the injured person still has to prove the damage, the defect and the link between them (art. 10(1)). Courts must presume a defect or causal link in some situations, including where technical complexity makes proof excessively difficult for the claimant (art. 10(4); recital 48). A manufacturer can't avoid liability by saying a software problem appeared after sale, if it comes from software, updates or missing updates within its control (art. 11(2)). Several parties can be liable together (art. 12(1)), and liability can be reduced if the injured person was at fault (art. 13(2)).

The Directive has limits. It covers death, personal injury, damage to property and loss of private data (art. 6). Recital 24 says pure economic loss, privacy infringements and discrimination don't trigger liability on their own. A loss like Moffatt's, or a hiring discrimination claim, would need a different route.

The separate AI Liability Directive, proposed in 2022, was dropped in three steps. The Commission listed it for withdrawal in its 2025 work programme on February 11, 2025, saying there was "no foreseeable agreement" and that it would assess whether to propose something else (Andrews, 2025). It confirmed the withdrawal in July 2025 (Euronews, 2025), and a notice appeared in the Official Journal on October 6, 2025 (EAPIL, 2025). I found no replacement proposal.

### Canada

Canada has no AI-specific liability law. The proposed Artificial Intelligence and Data Act was part of Bill C-27 and never became law, and the AI minister, Evan Solomon, has said he won't revive it (BetaKit, 2025).

On June 4, 2026 the government launched its National AI Strategy, "AI for All," and in July it opened a consultation on AI transparency that ran until September 23, 2026 (Innovation, Science and Economic Development Canada, 2026a, 2026b). Legal commentator Michael Geist reads the strategy as showing no plans for AI-specific regulation, with the government relying on updated privacy rules and a reintroduced online safety bill (Geist, 2026). That is commentary, not an official statement. Reporting from BNN Bloomberg (2026) says the planned online harms bill could cover AI chatbots.

For harm like Moffatt's, then, Canadian law still means general rules such as negligent misrepresentation.

### United States

I didn't find a single federal AI liability law. Cases are decided under product liability, negligence, anti-discrimination and criminal law, which is why outcomes differ from case to case.

## How consequences are handled

| Consequence | Where it showed up |
|---|---|
| Compensation | *Moffatt* ($650.88 in damages); *Benavides* (about $42.6 million, Tesla's share) |
| Shared blame | *Benavides* (Tesla 33%) |
| Punitive damages | *Benavides* ($200 million, under appeal) |
| Criminal charge against an individual | Uber backup driver (guilty plea to endangerment, three years of probation) |
| Settlement | McGee in *Benavides*; Character.AI and Google agreed to negotiate settlements in January 2026 |
| Changes to the product | Character.AI banned open-ended chats for children in November 2025 |
| New regulation | EU Directive from December 9, 2026; Canada's privacy and online harms bills |

## Open questions

What happens when nobody could reasonably have predicted what the AI did? Matthias (2004) says traditional ideas of responsibility can't handle that case. The EU answers by keeping the manufacturer liable for unexpected behaviour, but I found no equivalent written rule for the US or Canada.

The largest US verdict, *Benavides*, is under appeal and could change. The EU Directive leaves out pure economic loss and discrimination, and the EU dropped its AI-specific liability proposal, so some harms have no clear route to compensation. Canada has chosen general law over AI-specific rules.

## Video outline (2:30 to 3:00, about 400 to 450 words)

1. 0:00 to 0:20. Opening: an airline argued its chatbot was responsible for its own words, and the tribunal called that "a remarkable submission."
2. 0:20 to 0:50. What "unintended" means and why it makes blame harder to assign.
3. 0:50 to 1:50. Three examples: Air Canada (the company), Tesla (shared blame) and Uber (the individual).
4. 1:50 to 2:25. The law: Canada's choice not to regulate, and the EU rules starting December 9, 2026.
5. 2:25 to 3:00. The open question and a closing line.

## Limits of this research

The Tesla appeal and the Workday case are still active, so their status may have changed since I wrote this. I read the abstract and part of the Matthias paper, not the whole article. Several 2026 Workday details come from the plaintiffs' lawyers, not the court. I couldn't find a source for the Uber settlement, so it isn't included.

Comments are welcome in the pull request for this branch.
