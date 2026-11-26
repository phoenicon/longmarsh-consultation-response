# CHECK.md — What to verify before relying on these drafts

This file lists:
- **(a)** factual claims found in only one AI draft, plus claims that a second draft has since confirmed;
- **(b)** places where the drafts disagree;
- **(c)** links in SOURCES.md that did not come from any draft.

There are three drafts: Claude (`versions/claude.md`), ChatGPT (`versions/chatty.md`) and Gemini (`versions/gemini.md`).

There are also **primary sources**: the borough council's own documents for its 16 November 2026 Extraordinary Council meeting. These are the agenda, the NSIP report, the NSIP presentation, the summary of public questions and responses, and the minutes, which are still marked draft. Where they settle a point, that is stated below. They are listed in [SOURCES.md](SOURCES.md) and not copied into this repository.

There is also the **Stop Longmarsh campaign's own material**, in [`campaign/`](campaign/): a letter to the developer, a letter to ministers and Schedule A. It is the campaign's work and has not been checked here. Where it changes our files, that is noted below.

## From the campaign's material

| Point | What it says | What we did |
|-------|--------------|-------------|
| **Dimensions** | Schedule A's source note quotes the developer's proposals page: solar panels up to **4.5 m**, battery containers up to **4.5 m**, agricultural fencing up to 2.5 m, CCTV poles up to 5 m, palisade fencing up to 3 m around high-voltage areas. It quotes the October 2026 Scoping Report: data-centre buildings up to **25 m including plant** | Added the panel, battery and data-centre heights to RESPONSE and QUESTIONS and the README, all marked "check before quoting" because they come via the campaign and nobody here has seen the developer's pages. Gemini's "2.5 m security fencing" matches the agricultural fencing figure; the high-voltage areas get 3 m palisade fencing |
| **"15 m panels" and "four double-decker buses"** | Schedule A says: "The earlier suggestion of 15-metre solar panels and a four-double-decker-bus building height is not treated as fact." | **No such claim was in any of our files or the three AI drafts** (checked by search). Nothing to remove. Don't introduce it |
| **Pylon height of 50 m** | The campaign's developer letter and Schedule A (G8) say "the Council's comments refer to 50m pylons" and ask the developer to confirm the real design | **This comes from council comments, not a confirmed design.** It is also not in any of the council documents we have: the 16 November minutes, report, presentation and public questions summary don't mention pylons at all. It may come from another council response, such as its scoping comments. Don't quote 50 m as the pylon height. Not used in our files |
| **High Grove** | The campaign's letters list High Grove, The Droves and East Pye as major **Norfolk** solar proposals, with Tasway paused, and say their published areas shouldn't simply be added together | High Grove is restored in RESPONSE as a **Norfolk regional** cumulative scheme only, with no distance figure. It is kept separate from the council's West Norfolk list, which doesn't include it. Gemini's "832 m away" figure is still unsourced and not used |
| **Energy figures** | Both letters and Schedule A (H1) cite a "reported" estimate of about **6,000 GWh** a year of data-centre demand, with solar meeting about **20%**, and ask the developer to confirm or correct it | Not used in our files. Unverified, and the campaign itself presents it as reported. It is roughly in line with ChatGPT's ~16% and Gemini's 15–20%, which are also unverified |
| **Data Centre Covenant date** | The ministers letter ties the Covenant to "the November 2026 Budget announcement" | **Possible conflict:** ChatGPT says the Covenant was published on 28 October 2026. These may be two different events, an announcement and a publication. RESPONSE already marks the Covenant "check before quoting" |
| **Who it's addressed to** | The ministers letter names ministers and their roles, for example the AI Minister and ministers for energy, planning and the Treasury | Not checked. Confirm each name, role and address is current before sending |
| **Petition link** | The README's campaign petition is change.org/Stopthedatacentre | This differs from the petition URL in the ChatGPT draft. They may be the same petition or different ones |

## Settled by the council documents

