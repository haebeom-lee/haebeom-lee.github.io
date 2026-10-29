---
permalink: /
title: "About me"
excerpt: "System 2 intelligence, world models, and scientific discovery"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="hb">

<p class="hb-intro">I am an Assistant Professor in the School of Electrical Engineering at Korea University. Previously, I was a postdoctoral researcher at KAIST, working with <a href="https://juho-lee.github.io/">Prof. Juho Lee</a>, and at Mila and Université de Montréal, working with <a href="https://yoshuabengio.org/">Prof. Yoshua Bengio</a>. I received my Ph.D. from KAIST, where I was advised by <a href="http://www.sungjuhwang.com/">Prof. Sung Ju Hwang</a>.</p>

<section class="hb-vision" id="research-vision" aria-labelledby="vision-title">
  <h2 class="hb-h2" id="vision-title">Research vision</h2>
  <p class="hb-statement">I want to build AI systems that can discover how the world works, accumulate what they learn, and reason with that knowledge.</p>

  <figure class="hb-loop">
    <svg class="hb-loop__svg" viewBox="0 0 640 440" role="img" aria-labelledby="loop-title loop-desc">
      <title id="loop-title">The discovery loop</title>
      <desc id="loop-desc">A cycle of five steps around a world model: propose hypotheses, make predictions, seek informative evidence, update the world model, and reason and act. Direction 1 covers the first three steps, Direction 2 the update step, and Direction 3 the reason and act step.</desc>
      <defs>
        <marker id="hb-arrow-d1" viewBox="0 0 10 10" refX="7" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
          <path d="M0,1 L9,5 L0,9 z" class="hb-arrowhead--d1"/>
        </marker>
        <marker id="hb-arrow-d2" viewBox="0 0 10 10" refX="7" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
          <path d="M0,1 L9,5 L0,9 z" class="hb-arrowhead--d2"/>
        </marker>
        <marker id="hb-arrow-d3" viewBox="0 0 10 10" refX="7" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
          <path d="M0,1 L9,5 L0,9 z" class="hb-arrowhead--d3"/>
        </marker>
      </defs>
      <!-- arcs: circle centre (320,220) r 150; nodes at -90, -18, 54, 126, 198 degrees -->
      <path class="hb-arc hb-arc--d1" d="M 346.0 72.3 A 150 150 0 0 1 449.9 145.0" marker-end="url(#hb-arrow-d1)"/>
      <path class="hb-arc hb-arc--d1" d="M 468.5 199.1 A 150 150 0 0 1 431.5 320.4" marker-end="url(#hb-arrow-d1)"/>
      <path class="hb-arc hb-arc--d2" d="M 385.8 354.8 A 150 150 0 0 1 259.0 357.0" marker-end="url(#hb-arrow-d2)"/>
      <path class="hb-arc hb-arc--d3" d="M 212.1 324.2 A 150 150 0 0 1 170.8 204.3" marker-end="url(#hb-arrow-d3)"/>
      <path class="hb-arc hb-arc--d1" d="M 187.6 149.6 A 150 150 0 0 1 288.8 73.3" marker-end="url(#hb-arrow-d1)"/>

      <g class="hb-core">
        <circle cx="320" cy="220" r="74"/>
        <text x="320" y="214" class="hb-core__title">World model</text>
        <text x="320" y="238" class="hb-core__sub">inspect, test, revise,</text>
        <text x="320" y="256" class="hb-core__sub">compose, reuse</text>
      </g>

      <g class="hb-node hb-node--d1"><circle cx="320" cy="70" r="15"/><text x="320" y="75" class="hb-node__num">1</text></g>
      <g class="hb-node hb-node--d1"><circle cx="462.7" cy="173.6" r="15"/><text x="462.7" y="178.6" class="hb-node__num">2</text></g>
      <g class="hb-node hb-node--d1"><circle cx="408.2" cy="341.4" r="15"/><text x="408.2" y="346.4" class="hb-node__num">3</text></g>
      <g class="hb-node hb-node--d2"><circle cx="231.8" cy="341.4" r="15"/><text x="231.8" y="346.4" class="hb-node__num">4</text></g>
      <g class="hb-node hb-node--d3"><circle cx="177.3" cy="173.6" r="15"/><text x="177.3" y="178.6" class="hb-node__num">5</text></g>

      <text x="320" y="38" class="hb-label" text-anchor="middle">Propose hypotheses</text>
      <text x="486" y="170" class="hb-label" text-anchor="start">Make</text>
      <text x="486" y="190" class="hb-label" text-anchor="start">predictions</text>
      <text x="430" y="384" class="hb-label" text-anchor="start">Seek informative</text>
      <text x="430" y="404" class="hb-label" text-anchor="start">evidence</text>
      <text x="210" y="384" class="hb-label" text-anchor="end">Update the</text>
      <text x="210" y="404" class="hb-label" text-anchor="end">world model</text>
      <text x="154" y="170" class="hb-label" text-anchor="end">Reason</text>
      <text x="154" y="190" class="hb-label" text-anchor="end">and act</text>
    </svg>
    <ol class="hb-loop__list">
      <li class="hb-d1">Propose hypotheses</li>
      <li class="hb-d1">Make predictions</li>
      <li class="hb-d1">Seek informative evidence</li>
      <li class="hb-d2">Update the world model</li>
      <li class="hb-d3">Reason and act, then repeat</li>
    </ol>
    <figcaption>The agents I envision run this loop continuously. In this view, scientific discovery, learning from experience, and planning are aspects of the same problem.</figcaption>
  </figure>

  <dl class="hb-terms">
    <div>
      <dt>System 2 intelligence</dt>
      <dd>Deliberate, evidence-grounded reasoning that forms hypotheses, weighs alternatives, recognizes uncertainty, and revises beliefs. Reasoning that is reliable and adaptive, not just longer.</dd>
    </div>
    <div>
      <dt>World model</dt>
      <dd>A structured, uncertainty-aware account of how a system works: its causal relationships, relational rules, mathematical laws, and mechanisms of change.</dd>
    </div>
  </dl>

  <details class="hb-more">
    <summary>Read the full research statement</summary>
    <p>My research is motivated by a fundamental question: <em>How can an AI system go beyond recognizing patterns to understand the mechanisms behind its observations, and use that understanding to solve new problems?</em> I view this as an important step toward <strong>System 2 intelligence</strong>: deliberate, evidence-grounded reasoning that can formulate hypotheses, evaluate alternatives, recognize uncertainty, and revise beliefs when new evidence arrives. The goal is not simply to make language models generate longer reasoning traces, but to make their reasoning more reliable, grounded, and adaptive.</p>
    <p>I believe <strong>world models</strong> are central to this goal. By a world model, I mean a structured and uncertainty-aware representation of how a system works: its causal relationships, relational rules, mathematical laws, and mechanisms of change. Rather than storing experience only as unstructured text or implicit model parameters, I am interested in <strong>explicit models that an agent can inspect, test, revise, compose, and reuse</strong> across different problems.</p>
    <p>Ultimately, I envision agents that operate in a continuous loop: <strong>propose hypotheses, make predictions, seek informative evidence, update their world models, and use the resulting knowledge to reason and act.</strong> In this view, scientific discovery, learning from experience, and intelligent planning are closely connected aspects of the same problem.</p>
  </details>
