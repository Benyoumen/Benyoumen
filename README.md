<!-- Images are served from GitHub Pages (benyoumen.github.io/Benyoumen) so they still load when raw.githubusercontent.com is down. Edit the files in assets/, push, and Pages republishes them. -->

<p align="center"><img src="https://benyoumen.github.io/Benyoumen/assets/banner.svg?v=3" alt="Benjamin Tayar, Forward Deployed PM building AI products and agents" width="100%"></p>

<h2 align="center">Hi, I'm Ben 👋</h2>

<p align="center"><b>Forward Deployed PM in São Paulo. I find the problem worth solving, decide what to build first, and build it with AI, without the slop.</b></p>

## About me

I have 17 years of experience building digital products, as VP Product & Growth, CEO and founder. I scaled a B2B SaaS platform used by thousands of real estate businesses.

Since 2023, I build AI products and AI agents. I also teach product, executive and engineering teams how to work with them.

Most of my energy goes into two things: finding the right problem, and putting the work in the right order.

## Recent work: an AI sales assistant

I built a multi-agent system that supports salespeople from prospecting to forecast. It researches and qualifies accounts, finds similar customers to prospect, and prepares sellers for meetings. It also keeps the CRM up to date and flags risks in the pipeline.

- **From 2 days to 30 minutes** to prepare an account.
- **90% adoption** across the teams using it.
- **1 to 2 hours saved** per salesperson, every day.

Three rules shaped the design:

1. Use fixed rules where the process is known. Use AI only where judgment adds value.
2. A person approves before the agent writes to the CRM, until the agent earns more autonomy.
3. Agree on the business KPI and its baseline before building anything.

## Forward Deployed PM

I work as a Forward Deployed PM: inside the client's operation, next to the people who do the job. I learn their workflow in detail. Then I build the agent where they already work: their CRM, their spreadsheet or their chat tool.

Nobody relays the problem through a chain of handoffs. I hear it directly from the people who have it, so the solution fits the real constraint.

Four rules keep this work from turning into one-off consulting:

- **Outcome first, then scale.** First, a result the client can measure. Then, a version we can repeat.
- **Build once, reuse often.** A piece built for one client is designed so the next client can use it too.
- **Function over form.** If people don't use what we built, we change it, even if we liked it.
- **Value that stays.** The client's team runs and corrects the agent with its own evals. The value should not leave when I do.

## How I work

<p align="center"><img src="https://benyoumen.github.io/Benyoumen/assets/product-loop.svg?v=2" alt="The 4D product loop: 1 Discover, 2 Design, 3 Develop, 4 Deploy, then the next loop" width="100%"></p>

I follow the 4D method from Product Faculty: Discover, Design, Develop and Deploy. Each phase ends with a clear check. If the check fails, the work goes back one phase. The loop is the same for a client's operation and for a product with many customers.

Prioritization gets as much care as discovery. I rank work by user value, KPI impact, expected ROI, effort and dependencies. Sometimes a small feature goes first because a bigger one depends on it.

<p align="center"><img src="https://benyoumen.github.io/Benyoumen/assets/autonomy-ladder.svg?v=2" alt="How an AI agent earns autonomy: 1 Suggest, 2 Recommend, 3 Approve, 4 Veto window, 5 Act and report" width="100%"></p>

The levels follow Sheridan's scale of automation, the model Product Faculty uses to design AI features. An agent gets a level per type of action, not one level overall. For example, it may log a note on its own but still need approval to send an email. To move up, it needs evidence: a pass rate on real test cases, a trial run next to the team, a working undo, and the process owner's sign-off.

## How I evaluate AI agents

<p align="center"><img src="https://benyoumen.github.io/Benyoumen/assets/evals-loops.svg" alt="Two eval loops. Offline decides if a change may ship. Online finds what the agent gets wrong. Each new failure becomes a test case." width="100%"></p>

I treat evals as product work. Before a change ships, it must pass a fixed dataset with code checks and a validated LLM judge, in repeated runs. After it ships, every run is traced, users rate the output, and each new failure becomes a test case.

- **Code before judges.** Anything a rule can check goes in code. A judge covers only what needs interpretation.
- **One judge, one failure.** Pass or Fail, never a 1 to 5 score, and no trust before it agrees with human labels.
- **Honest numbers.** Zero failures in 10 cases does not mean 100% accuracy. I state the margin.
- **Watch it after launch.** A nine-step production loop with alerts and a 30-minute weekly review of the worst runs.