| Point | What the drafts said | What the council documents say |
|-------|---------------------|-------------------------------|
| **The council's position on Longmarsh** | Claude: the council "voted unanimously against". Gemini: the council backed a fight against it. News headlines: "votes to challenge" or "backs fight against" | The council unanimously passed a **general five-point NSIP resolution** (minutes C:77), not a vote on Longmarsh. The Monitoring Officer said the meeting "was not determining an individual proposal". The public questions summary says: "The Council has not reached a formal position on the proposal." **Claude's and Gemini's wording is wrong, and has been corrected in the README and in notes at the top of each draft.** |
| **Does the developer have to respond to every comment?** | Gemini: "legally required" to respond to every comment. ChatGPT: statutory pre-application consultation was removed in July 2026 (UNVERIFIED) | **Resolved against Gemini.** The council's report refers to "the removal of Statutory Consultation earlier this year" and says pre-application phases are now shorter. That supports ChatGPT's point, though the report gives no month, so "July" is still unconfirmed. Don't tell anyone the developer must answer each comment. The responses still *ask* for answers |
| **Registering as an interested party** | Gemini: register in a window after the application is accepted (planningsignal.co.uk) | **Confirmed.** The council's report (stage 3, pre-examination) says interested parties register and submit relevant representations. The gov.uk pre-examination guidance (para 2.4) says the deadline is at least 28 days, or 30 for EIA development. Now in the README |
| **Other NSIPs nearby (cumulative impact)** | Gemini: High Grove Solar, Fens Reservoir, The Droves Solar Farm, Medworth EfW, Redmere Wind Farm | **Mostly confirmed.** The council's presentation lists The Droves Solar Farm, Fens Reservoir, Redmere Wind Farm and Medworth Energy from Waste, plus National Grid's Eastern Green Link 3 and 4 and Grimsby to Walpole. **High Grove Solar is not on the council's list**; the campaign lists it as a Norfolk regional scheme instead (see above). Gemini's distances are still unsourced |
| **Longmarsh's stage** | Pre-application | The presentation shows Longmarsh at "Scoping" within pre-application |

### New claim from the council documents: Councillor Long's bread figure

In the minutes (C:77), Councillor Long says that "independently of Dr Martin Little" he calculated the land could produce "around 25 million standard 800g loaves of bread annually, equivalent to three days of UK supply". He also says the scheme covers "more than seven square miles", which matches ChatGPT's 7.34 square miles.

**The bread figure is his own calculation.** The minutes record that he said it, not that it is correct, and his method and assumptions aren't published. Don't quote it as fact. If you use it, attribute it: "Councillor Long told the council he had calculated…". It is not used in the response files.

The minutes also record Councillor Squire mentioning an unsuccessful judicial review by Lincolnshire County Council that relied mainly on loss of farmland. That is relevant context if anyone suggests farmland alone will stop the scheme. It hasn't been checked and is not used.

When Claude or ChatGPT labels something VERIFIED, that is the AI's own claim to have opened the source. Gemini cites sources but labels nothing. No person has checked any of it. Two drafts agreeing is not proof: they may share a source, or share a mistake.

---

## (a) Claims found in only one draft

### Only in ChatGPT