</section>

<section class="hb-directions" id="research-directions" aria-labelledby="directions-title">
  <h2 class="hb-h2" id="directions-title">Research directions</h2>
  <div class="hb-dir-grid">
    <article class="hb-dir hb-dir--d1">
      <p class="hb-dir__steps">Loop steps 1–3</p>
      <h3 class="hb-dir__title"><span class="hb-dir__n">1</span>Discovering world models from data and interaction</h3>
      <p class="hb-dir__q">How can AI infer the rules and mechanisms of an unfamiliar system from limited observations?</p>
      <ul class="hb-tags"><li>LLM-proposed hypotheses</li><li>Probabilistic inference</li><li>Active experimentation</li></ul>
      <details class="hb-more hb-more--sm">
        <summary>More</summary>
        <p>I study the discovery of mathematical, causal, and relational models, including the use of language models to propose hypotheses, probabilistic inference to evaluate them, and active experimentation to distinguish between competing explanations.</p>
      </details>
    </article>
    <article class="hb-dir hb-dir--d2">
      <p class="hb-dir__steps">Loop step 4</p>
      <h3 class="hb-dir__title"><span class="hb-dir__n">2</span>Accumulating, revising, and reusing knowledge</h3>
      <p class="hb-dir__q">How can agents turn experience into lasting knowledge that they can correct and build on?</p>
      <ul class="hb-tags"><li>Structured knowledge</li><li>Belief revision</li><li>Reuse of known mechanisms</li></ul>
      <details class="hb-more hb-more--sm">
        <summary>More</summary>
        <p>An intelligent system should learn more than isolated solutions to individual tasks. I am interested in how agents can consolidate experiences into persistent, structured knowledge; reconcile new evidence with prior beliefs; and identify and correct mistaken assumptions. Crucially, agents should be able to build on existing scientific knowledge, determine which known mechanisms apply to a new system, and discover what remains unknown. The aim is to develop world models that can be revised, composed, and reused instead of being reconstructed from scratch for every task.</p>
      </details>
    </article>
    <article class="hb-dir hb-dir--d3">
      <p class="hb-dir__steps">Loop step 5</p>
      <h3 class="hb-dir__title"><span class="hb-dir__n">3</span>Reasoning and planning with world models</h3>
      <p class="hb-dir__q">How can learned mechanisms and calibrated uncertainty guide what an agent does next?</p>
      <ul class="hb-tags"><li>Calibrated uncertainty</li><li>Experiment selection</li><li>Planning</li><li>Self-improving agents</li></ul>
      <details class="hb-more hb-more--sm">
        <summary>More</summary>
        <p>A world model should do more than explain past observations: it should guide future decisions. I investigate how agents can use learned mechanisms and calibrated uncertainty to reason through unfamiliar situations, select informative actions or experiments, and plan toward goals. This includes developing agents that can improve how they search, reason, and learn from their own experience.</p>
      </details>
    </article>
  </div>
  <p class="hb-tools">My work draws on Bayesian inference, language models, structured representations, and sequential decision-making, as tools toward AI that <strong>learns reusable knowledge about the world and reasons with it</strong>.</p>