The full version of the method: [AI evals workflow](https://github.com/Benyoumen/ai-evals-method) · [Production monitoring](https://github.com/Benyoumen/ai-evals-method/blob/main/docs/production-monitoring.md) · [RAG evals](https://github.com/Benyoumen/ai-evals-method/blob/main/docs/rag-evals.md) · [LLM-as-a-Judge](https://github.com/Benyoumen/ai-evals-method/blob/main/docs/llm-as-a-judge.md) · [the backlog workflow](https://github.com/Benyoumen/backlog-writing-system/blob/main/docs/workflow.md) · [the agent principles](https://github.com/Benyoumen/agent-design-principles/blob/main/docs/principles.md).

## What you'll find here

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Benyoumen/backlog-writing-system"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/backlog.svg" alt="Backlog Writing System" width="100%"></a>
      <p><b>Backlog Writing System.</b> My method from problem to weekly delivery: a Now / Next / Later roadmap, readable specs, a capacity simulator, and evals for AI behavior. 21 skills and a worked example.<br><a href="https://benyoumen.github.io/backlog-writing-system/">Field guide</a> · <a href="https://benyoumen.github.io/backlog-writing-system/capacity.html">Capacity simulator</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Benyoumen/no-slop-design"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/noslop.svg" alt="No-slop design" width="100%"></a>
      <p><b>No-slop design.</b> How to spot screens that look generic and AI-made, and how to fix them. Each live mockup sits next to its generic version.<br><a href="https://benyoumen.github.io/no-slop-design/">Mockup gallery</a> · <a href="https://github.com/Benyoumen/no-slop-design/blob/main/docs/visual-slop-tells.md">The 16 tells</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Benyoumen/ai-evals-method"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/evals.svg" alt="AI Evals Method" width="100%"></a>
      <p><b>AI Evals Method.</b> How I measure, improve and ship an agent: traces, datasets, experiments, a validated judge and a six-point release gate. Built and tested with Arize AX.<br><a href="https://github.com/Benyoumen/ai-evals-method#the-workflow">The workflow</a> · <a href="https://github.com/Benyoumen/ai-evals-method/blob/main/docs/production-monitoring.md">Monitoring</a> · <a href="https://github.com/Benyoumen/ai-evals-method/blob/main/docs/rag-evals.md">RAG evals</a> · <a href="https://github.com/Benyoumen/ai-evals-method#lessons-from-running-it">Lessons</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Benyoumen/ai-evals-method/blob/main/docs/llm-as-a-judge.md"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/judge.svg" alt="LLM-as-a-Judge" width="100%"></a>
      <p><b>LLM-as-a-Judge.</b> How to write a judge that can be trusted, and what the PM should decide. Includes a ready-to-adapt judge prompt.<br><a href="https://github.com/Benyoumen/ai-evals-method/blob/main/docs/llm-as-a-judge.md">The method</a> · <a href="https://github.com/Benyoumen/ai-evals-method/blob/main/examples/evidence-supported-judge.md">Example judge</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Benyoumen/nextstone-concept"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/nextstone.svg" alt="NextStone concept" width="100%"></a>
      <p><b>NextStone.</b> A full product concept: a marketplace where real estate developers meet investment funds. Four roles, each with its own dashboard.<br><a href="https://benyoumen.github.io/nextstone-concept/">Live demo</a> · <a href="https://github.com/Benyoumen/nextstone-concept#readme">Case study</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Benyoumen/agent-design-principles"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/agent.svg" alt="Agent Design Principles" width="100%"></a>
      <p><b>Agent Design Principles.</b> How an agent earns autonomy, how it writes safely to a system of record, and how to design screens people use all day.<br><a href="https://github.com/Benyoumen/agent-design-principles/blob/main/docs/principles.md">Read the principles</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Benyoumen/pm-deck-and-writing-skills"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/deck.svg" alt="PM Deck and Writing Skills" width="100%"></a>
      <p><b>PM Deck and Writing Skills.</b> Rules and a QA pipeline for decks and project messages that read as professional, not AI-generated. The sample deck follows its own rules.<br><a href="https://benyoumen.github.io/pm-deck-and-writing-skills/">Live deck</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://benyoumen.github.io/backlog-writing-system/backlog-document.html"><img src="https://benyoumen.github.io/Benyoumen/assets/cards/backlogdoc.svg" alt="The backlog document" width="100%"></a>
      <p><b>The backlog document.</b> One page to review a whole backlog before it goes to Jira or Azure DevOps. Set owners and story points, and see each person's load against their capacity.<br><a href="https://benyoumen.github.io/backlog-writing-system/backlog-document.html">Open the document</a> · <a href="https://benyoumen.github.io/backlog-writing-system/spec-preview.html">Spec preview</a></p>
    </td>
  </tr>
</table>

Every example uses a fictional product and fictional data. Nothing comes from a customer or an employer.

## Teaching

I co-designed and delivered AI adoption programs for about 3,000 leaders, product managers and developers. Partners include FGV, Secovi-SP and LARES. The programs teach teams to find high-value AI use cases, link them to KPIs and ROI, and redesign their workflows.

## Certifications

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://lms.productfaculty.com/verify/benjamin-tayar-60888"><img src="https://benyoumen.github.io/Benyoumen/assets/certs/productfaculty-aipm.svg?v=2" alt="Product Faculty, AI Product Management Certificate" width="100%"></a>
      <p><b>AI Product Management.</b> Product Faculty. <a href="https://lms.productfaculty.com/verify/benjamin-tayar-60888">Verify the certificate</a>. Taught by Rohan Varma (Product, Codex at OpenAI) and Shubham Saboo (Senior AI Product Manager, Google).</p>
    </td>
    <td width="33%" valign="top">
      <a href="#certifications"><img src="https://benyoumen.github.io/Benyoumen/assets/certs/lewagon-data.svg" alt="Le Wagon, Data Science and AI" width="100%"></a>
      <p><b>Data Science and AI.</b> Le Wagon bootcamp. Python, machine learning, deep learning and models in production.</p>
    </td>
    <td width="33%" valign="top">
      <a href="#certifications"><img src="https://benyoumen.github.io/Benyoumen/assets/certs/lewagon-web.svg" alt="Le Wagon, Web Development" width="100%"></a>
      <p><b>Web Development.</b> Le Wagon bootcamp. Full-stack web apps, from database to interface.</p>
    </td>
  </tr>
</table>

## Background

- 17 years in product, B2B SaaS, growth and digital platforms. Former VP Product & Growth, CEO and founder.
- Two master's degrees in law and an MBA in real estate management (ESSEC).
- Trained in Paris, based in São Paulo, working internationally.
- Native French, fluent English and Portuguese.

## Open to

**Forward Deployed PM · Head of AI Product · Director of Product · Group PM · Senior AI PM**

Remote roles across the US, Europe and Latin America.
