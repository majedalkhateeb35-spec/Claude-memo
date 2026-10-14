# SpearX / SpearAI — website copy deck

Paste-ready copy for the eleven product sections. Each block is: eyebrow, headline,
body, three proof points, screenshot caption.

**Open items before this goes live** are listed at the bottom. Read them first.

---

## 0. Hero

**Eyebrow:** SpearX platform · powered by SpearAI
**Headline:** One platform. A team of AI agents. Every alert answered.
**Body:** SpearX puts detection, threat intelligence, vulnerabilities, cloud posture and file
integrity on a single data model. SpearAI puts a team of specialist agents on top of it, so a
signal arrives already triaged, enriched and explained, with the evidence attached and a human
in control of anything that changes state.
**CTAs:** Book a walkthrough · See the agent canvas

| Proof point | Supporting line |
|---|---|
| One data model | Endpoint, cloud, identity and intel joined once, queried everywhere. |
| Agents you can watch | Every step, input and output of a run is on the canvas and in the log. |
| Evidence on every verdict | No conclusion without the artefacts that produced it. |

---

## 1. Agent canvas (SpearAI)

**Eyebrow:** SpearAI · agent canvas
**Headline:** Your analysts get a team, not a chat box.
**Body:** Specialist agents hand work to each other on a canvas you can watch, pause and take
over. They share one evidence store, so nothing is asked twice, and nothing that changes your
estate happens without an analyst approving it.

- Triage, enrichment, correlation, hunt and response each run as their own agent with its own tools and limits.
- Every step is recorded with its inputs, outputs, tool calls and cost, so a run can be replayed and audited.
- Containment waits at an approval gate. The agent proposes, a named analyst decides.

**Caption:** SpearAI agent canvas — agents hand off left to right, share one evidence store, and stop at a human gate before anything is contained.

---

## 2. Threat intelligence

**Eyebrow:** Threat intelligence
**Headline:** Intelligence that lands on your assets, not in a PDF.
**Body:** Feeds are normalised, deduplicated and confidence-scored, then matched continuously
against your own telemetry. You see which indicators actually touched your estate, on which
host, at what time, and what the agents did about it.

- Actor and campaign tracking mapped to ATT&CK techniques, so intel arrives as detection logic rather than reading material.
- Confidence and decay scoring retires stale indicators instead of letting them generate noise forever.
- Retro-hunt sweeps every new indicator back across your history the moment it lands.

**Caption:** Threat intelligence — indicators scored, matched against live telemetry, and shown with the hosts they actually touched.

---

## 3. Entity risk

**Eyebrow:** Entity risk
**Headline:** Risk that points at a name, not a number.
**Body:** Every user, host, service account and workload carries a risk score built from its own
behavioural baseline and its peer group. The score is never a black box: the contributing
signals are listed, weighted and clickable down to the raw event.

- Behavioural baselines per entity and per peer group, so "unusual" means unusual for that account, not for the average one.
- Score movement is explained by its drivers, with the weight each one contributed.
- Watchlists and risk thresholds feed the agents directly, raising scrutiny before an incident, not after.

**Caption:** Entity risk — scores with their drivers shown and weighted, measured against each entity's own baseline and its peer group.

---

## 4. MITRE ATT&CK coverage

**Eyebrow:** MITRE ATT&CK coverage
**Headline:** Know what you would catch before someone asks you.
**Body:** Every detection in SpearX is mapped to the techniques it covers, so coverage is a
measured property of your deployment rather than a claim on a slide. The gaps are listed with
the telemetry that would close them.

- Technique-level coverage computed from the detections and telemetry you actually have connected.
- Gaps come with the missing log source or rule named, so the next step is concrete.
- Observed techniques from live incidents overlay the same matrix, showing coverage against what is hitting you.

**Caption:** ATT&CK coverage — technique-level detection coverage, with every gap named alongside the telemetry that closes it.

---

## 5. Analysis canvas

**Eyebrow:** Analysis canvas
**Headline:** The whole investigation on one surface.
**Body:** The canvas is the case file. Entities, the path between them, the timeline and every
artefact sit together, so an analyst pivots across identity, endpoint, network and cloud
without changing tool or losing the thread. SpearAI lays out the first draft of the graph; the
analyst edits it.

- Pivot from any node to every related event, with the ATT&CK technique on the edge that connects them.
- Agent hypotheses are shown with their confidence and the evidence that confirmed or killed them.
- Export the canvas straight into a case, a report, or a detection rule for what you just found.

**Caption:** Analysis canvas — one surface holding the attack path, the timeline, the agents' hypotheses and the sealed evidence behind them.

---

## 6. Vulnerability management

**Eyebrow:** Vulnerability management
**Headline:** Patch what an attacker can actually reach.
**Body:** A severity score on its own cannot tell you what to fix first. SpearX narrows every
finding by exposure, exploit availability, network reachability and the value of the asset
behind it, so the queue your engineers get is short and defensible.

- Prioritisation chain you can inspect and tune, with the rule behind every stage shown.
- Remediation campaigns with owners and SLAs, tracked against the ticketing system you already use.
- Known-exploited and actively-targeted findings are promoted automatically from the intel module.

**Caption:** Vulnerability management — the prioritisation chain that turns 18 420 findings into a queue of 23, with every filter visible.

---

## 7. Cloud security posture (CSPM)

**Eyebrow:** Cloud security posture
**Headline:** Cloud posture, with the path to your data drawn.
**Body:** Misconfigurations across AWS, Azure and GCP are mapped to the control that fails and
the framework that requires it. SpearX then chains them into the paths that actually reach
sensitive data, so a public bucket and an over-permissive role stop being two separate tickets.