| Claim | ChatGPT's label | Used in |
|-------|-----------------|---------|
| Planning Inspectorate reference EN0110048 | VERIFIED | SHORT, RESPONSE |
| EPL Norfolk Limited is the applicant, a wholly owned subsidiary of Evolution Power Limited | VERIFIED | RESPONSE (applicant name only) |
| Korkia (Finnish) backs Evolution Power | UNVERIFIED | not used |
| Directors Giles Frampton and Conor McNally | UNVERIFIED | not used |
| Company numbers 13808423 and 13544817 | UNVERIFIED | SOURCES only (marked UNVERIFIED) |
| Emily Gerard organised the petition | UNVERIFIED | not used |
| Solar lifetime about 60 years | VERIFIED (developer's proposals) | SHORT, RESPONSE, QUESTIONS |
| After solar decommissioning, Western Site data centre, substation, batteries and Western Cable Route remain | VERIFIED (developer's proposals) | SHORT, RESPONSE, QUESTIONS |
| Cable routes: Western ~8 km mostly overhead; Eastern ~8 km underground + ~8 km overhead | VERIFIED (developer's proposals) | RESPONSE |
| Construction from 2029 | VERIFIED (developer's proposals) | not used |
| Fossil-fuel backup generators included | VERIFIED developer claim | RESPONSE (asks for details) |
| ~1,500 supported jobs; investment over £25bn; prices below UK average; offshore wind access | VERIFIED developer claims | not used |
| Heritage assets on Eastern route: Stradsett Hall park, Grade I Church of St Botolph | VERIFIED (developer's proposals) | not used |
| EN-1 (2025) para 5.11.12 quote on minimising impacts on BMV land | VERIFIED exact extract | SHORT, RESPONSE (marked check before quoting) |
| EN-3 (2025) para 2.10.21 quote "poorer quality land should be preferred" | VERIFIED exact extract | SHORT, RESPONSE (marked check before quoting) |
| EN-3 (2025) para 2.10.22: solar on BMV land not prohibited outright | VERIFIED (paraphrase) | RESPONSE (marked check before quoting) |
| Other EN-3 paragraph numbers (2.10.23–25, 2.10.56, 2.10.137, etc.) | described, not quoted, or UNVERIFIED | not used |
| Planning Act 2008 s.122(3) "compelling case in the public interest" | VERIFIED | RESPONSE (marked check before quoting) |
| EIA Regulations 2017 reg 14 and sch 4 require reasonable alternatives to be described | VERIFIED | RESPONSE (marked check before quoting) |
| Data Centre Covenant published 28 October 2026 | VERIFIED | RESPONSE (marked check before quoting). The campaign's ministers letter links it to "the November 2026 Budget announcement"; see "From the campaign's material" |
| Draft NPS for Data Centres; national consultation closes 8 January 2027 | VERIFIED | not used |
| Separation distances 30 m panels and 100 m inverters/transformers | from earlier draft, not confirmed | not used. Gemini gives a different meaning for the 100 m; see (b) |
| Statutory NSIP pre-application consultation duties removed in July 2026 | UNVERIFIED | **Supported by the council's report** ("earlier this year"; the month isn't confirmed). Now in the README |
| Abbots Langley: council refused Jan 2024; Secretary of State allowed the appeal 12 May 2025 | VERIFIED (gov.uk appeal page) | not used |
| Google Grange Castle (Dublin) approved on appeal Sept 2026; Vantage left Aurora (US) Nov 2026 | VERIFIED | not used |

### Only in Claude

| Claim | Claude's source | Used in |
|-------|-----------------|---------|
| Site runs about 29 km from Walpole to Barton Bendish | Digital Urban blog | RESPONSE |
| Data centre at least 300 m from any resident | Lynn News | RESPONSE, QUESTIONS (Gemini and ChatGPT give 300 m for "major built infrastructure") |
| Occupier unnamed and no visuals published | Lynn News | SHORT, RESPONSE, QUESTIONS |
| Over 400 people at the 2 November meeting; developer did not attend | Resultsense | not used |
| Farmer James Kitchen's silt soil held yields through drought | Resultsense | not used |
| Councillor called the solar a "Trojan horse" | BBC via now.solar | not used |
| Three pylons crossing one neighbouring farm | BBC via now.solar | RESPONSE (general form only) |
| Terry Jermy MP quote on energy vs food security, and plan to bar solar on grade 2+ land | Resultsense | not used |
| Edinburgh, Amlwch, Hertsmere, Waterford, Spain/Netherlands, US precedents | various | SOURCES only |
| "1 GW uses the power of eleven UK cities" | Claude flagged it unverified and did not use it | not used. Do not use it |

### Only in Gemini (new)

Gemini gives sources for some of these but not all. None is labelled verified.

| Claim | Gemini's source | Used in |
|-------|-----------------|---------|
| Developer email info@longmarshgreenenergy.co.uk | not cited separately | not used |
| Islington Heronry SSSI near the site, with only a 100 m buffer | developer's leaflet and design material (cited) | RESPONSE, QUESTIONS (marked check before quoting) |
| Birch Wood ancient woodland and Fincham Conservation Area nearby | as above | RESPONSE, QUESTIONS (marked check before quoting) |
| Parts of the site boundary are in Flood Zone 3 | as above | RESPONSE, QUESTIONS (marked check before quoting) |
| Developer's leaflet says "sealed closed-loop cooling system" means "no significant impact on local water supply" | developer's consultation leaflet (PDF) | RESPONSE (marked check before quoting). ChatGPT has the same wording |
| 4.5 m battery containers; 2.5 m security fencing | developer's material | **Matches the developer figures quoted in the campaign's Schedule A** (battery containers up to 4.5 m; agricultural fencing up to 2.5 m; palisade fencing up to 3 m around high-voltage areas). Battery height now in RESPONSE and QUESTIONS, marked check before quoting |
| Nearby projects for cumulative assessment: High Grove Solar (832 m), Fens Reservoir (3.9 km), The Droves Solar Farm (6.1 km), Medworth EfW (6.3 km), Redmere Wind Farm | no specific source | RESPONSE (names only; distances left out). **Four of the five are confirmed by the council's presentation and listed as West Norfolk schemes. High Grove isn't on the council's list; it is now listed separately as a Norfolk regional scheme, per the campaign's letters** |
| Water UK warned in July 2026 that there is not enough water for the data centre plans, citing a 220 million litre daily shortfall | The Guardian, 21 July 2026 | RESPONSE (marked check before quoting) |
| East Anglia is "officially classified as severely water-stressed" | no source | not used |
| Solar supplies "15–20%" of data centre demand, or "~80%" from the grid | no source ("reportedly") | not used. ChatGPT's own sum, with assumptions, gives ~16% |
| Process: Planning Inspectorate takes ~28 days to accept; registration window of at least 28 days; 6-month examination about Sept 2027–Mar 2028; decision July–Sept 2028 | planningsignal.co.uk | The interested-party step, the registration window and the 6-month maximum examination are **confirmed** by the council's report and gov.uk guidance, and are now in the README. Gemini's specific dates are still unconfirmed |
| 70–125 GW of data centre grid connection requests in the UK queue | no specific source | not used |
| "Five separate submissions from one household carry far more weight" | no source | not used |
| An "April 2026 landmark High Court ruling" forced data centres to account for full climate impacts | no source | not used. Conflicts with ChatGPT; see (b) |

### Claims now found in two drafts

These were single-source before Gemini. Treat agreement with care, because two drafts may rely on the same news story.

| Claim | Drafts |
|-------|--------|
| Consultation opened 15 October 2026; closes 11:59pm on 26 November | ChatGPT, Gemini |
| Freepost LONGMARSH GREEN ENERGY; Freephone 0800 246 1782 | ChatGPT, Gemini |
| Closed-loop cooling claim | ChatGPT, Gemini |
| Operation targeted for 2032 | ChatGPT, Gemini |
| About 500 direct operational jobs; thousands of construction jobs | ChatGPT, Gemini |
| Council voted unanimously on 16 November 2026 | ChatGPT (UNVERIFIED), Gemini (cites Resultsense, 17 Nov). Claude gives no date. **Confirmed by the minutes, but it was a general NSIP resolution, not a vote against Longmarsh.** See "Settled by the council documents" above |
| James Wild MP and Terry Jermy MP | ChatGPT (UNVERIFIED), Gemini (no source). Claude has Terry Jermy only, sourced |
| A new NPPF in August 2026 | ChatGPT, Gemini |
| Data centres designated Critical National Infrastructure | ChatGPT (12 Sept 2024, UNVERIFIED), Gemini (no date) |
| Natural England rates the land Grade 1 | Claude, Gemini (but see (b) on Grade 2) |
| 4,695 acres | Claude, Gemini ("4,695 to 4,700") |
| Decision possible in 2028 | Claude, Gemini |

## (b) Where the drafts disagree

| Topic | Claude | ChatGPT | Gemini | What I did |
|-------|--------|---------|--------|------------|
| **Land grade** | "Natural England rates the land grade one" | The breakdown is unknown; don't claim all of it is grade 1–3a | "Grade 1 **and Grade 2**" (no grade 2 source) | Kept "much of it reported to be grade one"; the full breakdown is unpublished |
| **Who the developer is** | EPL Norfolk Limited / Longmarsh Green Energy | Applicant is EPL Norfolk Limited, a subsidiary of Evolution Power Limited | Says "Evolution Power Limited (EPL)" is the developer | Kept "EPL Norfolk Limited and Longmarsh Green Energy". Gemini seems to have merged the parent and the subsidiary |
| **Does the developer have to respond to every comment?** | Doesn't say | Says statutory pre-application consultation duties were removed in July 2026 (UNVERIFIED) | Says the developer is "legally required" to log and respond to every comment | **Resolved against Gemini** by the council's report. See "Settled by the council documents" above |
| **The 100 m distance** | Not mentioned | 100 m for inverters and transformers | 100 m buffer from Islington Heronry SSSI | Not used. Check the developer's design commitments |
| **The 300 m distance** | From any resident (data centre) | From major built infrastructure; only the data centre figure confirmed | From major built infrastructure | Used Claude's "from any resident", attributed to the developer via Lynn News |
| **Solar share of demand** | Not given | ~16%, from its own assumptions | "15–20%", no source | Kept ChatGPT's figure, labelled as an assumption |
| **When the DCO application goes in** | By April 2027 | About April 2027 | April 2027, but later says "expected around May 2027" | Not used |
| **Decision date** | Possibly by July 2028 | Not given | July–September 2028 | Not used |
| **Government rejected a data centre moratorium** | Yes, Construction Magazine (Aug 2026) | Not mentioned | Says November 2026, but its own sources are dated August 2026 | Not used |
| **Site area** | 4,695 acres (BBC); 4,700 headline | 4,700 acres | "4,695 to 4,700" | Used "about 4,700 acres" |
| **Earlier petition counts** | 39,000+ about a month before; almost 45,000 about three weeks before | 45,000 (5 Nov), 47,000 (12 Nov), UNVERIFIED | Cites a "nearly 50,000" headline | Not used. All agree on 57,000+ on 25 Nov |

### Precedents re-checked against Gemini

Gemini names no specific precedent. It says only that "major proposals in Buckinghamshire and West London" were "thrown out by Planning Inspectors and the Secretary of State" over alternative sites. It also mentions a High Court ruling in April 2026. Nothing here confirms either of the other two drafts, and some of it conflicts with them.

| Case | Claude | ChatGPT | Gemini | Conclusion |
|------|--------|---------|--------|------------|
| **Woodlands / Greystoke, Buckinghamshire** | Two items: (1) "Iver / West London Technology Park", Secretary of State refused a 147 MW scheme in Oct 2023 over Green Belt and alternative sites (cites a CMS "Woodlands refusal" article); (2) "Greystoke Land", Government admitted a "serious logical error" in Jan 2026, permission likely to be quashed | 90 MW. Council refused; Government overturned that in July 2025; Foxglove and Global Action Plan challenged; Government conceded; developer accepted binding environmental conditions in April 2026. ChatGPT says this is **not** a court ruling with a citation | "Thrown out" by the Secretary of State (no name or date). Separately, an "April 2026 landmark High Court ruling" | **Three-way conflict.** The capacity differs (147 MW vs 90 MW), and so does the outcome (refused, likely quashed, or approved with binding conditions). Gemini's "High Court ruling" probably refers to the April 2026 Woodlands outcome, which ChatGPT says was a concession, not a judgment. **Do not cite any version without the primary documents** |
| **Iver** | Treated as the 147 MW refusal above. Also says a separate Court Lane, Iver appeal was **allowed** in Dec 2024 (search snippet only) | Not named | Covered only by the general "Buckinghamshire and West London" line | There may be several Iver sites. Unresolved |
| **Abbots Langley** | Only a "Three Rivers (Abbots Langley) 96 MW refusal", date unverified | Council refused Jan 2024; Secretary of State **allowed** the appeal 12 May 2025 (84,000 m² across two buildings) | Not mentioned | **Correction to my earlier summary:** I said it "was actually granted on appeal". That rests on ChatGPT alone. The two drafts may not conflict, since a council refusal followed by an appeal grant fits both. Floorspace (m²) and power (MW) can't be compared. Don't cite it as a refusal. If you use it, use it as a warning that refusals get overturned, and check the gov.uk decision first |

None of the response files cites any precedent.

## (c) Links in SOURCES.md that did not come from any draft

| Link | Note |
|------|------|
| https://infrastructure.planninginspectorate.gov.uk | General Planning Inspectorate home page, added as a signpost. Check that it still resolves. |
| https://www.gov.uk/guidance/planning-act-2008-guidance-on-the-pre-examination-stage-of-an-application | Added for interested-party guidance. Loaded and confirmed on 25 Nov 2026 (published 3 July 2026) |
| https://www.gov.uk/guidance/planning-act-2008-guidance-on-the-examination-stage-of-an-application | Added for examination guidance. Loaded and confirmed on 25 Nov 2026 |
| https://www.gov.uk/government/collections/national-infrastructure-planning-guidance | Added as a guidance index. Loaded and confirmed on 25 Nov 2026 |
| https://www.west-norfolk.gov.uk/meetings | The council's agendas, reports and minutes index, found by web search. The meeting's own page address wasn't found, so the council documents are listed by name |
| https://stoplongmarsh.com and https://www.change.org/Stopthedatacentre | Campaign links you supplied, not checked. The change.org link differs from the petition URL in the ChatGPT draft |

Before the council documents arrived, I had added no further links. Every Gemini link in SOURCES.md is copied from its source lists. Two other links in the repo are not from a draft: the README's link to longmarshgreenenergy.co.uk, which you supplied (Gemini also cites it), and the feedback-page link, which is from ChatGPT.

## Removed for privacy

- `versions/chatty.md`: your name, Section 6 (personal business plan, naming a private individual) and Section 8.1 (facts about you). Sections describing the author's own business concept (2.4.3, 2.8.4, 7.26, response item 18) and claims-register row C14 were also removed.
- `versions/gemini.md`: the private Gemini chat link and a broken Google map placeholder. Gemini had no name, address or business plan to remove, and no utm tags. Your prompts are kept as written. They include some swearing, so delete them if you'd rather not publish them.

## Interested-party registration: now in the README

Gemini's advice to register as an interested party after the application is accepted is **confirmed** by the council's report and by the gov.uk pre-examination guidance. It is now in the README under "What this consultation is, and what comes next".

One part is still unconfirmed: Gemini says anyone who doesn't register loses the right to submit evidence or speak at hearings. Check that in the Planning Inspectorate guidance before repeating it.
