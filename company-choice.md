# Company Choice — Milestone 0

## My company: Nexova Solutions

I chose **Nexova Solutions**, the HR and talent-acquisition consultancy based in Valencia (Spain) with an expansion office in Miami. What convinced me is that at Nexova AI is not a side tool but the competitive advantage itself: CV scoring, candidate matching, RAG over a knowledge base and first-line support agents sit at the core of how the company earns its money. The problems are concrete and measurable: 40 recruiters read between 30 and 80 CVs per search by hand, clients have to call to find out where their candidates are, and the outsourced support team takes 48 hours on average to resolve a ticket against a committed SLA of 24. My background is in business administration, marketing and delivering training, so I understand the commercial and training sides of the business, and I know the candidate side of a hiring process first-hand. Nexova also means building for five very different teams, which is the kind of cross-functional work I want my portfolio to show.

## Departments I find most interesting

### 1. Recruitment Operations (Javier Almeida)
This is the core business and the place where AI has the biggest impact. Screening is fully manual, there is no real-time status for candidates, and the match between candidate and vacancy depends entirely on each consultant's intuition. An AI-assisted pipeline with explainable rankings could save hours on every search and help Nexova keep its delivery times (6 to 8 weeks for managerial and executive searches).

### 2. Corporate Training (Elena Vargas)
The catalogue lives in a PDF updated once a quarter, enrolments go through a Google Form that someone copies into a spreadsheet by hand, and every client receives the same proposal. A searchable catalogue with recommendations based on each client's profile would turn a static brochure into a sales tool. I have delivered training myself, so this department is especially close to my experience.

## The challenge I most look forward to building

The **AI-assisted recruitment pipeline**: automatic CV scoring and ranking with an explanation for every score, plus a RAG search over the candidate database so that a consultant can ask, for example, *"find profiles with B2B sales experience and C1 English"*. It brings together several things I want to master in this course: data pipelines, retrieval, agents and the evaluation of AI output.

## My AI Agent Idea

**Screening Agent for Recruitment Operations**

- **What it does:** when a consultant opens a new search, the agent reads the client's job brief, screens every incoming CV against it and proposes a ranked shortlist. Each candidate gets a score, a two-line justification and the list of must-have requirements they are missing. It also drafts status-update emails to candidates and keeps each candidate's stage up to date, so clients can follow progress without calling.
- **Information it needs:**
  - the job brief: role, seniority, must-have and nice-to-have skills, languages and level, location and salary band;
  - the CVs (PDF or text) and the history of the candidate database;
  - Nexova's delivery commitments, for example: escalate an executive search to Javier Almeida if there is no qualified candidate after 4 weeks;
  - the email templates and the current stage of each candidate.
- **What it produces or triggers:**
  - a ranked, explained shortlist in the consultant's dashboard;
  - draft emails to candidates, sent only after the consultant approves them;
  - an alert to the consultant, and an escalation to Javier Almeida, when a search is at risk of missing its delivery time.
- **Guardrails:** the consultant always makes the final decision (human in the loop). The agent never rejects a candidate on its own, and it ignores personal attributes such as age, gender, photo or nationality to reduce bias and respect GDPR.
