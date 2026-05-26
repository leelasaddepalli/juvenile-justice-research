# Juvenile Justice Research

A child's fate in the justice system often depends less on their conduct than on their zip code. This repository contains two complementary research projects examining that reality from different angles: one mapping the systemic and political forces that shape juvenile outcomes across states, and one documenting the human cost of those systems and proposing evidence-backed alternatives.

---

## Part One: Different States, Different Fates

**Course:** POL 342: Law and Judicial Policy, Washington and Lee University

### Research Question
Under what conditions do states transfer juveniles to adult status — and is that a function of political ideology?

### Approach
This paper compares juvenile justice frameworks across three states representing distinct political identities: California (liberal), Virginia (moderate/control), and Florida (conservative). Each state's system is evaluated across three domains:

- **Legal rules** — minimum age for criminal responsibility, minimum age for juvenile court jurisdiction, and age of transfer eligibility
- **Legal policies** — pre-judicial discretion, mandatory sentencing requirements, and prosecutorial discretion
- **Legal resources** — average public defender compensation, number of juvenile detention facilities, and minimum judicial experience requirements

Each variable was scored on a 0–1 scale, with reverse scoring applied where higher values indicated more punitive policy (e.g., statutory exclusion, prosecutorial discretion). Scores were aggregated by category and correlated against 2023 juvenile intake and transfer data.

### Key Findings
In 2023, Florida recorded 991 juvenile transfers to adult status, Virginia 33, and California 12. Correlation analysis across all three legal domains showed strong negative relationships between political liberalism scores and both juvenile arrest rates (r = –0.97 to –1.00) and transfer rates (r = –0.87 to –0.97).

The data supports both hypotheses: higher political liberalism is associated with lower rates of juvenile arrests and transfers, and transfer rates follow the expected pattern of Florida > Virginia > California.

### Limitations
The study is limited to a single year and three states. Demographic differences, recidivism rates, and absolute youth population sizes were not fully controlled for. The 0–1 scoring scale simplifies complex policy differences. These findings suggest correlation, not causation, and call for longitudinal and multi-state replication.

📄 [Different States, Different Fates (PDF)](./Different_States_Different_Fates.pdf)

---

## Part Two: Stolen Childhoods

**Course:** Poverty and Human Capability Studies Capstone, Washington and Lee University

### Argument
Young people who encounter the justice system are not simply rule-breakers being appropriately corrected. They are children whose capabilities — as defined by Martha Nussbaum's capabilities approach — are being structurally curtailed, often before they have the cognitive or social development to understand the consequences. These harms fall disproportionately on Black, Hispanic, and economically disadvantaged youth, and they are not incidental to the system: they are the system working as designed.

The paper is structured in three parts.

**Part One: The lasting harms of punitive discipline**
Documents the collateral consequences of juvenile justice involvement across five domains: psychological and physical health, educational opportunity, economic and social development, legal standing, and recidivism. Key evidence includes a longitudinal Seattle study finding incarcerated youth four times more likely to be incarcerated as adults, a 2019 study finding confined youth four times less likely to complete high school, and Prison Policy Initiative data showing formerly incarcerated individuals face unemployment rates exceeding 27%.

**Part Two: The school-to-prison pipeline**
Traces the structural origins of juvenile criminalization through Jonathan Eastwood's social structures framework — examining rules (zero-tolerance discipline policies, three-strikes laws), representations (the "super predator" myth, racial profiling), and relationships (undertrained SROs, biased referral practices). Draws on Virginia-specific data showing Black students, at 22% of K-12 enrollment, experienced 42% of all exclusionary discipline.

**Part Three: Advocating for restorative solutions**
Proposes three concrete, evidence-backed interventions for Rockbridge County Public Schools: Calm Corners (classroom-based emotional regulation spaces as an alternative to suspension), Restorative Circles (pre-charge community accountability processes), and Student Advocates (trained volunteers to represent students in disciplinary hearings, funded through Communities in Schools grants). Engages contractualist and utilitarian objections to each proposal.

📄 [Stolen Childhoods (PDF)](./Stolen_Childhoods_Capstone_Paper.pdf)

---

## Data & Methods

| | Different States, Different Fates | Stolen Childhoods |
|---|---|---|
| Primary data | 2023 state juvenile justice reports (CA, VA, FL) | Virginia DOE school climate data, federal victimization surveys |
| Analytical approach | Comparative policy scoring, Pearson correlation | Capabilities framework, structural analysis, policy review |
| Tools | R, ggplot2 | Qualitative synthesis, data visualization |
| Frameworks | Political liberalism operationalization | Nussbaum capabilities approach, Eastwood social structures |

---

## Policy Implications

Together, these papers make a linked argument: conservative legal frameworks produce higher rates of juvenile transfer (Part One), and those transfers cause serious, measurable, and lasting harm to the children they affect (Part Two). The logical conclusion is a need for federal minimum standards — including a national minimum age for adult transfer, limits on prosecutorial discretion, and mandatory trauma-informed assessment before transfer decisions — alongside school-level restorative practices that interrupt the pipeline before children reach the courtroom.