- One control library behind every cloud, so posture is comparable across providers instead of per-console.
- Attack paths chain identity, network and data findings into a single ranked route.
- Framework evidence is collected continuously, so an audit is an export rather than a project.

**Caption:** Cloud posture — findings tied to the control and framework they break, and chained into the paths that reach real data.

---

## 8. File integrity monitoring (FIM)

**Eyebrow:** File integrity monitoring
**Headline:** Know the moment a file changes, and who changed it.
**Body:** Baselines, hashes and permissions on the paths that matter, with the process and
account behind every change. Each change is checked against your approved change windows and
tickets, so routine deployment noise separates itself from the one edit nobody authorised.

- Before and after hashes with the diff for text and configuration files.
- Changes correlated against change tickets and maintenance windows, so unauthorised means unauthorised.
- Baseline drift tracked per path, with one click to re-baseline after an approved release.

**Caption:** File integrity monitoring — 4 912 changes in a day, 28 that nobody authorised, and three of them already attached to a live incident.

---

## 9. CQS analysis

**Eyebrow:** CQS analysis
**Headline:** One score your board can follow month to month.
**Body:** CQS rolls detection coverage, cloud posture, exposure, identity hygiene and response
performance into a single trendable number, and then shows exactly which drivers moved it.
Every component is traceable back to the module that produced it, so the score survives the
question "where does that come from?".

- Six weighted components, each one a live measurement rather than a questionnaire answer.
- Month-on-month movement attributed to named drivers, with the work that caused the change.
- Weights are yours to set, so the score reflects the risks your organisation actually cares about.

**Caption:** CQS analysis — one weighted score, six live components, and every month's movement attributed to a named driver.

---

## 10. Custom dashboards

**Eyebrow:** Custom dashboards
**Headline:** Build the view your team actually runs on.
**Body:** Drag any widget from any module onto a shared canvas. A SOC lead, a cloud team and an
audit committee need three different pictures of the same data, and none of them should need a
ticket to get one.

- Widgets from every module on one canvas, bound to the same filters and time range.
- Share with a team, embed in a wiki, or schedule as a snapshot to an inbox.
- Any widget opens into the module it came from, with your filters carried through.

**Caption:** Custom dashboards — widgets dragged from any module onto one canvas, every tile still linked back to its source.

---

## 11. Reporting

**Eyebrow:** Reporting
**Headline:** The report writes itself from the evidence.
**Body:** Reports are generated from the same evidence store the agents wrote to, so the
executive summary, the technique list and the remediation table all reconcile with the case
they came from. Pick the audience, pick the period, and the document is ready with its figures
already sourced.

- Executive, technical and audit templates drawn from one data set, so versions cannot drift apart.
- Every figure in the document links back to the query and artefacts that produced it.
- Scheduled distribution per audience, with classification and retention applied automatically.

**Caption:** Reporting — an executive document generated from the same evidence the agents used, with every figure traceable to its query.

---

## 12. Closing CTA

**Eyebrow:** See it on your own data
**Headline:** Bring one week of your telemetry. Watch the agents work it.
**Body:** A guided walkthrough runs on your environment, not a sandbox: we connect a sample of
your telemetry, run the agent canvas against it live, and leave you with the coverage map, the
prioritised queue and the first report it produced.

---

# Open items — resolve before publishing

1. **CQS is unexpanded.** I do not know what the acronym stands for, so the copy uses "CQS"
   on its own and describes only its structure. Supply the expansion and I will work it in.
   The six components and weights shown (detection coverage 25, cloud posture 20, exposure 20,
   response 15, identity hygiene 10, integrity 10) are my invention and need replacing with
   your real model.

2. **Product naming assumption.** The copy treats SpearX as the platform and SpearAI as the
   agent layer inside it. If that split is wrong, it is a find-and-replace across every section.

3. **No performance statistics anywhere.** There is deliberately no "cuts triage time by X%"
   or "reduces MTTR by Y". Those need a measured source before they go on a public site.
   The places that would normally carry one are the hero proof points and sections 1, 6 and 11.
   Give me measured figures and the method behind them, and I will write them in.

4. **All data in the screenshots is synthetic.** Host names, users, indicators, findings,
   scores, actor names (Hydra Panel, Silent Ferry, Pale Lantern, Dusk Adder, Cobalt Wren) and
   vulnerability IDs (VLN-2026-xxxx) are invented. External IPs use the IETF documentation
   ranges 192.0.2.0/24, 198.51.100.0/24 and 203.0.113.0/24, which never route.
   Source: RFC 5737, https://www.rfc-editor.org/rfc/rfc5737

5. **MITRE ATT&CK identifiers are real; the coverage numbers are not.** Tactic and technique
   IDs and names come from ATT&CK for Enterprise, https://attack.mitre.org/. The 67% weighted
   coverage figure is computed from the demo matrix itself ((29 full + 24 partial x 0.5) / 61)
   and means nothing about any real deployment. MITRE ATT&CK is a registered trademark of
   The MITRE Corporation; check their terms of use before shipping, as attribution is expected:
   https://attack.mitre.org/resources/legal-and-branding/terms-of-use/

6. **Framework names** (CIS Benchmarks, SOC 2, ISO/IEC 27001, PCI DSS 4.0, NIST CSF 2.0) are
   real standards shown with invented readiness percentages. Confirm you are entitled to name
   each one on marketing material before publishing.

7. **The "Demo data" chip** sits in the window chrome of all eleven screens, and the closing
   section states plainly that the interfaces are illustrative. I recommend keeping both.
   Removing them makes mockups read as photographs of a shipping product, which is the kind of
   claim a prospect's procurement team checks.
