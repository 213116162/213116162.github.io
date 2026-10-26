# Industry placement: Agile portfolio

**Student:** Phumelela Nzewu (213116162)  
**Qualification:** Diploma in ICT: Communication Networks, CPUT  
**Subject:** Project Presentation 3 (PRP370S), Assessment 2  
**Host employer:** Huawei Technologies, Information Technology department  
**Role:** Optical Network Engineer  
**Mentor:** Mohammed Bismilla  
**Project:** Optical transmission network (OTN) site delivery: design, preparation and customer handover  
**Period covered:** 29 June to 28 August 2026, as nine one-week sprints  

Customer names, site names, addresses, IP plans and firmware versions are left out of this portfolio because they belong to the customer.

## Contents

1. [Agile team charter](#1-agile-team-charter)
2. [User stories and tasks](#2-user-stories-and-tasks)
3. [Product backlog](#3-product-backlog)
4. [Sprint backlog](#4-sprint-backlog)
5. [Agile logbook](#5-agile-logbook)

The five artefacts follow the order of the work. The charter sets the rules. The user stories turn the project into requests from users. The product backlog ranks those stories. The sprint backlog picks from the top of the backlog for one week. The logbook records what happened in each sprint.

---

## 1. Agile team charter

### Evidence

**Project:** OTN site delivery for a customer. Each site goes through the same path: site detail design, installation and configuration, preparation for acceptance, then handover.

**Purpose:** Deliver optical transmission network sites that are documented correctly, labelled correctly and working when the customer accepts them.

**Team and roles**

| Name | Role | Responsibility |
|---|---|---|
| Phumelela Nzewu | Optical Network Engineer (WIL learner) | Site detail design, OTN planning, hardware installation and configuration, site preparation, handover support |
| Mohammed Bismilla | Mentor | Reviews work, signs the monthly report and attendance register |

**Values**

- Accurate documentation. A design document is the instruction the installer works from.
- Working sites at handover. A site is ready when its services work, not when the equipment is powered.
- Early questions. If a design detail is unclear, ask before installation.
- Open updates. Progress and problems are said at the stand-up.

**Working agreements**

- Daily stand-up with the team.
- Working days are Monday to Friday, 08h00 to 17h00.
- Work runs in one-week sprints, from Monday to Friday.
- Every design document includes the equipment layout, the firmware to be installed, the fibre and power cabling diagram, and the board layout inside the chassis.
- Labelling and documentation are checked against the design before a site is offered for acceptance.
- Changes to the agreed equipment list or firmware version need approval before the design is updated.
- A monthly report and attendance register go to the mentor for signature.

**Definition of done for a site**

1. The site detail design is complete and reviewed.
2. The equipment is installed and configured as designed.
3. Labelling and documentation match the installed equipment.
4. Services are tested and working.
5. The customer has seen the installation quality and the equipment functionality at handover.

**Boundaries**

- In scope: OTN planning and design, site detail design, installation and configuration, site preparation, handover.
- Out of scope: Customer network design decisions outside the agreed scope.
- Escalation: Problems that block a sprint goal go to the mentor on the day they are found.

### Reflection

Writing the charter made me state rules I already followed without thinking. The daily stand-up, the 08h00 to 17h00 day and the mentor signature on my monthly report all existed at work, but they lived in habit. Putting them on one page showed me which agreements protect the handover date.

The labelling and documentation check is one of them. In August I spent two full weeks preparing sites for acceptance. The definition of done explains why that time was needed: a site is finished when the customer can verify it, not when the equipment works.

The weak point is that I wrote the charter from my side. I am the only learner, and the team members are colleagues, not students. Next time I would read it out at a stand-up and change whatever does not match how the team works.

---

## 2. User stories and tasks

### Evidence


**US-01 Site detail design**
As an installation engineer, I want a complete site detail design, so that I can install the site without guessing the layout, firmware or cabling.

- Acceptance criteria: equipment layout, firmware, fibre and power cabling diagram and chassis board layout are all in the document.
- Tasks: collect site information; draw the equipment layout; record the firmware to install; draw the fibre and power cabling diagram; list the boards in each chassis; review the document.
- Volume delivered: 28 sites (week of 20 July), 37 sites (week of 27 July), 22 sites (week of 3 August). Total 87.

**US-02 Capacity expansion**
As the customer's network owner, I want more capacity on my existing optical network, so that it carries more throughput.

- Acceptance criteria: expansion plan and design agreed; hardware installed; configuration complete; capacity confirmed.
- Tasks: review the existing network; plan the expansion; produce the design; install the expansion hardware; configure the equipment; verify capacity.
- Delivered: planning and design in the week of 6 July, installation and configuration in the week of 13 July.

**US-03 Site preparation**
As the handover lead, I want each site's labelling, documentation and services checked before acceptance, so that the customer accepts the site at the first visit.

- Acceptance criteria: labels match the design; documentation is correct; services work as expected.
- Tasks: compare labels with the design; check documentation against installed equipment; test services; fix differences.
- Delivered: weeks of 10 and 17 August.

**US-04 Site acceptance**
As the customer's representative, I want a demonstration of installation quality and equipment functionality, so that I can accept the site.

- Acceptance criteria: quality walkthrough done; functionality confirmed on site; acceptance recorded.
- Tasks: agree the site list and date; prepare the demonstration; run the walkthrough and functionality checks; record the result.
- Delivered: 18 sites (week of 29 June), 14 sites (week of 24 August). Total 32.

**US-05 Placement reporting**
As the WIL mentor, I want a monthly report and attendance register, so that progress and attendance are on record.

- Acceptance criteria: work done for each week is described; the register is complete; both are signed.
- Tasks: write the weekly summaries; complete the register; send both for signature.

### Reflection

Writing stories from the user's side changed how I read my own tasks. "Site detail design for 28 sites" sounds like a document count. As a story, it is something an installer needs so that nobody opens a chassis and has to guess which board goes where. The acceptance criteria forced me to say what done looks like before I started.

Splitting stories into tasks also made the volume visible. Eighty-seven designs in three weeks is workable because the steps repeat for every site.

My first draft of US-02 was too large. It covered planning, installation and configuration in one story. In a sprint plan that would not fit one week, so I would split it into a planning story and an installation story.

---

## 3. Product backlog

### Evidence

The backlog is ordered by priority. Points are my relative estimates (1 is a small task, 13 is a full week of work).

| ID | Item | Story | Priority | Points | Status | Sprint |
|---|---|---|---|---|---|---|
| PB-01 | Site acceptance, first batch of 18 sites | US-04 | High | 8 | Done | S1 |
| PB-02 | OTN expansion: planning and design | US-02 | High | 8 | Done | S2 |
| PB-03 | OTN expansion: hardware installation and configuration | US-02 | High | 8 | Done | S3 |
| PB-04 | Site detail design, 28 sites | US-01 | High | 8 | Done | S4 |
| PB-05 | Site detail design, 37 sites | US-01 | High | 13 | Done | S5 |
| PB-06 | Site detail design, 22 sites | US-01 | High | 8 | Done | S6 |
| PB-07 | Site preparation: labelling, documentation, service checks | US-03 | High | 5 | Done | S7 |
| PB-08 | Site preparation, continued | US-03 | High | 5 | Done | S8 |
| PB-09 | Site acceptance, 14 sites | US-04 | High | 8 | Done | S9 |
| PB-10 | July report and attendance register | US-05 | Medium | 2 | Done | S1 to S5 |
| PB-11 | August report and attendance register | US-05 | Medium | 2 | Done | S6 to S9 |
| PB-12 | Install the sites designed in July and August | US-01 | High | 8 | Done | S9 |

### Reflection

The order of the backlog follows dependencies, not effort. Design comes first because installation, preparation and handover all depend on it. Preparation sits before handover because a site that fails the customer's check costs another visit.

Estimating was harder for design work than for the other items. PB-04, PB-05 and PB-06 are the same story with 28, 37 and 22 sites, and the load is different each time. I scored the 37-site batch higher for that reason. A better method is to size one site and multiply, then compare that with what the team can finish in a week.

The backlog also showed me that the July and August work follows one cycle: design, prepare, hand over. PB-12 starts that cycle again with the next batch of sites.

---

## 4. Sprint backlog

### Evidence

**Sprint overview**

| Sprint | Dates | Goal |
|---|---|---|
| S1 | 29 Jun to 3 Jul | Hand over 18 sites |
| S2 | 6 to 10 Jul | Plan and design the capacity expansion |
| S3 | 13 to 17 Jul | Install and configure the expansion hardware |
| S4 | 20 to 24 Jul | Site detail design for 28 sites |
| S5 | 27 to 31 Jul | Site detail design for 37 sites |
| S6 | 3 to 7 Aug | Site detail design for 22 sites |
| S7 | 10 to 14 Aug | Prepare sites for acceptance |
| S8 | 17 to 21 Aug | Prepare sites for acceptance |
| S9 | 24 to 28 Aug | Hand over 14 sites |

**Sprint 9 in detail (24 to 28 August)**

**Sprint goal:** Hand over 14 sites to the customer, with the customer shown the installation quality and the equipment functionality.

| ID | Task | Story | Day | Status |
|---|---|---|---|---|
| T-01 | Confirm the site list and acceptance date with the customer | US-04 | Mon | Done |
| T-02 | Final check of labels against the design, all 14 sites | US-03 | Mon | Done |
| T-03 | Check documentation matches the installed equipment | US-03 | Tue | Done |
| T-04 | Test services and record results | US-03 | Tue to Wed | Done |
| T-05 | Prepare the demonstration: quality walkthrough and functionality checks | US-04 | Wed | Done |
| T-06 | Hand over the sites and demonstrate to the customer | US-04 | Thu to Fri | Done |
| T-07 | Record the outcome and any open items | US-04 | Fri | Done |
| T-08 | Complete the August report and attendance register | US-05 | Fri | Done |

### Reflection

A sprint goal of "14 sites handed over" only works if the earlier sprints are finished. By Sprint 9, almost no new work was left. The tasks were checks and the customer demonstration, and that is the reason the goal was realistic for one week.

The sprint backlog also gave me a daily picture that the product backlog does not. At each stand-up I could see which task was open and whether it threatened Friday's handover. Tasks T-03 and T-04 were the ones with the most risk, because a failed service test cannot be fixed on the day of the demonstration.

If I plan another handover sprint, I will add a buffer day before the customer visit. Sprint 9 had none, and any failed check would have pushed the handover into the next sprint.

---

## 5. Agile logbook

### Evidence

**Stand-up format**

- Yesterday: what I finished.
- Today: what I will work on.
- Blockers: anything stopping the sprint goal.

**Sample entry, Monday 24 August**

- Yesterday: finished preparing the remaining sites for acceptance.
- Today: final label check on all 14 sites; confirm the acceptance date with the customer.
- Blockers: none.

**Sprint log**

| Sprint | Dates | Goal and outcome | Retrospective |
|---|---|---|---|
| S1 | 29 Jun to 3 Jul | Handed over 18 sites. | Went well: the handover demonstration ran the same way at each site. Change: keep one written order for the functionality checks. |
| S2 | 6 to 10 Jul | Expansion planned and designed. | Went well: the plan was ready for installation the following week. Change: agree the capacity target before drafting the design. |
| S3 | 13 to 17 Jul | Expansion hardware installed and configured. | Went well: installation followed the design. Change: check the configuration against the plan at the end of each day. |
| S4 | 20 to 24 Jul | Site detail design for 28 sites. | Went well: a repeatable design routine. Change: review designs in batches to catch repeated mistakes. |
| S5 | 27 to 31 Jul | Site detail design for 37 sites. | Went well: the routine held at a higher volume. Change: split the batch across the week with a review point mid-sprint. |
| S6 | 3 to 7 Aug | Site detail design for 22 sites. | Went well: the smaller batch left time for review. Change: finish designs by Thursday so Friday is for checking. |
| S7 | 10 to 14 Aug | Prepared sites for acceptance: labels, documentation, services. | Went well: checks were done against the design document. Change: record each fix as it is made. |
| S8 | 17 to 21 Aug | Continued site preparation. | Went well: remaining differences were closed. Change: finish service tests earlier in the week. |
| S9 | 24 to 28 Aug | Handed over 14 sites. | Went well: preparation in S7 and S8 made the demonstration straightforward. Change: add a buffer day before the customer visit. |

**Supporting evidence**

- July internship report and attendance register: [link or redacted PDF]
- August internship report and attendance register: [link or redacted PDF]

### Reflection

The logbook is where I saw the pattern across the nine weeks. July and August follow one cycle: design the sites, prepare them, hand them over. The retrospective notes repeat one theme. Work done earlier in the cycle decides how calm the handover week is.

Before this assessment I treated the weekly report as the record of my work. The logbook is more useful because it records what I would change, not only what I did. The "change" column gave me an action for each sprint, and several of them, such as batching design reviews and adding a buffer day, apply to the next batch of sites.

The main gap is detail. My reports describe each week in a paragraph. A logbook kept every day would show the small blockers that a weekly summary hides, so I will write the stand-up entry at the end of each day from now on.