</section>

<section class="hb-students" id="prospective-students" aria-labelledby="students-title">
  <h2 class="hb-h2" id="students-title">Prospective students</h2>
  <p>I welcome motivated students from electrical engineering, computer science, mathematics, and related fields who are excited by questions about intelligence, reasoning, and learning. If these directions interest you, please feel free to contact me.</p>
  <dl class="hb-req">
    <div><dt>Undergraduate interns</dt><dd>No prior AI or ML experience required. Curiosity, initiative, and enthusiasm for research matter most.</dd></div>
    <div><dt>Master’s students</dt><dd>Some background in AI or ML, shown through coursework, research internships, or relevant experience.</dd></div>
    <div><dt>Ph.D. students</dt><dd>At least one first-authored paper at a leading AI/ML venue, such as NeurIPS, ICML, ICLR, ACL, EMNLP, CVPR, or ICCV.</dd></div>
  </dl>
  <p class="hb-callout">For graduate applicants, I strongly recommend a research internship in my group for <strong>at least three months</strong> before applying.</p>
  <p class="hb-contact"><span class="hb-contact__label">Contact</span> haebeomlee [at] korea [dot] ac [dot] kr</p>
</section>

<section class="hb-awards" id="awards" aria-labelledby="awards-title">
  <h2 class="hb-h2" id="awards-title">Awards</h2>
  <ul class="hb-awards__list">
    <li><span class="hb-awards__year">2021</span>Google Ph.D. Fellowship</li>
    <li><span class="hb-awards__year">2019–2021</span>Global Ph.D. Fellowship</li>
    <li><span class="hb-awards__year">2020, 2022</span>Outstanding Reviewer, ICML (Top 33% and Top 10%)</li>
  </ul>
</section>

<section class="hb-pubs" id="publications" aria-labelledby="pubs-title">
  <h2 class="hb-h2" id="pubs-title">Publications</h2>
  {%- assign groups = "preprints|Recent preprints,conference|Conference publications,earlier|Earlier preprints" | split: "," -%}
  {%- for g in groups -%}
  {%- assign parts = g | split: "|" -%}
  {%- assign papers = site.data.papers[parts[0]] -%}
  <h3 class="hb-h3">{{ parts[1] }}</h3>
  <ol class="hb-pub-list">
    {%- for p in papers -%}
    <li class="hb-pub">
      <div class="hb-pub__venue{% if p.venue == 'arXiv' %} hb-pub__venue--pre{% endif %}">
        <span class="hb-pub__conf">{{ p.venue }}</span>
        <span class="hb-pub__year">{{ p.year }}</span>
        {%- if p.highlight %}<span class="hb-pub__hl">{{ p.highlight }}</span>{% endif -%}
      </div>
      <div class="hb-pub__body">
        <p class="hb-pub__title">{{ p.title }}</p>
        <p class="hb-pub__authors">{{ p.authors | replace: "Hae Beom Lee", "<strong>Hae Beom Lee</strong>" }}</p>
        {%- if p.note %}<p class="hb-pub__note">{{ p.note }}</p>{% endif -%}
        {%- if p.links %}<p class="hb-pub__links">{% for l in p.links %}<a href="{{ l.url }}">{{ l.name | capitalize }}</a>{% endfor %}</p>{% endif -%}
      </div>
    </li>
    {%- endfor -%}
  </ol>
  {%- endfor -%}
</section>

</div>
